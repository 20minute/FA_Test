# FA_Test
For testing purposes, each object currently supports only a single interaction mode. However, the current architecture is fully prepared for easy extension to multiple interaction modes. Logic is cleanly decoupled using Actor Components, and any unused UI widgets are properly destroyed to manage memory.

### How to Play

1. Press `E` to interact (pick up items or trigger dialogue).
2. Press `I` to open the inventory.
3. Drag an item to the preview slot:
    - If 2D → Large icon appears.
    - If 3D → Mesh appears, rotatable and zoomable.
5. Use the mouse to rotate, scroll to zoom.
6. Click `Forget Notes` button to remove 2D assets and refresh the inventory UI.
7. Press `0` or use the Close button to exit.


### TODO

1. Replace structs with Data Assets for dialogue entries and inventory items.
2. Refactor the inventory system to remove the hardcoded 4-slot limitation and support dynamic slot counts.