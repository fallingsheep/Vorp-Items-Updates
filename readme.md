# VORP ITEM UPDATES

This repo holds the standalone  item updates that are now included in the VORPCore premade server files

# Item Description Updates  
This SQL will update the orginal 728 items with descriptions

## **WARNING!**  
always take a backup before changing/updating any files or databases!

### **INSTALLATION**    
run the **updateDB_item_descriptions_orginalitems.sql** to update the item descriptions


# 200+ new items
This will add 200+ new items and there icons

## **WARNING!**  
always take a backup before changing/updating any files or databases!

### **INSTALLATION**  
inside the folder **200+ New items** you will find a folder called **img** and a SQL file called **insertDB_new_items.sql**

run the **insertDB_new_items.sql** to add the new items to the database

you then copy the **img** folder to **resources\\[VORP]\\[vorp_essentials]\vorp_inventory\html**


# Store updates
This adds ALL items from the premade files to the stores
(if you dont have the new items see the 200+ new items update)

- adds 10 new stores
- all items support the random prices (min,max)
- no weapons,ammo or weapon parts are included (this will be a seperate update)
- no 'doctor items'are included (this will be a seperate update)

## **WARNING!**  
always take a backup before changing/updating any files or databases!  
this adds EVERY ITEM to the stores so you will need to remove what you dont want to buy/sell  
(eg if you dont want handcuffs sold/bought then remove them, best way is to comment them out)  
buy and sell prices are not balanced in any way  
the only "balance" is items sell for approx half the buy cost  

### **INSTALLATION**  
simply copy the **config.lua** to **resources\\[VORP]\vorp_stores** folder overwriting the existing one

### **NEW STORES**  
- Adds 5 new "Trapper" stores there locations are the same as the story/online
(Saint Denis, Tall Trees, Near Riggs Station, Near Strawberry, Near Elysian Pool)
- Adds 4 new "Fence"stores there locations are the same as the story/online
(Saint Denis, ThievesLanding, Rhodes, Emerald Ranch)
- Adds the Lagras Bait shop

### **CATERGORYS**  
Items are split into the following catergorys
- "Fish"
- "Bait"
- "Furniture & Decor"
- "Food"
- "Meat"
- "Drinks"
- "Documents & Books"
- "Horse & Pets"
- "Misc"
- "Materials"
- "Herbs & Plants"
- "Fertilizer"
- "Liquor"
- "Tools"
- "Rare Plants"
- "Seeds"
- "Sweets"
- "Animals & Pelts"
- "Legendary"
- "Moonshine"
- "Valuables"

### **DEFAULT STORE CATERGORYS**  
**Bait stores**  
"Fish","Bait"

**General stores**  
"Furniture & Decor","Food","Meat","Drinks","Documents & Books",
"Horse & Pets","Misc","Materials","Herbs & Plants","Fertilizer",
"Liquor","Tools","Rare Plants","Seeds","Sweets"

**Trappers**  
"Animals & Pelts","Legendary"

**Fences**  
"Moonshine","Valuables"