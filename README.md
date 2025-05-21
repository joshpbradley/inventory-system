# inventory-system
A simple UE5 inventory system implementation built on the the Unreal first person template.

**Setup**
Drag the InventorySystem folder into the content folder in the Unreal Editor.

Launch the L_InventoryDemoLevel level in InventorySystem->ProjectSetup. This should set up the project automatically, but ensure BP_InventoryDemoGameMode is selected in World Settings, which should set up the default pawn to BP_InventoryDemoCharacter, the HUD to BP_InventoryDemoHUD, and the player controller to BP_InventoryDemoPlayerController.

**Controls**
WASD - move
E - pick up item
Tab - open inventory
Esc - close inventory
Up Arrow (↑) / Down Arrow (↓) - zoom mesh in/out in the inventory viewport
right mouse button: rotate viewport mesh/delete item
left mouse button: rotate viewport mesh/select item to view

**Instructions**
Move towards either of the two items (the gun and the 2D voodoo doll) placed in front of your character, and look at the object you wish to pick up.

If the item is in range, you can pick it up using the E key, which will be prompted in the top-left of the screen.

Your inventory can be opened with the Tab key, which will display the items you have picked up within the four item slots on the left. It can be closed with the escape key or by clicking the red button at the top right of the inventory.

In the inventory, use the left mouse button to drag one of the item icons into the middle of the empty space on the right side of the inventory (the item viewport) to inspect it. If the item is 2D (i.e. the voodoo doll) then a larger version of the sprite will appear. If the item is 3D (i.e. the gun) then a gun mesh will appear. You can use the up and down arrow keys to zoom the mesh in and out, and either mouse button using click/drag to rotate the sprite.

When hovering over an icon on the left of the inventory, a right mouse click will remove that item from the inventory and clear it from inspection if currently being viewed in the inventory viewport.

**Credit**
Gun and doll icons made by users Lorc and Skoll. Available on https://game-icons.net
