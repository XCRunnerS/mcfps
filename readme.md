# Minecraft FPS Increasing

## Basics for all Versions and Usecases

There are some basic things you can do to increase your FPS, however these typically will `reduce visual quality` of the game

- Reduce render distance: recommended to always stay above `4`.
  - In modern versions, there is also the `simulation distance` which can be lowered if you are using a higher render distance
- Change `Graphics` to `fast`
  - This wil cause a decrease in tree quality
- Decrease `mipmap` levels
  - this will reduce quality of far away blocks
- Disable `clouds`
- Reduce `particles`

## PVP Specific MC Settings

These settings may be bad for standard survival gameplay, or have minimal impact on fps while reducing quality substantially

- set `Weather` to `fast` or disable entirely
- set `Biome Blend` to lower value
  - low values can look bad
- disable `smooth lighting`
  - not recommended, it looks bad
- disable `vignette` or set it to `fast`
  - highly recommended, some packs break with this set to a normal value
- in modern versions, disable `distortion` and `fov effects`
  - distortion disables nausia and portal distortion
  - fov effects disables dynamic fov

## Texturepacks

Texturepacks dont usually affect FPS, however using a texturepack with reduced animations, simplified models, or lower resolution blocks can improve fps.
Check out the following packs:

- [FPS Models](https://www.curseforge.com/minecraft/texture-packs/qwuiblingtons-fps-block-model-pack/files/all) by `Qwuiblington`
- [FineFault](https://pvprp.com/pack?p=2080) by `XCRunnerS`
- [F8thful and 4thful](https://www.ewanhowell.com/?resourcepacks) by `Ewan Howell`

## PVP FPS Mods and versions before 1.12

Mods can dramatically improve FPS and increase game stability, in versions `before 1.14` use `forge` or a client like `lunar client`, `badlion client`, or `feather`
in `forge` and `feather` use the following mods:

- [Optifine](https://optifine.net/downloads) - click `show all versions`
- [Patcher](https://sk1er.club/mods/patcher)
- [Essentials](https://essential.gg/download)

!TODO

## FPS Mods in Modern Versions

In newer versions, it is highly recommended to use `fabric` or `quilt*` because it is typically faster and has more mods, specifically, mods by `CaffeineMC and JellySquid`.
The following mods are recommended for newer versions:

- `REQUIRED:` [FABRIC API](https://modrinth.com/mod/fabric-api)
- [Sodium](https://modrinth.com/mod/sodium)
- [LazyDFU](https://modrinth.com/mod/lazydfu)
- [Lithium](https://modrinth.com/mod/lithium)
- [Dashloader](https://modrinth.com/mod/dashloader)
- [Entity Culling-Fabric](https://www.curseforge.com/minecraft/mc-mods/entityculling/files) - make sure youre downloading the `fabric` version for your mc version ( typically the ones with a green `R` )
- [Essentials](https://essential.gg/download)
- [No Telemetry](https://modrinth.com/mod/no-telemetry) - QOL, barely any FPS impact
- [Antighost](https://modrinth.com/mod/antighost)

```json
caution zone

Krypton
FerriteCore
sodium extras
Spark
```

*quilt is stil in beta, but is most likely going to be a replacement for fabric

### Modern Mod Configs

Configuring these mods is fairly simple, and when you hover over the options it will give you more detailed information, but I will go over them here

- `Max Shadow Distance` - if you have a high render distance, lower your shadow distance and simulation distance to `12` (the default most likely), it will help with FPS and auto-farms
- make sure everything in the `Preformance` tab is **ON** besaides `Defer Chunk Updates`
- feel free to change any settings in the `Animations`, `Particles`, `Details`, and `Render` tabs
