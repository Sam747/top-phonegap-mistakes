# Core Plugins Setup#


**Phonegap Build**
- http://docs.build.phonegap.com/en_US/configuring_plugins.md.html#Plugins
- http://docs.build.phonegap.com/en_US/configuring_plugins.md.html#plugin-params

**To version or not to version.**

- Do **not set** the version, get the latest and greatest. However, as version change so does the chance for you code to break.
- Do **set** the version, your code will always work. Make the chanes at your pace, not those of the Cordova "core" team.

Source: https://cordova.apache.org/news/2015/06/22/plugins-release.html<br>
**Versions set**
```
<gap:plugin name=cordova-plugin-battery-status source=npm version=1.1.0 />
<gap:plugin name=cordova-plugin-camera         source=npm version=1.2.0 />
<gap:plugin name=cordova-plugin-console        source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-contacts       source=npm version=1.1.0 />
<gap:plugin name=cordova-plugin-device         source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-device-motion  source=npm version=1.1.1 />
<gap:plugin name=cordova-plugin-device-orientation source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-dialogs        source=npm version=1.1.1 />
<gap:plugin name=cordova-plugin-file           source=npm version=2.1.0 />
<gap:plugin name=cordova-plugin-file-transfer  source=npm version=1.2.0 />
<gap:plugin name=cordova-plugin-geolocation    source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-globalization  source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-inappbrowser   source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-legacy-whitelist source=npm version=1.1.0 />
<gap:plugin name=cordova-plugin-media          source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-media-capture  source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-network-information source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-splashscreen   source=npm version=2.1.0 />
<gap:plugin name=cordova-plugin-statusbar      source=npm version=1.0.0 />
<gap:plugin name=cordova-plugin-test-framework source=npm version=1.0.1 />
<gap:plugin name=cordova-plugin-vibration      source=npm version=1.2.0 />
<gap:plugin name=cordova-plugin-whitelist      source=npm version=1.1.0 />
```

**NO Versions set**
```
<gap:plugin name=cordova-plugin-battery-status source=npm />
<gap:plugin name=cordova-plugin-camera         source=npm />
<gap:plugin name=cordova-plugin-console        source=npm />
<gap:plugin name=cordova-plugin-contacts       source=npm />
<gap:plugin name=cordova-plugin-device         source=npm />
<gap:plugin name=cordova-plugin-device-motion  source=npm  />
<gap:plugin name=cordova-plugin-device-orientation source=npm />
<gap:plugin name=cordova-plugin-dialogs        source=npm />
<gap:plugin name=cordova-plugin-file           source=npm />
<gap:plugin name=cordova-plugin-file-transfer  source=npm />
<gap:plugin name=cordova-plugin-geolocation    source=npm />
<gap:plugin name=cordova-plugin-globalization  source=npm />
<gap:plugin name=cordova-plugin-inappbrowser   source=npm />
<gap:plugin name=cordova-plugin-legacy-whitelist source=npm />
<gap:plugin name=cordova-plugin-media          source=npm />
<gap:plugin name=cordova-plugin-media-capture  source=npm />
<gap:plugin name=cordova-plugin-network-information source=npm />
<gap:plugin name=cordova-plugin-splashscreen   source=npm />
<gap:plugin name=cordova-plugin-statusbar      source=npm />
<gap:plugin name=cordova-plugin-test-framework source=npm />
<gap:plugin name=cordova-plugin-vibration      source=npm />
<gap:plugin name=cordova-plugin-whitelist      source=npm />
```