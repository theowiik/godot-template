## Godot Template Project

Template project for Godot 4.

- [Godot Template Project](#godot-template-project)
- [Formatting](#formatting)
- [Project Structure](#project-structure)

## Formatting

The following commands require Make and [Nix](https://nixos.org/), but it can easily be
ran without them, check the contents of the [Makefile](./Makefile) for how to run
formatting manually.

```
$ make help
Available targets:
  format  - Format all gdscript files
  check   - Check formatting of all gdscript files
```

## Project Structure

Example structure for organizing a Godot project:

**File tree:**

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
└── project.godot        # Godot project configuration
```

**Naming Conventions:**

- **Root Node**: PascalCase (e.g., `Player`, `MainMenu`, `GameLevel`)
- **File Names**: snake_case matching the root node (e.g., `player.tscn`,
  `main_menu.tscn`, `game_level.tscn`)
- **Script Files**: snake_case (e.g., `player.gd`, `enemy_controller.gd`)
- **Directories**: snake_case, always lowercase (e.g., `assets/`, `scenes/`, `scripts/`)
