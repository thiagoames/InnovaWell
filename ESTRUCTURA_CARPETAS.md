# 📁 Estructura de Carpetas - InnovaWell

```
InnovaWell/
├── 📄 README.md
├── 📄 ARQUITECTURA.md
├── 📄 ESTRUCTURA_CARPETAS.md
├── 📄 DISEÑO_INTERFAZ.md
├── 📄 .gitignore
├── 📄 .env.example
│
├── 🔧 backend/
│   ├── 📄 package.json
│   ├── 📄 server.js
│   ├── 📄 .env
│   │
│   ├── 📁 config/
│   │   ├── database.js
│   │   ├── auth.js
│   │   └── redis.js
│   │
│   ├── 📁 routes/
│   │   ├── auth.js
│   │   ├── users.js
│   │   ├── meals.js
│   │   ├── routines.js
│   │   ├── points.js
│   │   ├── ranking.js
│   │   ├── recommendations.js
│   │   └── rewards.js
│   │
│   ├── 📁 controllers/
│   │   ├── authController.js
│   │   ├── userController.js
│   │   ├── mealController.js
│   │   ├── routineController.js
│   │   ├── pointController.js
│   │   ├── rankingController.js
│   │   ├── recommendationController.js
│   │   └── rewardController.js
│   │
│   ├── 📁 models/
│   │   ├── User.js
│   │   ├── Meal.js
│   │   ├── Routine.js
│   │   ├── Points.js
│   │   ├── Recommendation.js
│   │   └── Reward.js
│   │
│   ├── 📁 middleware/
│   │   ├── auth.js
│   │   ├── validation.js
│   │   └── errorHandler.js
│   │
│   ├── 📁 utils/
│   │   ├── mealAnalyzer.js
│   │   ├── pointsCalculator.js
│   │   ├── recommendationEngine.js
│   │   └── emailService.js
│   │
│   ├── 📁 migrations/
│   │   ├── 001_create_users.sql
│   │   ├── 002_create_meals.sql
│   │   ├── 003_create_routines.sql
│   │   ├── 004_create_points.sql
│   │   ├── 005_create_recommendations.sql
│   │   └── 006_create_rewards.sql
│   │
│   └── 📁 tests/
│       ├── auth.test.js
│       ├── meals.test.js
│       ├── ranking.test.js
│       └── points.test.js
│
├── 🎨 frontend/
│   ├── 📄 package.json
│   ├── 📄 vite.config.js
│   ├── 📄 index.html
│   │
│   ├── 📁 public/
│   │   ├── favicon.ico
│   │   └── logo.svg
│   │
│   ├── 📁 src/
│   │   ├── 📄 main.js
│   │   ├── 📄 App.vue
│   │   │
│   │   ├── 📁 components/
│   │   │   ├── Header.vue
│   │   │   ├── Navigation.vue
│   │   │   ├── Card.vue
│   │   │   ├── Button.vue
│   │   │   ├── Modal.vue
│   │   │   └── Loader.vue
│   │   │
│   │   ├── 📁 pages/
│   │   │   ├── Dashboard.vue
│   │   │   ├── RegisterMeal.vue
│   │   │   ├── MyRoutines.vue
│   │   │   ├── Ranking.vue
│   │   │   ├── RewardsShop.vue
│   │   │   ├── Recommendations.vue
│   │   │   ├── Login.vue
│   │   │   ├── Register.vue
│   │   │   └── Profile.vue
│   │   │
│   │   ├── 📁 stores/
│   │   │   ├── authStore.js
│   │   │   ├── userStore.js
│   │   │   ├── mealStore.js
│   │   │   ├── rankingStore.js
│   │   │   └── pointsStore.js
│   │   │
│   │   ├── 📁 services/
│   │   │   ├── api.js
│   │   │   ├── authService.js
│   │   │   ├── mealService.js
│   │   │   ├── rankingService.js
│   │   │   └── recommendationService.js
│   │   │
│   │   ├── 📁 utils/
│   │   │   ├── formatters.js
│   │   │   ├── validators.js
│   │   │   ├── constants.js
│   │   │   └── notifications.js
│   │   │
│   │   ├── 📁 assets/
│   │   │   ├── 📁 icons/
│   │   │   ├── 📁 images/
│   │   │   ├── 📁 styles/
│   │   │   │   ├── global.css
│   │   │   │   ├── variables.css
│   │   │   │   └── animations.css
│   │   │   └── 📁 fonts/
│   │   │
│   │   └── 📁 router/
│   │       └── index.js
│   │
│   └── 📁 tests/
│       ├── components.test.js
│       ├── pages.test.js
│       └── services.test.js
│
├── 🐳 docker/
│   ├── Dockerfile.backend
│   ├── Dockerfile.frontend
│   └── docker-compose.yml
│
├── 📚 docs/
│   ├── API_REFERENCE.md
│   ├── SETUP_GUIDE.md
│   ├── DEPLOYMENT.md
│   ├── DATABASE_SCHEMA.md
│   └── USER_STORIES.md
│
└── ⚙️ config/
    ├── .eslintrc.json
    ├── .prettierrc.json
    └── jest.config.js
```

---

## 📋 Descripción de Carpetas

### `backend/`
Servidor API con Express/Node.js
- **routes**: Definición de endpoints
- **controllers**: Lógica de negocio
- **models**: Esquemas de base de datos
- **middleware**: Autenticación, validación, errores
- **utils**: Funciones auxiliares
- **migrations**: Scripts SQL de base de datos
- **tests**: Tests unitarios e integración

### `frontend/`
Interfaz web con Vue 3
- **components**: Componentes reutilizables
- **pages**: Vistas principales
- **stores**: Gestión de estado global (Pinia)
- **services**: Llamadas a API
- **utils**: Funciones auxiliares
- **assets**: Imágenes, iconos, estilos
- **router**: Rutas de la aplicación

### `docker/`
Configuración de containerización
- Docker files para backend y frontend
- Docker compose para orquestación local

### `docs/`
Documentación del proyecto
- Guías de setup
- Referencia de API
- Esquema de base de datos
- Historias de usuario

---

## 🚀 Próximas Acciones
1. ✅ Crear estructura documentada
2. Configurar backend (Node + Express)
3. Configurar frontend (Vue 3)
4. Implementar autenticación
5. Diseñar base de datos en PostgreSQL