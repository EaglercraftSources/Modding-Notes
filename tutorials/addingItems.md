# how to add items to the the client:

## you must edit the following files
- Create the file at `net/minecraft/item/ItemItemname.java`
- create the item modal at `desktopRuntime/resources/assets/minecraft/models/item/itemname.json`
- add your item to `net/minecraft/init/Items.java`, `net/minecraft/item/Item.java`
- Finnally, to render your item add it to`net/minercaft/client/renderer/entity/RenderItem.java`
