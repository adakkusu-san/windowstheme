# windowstheme

## Use as Windows theme

Simple :3  
* Right-click either [dark](https://github.com/adakkusu-san/windowstheme/raw/main/nkdpd.theme) or [light](https://github.com/adakkusu-san/windowstheme/raw/main/nkdpl.theme) version
  * click Save Link As or similar
  * then click Save if needed
* With File Explorer
  * go to the folder you downloaded to
  * and run the `.theme` file

## Use as Wine theme

Also simple :3  
* Open up a Terminal
  * `cd` to the folder you want to download it in
  * then do
```bash
wget -nc https://github.com/adakkusu-san/windowstheme/raw/main/nkdpd.theme
```
* You may replace `.theme` with `.reg` if you'd like to import to Registry ^^
* By default, we get the dark version; so, replace `nkdpd` with `nkdpl` for the light one
* Then run `winecfg`
  * go to `[Desktop Integration]` tab
  * click on `[Install theme…]`
  * select the `.theme` file from the folder we saved it in
  * then click `[Apply]` and see if it works
* If you chose to download `.reg` file; `cd` to the folder you downloaded, and do `wine regedit "nkdpd.reg"`

(TODO: When/If I'm going to include more themes here, this file will need to be updated to reflect the added files)
