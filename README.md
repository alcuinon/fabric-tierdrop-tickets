# TierDrop

**TierDrop** is a server-side Minecraft mod that introduces a dynamic tier system for equipment, bringing a variety of gear with different power levels and stats. Designed with both PvP and exploration in mind, this mod enhances the gameplay experience by adding tiers to equipment and expanding rewards through various in-game features.

## Features:
- **Tiered Equipment**: Equipment drops, chests, and vaults now come with randomly assigned tiers, offering a broad range of gear for players to collect and use.
- **Trial Chamber Vaults**: Players can earn higher-tier equipment and additional rewards when opening **Trial Chamber Vaults**, adding depth to exploration and increasing the incentive to use these chambers.
- **Vault Rewards**: Upon opening a vault, there is a chance for players to receive additional equipment rewards, making the experience even more rewarding and engaging.
- **PvP Enhancements**: The variety in equipment tiers creates a more dynamic and competitive PvP environment, encouraging players to strategize and equip themselves with the best available gear.
- **Server-Side Mod**: The mod is optimized to work seamlessly on the server side, without requiring client-side modifications.
- **Higher-Tier Increases Chance**: Players that spent a lot of time have a better chance to get higher tiers.

![Equipments found on chest will now have a tiers](https://cdn.modrinth.com/data/cached_images/0234966a5c975aadcd17dd60f7ef4500fea05ed0.png)

## Configurations
- You can **add** tiers or **update/remove** existing tiers
- Don't worry I added a guide in the **tierdrop_config.json**

```
"Armor": [
      {
        "prefix": "Test",
        "color": "GRAY",
        "chance": [45, 40, 20],
        "attributes": [
          { "All": ["ARMOR", 1, 1.5] },
          { "All": ["MAX_HEALTH", 2, 4] }
        ]
      },
]
```
For easy testing (add this in config and make sure after testing this should be remove or empty)

```
"Test": [
      {
        "prefix": "Test",
        "color": "YELLOW",
        "chance": [50, 50, 100],
        "attributes": [
          { "All": ["ARMOR", 1, 1.5] },
          { "All": ["MAX_HEALTH", 2, 4] }
        ]
      }
]
```
  

## Future Plans:
- **Balance Improvements**: The mod will continue to evolve with regular updates to fine-tune the balance of equipment tiers, ensuring fair gameplay for all.
- **Additional Features**: New mechanics and features will be added over time, further enhancing the gameplay and expanding the possibilities for players.

## Installation:
- Place the mod file in your Minecraft server's `mods` folder.
- Restart the server to apply the changes.

## Compatibility:
- **Fabric**: Compatible with Minecraft versions [1.21.1, 1.21.4].
- **Multiplayer**: Fully functional on multiplayer servers.

## Incompatibility:
- 

---

Feel free to provide feedback or suggestions for new features! Stay tuned for more updates to improve **TierDrop** and its gameplay experience.
