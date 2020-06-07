# Blender 2.8x environment config

## Contents

* userpref: customized user preferences with vertex color set to red and auto depth enabled, for a better user experience.

* startup: custom startup file with units configured to match UE4, a cube of 1x1x1 meter and a gizmo showing the orientation of the exported asset.

## Instructions

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
    
Inside that directory, open the folder representing the installed Blender version (EX: 2.8, 2.83, etc).

Copy the **.blend** files contained in this repo that you want to apply to your configuration (it could be just one or both).