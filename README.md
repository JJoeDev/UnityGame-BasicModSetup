# A basic guide for unity game mods (BepInEx setup not included)

The first thing you will need to do is get [Visual Studio](https://visualstudio.microsoft.com) installed. Download the comunity edition as its free.

Once you have Visual studio (VS) Installed and launched you will have to add some packages. You need .NET desktop development.

After the selected packages have been installed you will have to make a project for your mod. Click "Create a new project".

Now you will have to find the C# Class Library template, the description should be "A project for creating a class library that targets .NET or .NET Standard"
If you are unable to find that spicific template the "Class Library (.NET Framework)" will also work fine.

## Before we set up the class we need to get the dependencies

First you need to go to your games folder. I will be using Gorilla Tag as my game.

Now you will need to follow the path Gorilla Tag_Data\Managed and we can now get all the dependencies we need. Copy them to a blace you can find again.

Files such as 0Harmony.dll, BepInEx.dll, Bepinject.dll, Utilla.dll, Zenject.dll, and Zenject-usage.dll will not be in this folder and some is made for other mods.

After this we need to go to Gorilla Tag\BepInEx\core and get the following files. 0Harmony.dll and BepInEx.dll.

# Class Library Setup

Once you have selected this template and clicked next you can give it a name and a save location you can find.

After that you will need to select ".NET Standard 2.0"
