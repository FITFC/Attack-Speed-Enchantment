# Attack-Speed-Enchantment

[
![Curseforge Downloads](http://cf.way2muchnoise.eu/attack-speed-enchantment.svg)
![Curseforge Versions](http://cf.way2muchnoise.eu/versions/attack-speed-enchantment.svg)
](https://www.curseforge.com/minecraft/mc-mods/attack-speed-enchantment)
[
![Discord](https://img.shields.io/discord/297104769649213441?label=Discord)
](https://discordapp.com/invite/QXbWS36)

### This mod adds a new enchantment that increase the attack speed time.

- Download on [curseforge](https://www.curseforge.com/minecraft/mc-mods/attack-speed-enchantment).  
- Find more information on our [website](https://u-team.info/mods/attackspeedenchantment).
- Updates can be found in the [changelog](CHANGELOG.md).

### How to build this mod

#### Setup Eclipse
- ``./gradlew genEclipseRuns eclipse``
- Import project as existing workspace

#### Setup IntelliJ IDEA
- ``./gradlew genIntellijRuns``
- Import as gradle project

#### Build
- ``./gradlew build``

### How to include this mod

- Repository: [repo.u-team.info](https://repo.u-team.info)
- Artifact: **info.u-team:attack_speed_enchantment-${config.forge.mcversion}:${config.attackspeedenchantment.version}** 
- *{config.forge.mcversion}* is the minecraft version.
- *{config.attackspeedenchantment.version}* is the attackspeedenchantment version.

#### Using in Forge Gradle 3:
```gradle
repositories {
    maven { url = "https://repo.u-team.info" }
}

dependencies {
  compileOnly fg.deobf("info.u-team:attack_speed_enchantment-${config.forge.mcversion}:${config.attackspeedenchantment.version}")
}
```

### License

- This mod is licensed under apache 2 license. For more information see [here](LICENSE).  
- This mod can be packed in any curseforge modpack you like.

### Issues

- Please report issues to the [github issues](../../issues).
- Include your minecraft version, forge version and mod version.
- Upload your log on [gist](https://gist.github.com) or [pastebin](https://pastebin.com) and include link in your report.
