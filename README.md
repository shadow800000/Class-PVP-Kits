# **🗡️ Class PVP Kits 🏹** 
A Minecraft datapack that adds PVP kits based on different classes. Classes include Alchemist, Beserker, Knight, Archer and more!

## **Overview**
Class PVP Kits is a datapack that adds classes such as alchemist, knight, archer and pyromancer into PVP kits through the use of commands. If you like the idea of PVPing with kits based on classes then you would enjoy using this datapack. This project is a datapack, which means it requires to be in the world/server files, specifically the datapack folder. OP is required to use the commands assocciated with this datapack.

## **How to use**
1. Download relevant version
2. Navigate to your **minecraft instance folder**, select **saves**, then select **your desired world**, and then place the download in your **datapack** folder.
3. Launch Minecraft and Start Playing your world.

## **Commands**
**For a Shulker Box:** 
```
/give <targets> minecraft:shulker_box[container_loot={loot_table:"class_kits:random_class_kit"}]
```  
 
**For an Ominous Vault:** 
```
/give <targets> minecraft:vault[block_state={ominous:"true"},block_entity_data={id:"minecraft:vault",config:{key_item:{count:1,id:"minecraft:ominous_trial_key"},loot_table:"class_kits:random_class_kit"}}]
```  
 
**For direct give:** 
```
/loot give <targets> loot class_kits:random_class_kit
```
 


**REPLACE  <targets>  with the target entity/s. Examples: @s , @a,  username.** See [this article](https://minecraft.wiki/w/Target_selectors) for help with target selectors. 

To get specific class kits rather than random, replace **random_class_kit** with the name of any class. Examples: **alchemist**, **knight**, **assassin**.

## Licence Information
This Project is free to download and use. You are allowed to modify this project in any way if used purely for personal use. You are allowed to upload Forks of this project, but credit to the original author of this project is required. "Forks" are defined as modified copies of a project which have diverged substantially from the original project. In accordance with Minecraft EULA, you are required to keep your project free for download for the End User.
