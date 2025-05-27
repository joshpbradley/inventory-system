# inventory-system
A simple UE5 inventory system implementation built on the Unreal First Person project template.

**Setup**

Drag the InventorySystem folder into the content folder in the Unreal Editor.

Launch the L_InventoryDemoLevel level in InventorySystem->ProjectSetup. This should set up the project automatically, but ensure BP_InventoryDemoGameMode is selected in World Settings, which should set up the default pawn to BP_InventoryDemoCharacter, the HUD to BP_InventoryDemoHUD, and the player controller to BP_InventoryDemoPlayerController.

**Controls**

• WASD - move

• E - pick up item

• Tab - open inventory

• Esc - close inventory

• Up Arrow [↑] / Down Arrow [↓] - zoom mesh in/out in the inventory viewport

• Right mouse button:= - rotate viewport mesh/delete item

• Left mouse button - rotate viewport mesh/select item to view

• R - reset the demonstration

• Enter - exit the demonstration

**Instructions**

• Move towards either of the two items (the gun and the 2D voodoo doll) placed in front of your character, and look at the object you wish to pick up.

• If the item is in range, you can pick it up [E] which will be prompted in the top-left of the screen.

• Open your inventory [Tab] to display the items you have picked up within the four item slots on the left.

• In the inventory, drag [left mouse btn] one of the item icons into the middle of the empty space on the right side of the inventory (the item viewport) to inspect it. If the item is 2D (i.e. the voodoo doll) then a larger version of the sprite will appear. If the item is 3D (i.e. the gun) then an interactable 3D static mesh will appear.

• During item inspection you can zoom the mesh in and out [↑]/[↓] and rotate it [left mouse btn]/[right mouse btn].

• You can remove any item from the inventory [right mouse btn] while hovering over its icon - this will clear the viewport if that item is currently being inspected.

• Close the inventory [Esc], or by clicking the red button at the top right of the inventory to resume play.

**Credit**
Gun and doll icons made by users Lorc and Skoll. Available on https://game-icons.net
