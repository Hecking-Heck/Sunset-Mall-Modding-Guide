# Sunset Mall Modding Guide
A comprehensive modding guide for Sunset Mall.

> [!NOTE]
> Right now this guide only shows how to Asset Swap. I am working on a more indepth system and it will be out ASAP!

# Requisites
[FModel](https://fmodel.app)

[UnrealPak](https://github.com/allcoolthingsatoneplace/UnrealPakTool)

[Unreal Engine](https://www.unrealengine.com/en-US)

# Extracting Files
Use [FModel](https://fmodel.app)

# FModel Tutorial
Run Fmodel, click on "Add Undetected game", type any name and enter the directory path to Sunset Mall game. Click on the blue plus button.
Unreal Engine version of the Sunset Mall game is 4.27.1, so use GAME_UE4_27 setting.
Go to settings and enable Local Mapping File
Select Mappings.usmap file under Mapping file path
Now you're able to explore game files and export textures/models and stuff!

Note: Fmodel requires .NET 8.0 Desktop Runtime installed on your computer!

# Get the right version of Unreal Engine
Current version -> Unreal Engine 4.27.1

# Creating the Unreal Engine Project
Creating Unreal Engine 4.27.1 mod project and preparing it

Use Pak file only
Packaging --> Advanced ---> Cook everything  in the project content directory

# Notes on Texture Names
Texture names:

<Texturenamehere>_B = Base texture

<Texturenamehere>_M = MRAO (MetallicRoughnessOcclusionSpecular)

<Texturenamehere>_N = Normal Map

Normal map can be created with online software or Crazybump
MRAO creation tutorial: https://dev.epicgames.com/community/learning/tutorials/6Gn5/creating-mrao-textures-using-free-software

# Cooking the Project
After you have finished with everything in the editor, you can go to File > Cook Content For Windows
After this go to Sunset-Mall-Modding-Guide-main\Saved\Cooked\WindowsNoEditor\SunsetMall\Content\
Copy all of those files into a new folder called whatever your naming your mod but add "_P" on the end.
For Example "SunsetMallTextureOverhaul_P".

Now drag and drop the _P folder you just made onto UnrealPack With Compression, it will make a .PAK file in the location of your folder. This is your mod.

# Installing the mod
Drag the .PAK file to your Sunset Mall Steam Dir, in the Paks folder

``
for example C:\Program Files (x86)\Steam\steamapps\common\Sunset Mall\SunsetMall\Content\Paks
``

Now boot the game up, it should run your mod!

I tested this with a Poster Replacement mod and it worked perfectly!


# Credits

[FModel](https://fmodel.app)

[UnrealPak](https://github.com/allcoolthingsatoneplace/UnrealPakTool)

[Unreal Engine](https://www.unrealengine.com/en-US)
