# Development Instruction
## File Structure
```
|-  <repo-root>      // This repo folder
    |-  PluginProject.code-workspace        // Open this file to start
    |-  PluginProject.csproj                
    |-  Plugin.cs
    |-  ...
|- RoomGirl         // Symbolic link to Game Folder / Game Folder
|- ...
```

**PluginProject.csproj**

Edit `Plugin Info` section to set info for plugin binary

**Plugin.cs**

Edit `BepInPlugin` Attribute to set info for plugin in BepInEx