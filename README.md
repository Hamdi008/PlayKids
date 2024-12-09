# KayKids Game Project

## Overview
The **KayKids Game** is a Kotlin-based game project that implements an **Entity-Component-System (ECS)** architecture.
The game features multiple user screens and a real-time game loop, with components for entities like position, velocity,
and sprite rendering.

## Directory Structure

### `ecs/`
Contains the core ECS logic for components, entities, and systems.

- **`components/`**  
  Defines the properties of entities.
    - `PositionComponent.kt`: Represents an entity's position.
    - `VelocityComponent.kt`: Represents an entity's velocity.
    - `SpriteComponent.kt`: Defines the graphical properties of entities.

- **`entities/`**  
  Contains entity classes and the entity manager.
    - `Entity.kt`: Base class for game entities.
    - `EntityManager.kt`: Manages the lifecycle and operations of entities.

- **`systems/`**  
  Contains systems that process entities.
    - `MovementSystem.kt`: Handles movement logic based on position and velocity.
    - `RenderSystem.kt`: Responsible for rendering entities on screen.

### `ui/`
Contains user interface screens.

- **`screens/`**  
  Defines different UI screens of the game.
    - `SignInScreen.kt`: The sign-in screen for user authentication.
    - `SignUpScreen.kt`: The sign-up screen for new users.
    - `GameSelectionScreen.kt`: Screen for selecting a game mode or level.
    - `GameScreen.kt`: The main game screen where the gameplay takes place.

### `core/`
Contains essential components that drive the application.

- `MainActivity.kt`: The main entry point of the application.
- `Navigation.kt`: Manages the navigation between screens.
- `GameLoop.kt`: Controls the game loop, which updates and renders the game state.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Hamdi008/PlayKids.git
