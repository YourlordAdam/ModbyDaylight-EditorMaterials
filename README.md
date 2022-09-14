# ModbyDaylight-EditorMaterials
Collection of materials for use in Dead by Daylight modding

## Changelog

9/13/22

Added M_Foliage_v2 and MI_Foliage_v2

-This material should be used for Map objects only. it uses the basic BC/ORM/N setup with some extra parameters for grass wind and some Hue/Saturation/Tint parameters for the BC

9/10/22

Added M_BlendMapRgb and MI_BlendMapRgb_AdamInstance

-This material should be used for Map objects only. it uses Vertex Paint to blend textures together Red and Green both use BC/HRM/N textures HRM being an ORM but with Height inplace of AO the Blue channel uses a Color Vector to color the area and a Scalar parameter to control Roughness it uses no actual textures and should only be used for Water like surfaces. 

8/30/22

Updated M_DirtyGlass

-Material should now be 1:1 to in-game.

8/28/22

Added M_DirtyGlass and its instance

8/23/22

Updated M_HairTAA so that the material better matches in-game settings.

8/22/22

Added M_Structures_v2 and its instance

8/17/22

Updated `MI_Slasher_Cust_AdamEmission` and `MI_Camper_Cust_AdamEmission` to have real default values.