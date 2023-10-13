<div align="center">

<img src="https://dl.isxander.dev/logos/debugify/v2/debugify-512x.png" width="100"/>

# Debugify Reforged
#### Debugify Reforged is unofficial fork of a project that fixes **over 70** bugs found on the <a href="https://bugs.mojang.com/projects/MC/issues">bug tracker</a> in Minecraft.
(and does nothing more!)

</div>

## What does this mod replace?
This mod replaces many mods and implements fixes from some others

- **[FastOpenLinksAndFolders](https://www.curseforge.com/minecraft/mc-mods/fastopenlinksandfolders)**: Fixed underlying bug causing MC to lag
- **[Shift-Scroll Fix](https://www.curseforge.com/minecraft/mc-mods/shift-scroll-fix)**: Superseded
- **[ForgetMeChunk](https://www.curseforge.com/minecraft/mc-mods/forgetmechunk)**: Superseded
- **[ChunkSavingFix](https://www.curseforge.com/minecraft/mc-mods/chunk-saving-fix)**: Superseded
- **[force-close-world-loading-screen](https://modrinth.com/mod/forcecloseworldloadingscreen)**: Missing option to remove menu fully (as it isn't a bug)
- **[No Telemetry](https://www.curseforge.com/minecraft/mc-mods/no-telemetry/)**: Superseded
- **[ToolTipFix](https://www.curseforge.com/minecraft/mc-mods/tooltipfix)**: Alternative method - tooltips still go off-screen in modded scenarios
- **[Title Fix Mod](https://modrinth.com/mod/title-fix-mod)**: Superseded
- **[Entity Collision FPS Fix Refabricated](https://www.curseforge.com/minecraft/mc-mods/entity-collision-fps-fix-fabric)**: Superseded
- **[Ctrl Q](https://www.curseforge.com/minecraft/mc-mods/ctrl-q)**: Superseded
- **[Skeleton Aiming Fix](https://www.curseforge.com/minecraft/mc-mods/skeleton-aiming-fix)**: Superseded

These superseded mods are not hard conflicts and can be used in conjunction with Debugify for any additional advanced features.

## Links and other info
[GitHub](https://github.com/isXander/Debugify) • [Curseforge](https://curseforge.com/minecraft/mc-mods/debugify) • [Modrinth](https://modrinth.com/mod/debugify) • [Patched bug list](https://github.com/isXander/Debugify/blob/1.19/PATCHED.md) • [Discord](https://short.isxander.dev/discord)

## What if I want to enable some bug fixes, but not others?
Debugify has a configuration GUI accessible by Fabric's [Mod Menu](https://modrinth.com/mod/modmenu) or Forge's Built-in mod list.
If you don't want to use either of them, there is always the configuration file located at
`.minecraft/config/debugify.json`
![configuration menu](https://i.imgur.com/0hv9cvu.png)

## Client, or Server?
Debugify includes many fixes for both the client and server (all server fixes also apply to client).
So you should definitely use it on both.

## Can I include this in my modpack?
Yes! Of course! We even added a little feature in the mod for you! The constant updates may be exhausting to maintain,
so we added a config option that defaults new bug fixes to off, until you get round to looking at it.

```json5
{
  // ...
  "default_disabled": true
}
```

## Credits
- [**isXander**](https://github.com/isXander) - Founder of project
- [**Contributors**](https://github.com/isXander/Debugify/graphs/contributors) - For PRing new fixes!
- [**MoonTidez**](https://github.com/MoonTidez) - Creating an awesome logo!
