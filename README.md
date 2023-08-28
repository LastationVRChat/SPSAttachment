# SPSAttachment
This is a edit of https://booth.pm/en/items/3474757

Simple prefab to simplify the process of attaching SPS orifices and rings to VRChat avatar 3.0.
compatible by default with **OSCGoesBrr**
Made for use with Super Plug Shader https://vrcfury.com/sps/

Using only 1 orifice and 1 ring with parent constraints you can cover a wide range of possible penetration points.

      SPS Constraint Attachment
======================================
THIS PREFAB ASSUMES WriteDefaults Off
CHANGING TO WriteDefaults On IS SUPPORTED

1. Import SPS into your project https://vrcfury.com/sps/
2. Import SPSConstraintAttachment.unitypackage into your project
3. From SPSConstraintAttachment folder, drag the SPS_Container prefab onto root of your avatar
4. Unpack SPS_Container prefab in scene
5. Drag the attach points from SPS_Rings and SPS_Orifices groups onto correct bones
6. Position and rotate the points using the guides
7. Delete the GUIDES_DELETE container
8. Merge SPS_FX animator with your FX animator and SPS_EXPRESSIONS with your Expression Parameters
(you can use Avatar 3.0 Manager to simplify the process, available at https://github.com/VRLabs/Avatars-3.0-Manager)
9. Add SPS_MENU to your Expressions Menu as submenu item
10. Test the correct functionality with AV3 Emulator available at https://github.com/lyuma/Av3Emulator
0. Upload your avatar, enjoy!

