# PlayKids
Android game application for kids

# Project Structure
Entity-Component-System (ECS) architecture is used:

com.hel.pkaykids
│
├── ecs
│   ├── components
│   │   ├── PositionComponent.kt
│   │   ├── VelocityComponent.kt
│   │   ├── SpriteComponent.kt
│   │
│   ├── entities
│   │   ├── Entity.kt
│   │   ├── EntityManager.kt
│   │
│   ├── systems
│   │   ├── MovementSystem.kt
│   │   ├── RenderSystem.kt
│
├── ui
│   ├── SignInScreen.kt
│   ├── SignUpScreen.kt
│   ├── GameSelectionScreen.kt
│   ├── GameScreen.kt
│
├── MainActivity.kt
├── Navigation.kt
└── GameLoop.kt
