# 🎨 Diseño de Interfaz - InnovaWell

## Paleta de Colores
```
Primario: #10B981 (Verde Esmeralda) - Salud, Bienestar
Secundario: #F59E0B (Ámbar) - Energía, Motivación
Acento: #EF4444 (Rojo) - Alertas, Urgencia
Fondo: #F9FAFB (Gris Muy Claro)
Texto Principal: #1F2937 (Gris Oscuro)
Éxito: #22C55E (Verde Claro)
Advertencia: #FBBF24 (Amarillo)
```

---

## 📱 Wireframes por Pantalla

### 1. 🔐 PANTALLA DE LOGIN
```
┌─────────────────────────────┐
│                             │
│    🏥 INNOVA WELL LOGO      │
│                             │
├─────────────────────────────┤
│                             │
│  📧 EMAIL / USUARIO         │
│  ┌─────────────────────────┐│
│  │                         ││
│  └─────────────────────────┘│
│                             │
│  🔐 CONTRASEÑA              │
│  ┌─────────────────────────┐│
│  │                         ││
│  └─────────────────────────┘│
│                             │
│  ┌─────────────────────────┐│
│  │   INICIAR SESIÓN        ││
│  └─────────────────────────┘│
│                             │
│  ¿No tienes cuenta?         │
│  → REGISTRARSE              │
│                             │
└─────────────────────────────┘
```

---

### 2. 📊 DASHBOARD (Pantalla Principal)
```
┌─────────────────────────────────────┐
│ ← Menú          👤 NOMBRE           │
├─────────────────────────────────────┤
│                                     │
│  📈 MIS PUNTOS ESTA SEMANA         │
│  ╔═════════════════════════════════╗│
│  ║  1,250 pts                      ║│
│  ║  Posición: #3 en el ranking     ║│
│  ╚═════════════════════════════════╝│
│                                     │
│  🎯 ACTIVIDADES DE HOY             │
│  ┌────────────────────────────────┐│
│  │ ✓ Desayuno registrado          ││
│  │ ⏳ Almuerzo (5:30 pm)           ││
│  │ ◯ Rutina ejercicio (pendiente)  ││
│  │ ◯ Hidratación (2L faltante)     ││
│  └────────────────────────────────┘│
│                                     │
│  🎁 RECOMPENSAS PRÓXIMAS           │
│  ┌────────┐ ┌────────┐ ┌────────┐  │
│  │Asiento │ │Tutoría │ │Sorteo  │  │
│  │500 pts │ │750 pts │ │300 pts │  │
│  └────────┘ └────────┘ └────────┘  │
│                                     │
│  [🍽️ REGISTRAR COMIDA] [📋 VER MÁS]│
│                                     │
└─────────────────────────────────────┘
```

---

### 3. 🍽️ REGISTRAR COMIDA
```
┌─────────────────────────────────────┐
│ ← Dashboard    REGISTRAR COMIDA      │
├─────────────────────────────────────┤
│                                     │
│  TIPO DE COMIDA:                   │
│  ◉ Desayuno  ◯ Almuerzo           │
│  ◯ Merienda  ◯ Cena               │
│                                     │
│  DESCRIPCIÓN:                      │
│  ┌────────────────────────────────┐│
│  │ Ej: Huevo con tostadas         ││
│  └────────────────────────────────┘│
│                                     │
│  FOTO:  [📷 TOMAR FOTO]            │
│  ┌────────────────────────────────┐│
│  │ [Imagen de comida]             ││
│  └────────────────────────────────┘│
│                                     │
│  ANÁLISIS NUTRICIONAL (Automático):│
│  Calorías: 450 cal                 │
│  Proteína: 15g                     │
│  Carbohidratos: 35g                │
│  Grasas: 8g                        │
│                                     │
│  CALIFICACIÓN NUTRICIONAL:         │
│  ★★★★☆ Muy Bueno (35/50 pts)      │
│                                     │
│  [GUARDAR COMIDA]  [CANCELAR]      │
│                                     │
└─────────────────────────────────────┘
```

---

### 4. 🏃 MIS RUTINAS
```
┌─────────────────────────────────────┐
│ ← Dashboard         MIS RUTINAS      │
├─────────────────────────────────────┤
│                                     │
│  [+ CREAR NUEVA RUTINA]            │
│                                     │
│  HOY - MARTES                      │
│  ┌────────────────────────────────┐│
│  │ ✓ Correr 20 min        +10 pts ││
│  │   6:00 AM - Completada        ││
│  └────────────────────────────────┘│
│  ┌────────────────────────────────┐│
│  │ ⏳ Beber 2L agua       +5 pts  ││
│  │   1.2L de 2L completado       ││
│  │   [ACTUALIZAR] [COMPLETAR]    ││
│  └────────────────────────────────┘│
│                                     │
│  ESTA SEMANA                       │
│  Lunes     ✓ ✓ ✓ (30 pts)          │
│  Martes    ✓ ⏳ ◯ (15 pts)         │
│  Miércoles ◯ ◯ ◯ (0 pts)          │
│                                     │
│  PRÓXIMAS RUTINAS:                 │
│  ◯ Yoga 30 min (jueves)            │
│  ◯ Meditación 10 min (todos días) │
│                                     │
└─────────────────────────────────────┘
```

---

### 5. 🏆 RANKING SEMANAL
```
┌─────────────────────────────────────┐
│ ← Dashboard      RANKING SEMANAL     │
├─────────────────────────────────────┤
│                                     │
│  SEMANA: 01 - 07 JUL               │
│                                     │
│  🥇 1. JUAN CARLOS    👤  2,450 pts│
│  🥈 2. MARÍA JOSÉ     👤  2,380 pts│
│  🥉 3. TÚ (THIAGO)    👤  1,250 pts│
│                                     │
│  4. CARLOS            👤  1,180 pts│
│  5. SOFÍA             👤  1,095 pts│
│  6. ANDRÉS            👤    980 pts│
│  7. LAURA             👤    875 pts│
│  8. DIEGO             👤    750 pts│
│  9. VALENTINA         👤    680 pts│
│ 10. FELIPE            👤    620 pts│
│                                     │
│  [PRÓXIMA SEMANA]                  │
│                                     │
│  🎯 TU POSICIÓN: #3                │
│  🎖️ BADGES OBTENIDOS:             │
│     🌟 Semana Saludable            │
│     🔥 Racha de 5 días             │
│                                     │
└─────────────────────────────────────┘
```

---

### 6. 🎁 TIENDA DE RECOMPENSAS
```
┌─────────────────────────────────────┐
│ ← Dashboard    TIENDA DE RECOMPENSAS │
├─────────────────────────────────────┤
│  Puntos disponibles: 1,250 ⭐      │
├─────────────────────────────────────┤
│                                     │
│  RECOMPENSAS DISPONIBLES:           │
│                                     │
│  ┌─────────────────────────────────┐│
│  │ 🪑 ASIENTO DEL MES (Premium)   ││
│  │ Lugar especial en la cafetería  ││
│  │ Válido por: 30 días             ││
│  │ Costo: 500 pts                  ││
│  │ [CANJEAR] - Disponible ✓        ││
│  └─────────────────────────────────┘│
│                                     │
│  ┌─────────────────────────────────┐│
│  │ 👨‍🎓 TUTORÍA EN EL PATIO         ││
│  │ Sesión 1:1 con tutor/a         ││
│  │ Válido por: 1 semana            ││
│  │ Costo: 750 pts                  ││
│  │ [CANJEAR] - Faltan 500 pts      ││
│  └─────────────────────────────────┘│
│                                     │
│  ┌─────────────────────────────────┐│
│  │ 🎲 SORTEO SEMANAL               ││
│  │ Premios: Auriculares, Libros   ││
│  │ Válido por: 1 semana            ││
│  │ Costo: 300 pts                  ││
│  │ [CANJEAR] - Disponible ✓        ││
│  └─────────────────────────────────┘│
│                                     │
│  MIS CANJES:                        │
│  [Ver Historial]                   │
│                                     │
└─────────────────────────────────────┘
```

---

### 7. 💡 RECOMENDACIONES
```
┌─────────────────────────────────────┐
│ ← Dashboard      RECOMENDACIONES     │
├─────────────────────────────────────┤
│                                     │
│  BASADO EN TUS HÁBITOS:             │
│                                     │
│  ┌─────────────────────────────────┐│
│  │ 🥗 NUTRICIONAL                  ││
│  │ "Aumenta consumo de frutas"     ││
│  │ Notaste bajo consumo de         ││
│  │ vitamina C. Añade naranjas,    ││
│  │ fresas o kiwi a tus comidas.   ││
│  │ [✓ SEGUIR] [✗ DESCARTAR]       ││
│  └─────────────────────────────────┘│
│                                     │
│  ┌─────────────────────────────────┐│
│  │ 💧 HIDRATACIÓN                  ││
│  │ "Bebe más agua"                 ││
│  │ Promedio: 1.2L/día vs 2L ideal ││
│  │ Consejo: Lleva botella siempre ││
│  │ [✓ SEGUIR] [✗ DESCARTAR]       ││
│  └─────────────────────────────────┘│
│  ┌─────────────────────────────────┐│
│  │ 🏃 EJERCICIO                    ││
│  │ "Diversifica ejercicios"        ││
│  │ Prueba yoga o natación en fin  ││
│  │ de semana para mayor beneficio ││
│  │ [✓ SEGUIR] [✗ DESCARTAR]       ││
│  └─────────────────────────────────┘│
│                                     │
│  TIP DEL DÍA:                       │
│  ⭐ "Una buena hidratación mejora  │
│     concentración en un 15%"        │
│                                     │
└─────────────────────────────────────┘
```

---

## 🎯 Flujos de Interacción

### Flujo de Gamificación
```
Registra Comida → +5 pts → Suma al ranking → 
Si top 3 → Notificación → Motivación → 
Continúa semana → Acumula pts → Canjea recompensa
```

### Flujo de Recomendación
```
Sistema analiza comidas → 
Identifica patrones → 
Crea recomendación personalizada → 
Usuario puede seguir/descartar → 
+8 pts si sigue → Mejoría en hábitos
```

---

## 🎨 Guía de Componentes

### Botones
- **Primario**: Verde (#10B981) - Acciones principales
- **Secundario**: Gris - Acciones secundarias
- **Éxito**: Verde claro (#22C55E) - Confirmaciones
- **Peligro**: Rojo (#EF4444) - Eliminar/Cancelar

### Tarjetas
- Sombra suave
- Radio 8px
- Padding 16px
- Transiciones suaves

### Badges
- 🥇 #FFD700 Oro (1er lugar)
- 🥈 #C0C0C0 Plata (2do lugar)
- 🥉 #CD7F32 Bronce (3er lugar)

---

## 📱 Responsive Design
- **Mobile First**: Diseño base para 360px
- **Tablet**: 768px - Layouts expandidos
- **Desktop**: 1024px - Vista completa con sidebar
