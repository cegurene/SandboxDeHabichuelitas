# SandboxDeHabichuelitas - Bean a Hero 🫘🎮

A medieval-themed action arcade game developed in Python using the Arcade library. This repository serves as both a learning sandbox and the development workspace for "Bean a Hero" (Habichuelas Radioactivas).

## 📖 About the Project

**Bean a Hero** is a medieval action game where a weak knight gains superpowers from radioactive beans to save the world from a food contamination crisis. The game features wave-based combat, boss battles, and unique power-ups obtained throughout the adventure.

### Story
In a distant medieval era, a food scarcity crisis led people to consume contaminated food that drove them mad. A weak knight becomes humanity's last hope by harnessing the power of mysterious Radioactive Beans to defeat the infected and restore peace to the world.

## 🎮 Game Features

- **Wave-based Combat System**: Progress through increasingly challenging enemy waves
- **Two Complete Levels**: Each with multiple waves and boss encounters
- **Multiple Enemy Types**: Melee and ranged enemies with unique behaviors
- **Power-ups**: Radioactive Beans that grant special abilities
  - Bean 1: Strength boost (transforms into a knight)
  - Bean 2: Speed boost with cooldown mechanic
- **Boss Battles**: State machine-driven boss fights with varied attack patterns
- **NPC Interactions**: Quest-giving NPCs to guide your journey
- **Menu System**: Start menu, pause functionality, and game over screens
- **Tiled Map Editor Integration**: Custom-designed levels

## 🛠️ Technology Stack

- **Language**: Python 3
- **Game Engine**: Python Arcade
- **Map Editor**: Tiled Map Editor
- **Version Control**: Git/GitHub

## 📂 Repository Structure

```
SandboxDeHabichuelitas/
├── beta_version/          # Current beta version of the game
│   ├── src/              # Source code
│   │   ├── main.py       # Game entry point
│   │   ├── bean_a_hero_beta.py
│   │   ├── player.py     # Player character logic
│   │   ├── enemies.py    # Enemy AI and behaviors
│   │   ├── menu_views.py # Menu system
│   │   └── ...
│   ├── assets/           # Game assets (sprites, sounds, etc.)
│   └── README.md         # Beta version documentation
├── take_a_bite/          # Learning modules and prototypes
│   ├── animation/        # Animation experiments
│   ├── menu/            # Menu prototypes
│   ├── movimientos/     # Movement mechanics
│   ├── sonido/          # Sound system tests
│   ├── tiled_map_editor/ # Map editor experiments
│   └── Alpha Version/   # Alpha version files
├── project_deliveries/   # Project documentation and reports
│   ├── BeanAHero.md     # Game design document
│   ├── DocumentoDiseño.pdf
│   └── ProjectReport.pdf
└── README.md            # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/cegurene/SandboxDeHabichuelitas.git
cd SandboxDeHabichuelitas
```

2. Install the required dependencies:
```bash
pip install arcade
```

### Running the Game

To run the beta version of Bean a Hero:

```bash
cd beta_version/src
python main.py
```

### Running Learning Modules

The `take_a_bite` directory contains individual learning modules for different game mechanics. Each module can be run independently to test specific features.

## 🎯 Controls

- **WASD** or **Arrow Keys**: Move character
- **Space/Attack Key**: Attack
- **Shift**: Use special ability (Bean power)
- **ESC**: Pause menu

## 🧑‍💻 Development Philosophy

This repository serves dual purposes:

1. **Learning Sandbox** (`take_a_bite/`): Individual modules for team members to learn Arcade library features, GitHub collaboration, and game development concepts
2. **Production Game** (`beta_version/`): Integration of refined concepts into the complete Bean a Hero game

## 📝 Project Status

🔨 **Currently in Beta Development**

- [x] Core movement mechanics
- [x] Animation system
- [x] Menu system
- [x] Sound integration
- [x] Tiled map integration
- [x] Enemy AI basics
- [x] Player combat system
- [ ] Boss battle mechanics (in progress)
- [ ] Complete level design
- [ ] Final polish and balancing

## 🤝 Contributing

This is a collaborative university project. Team members should:

1. Work on individual learning modules in `take_a_bite/`
2. Test features independently before integration
3. Follow the existing code structure and naming conventions
4. Commit frequently with descriptive messages
5. Coordinate with team members before merging to main branches

## 📚 Documentation

- **Game Design Document**: `project_deliveries/BeanAHero.md`
- **Project Report**: `project_deliveries/ProjectReport.pdf`
- **Design Document**: `project_deliveries/DocumentoDiseño.pdf`
- **Beta Documentation**: `beta_version/README.md`
- **Learning Modules**: `take_a_bite/README.md`

## 👥 Team

Developed by the Habichuelas Radioactivas team as a university project.

## 📄 License

This project is developed for educational purposes.

## 🙏 Acknowledgments

- Python Arcade library and community
- Tiled Map Editor
- All team members who contributed to the project

---

**¡Que comience la aventura! 🫘⚔️**
