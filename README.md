# OGFN CUSTOM ITEM SHOP TUTO
## First you are going to want to find the IDS with https://fortnite.gg/cosmetics

**In the catalog.json or catalog_config.json of your backend (can be different) you will be met with the item shop template**

"//": "BR Item Shop Config",
  "daily1": {
      "itemGrants": [""],
      "price": 1500

Look for this: "itemGrants": [""],

Between the quotation marks set it to **example: AthenaCharacter:ID** -- Item id goes there

*Notice: you cant put ch2 skin id's and expect them to be magically ported lol*


# Here is a list of item types
## Skins - AthenaCharacter
## Emotes - AthenaDance
## Pickaxes - AthenaPickaxe
## Backblings - AthenaBackpack
## Gliders - AthenaGlider
## Wraps - AthenaItemWrap
## Loading Screens - AthenaLoadingScreen
## Contrails - AthenaSkyDiveContrail

-----------------------------
-----------------------------
# Example of a correct template ✅:

## itemGrants": ["AthenaPickaxe:Pickaxe_ID_376_FNCS"],

-----------------------------
----------------------------
# Incorrect templates ❌:
## "itemGrants": ["AthenaCharacter:Pickaxe_ID_376_FNCS"], --- Use the proper item type

## "itemGrants": [AthenaCharacter:Pickaxe_ID_376_FNCS], --- Remember the **quotation marks**
------------------------------
--------------------------------


**Hit save after setting everything and then boom, now you have made a custom item shop!**


