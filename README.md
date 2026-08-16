# **🗡️ Class PVP Kits 🏹** 

## 🔎 Overview
Class PVP Kits is a datapack that adds classes such as alchemist, knight, archer and pyromancer into PVP kits. If you like the idea of PVPing with kits based on classes then you would enjoy using this datapack. This project is a [datapack](https://minecraft.wiki/w/Data_pack), which means it requires to be in the world/server files, specifically the datapack folder. Permission Level 2 or more / OP is required to use the commands associated with this datapack.

## ❓ How to use
1. Download relevant version
2. Navigate to your **minecraft instance folder**, select **saves**, then select **your desired world**, and then place the download in your **datapack** folder.
3. Launch Minecraft and start playing your world.
4. Run ```
/datapack enable "file/Class PVP Kits.zip" ```
5. See the section below on how to obtain the kits.

For help with installing datapacks, see [this article](https://minecraft.wiki/w/Tutorial:Importing_a_data_pack).

## ⌘  Commands
**For main menu (v2.0.0+):**

```
/dialog show @s class_kits:menu
```

**Dialog to pick class (v2.0.0+):**

```
/dialog show @s class_kits:pick_class
```

**For a Shulker Box:** 
```
/give @s minecraft:shulker_box[container_loot={loot_table:"class_kits:random_class_kit"}]
```  
 
**For an Ominous Vault:** 
```
/give @s minecraft:vault[block_state={ominous:"true"},block_entity_data={id:"minecraft:vault",config:{key_item:{count:1,id:"minecraft:ominous_trial_key"},loot_table:"class_kits:random_class_kit"}}]
```  
 
**For direct give:** 
```
/loot give @s loot class_kits:random_class_kit
```
 


**You can REPLACE  @s  with a target entity/s. Examples: @s , @a,  username.** See [this article](https://minecraft.wiki/w/Target_selectors) for help with target selectors. 

To get specific class kits rather than random, replace **random_class_kit** with the name of any class. Examples: **alchemist**, **knight**, **assassin**.

## 💡 Suggestions
If you have ideas for more classes to add to this project, feel free to suggest them [here](https://github.com/shadow800000/Class-PVP-Kits/issues), with the label **Enhancement**.

## 📄 Licence Information
This Project is free to download and use. You are allowed to modify this project in any way if used purely for personal use. You are allowed to upload Forks of this project, but credit to the original author of this project is required. "Forks" are defined as modified copies of a project which have diverged substantially from the original project. In accordance with [Minecraft EULA](https://www.minecraft.net/en-us/eula), you are required to keep your project free for download for the End User.
