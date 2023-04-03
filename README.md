# DPSAttachment
Simple prefab to simplify the process of attaching DPS orifices and rings to VRChat avatar 3.0.
Made for use with Dynamic Penetration System by Raliv https://raliv.booth.pm/items/2825903

Using only 1 orifice and 1 ring with parent constraints you can cover a wide range of possible penetration points. The lights of the orifices have been optimized to minimize clashing with other DPS in the scene.

**How To**
======================================
THIS PREFAB ASSUMES WriteDefaults On

1. Import DPS_ATTACH.unitypackage into your project
2. From DPS_Attach folder, drag the DPS_Container prefab onto root of your avatar
3. Unpack DPS_Container prefab in scene
4. Drag the attach points from DPS_Rings and DPS_Orifices groups onto correct bones
5. Position and rotate the points using the guides
6. Delete the GUIDES_DELETE container
7. Merge DPS_FX animator with your FX animator and DPS_EXPRESSIONS with your Expression Parameters
(you can use Avatar 3.0 Manager to simplify the process, available at https://github.com/VRLabs/VRChat-Avatars-3.0)
8. Add DPS_MENU to your Expressions Menu as submenu item
9. Test the correct functionality with AV3 Emulator available at https://github.com/lyuma/Av3Emulator
0. Upload your avatar, enjoy!
