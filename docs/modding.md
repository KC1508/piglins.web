---
sidebar_position: 2
---

# Modding
Applies to the **Java Edition** of Minecraft only.

:::danger
Due to liability risks, **we cannot help** with **installing mod loaders**, **mods (.jars)** or **any other modifications** outside of this documentation page. **Some mods** may **contain malware** - research everything you're downloading and **consider installing a strong antivirus**. 
:::

### What's modding?
Customizing the visual and auditory aspects of Minecraft, and even modifying its gameplay in some cases. This involves adjusting graphics settings, introducing novel mechanics, designing new blocks, and changing your character's appearance. It's important to note that certain mods may not function correctly with Piglins as they were originally designed for singleplayer or modded server use.
<details>
  <summary>What type of mods are allowed?</summary>
  <div>
    <div>In most cases, any mod that <b>doesn't give the player an unfair advantage</b> over others is <b>allowed</b>. For specific cases or more information, please consider reading our <a href="#">server rules</a> page. Always reach out to a community admin if you're unsure.</div>
  </div>
</details>

### Prerequisites
- Updated modding loader ([Fabric](https://fabricmc.net/), [Forge](https://files.minecraftforge.net/), [Quilt](https://quiltmc.org/), etc).
- Vanilla game version of the mod launcher you're installing.
- At least one successful connection to our server from Minecraft: Java.

### Installing Fabric
*\*these are simplified instructions, consider reading their docs at [the wiki](https://fabricmc.net/wiki/install)*
1. Download [the Fabric installer](https://fabricmc.net/use/installer/).
2. Open to configure mapping/loader version (use Piglins's latest supported game version).
3. Click install. This creates a new game profile you may have to manually select in the launcher.

### Installing Mods
*\*see below for common mods, in this example we're installing [Sodium](https://modrinth.com/mod/sodium)*
1. Download the latest [Sodium](https://modrinth.com/mod/sodium/versions) and [Fabric API](https://modrinth.com/mod/fabric-api) versions if applicable.
2. Find your `.minecraft` data folder (usually in `C:\Users\{user}\AppData\Roaming`) by doing `Win + R`.
3. Inside `.minecraft`, create a `mods` folder.
4. Drop & drop the `sodium-fabric-mcx.xx.x-x.x.x.jar` and `fabric-api-x.xx.x+x.xx.x.jar` into `mods` if applicable.
5. Launch Minecraft and select **fabric-loader-x.xx.x** in the bottom left or under installations.
6. Click "**PLAY**".

### Common Mods
*\*primarily designed for [Fabric](https://fabricmc.net/)*
- **[Iris](https://modrinth.com/mod/iris)** [*alt](https://github.com/IrisShaders/Iris) (modern shaders)
- **[Sodium](https://modrinth.com/mod/sodium)** [*alt](https://github.com/CaffeineMC/sodium-fabric) (client optimization)
- **[Lithium](https://modrinth.com/mod/lithium)** [*alt](https://github.com/CaffeineMC/lithium-fabric) (client optimization)
- **[Zoomify](https://modrinth.com/mod/zoomify)** [*alt](https://github.com/isXander/Zoomify) (spyglass client zooming)
- **[Fabric API](https://modrinth.com/mod/fabric-api)** [*alt](https://github.com/FabricMC/fabric) (lightweight modular API)
- **[LambDynamicLights](https://modrinth.com/mod/lambdynamiclights)** [*alt](https://github.com/LambdAurora/LambDynamicLights) (dynamic lighting)

### Other tips
- **Never** download from sketchy or suspicious websites, including us!
- Ensure when installing mods, you **check their dependencies** (APIs, etc).
- When using lots of mods, you may want to consider **increasing your JVM Arguments**.
    - Launch Minecraft and click "Installations" at the top.
    - Find **fabric-loader-x.xx.x** and click the `...` on the right, then "Edit".
    - When the new menu opens, click "More Options" at the bottom right.
    - Edit `-Xmx{value}G`. Default is 2G = 2 gigabytes of memory allocation.
        - We suggest 4G or 6G if your computer has enough available memory.