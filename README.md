# Godot Template Project

Template project for Godot 4

- [Godot Template Project](#godot-template-project)
  - [Dev Tools](#dev-tools)
  - [Project Structure](#project-structure)
    - [File Structure](#file-structure)
    - [Naming Conventions](#naming-conventions)

## Dev Tools

text

## Project Structure

Example structure and naming conventions for organizing Godot 4 projects.

### File Structure

```
godot-template/
├── assets/              # Asset files (textures, icons, sprites, sounds, etc.)
│   └── ...
├── objects/             # Reusable game objects and components
│   └── ...
├── scenes/              # Game scenes and levels
│   └── ...
├── scripts/             # GDScript files
│   └── ...
├── .editorconfig        # Editor configuration
├── .gitattributes       # Git attributes
├── .gitignore           # Git ignore rules
├── project.godot        # Godot project configuration
└── README.md            # Project documentation
```

### Naming Conventions

- **Root Node**: PascalCase (e.g., `Player`, `MainMenu`, `GameLevel`)
- **File Names**: snake_case matching the root node (e.g., `player.tscn`, `main_menu.tscn`, `game_level.tscn`)
- **Script Files**: snake_case (e.g., `player.gd`, `enemy_controller.gd`)
- **Directories**: snake_case, always lowercase (e.g., `assets/`, `scenes/`, `scripts/`)
