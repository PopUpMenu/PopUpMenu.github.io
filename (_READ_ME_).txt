>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
A_AppDataCommon "\PopUpMenu_PUM\addons"
any addon menu text file must start with "addon_"
A_AppDataCommon "\PopUpMenu_PUM\addons\(APP NAME)\(LANG)\addon_(APP NAME)_(LANG).txt
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
(CREATE)(UPDATE)(ZIP)
Addon Update zip
update_(UPDATE NUMBER)_(APP NAME)_(LANG).zip

Folder in Zip
\Addon\

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
(CREATE)(UPDATE)(ZIP)
PUM Update zip
update_(UPDATE NUMBER)_pum.zip

Folders in Zip (Must have at least one)
\AppDataCommon\ (OPTIONAL)
\AppData\       (OPTIONAL)
\Installed\     (OPTIONAL)

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
(Web Locations)

Update Zips
"SiteROOT"/update/zip/(ZIP NAME)

Current PUM Update Txt File
"SiteROOT"/update/update_pum.txt

Current Addon Update Txt File
"SiteROOT"/update/update_(APP NAME)_(LANG).txt

Current Addons
"SiteROOT"/system/current_addons.txt

Used in F_ConnectCheck()
"SiteROOT"/system/connect_check.html

Addon Html Pages
"SiteROOT"/addons/(APP NAME)_(LANG).html
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
