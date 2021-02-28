; >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> (PopUpMenu Main Program Update)
"https://popupmenu.github.io/update/update_pum.txt"
A_AppDataCommon "\PopUpMenu_PUM\update\update_pum.txt"

First Line
is Web Last Update Number
; -------------------------------------------
A_AppDataCommon "\PopUpMenu_PUM\update\update_last_pum.txt"

(File Does Not Exist) CREATE it
The first Line will be 0

(File Exist) READ it
if (update_last_pum.txt) < (update_pum.txt)
Loops Download Until (update_last_pum.txt) = (update_pum.txt)
"https://popupmenu.github.io/update/update_" (update_last_pum.txt) + 1 "_pum.zip"

; -------------------------------------------
"https://popupmenu.github.io/update/update_" (update_last_pum.txt) + 1 "_pum.zip"
Can have 1 or More of these Folders in it

AppData\
AppDataCommon\ 
Installed\

AppData\PopUpMenu_PUM
AppDataCommon\PopUpMenu_PUM
Installed\cpl
Installed\ico
Installed\img
Installed\Lib
Installed\support

; >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> (PopUpMenu Main Program Update)



; >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> (Addon Update)
"https://popupmenu.github.io/addons/current_addons.txt"
A_AppDataCommon "\PopUpMenu_PUM\addons\current_addons.txt"

This File is a list of current Addons
photoshop_de
photoshop_en

Checks if 1 or More of the Addon are Inatalled
If Addon is Installed
Downloads the file (update_photoshop_de.txt)
"https://popupmenu.github.io/update/update_" ApplacationName "_" Language ".txt"
A_AppDataCommon "\PopUpMenu_PUM\update\update_" ApplacationName "_" Language ".txt"

; -------------------------------------------

A_AppDataCommon "\PopUpMenu_PUM\update\update_last_" ApplacationName "_" Language ".txt"
EXAMPLE
A_AppDataCommon "\PopUpMenu_PUM\update\update_last_photoshop_de.txt"

(File Does Not Exist) CREATE it
The first Line will be 0

(File Exist) READ it
if (update_last_photoshop_de.txt) < (update_photoshop_de.txt)
Loops Download Until (update_last_photoshop_de.txt) = (update_photoshop_de.txt)
"https://popupmenu.github.io/update/update_" (update_last_pum.txt) + 1 "_photoshop_de.zip"

; -------------------------------------------

"https://popupmenu.github.io/update/update_" (update_last_pum.txt) + 1 "_photoshop_de.zip"
Contains the Folder

Addon\

Addon\photoshop\en

; >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> (Addon Update)



; >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> (Icon Update)
"https://popupmenu.github.io/update/update_icon.txt"
A_AppDataCommon "\PopUpMenu_PUM\update\update_icon.txt"

First Line
is Web Last Update Number
; -------------------------------------------
A_AppDataCommon "\PopUpMenu_PUM\update\update_last_icon.txt"

(File Does Not Exist) CREATE it
The first Line will be 0

(File Exist) READ it
if (update_last_icon.txt) < (update_icon.txt)
Loops Download Until (update_last_icon.txt) = (update_icon.txt)
"https://popupmenu.github.io/update/update_" (update_last_icon.txt) + 1 "_icon.zip"

; -------------------------------------------
"https://popupmenu.github.io/update/update_" (update_last_icon.txt) + 1 "_icon.zip"
Can have 1 or More of these Folders in it

Icons\


Icons\(♔)_(_PopUpMenu_)_(♰)

; >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> (Icon Update)
