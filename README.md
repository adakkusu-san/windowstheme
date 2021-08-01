# windowstheme

## Use as Windows theme

Simple :3  
* Right-click either [dark](https://github.com/adakkusu-san/windowstheme/raw/main/nkdpd.theme) or [light](https://github.com/windowstheme/raw/main/nkdpl.theme) version
  * click Save Link As or similar
  * then click Save if needed  
* With File Explorer
  * go to the folder you downloaded to
  * and run the `.theme` file

## Use as Wine theme

Also simple :3  
* Open up a Terminal
  * and write the following in it
```bash
pushd ~/Downloads/
wget -nc https://github.com/adakkusu-san/windowstheme/raw/main/nkdpd.theme
popd
```
* You may instead replace `.theme` with `.reg` if you prefer to import to Registry instead ^^
* By default, we get the dark version; so, replace `nkdpd` with `nkdpl` for the light one  
  * (And if needed, replace `~/Downloads` with another folder of your choice)  
* Then run `winecfg`
  * go to `[Desktop Integration]` tab
  * click on `[Install theme…]`
  * select the `.theme` file from the folder we saved it in
  * then click `[Apply]` and see if it works
* If you instead chose to download .reg file instead, `cd` to the folder you downloaded, and do `wine regedit "nkdpd.reg"`

(TODO: When/If I'm going to include more themes here, this file will need to be updated to reflect the added files)
