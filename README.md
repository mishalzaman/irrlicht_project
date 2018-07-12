# irrlicht_project
Bare Irrlicht project for Visual Studio 15 (x64)

# Irrlicht Renderer Empty Project

This is a starter project to create 3D applications in Irrlicht, using Visual Code 15 (x64). This repository currently has the bin and lib files setup for Irrlicht, and a demo application that displays a 3D model.

## How to set up from scratch

1. Go to `File` -> `New` -> `Project`.
2. Select an empty project, give it a name and a location.
3. Once the new project has been created, go to the solution explorer and right click on the project name. Select `Properties`.
4. Select the tab fpr `VC++ Directories`.
5. In _Include Directories_ add the Irrlicht _include_ directory for your operating system.
6. In _Library Dependecies_ add the Irrlicht _lib_ directory for you operating system.
7. Now build the project.
8 If you run it and you get an error about a missing irrlicht.dll then you would need to copy the dll file to the executable that was created during the build process. I have to figure out how to include this on build time.

magicVoxel
