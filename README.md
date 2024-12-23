#  Simplified example website modifier extension template
## (Name very subject to change)

A template extension made to make the development of new client-side website HTML5 behavior extremely simple 

THIS PROJECT IS CONNECTED TO MY MULTI-PLATFORM EXTENSION GNERATOR APPLICATION AND RETURN-YOUTUBE-UI, UPDATES MAY TAKE TIME TO PROAGATE BETWEEN PROJECTS.

#### Supported Browsers
* Firefox
  * Main priority
  * Every version will be compatible with the latest version of Firefox at publish time
* Chromium-based browsers
  * Lesser priority, dedicated parity updates
  * Most functionality tested with Brave

Due to currently divulging implementation of V3 manifests between Mozilla and Google, to work with Chromium-based browsers instead of Firefox, you must switch the commented lines in manifest.json.
<br>
_manifest.json_
````json
"background": {
  "scripts": ["background/background.js"]//for Firefox
//    "service_worker": "background/background.js"//for Chromium-based
},
 ````

_In the future, the example app the latest release will be published to the Firefox Add-Ons page. To install another version or your own fork, visit [firefox-source-docs.mozilla.org/...](https://firefox-source-docs.mozilla.org/devtools-user/about_colon_debugging/index.html) for instructions (or just enter [about:debugging#/runtime/this-firefox](https://firefox-source-docs.mozilla.org/devtools-user/about_colon_debugging/index.html)) into your url-bar._

Extensions made using this repository
* Return YouTube UI [AddOns](https://addons.mozilla.org/en-US/firefox/addon/return-youtube-ui/) [Github](https://github.com/42null/Return-YouTube-UI)

<div style="text-align: center;">
    <img src="./Screenshots/PopupPageFullSettings_latestTOP.png" alt="[Recent settings screenshot]" width="128" height="auto" />
</div>

---

## Settings & Customization Flags

Settings are currently controlled in a few places. The vast majority, and where all future development will go into is at [./projectConfiguration.json](projectConfiguration.json). This is where extension-specific changes will be made. 
<hr/>

## Generators & Documentation

I am working on making generators to automate as much as this process as possible. As changes are still being made, documentation may be lacking and I have not published any guides yet, but I will be more than happy to answer any questions you may have.

Feel free to message me with any questions or suggestions! :)
