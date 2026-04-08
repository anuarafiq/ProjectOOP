# ProjectOOP — Space Shooter

A 2D space shooter built with MonoGame and C#, developed as an Object-Oriented Programming project.

## Gameplay

Pilot your ship through waves of alien enemies, collect power-ups, manage your ammo, and survive long enough to reach victory.

### Enemy Types
- **Alien Scout** — fast, low-health enemies that swarm in early waves
- **Alien Fighter** — tougher mid-tier enemies that return fire
- **Boss Alien Dragon** — a powerful boss enemy with high HP and heavy attacks

### Features
- Wave-based level progression
- Player ammo and reload system
- Power-ups: health restore and weapon upgrade
- Collision detection for player projectiles, enemy projectiles, and melee contact
- Audio system with per-level background music and sound effects
- Game states: Main Menu, Playing, Game Over, Victory

## Tech Stack

| | |
|---|---|
| Language | C# |
| Runtime | .NET 9.0 |
| Framework | MonoGame DesktopGL 3.8 |
| Platform | Windows |

## Prerequisites

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)
- [MonoGame](https://monogame.net/downloads/) (for content pipeline tools)

## Build & Run

```bash
cd MyFirstGame
dotnet build
dotnet run
```

## Project Structure

```
ProjectOOP/
├── MyFirstGame/
│   ├── Content/          # Game assets (sprites, audio, fonts)
│   ├── Game1.cs          # MonoGame entry point
│   ├── GameManager.cs    # Core game loop, state management
│   ├── Player.cs         # Player entity
│   ├── Enemy.cs          # Enemy base class
│   ├── AlienScout.cs     # Scout enemy type
│   ├── AlienFighter.cs   # Fighter enemy type
│   ├── BossAlienDragon.cs# Boss enemy type
│   ├── Projectile.cs     # Projectile entity
│   ├── PowerUp.cs        # Power-up entity
│   └── Level.cs          # Level/wave management
└── monogame.sln
```

## Contributors

- **Anuar Afiq**
- **Fira**
