# Godot 4 VSCode C# build configs

tasks.json and launch.json files that Just Work™ for Godot 4 projects made using C# in VSCode. Uses .NET Core (coreclr) for building and debugging your projects.

## Launch options:
- Launch - Launches your default scene
- Launch (Select Scene) - Prompts you to select the scene from your project you wish to open then launches that (using C# Tools for Godot's functionality)
- Launch Editor - Launches your project in the Godot editor
- Attach to Process - Prompts you to select which process you wish to attach to then attaches to that

## .NET SDK Required:
You will need at least the .NET 6.0 SDK installed on your PC. It looks like Godot 4 has also added support for .NET 7.0, so that should work too. You download them here:
- .NET 6.0: https://dotnet.microsoft.com/en-us/download/dotnet/6.0
- .NET 7.0: https://dotnet.microsoft.com/en-us/download/dotnet/7.0

## Required extensions:
- C#
  - .Net Install Tool for Extension Authors (Dependency for C# - probably auto-installs)
- C# Tools for Godot (only required for the Select Scene build config)
  - Mono Debug (Dependency for "C# Tools for Godot" - probably auto-installs)

These can be installed from within VSCode. Just open the Extensions tab and search the marketplace for them.

## Instructions:
1. Download and Install .NET 6.0 or 7.0 SDK
2. Search for Install required extensions in VSCode
3. Copy the .vscode folder to your Godot project folder
4. Edit the "program" values in launch.json to be the path to your Godot engine exe file
5. Done!
