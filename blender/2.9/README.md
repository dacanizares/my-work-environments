# Blender 2.9x environment config

## Contents

* userpref: customized user preferences with vertex color set to red and auto depth enabled, for a better user experience.

* startup: custom startup file with units configured to match UE4, a cube of 1x1x1 meter and a gizmo showing the orientation of the exported asset.

## Instructions

> Before doing this! Open Blender and go to **File > Defaults > Save Startup File** to generate the configuration folder.

Open the Blender user directory on your OS:

 * Windows:
    ```
    %USERPROFILE%\AppData\Roaming\Blender Foundation\Blender\
    ```
* Linux:
    ```
    $HOME/.config/blender/
    ```
* Mac:
    ```
    /Users/$USER/Library/Application Support/Blender/
    ```
    
Inside that directory, open the folder configuration folder for yor Blender version (EX: **2.9/config**, **2.91/config**, etc).

Copy the **.blend** files contained in this repo that you want to apply to your configuration (it could be just one or both).