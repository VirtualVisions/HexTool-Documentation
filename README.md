# HexTool Documentation
![HexTool Banner](/Media/HexTool_Documentation_Header.png)

HexTools can be accessed via the Tools menu.
In Unity 6 and up, it will appear at the end of the list.
In Unity 2021 / 2023, it will appear in a dropdown at the bottom of this list.

It can also be accessed with the shortcut "U".
This can be adjusted through Unity's Shortcuts menu to suit the user's taste.

![Tools Menu](/Media/Tools_Menu.png)

With HexTool selected, objects will snap to the visible hexagon grid, while moving smoothly on the axis the grid is oriented on.
The arrow handle fully respects the Transform settings, aligning to either Center/Pivot and Global/Local when selected.
All hexagonal grid snapping is in world-space and relative to the origin of the scene.

https://github.com/user-attachments/assets/728a1144-9081-4afb-bdeb-de5188f6082c

## Settings

HexTool's Settings can be accessed by enabling it from the SceneView Overlays menu.

In **Unity 6 and up**, it can be enabled from the floating Overlay Menu.

![Overlay Menu](/Media/Overlay_Menu.png)

In **Unity 2021 / 2022**, it can be enabled via the SceneView's Overlays popup menu through the "Kebab" 
(or the "More Options") button on the top right of the SceneView tab.

![Overlay Menu Popup](/Media/Overlay_Menu_Popup.png)

Once open, the HexTool overlay displays all the settings available for the tool.
This can either float on its own, be snapped to a corner, or docked on the sides, containing a dropdown of all HexTool settings.

![HexTool Overlays Menu](/Media/HexTool_Overlays_Menu.png)

![Toolbar Docked](/Media/Toolbar_Docked.png)

If the user prefers not to use the Overlay menu, all the HexTool options will appear within the Project Settings under "HexTool."

![Project Settings](/Media/Project_Settings.png)

All HexTool settings are project-specific, so the user can have different settings associated with different projects.

| Setting     | Description                                                                                             |
|-------------|---------------------------------------------------------------------------------------------------------|
| Unit Size   | Total diameter of the hexagon, point to point.                                                          |
| Radius      | Approximate distance from the center the grid expands to.                                               |
| Opacity     | Opacity of the center of the grid.                                                                      |
| Grid Color  | Color used for displaying the grid within the SceneView.                                                |
| Direction   | Whether the hexagons should be stacked horizontally with rows, or vertically with columns.              |
| Orientation | The global direction the grid aligns to.\n3D games will likely use Y, while 2D games will likely use Z. |