# 🏗️ Arquitectura de InnovaWell

## Visión General
**InnovaWell** es una plataforma gamificada de bienestar estudiantil que motiva a los estudiantes a mantener hábitos saludables de alimentación mediante un sistema de puntos, rankings y recompensas.

---

## 📊 Componentes Principales

### 1. **Gestión de Usuarios**
- Registro e login de estudiantes
- Perfiles personalizados con foto
- Seguimiento del progreso individual
- Historial de actividades

### 2. **Registro de Comidas**
- Interfaz para registrar comidas diarias
- Categorización: desayuno, almuerzo, merienda, cena
- Análisis nutricional básico (calorías, proteína, carbohidratos)
- Galería fotográfica de comidas
- Historial visual de comidas

### 3. **Sistema de Rutinas Saludables**
- Crear planes de ejercicio semanal
- Integración de metas de hidratación
- Recordatorios automáticos
- Seguimiento de cumplimiento

### 4. **Motor de Recomendaciones**
- Análisis de patrones de alimentación
- Sugerencias personalizadas
- Tips nutricionales basados en hábitos
- Recomendaciones de mejora

### 5. **Sistema de Gamificación**
#### Puntos
- Registrar comida: +5 puntos
- Completar rutina: +10 puntos
- Seguir recomendación: +8 puntos
- Racha de 7 días: +20 puntos bonus

#### Ranking Semanal
- Top 10 estudiantes por semana
- Reinicio automático los lunes
- Badges de logros especiales
- Comparación con compañeros

#### Canjes de Recompensas
- **Asientos del mes**: Lugares preferentes
- **Tutoría en el patio**: Sesión 1:1 con tutor
- **Sorteos semanales**: Premios sorpresa
- **Recreos especiales**: Actividades temáticas

---

## 🗄️ Modelo de Datos

### Usuarios
```
- id (UUID)
- email (unique)
- nombre
- apellido
- foto_perfil
- grado_escolar
- created_at
- updated_at
```

### Comidas
```
- id (UUID)
- usuario_id (FK)
- tipo (breakfast, lunch, snack, dinner)
- descripcion
- foto_url
- fecha
- calorias (estimadas)
- proteina (g)
- carbohidratos (g)
- grasas (g)
- calificacion_nutricional (1-5)
- created_at
```

### Rutinas
```
- id (UUID)
- usuario_id (FK)
- nombre
- descripcion
- tipo (ejercicio, hidratacion, meditacion)
- frecuencia (diaria, 3x semana, etc)
- puntos_por_completar
- created_at
```

### Puntos y Ranking
```
- id (UUID)
- usuario_id (FK)
- puntos_totales
- puntos_semana_actual
- racha_dias_consecutivos
- posicion_ranking
- week_start_date
- updated_at
```

### Recompensas
```
- id (UUID)
- usuario_id (FK)
- tipo (asiento, tutoria, sorteo, recreo)
- puntos_requeridos
- fecha_canje
- estado (pendiente, completado, expirado)
- descripcion
```

### Recomendaciones
```
- id (UUID)
- usuario_id (FK)
- tipo (nutricional, ejercicio, hidratacion)
- texto
- fecha_sugerencia
- seguida (boolean)
- created_at
```

---

## 🎨 Interfaz de Usuario (Figma/Wireframes)

### Pantallas Principales
1. **Dashboard**
   - Puntos totales y de la semana
   - Posición en ranking
   - Próximas actividades
   - Recompensas disponibles

2. **Registro de Comidas**
   - Formulario por tipo de comida
   - Cámara para foto
   - Sugerencias de análisis nutricional
   - Historial visual

3. **Mis Rutinas**
   - Crear nueva rutina
   - Verificar completadas hoy
   - Progreso semanal

4. **Ranking Semanal**
   - Top 10 con avatares
   - Tus estadísticas
   - Comparación con amigos

5. **Tienda de Recompensas**
   - Catálogo con costo en puntos
   - Mis canjes realizados
   - Historial de recompensas

6. **Recomendaciones**
   - Feed personalizado
   - Marcar como seguida
   - Historial de tips

---

## 🛠️ Stack Tecnológico Propuesto

### Frontend
- **Vue.js 3** - UI framework
- **Tailwind CSS** - Styling
- **Chart.js** - Gráficos y estadísticas
- **Axios** - Llamadas HTTP
- **Pinia** - State management

### Backend
- **Node.js + Express** - Servidor API
- **JWT** - Autenticación
- **WebSockets** - Actualizaciones en tiempo real (ranking)

### Base de Datos
- **PostgreSQL** - Datos estructurados
- **Redis** - Caché para rankings

### Infraestructura
- **Docker** - Containerización
- **AWS/Heroku** - Deployment
- **Cloudinary** - Almacenamiento de fotos

---

## 📅 Roadmap de Desarrollo

### Fase 1: MVP (Semanas 1-2)
- ✅ Autenticación
- ✅ Dashboard básico
- ✅ Registro de comidas
- ✅ Sistema de puntos simple

### Fase 2: Gamificación (Semanas 3-4)
- ✅ Ranking semanal
- ✅ Badges y logros
- ✅ Rutinas saludables

### Fase 3: Recomendaciones (Semana 5)
- ✅ Motor de análisis
- ✅ Sugerencias personalizadas
- ✅ Feed de tips

### Fase 4: Recompensas (Semana 6)
- ✅ Tienda de canjes
- ✅ Integración con administración
- ✅ Historial de premios

### Fase 5: Mejoras (Semana 7+)
- ✅ App móvil
- ✅ Notificaciones push
- ✅ Integración con wearables

---

## 🔐 Consideraciones de Seguridad
- Autenticación con JWT
- Validación de datos en backend
- HTTPS obligatorio
- Datos sensibles encriptados
- GDPR compliance (privacidad de estudiantes)

---

## 📊 Métricas de Éxito
- Tasa de adopción de estudiantes
- Consistencia en registros de comidas
- Mejora en hábitos nutricionales
- Engagement semanal
- Retención de usuarios