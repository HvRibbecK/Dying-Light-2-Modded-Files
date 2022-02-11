# Dying Light 2 Modded Files
 DL2 Modded Game Files

## Unlimited Weapon Durability (all difficulties)
-> scripts\player\player_variables.scr (Normal)
-> scripts\player\player_variables_easy.scr (Easy)
-> scripts\player\player_variables_nightmare.scr (Hard)

Standard Value: 
-> Param("MeleeWpnDurabilityMulReduce", "1.0");
Modded Value:
-> Param("MeleeWpnDurabilityMulReduce", "0.0");

## Bigger Stack Size 
-> scripts\inventoy\inventory.scr

Standard Value (for 70 items (Craft Components and Valuables)):
-> MaxStackCount(999);
Modded Value:
-> MaxStackCount(9999);

Standard Value (for 216 items (Ammo, Throwables, Lockpicks, Powerups etc.)):
-> MaxStackCount(99);
-> MaxAmmoCount(60);
Modded Value:
-> MaxStackCount(9999);
-> MaxAmmoCount(9999);

## Bigger Inventory, Storage and Quick Wheel Size
-> scripts\player\player_variables.scr (Normal)
-> scripts\player\player_variables_easy.scr (Easy)
-> scripts\player\player_variables_nightmare.scr (Hard)

Standard Value (Weapons):
-> Param("QuickSlotsCount", "24");
Modded Value:
-> Param("QuickSlotsCount", "48");

Standard Value (Equipment):
-> Param("EquipmentSlotsCount", "16");
Modded Value:
-> Param("EquipmentSlotsCount", "32"); 

Standard Value (Consumables):
-> Param("ConsumableSlotsCount", "16");   
Modded Value:
-> Param("ConsumableSlotsCount", "32");   

Standard Value (Ammo):
-> Param("AmmoSlotsCount", "12");
Modded Value:
-> Param("AmmoSlotsCount", "24");

Standard Value (Storage Equipment):
-> Param("StorageEquipmentSlotsCount", "25");
Modded Value:
-> Param("StorageEquipmentSlotsCount", "50");

Standard Value (Storage Consumables):
-> Param("StorageConsumamblesSlotsCount", "25");
Modded Value:
-> Param("StorageConsumamblesSlotsCount", "50");

Standard Value (Storage Other):
-> Param("StorageOtherSlotsCount", "50");
Modded Value:
-> Param("StorageOtherSlotsCount", "100");