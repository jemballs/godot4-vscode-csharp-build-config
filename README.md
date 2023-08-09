# Godot 4 VSCode C# build configs

tasks.json and launch.json files that Just Work™ for Godot 4 projects made using C# in VSCode. Uses .NET Core (coreclr) for building and debugging your projects.

## Launch options:
- Launch - Launches your default scene
- Launch (Select Scene) - Prompts you to select the scene from your project you wish to open then launches that (using C# Tools for Godot's functionality)
- Launch Editor - Launches your project in the Godot editor
- Attach to Process - Prompts you to select which process you wish to attach to then attaches to that

## Required extensions:
- C#
  - .Net Install Tool for Extension Authors (Dependency for C# - probably auto-installs)
- C# Tools for Godot (only required for the Select Scene build config)
  - Mono Debug (Dependency for "C# Tools for Godot" - probably auto-installs)

## Instructions:
1. Copy the .vscode folder to your Godot project folder
2. Edit the "program" values in launch.json to be the path to your Godot engine exe file
3. Done!
