# GamerBoyProject

A personal Unreal Engine project for a game prototype / level exploration setup created in Unreal Engine 5.3. The repository includes core project configuration, gameplay input setup, and a collection of content folders for characters, materials, blueprints, and environment assets.

## Project Overview

This project appears to be a sandbox/prototype environment built around a custom game setup with:

- Unreal Engine 5.3 project configuration
- Keyboard and gamepad input support
- Character and environment content folders
- Blueprint-driven gameplay setup
- A testing level for iteration and development

## Repository Structure

```text
GamerBoyProject/
├── Config/
│   ├── DefaultEditor.ini
│   ├── DefaultEngine.ini
│   ├── DefaultGame.ini
│   └── DefaultInput.ini
├── Content/
│   ├── Alex/
│   ├── Austin/
│   ├── Blueprints/
│   ├── DustinFolder/
│   ├── Imports/
│   ├── Levels/
│   ├── Mario/
│   ├── Materials/
│   ├── Meshes/
│   └── TestingLevel.umap
├── GB_Project.uproject
├── .gitignore
└── README.md
```

## Engine / Project Setup

The project is configured as an Unreal Engine 5.3 project:

- Engine association: `5.3`
- Project file: `GB_Project.uproject`
- Included plugins:
  - `ModelingToolsEditorMode`
  - `PaperZD`
  - `CommonUI`

## Input Configuration

The project includes input support for both mouse/keyboard and gamepad. The configuration files suggest a cross-device control setup with default PC input and CommonUI integration.

## Getting Started

1. Open `GB_Project.uproject` in Unreal Engine 5.3 or later.
2. Let the editor generate any missing project files if prompted.
3. Open `Content/Levels/TestingLevel.umap` or the relevant level asset to begin working.
4. If needed, verify project settings under `Config/` and adjust input or gameplay settings.

## Notes

- This repository contains content assets and editor/project data rather than a packaged game build.
- Some folders are named after individuals or asset groups, which suggests a collaborative / iterative project structure.
- The project is currently oriented as a game prototype and content sandbox.

## License

No explicit license file was found in the repository. If you plan to distribute or reuse this project, confirm the licensing terms before publishing or sharing derived work.

## Contributing

This appears to be a personal project repository with active development content. If you are using this repository as a reference or base, be sure to review any included asset and code dependencies before distributing modifications.
