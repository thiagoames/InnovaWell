# 🏥 InnovaWell - Platform de Bienestar Estudiantil

> Una plataforma gamificada que motiva a estudiantes a mantener hábitos saludables de alimentación mediante puntos, rankings y recompensas.

## 🎯 Visión

InnovaWell transforma el bienestar estudiantil en una experiencia divertida y motivadora. Los estudiantes registran sus comidas, completan rutinas saludables y compiten en rankings semanales para ganar puntos canjeables por recompensas especiales.

## ✨ Características Principales

### 📝 Registro de Comidas
- Registro diario de desayuno, almuerzo, merienda y cena
- Captura de fotos para documentación visual
- Análisis nutricional automático
- Historial visual de progreso

### 🏃 Rutinas Saludables
- Crear y seguir rutinas personalizadas
- Tipos: ejercicio, hidratación, meditación
- Verificación diaria de cumplimiento
- Progreso visual semanal

### 🤖 Motor de Recomendaciones
- Análisis inteligente de patrones alimenticios
- Sugerencias personalizadas en tiempo real
- Tips nutricionales basados en hábitos
- Tips del día para motivación continua

### 🎮 Sistema de Gamificación
- **Puntos**: Obtén puntos por cada acción saludable
- **Ranking Semanal**: Compite con tus compañeros
- **Badges**: Logros especiales por consistencia
- **Racha**: Bonus por días consecutivos

### 🎁 Tienda de Recompensas
- **Asientos del Mes**: Lugares preferentes
- **Tutoría en el Patio**: Sesiones 1:1
- **Sorteos Semanales**: Premios sorpresa
- **Recreos Especiales**: Actividades temáticas

## 🛠️ Stack Tecnológico

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Base de Datos**: PostgreSQL
- **Cache**: Redis
- **Autenticación**: JWT

### Frontend
- **Framework**: Vue.js 3
- **Styling**: Tailwind CSS
- **Estado**: Pinia
- **Build**: Vite
- **Gráficos**: Chart.js

### Infraestructura
- **Containerización**: Docker
- **Deployment**: Docker Compose (local), AWS/Heroku (prod)
- **Storage**: Cloudinary (imágenes)
- **Variables**: .env

## 📊 Modelo de Datos

### Tablas Principales
- `users` - Estudiantes registrados
- `meals` - Registro de comidas
- `routines` - Rutinas saludables
- `points` - Sistema de puntuación
- `recommendations` - Sugerencias personalizadas
- `rewards` - Recompensas y canjes

[Ver esquema completo en ARQUITECTURA.md](./ARQUITECTURA.md)

## 🚀 Inicio Rápido

### Requisitos Previos
```bash
- Node.js 18+
- PostgreSQL 12+
- Redis 6+
- Git
```

### Instalación

1. **Clona el repositorio**
```bash
git clone https://github.com/thiagoames/InnovaWell.git
cd InnovaWell
```

2. **Instala dependencias del backend**
```bash
cd backend
npm install
```

3. **Instala dependencias del frontend**
```bash
cd ../frontend
npm install
```

4. **Configura variables de entorno**
```bash
# Backend
cd ../backend
cp .env.example .env
# Edita .env con tus credenciales

# Frontend
cd ../frontend
cp .env.example .env
```

5. **Inicia con Docker Compose**
```bash
cd ..
docker-compose up
```

6. **Accede a la aplicación**
```
Frontend: http://localhost:3000
API: http://localhost:5000
```

## 📖 Documentación

- [ARQUITECTURA.md](./ARQUITECTURA.md) - Diseño arquitectónico completo
- [ESTRUCTURA_CARPETAS.md](./ESTRUCTURA_CARPETAS.md) - Organización del proyecto
- [DISEÑO_INTERFAZ.md](./DISEÑO_INTERFAZ.md) - Wireframes y diseño UI/UX
- [docs/API_REFERENCE.md](./docs/API_REFERENCE.md) - Referencia de endpoints (próximamente)
- [docs/DATABASE_SCHEMA.md](./docs/DATABASE_SCHEMA.md) - Esquema de BD (próximamente)

## 📅 Roadmap

### ✅ Fase 1: MVP (Semanas 1-2)
- [x] Setup inicial
- [ ] Autenticación
- [ ] Dashboard básico
- [ ] Registro de comidas
- [ ] Sistema de puntos

### 🔄 Fase 2: Gamificación (Semanas 3-4)
- [ ] Ranking semanal
- [ ] Badges y logros
- [ ] Rutinas saludables

### 📊 Fase 3: Recomendaciones (Semana 5)
- [ ] Motor de análisis
- [ ] Feed de sugerencias
- [ ] Tips personalizados

### 🎯 Fase 4: Recompensas (Semana 6)
- [ ] Tienda de canjes
- [ ] Historial de premios
- [ ] Panel administrativo

### ⭐ Fase 5: Mejoras (Semana 7+)
- [ ] App móvil
- [ ] Notificaciones push
- [ ] Integración con wearables
- [ ] Sistema de notificaciones en tiempo real

## 🎨 Diseño

### Paleta de Colores
- **Primario**: #10B981 (Verde Esmeralda)
- **Secundario**: #F59E0B (Ámbar)
- **Acento**: #EF4444 (Rojo)

[Ver diseño completo en DISEÑO_INTERFAZ.md](./DISEÑO_INTERFAZ.md)

## 👥 Contribuidores

- **Thiago Ames** - Desarrollador Principal

## 📝 Licencia

Este proyecto está bajo la licencia MIT - ver el archivo [LICENSE](./LICENSE) para detalles.

## 🤝 Soporte

¿Preguntas o sugerencias? 
- Abre un [Issue](https://github.com/thiagoames/InnovaWell/issues)
- Revisa la [Documentación](./docs)
- Contacta: thiagoames@example.com

---

**InnovaWell** - Promoviendo bienestar estudiantil de forma divertida 🌟
