Estructura del Proyecto

streamyard-clone/
├── backend/          # NestJS backend (puerto 3000)
│   ├── src/
│   │   ├── common/       # Decoradores, guards, interceptors, pipes
│   │   ├── config/       # Configuracion de DB, JWT, Redis
│   │   ├── modules/      # Modulos de negocio (auth, broadcasts, chat...)
│   │   └── media/        # WebRTC (Mediasoup) + FFmpeg
│   ├── docker-compose.yml
│   └── .env.example
├── frontend/         # Angular frontend (puerto 4200)
│   ├── src/app/
│   │   ├── core/        # Models, services, interceptors, guards
│   │   ├── shared/      # Componentes reutilizables, pipes, directives
│   │   ├── features/    # Modulos de negocio (auth, studio, broadcasts...)
│   │   └── layouts/     # Layouts (auth, main, studio)
│   └── environments/
└── guia_arquitectura_streamyard.pdf  # Guia completa de arquitectura
