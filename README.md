# Firefox-Classic-Photon
This is a collection of some CSS files for restoring Firefox Photon tab-bar's design. Works best with https://addons.mozilla.org/en-US/firefox/addon/photon-default-theme-ink/ but it seems to work fine even with the default light/dark themes.
Please note that this CSS tweak doesn't remove or add any icons from Photon (except for the playing audio icon).


### Installation guide
1. Download the code from this repository. Extract the ZIP file
2. Navigate to `about:config`. Make sure that `toolkit.legacyUserProfileCustomizations.stylesheets` is enabled (if not, set to `true`)
3. Navigate to `about:profiles`. Open your currently active profile's Root directory folder
4. Copy the "chrome" folder (extracted from ZIP file) into your Firefox's profile directory.
5. (Optional) If you like the "Dark blue" colored tab-bar, you can install this theme: https://addons.mozilla.org/en-US/firefox/addon/photon-default-theme-ink

### Sources
I used the code from other repositories and then just added some small tweaks to polish the design.  
https://github.com/pellaeon/firefox-91plus-photon-userchrome  
https://github.com/MrOtherGuy/firefox-csshacks
