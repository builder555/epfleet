# Change Log

All notable changes to this project will be documented in this file
automatically by Versionist. DO NOT EDIT THIS FILE MANUALLY!
This project adheres to [Semantic Versioning](http://semver.org/).

# v1.3.2
## (2023-01-27)

* Reducing image size by removing Docker as a dependency [Aurelien VALADE]

# v1.3.1
## (2023-01-23)

* Bumping Etcher version to v1.14.3 [Aurelien VALADE]

# v1.3.0
## (2023-01-17)


<details>
<summary> chore(deps): update etcher digest to 407138c [Renovate Bot] </summary>

> ## etcher-1.14.2
> ### (2023-01-17)
> 
> * patch: revert to lockfile v1 [Peter Makra]
> * patch: update etcher-sdk for cm4v5 [builder555]
> 
> ## etcher-1.14.1
> ### (2023-01-16)
> 
> * fix disabled-screensaver unhandled exception outside balena-electron env [Edwin Joassart]
> 
> ## etcher-1.14.0
> ### (2023-01-16)
> 
> * Anonymizes all paths before sending [Otávio Jacobi]
> * patch: Sentry fix path [Edwin Joassart]
> * Remove personal path on etcher [Otávio Jacobi]
> * Unifying sentry reports in a single project [Edwin Joassart]
> * Removes corvus in favor of sentry and analytics client [Otávio Jacobi]
> * Removes corvus in favor of sentry and analytics client [Otávio Jacobi]
> 
> ## etcher-1.13.4
> ### (2023-01-12)
> 
> * Adding EtcherPro device serial number to the Settings modal [Aurelien VALADE]
> 
> ## etcher-1.13.3
> ### (2023-01-11)
> 
> * patch: progress cm4 to second stage [Peter Makra]
> 
> ## etcher-1.13.2
> ### (2023-01-02)
> 
> * patch: fixed winget parameter name [mcraa]
> 
> ## etcher-1.13.1
> ### (2023-01-02)
> 
> * patch: updated sdk to fix bz2 issue [Peter Makra]
> * patch: update copyright in electron-builder [JOASSART Edwin]
> 

</details>

# v1.2.5
## (2023-01-05)

* patch: revert electron env to 1.2.9 [mcraa]
* Patch: removed redundant copy [Peter Makra]
* patch: rebased to new build process [Peter Makra]
* patch: etcher repo with sdk 7.2.4, ext2fs build handling [Peter Makra]
* Patch: testing modified build process to fix etcher [builder555]

# v1.2.4
## (2022-12-16)

* Update dependency @types/node to 18.11.11 [Renovate Bot]

# v1.2.3
## (2022-12-07)

* Fixing screensaver restart delay [Aurelien VALADE]

# v1.2.2
## (2022-12-06)

* Adding image pruning at startup to prevent disk saturation [Aurelien VALADE]

# v1.2.1
## (2022-11-24)

* added test checklist [builder555]

# v1.2.0
## (2022-11-23)

* Fixing LEDs colors configuration [Aurelien VALADE]
* Fixing the build with the newer versions of Etcher for Etcher Pro [wolvi-lataniere]

# v1.1.0
## (2022-11-11)

* Adding fan control block to the fleet [Aurelien VALADE]

# v1.0.8
## (2022-10-13)

* Switch to Flowzone [ab77]

# v1.0.7
## (2022-09-21)

* patch: added comment to separate dockerfile [mcraa]

# v1.0.6
## (2022-01-27)

* patch: fixed run righst in dockerfile [Peter Makra]
* patch: fixed exfat install with update first [Peter Makra]
* patch: added exfat libs [Peter Makra]

# v1.0.5
## (2022-01-27)

* patch: added submodules checkout [Peter Makra]
* patch: [gh] added secret variable name [skip ci] [Peter Makra]
* patch: added submodules checkout [Peter Makra]
* patch: [gh] added secret variable name [skip ci] [Peter Makra]
* patch: [gh] added secret variable name [skip ci] [Peter Makra]

# v1.0.4
## (2022-01-27)

* patch: added private proprety to package json [Peter Makra]

# v1.0.3
## (2021-09-13)

* Update balena-electron-env from v1.2.8 to v1.2.9 [Lorenzo Alberto Maria Ambrosi]
* Update etcher from v1.5.121 to v1.5.122 [Lorenzo Alberto Maria Ambrosi]
* Convert config script to TypeScript [Lorenzo Alberto Maria Ambrosi]

# v1.0.2
## (2021-05-26)

* Update balena-electron-env from v1.2.5 to v1.2.6 [Lorenzo Alberto Maria Ambrosi]
* Limit configs volume to include just etcher's configs [Lorenzo Alberto Maria Ambrosi]
* Remove pwm duty cycle config [Lorenzo Alberto Maria Ambrosi]
* Update balena-electron-env from 1.2.4 to 1.2.5 [Lorenzo Alberto Maria Ambrosi]

# v1.0.1
## (2021-04-07)


<details>
<summary> Update balena-electron-env from 1.2.1 to 1.2.4 [Alexis Svinartchouk] </summary>

> ## balena-electron-env-1.2.4
> ### (2021-04-06)
> 
> * Set contextIsolation to false [Alexis Svinartchouk]
> * Update dependencies [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.2.3
> ### (2021-04-06)
> 
> * Update project name and url in package.json [Alexis Svinartchouk]
> * Update electron to v12.0.2 [Alexis Svinartchouk]
> * Fix typo in README.md [Andrew Scheller]
> * Update rendition from 19.0.0 to 20.10.1 [Alexis Svinartchouk]
> * Update @balena/lint to to v5.4.1 [Alexis Svinartchouk]
> * Don't connect to a network when the "Configure" button is pressed [Alexis Svinartchouk]
> * Update electron to v11.2.3 [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.2.2
> ### (2021-02-03)
> 
> * Add .versionbot/CHANGELOG.yml [Alexis Svinartchouk]
> 
</details>


<details>
<summary> Update etcher from 1.5.116 to 1.5.117 [Alexis Svinartchouk] </summary>

> ## etcher-1.5.117
> ### (2021-04-02)
> 
> * Rename mac releases (keep old naming) [Alexis Svinartchouk]
> * Disable spectron tests on macOS [Alexis Svinartchouk]
> * Update electron to v12.0.2 [Alexis Svinartchouk]
> 
> <details>
> <summary> Update etcher-sdk from 6.1.1 to 6.2.1 [Alexis Svinartchouk] </summary>
> 
>> ### etcher-sdk-6.2.1
>> #### (2021-03-26)
>> 
>> 
>> <details>
>> <summary> Update node-raspberrypi-usbboot from 0.2.11 to 0.3.0 [Alexis Svinartchouk] </summary>
>> 
>>> #### node-raspberrypi-usbboot-0.3.0
>>> ##### (2021-03-26)
>>> 
>>> * Add support for compute module 4 [Alexis Svinartchouk]
>>> * Fix size endianness of boot_message_t message [Alexis Svinartchouk]
>>> 
>> </details>
>> 
>> 
>> ### etcher-sdk-6.2.0
>> #### (2021-02-18)
>> 
>> * Added BeagleBone USB Boot example [Parthiban Gandhi]
>> * Added BeagleBone USB Boot support [Parthiban Gandhi]
>> 
> </details>
> 
> * Fix getAppPath() returning an asar file on macOS [Alexis Svinartchouk]
> * Grammar fix [Andrew Scheller]
> * (docs) update README.md [vlad doster]
> * Update copyright year in electron-builder.yml [Andrew Scheller]
> * Update copyright year in .resinci.json [Andrew Scheller]
> * Separate the Yum and DNF instructions. [Dugan Chen]
> * Set msvs_version to 2019 when rebuilding [Alexis Svinartchouk]
> * Use moduleIds: 'natural' in webpack config to keep js files in arm64 and x64 mac builds identical [Alexis Svinartchouk]
> * Update electron-builder to 22.10.5 [Alexis Svinartchouk]
> * Update spectron to v13 [Alexis Svinartchouk]
> * Update dependencies, use aws4-axios@2.2.1 to avoid adding more dependiencies [Alexis Svinartchouk]
> * Update scripts to build universal mac dmgs on the ci [Alexis Svinartchouk]
> * Fix beforeBuild.js script to also work on mac [Alexis Svinartchouk]
> * Support building universal dmgs (x64 and arm64) for mac [Alexis Svinartchouk]
> * Update electron-builder to 22.10.4 [Alexis Svinartchouk]
> * Fix titlebar z-index [Alexis Svinartchouk]
> * Explicitly set contextIsolation to false [Alexis Svinartchouk]
> * Update electron from 9.4.1 to 11.2.3 [Alexis Svinartchouk]
> 
> <details>
> <summary> Update etcher-sdk from 6.1.0 to 6.1.1 [Alexis Svinartchouk] </summary>
> 
>> ### etcher-sdk-6.1.1
>> #### (2021-02-10)
>> 
>> 
>> <details>
>> <summary> Update node-raspberrypi-usbboot from 0.2.10 to 0.2.11 [Alexis Svinartchouk] </summary>
>> 
>>> #### node-raspberrypi-usbboot-0.2.11
>>> ##### (2021-02-10)
>>> 
>>> * Update @balena.io/usb from 1.3.12 to 1.3.14 [Alexis Svinartchouk]
>>> 
>> </details>
>> 
>> 
> </details>
> 
> 
</details>


<details>
<summary> Update etcher from 1.5.115 to 1.5.116 [Lorenzo Alberto Maria Ambrosi] </summary>

> ## etcher-1.5.116
> ### (2021-02-03)
> 
> * Only cleanup temporary decompressed files in child-writer [Alexis Svinartchouk]
> * Add .versionbot/CHANGELOG.yml [Alexis Svinartchouk]
> * Stop using node-tmp, use withTmpFile from etcher-sdk instead [Alexis Svinartchouk]
> 
> <details>
> <summary> Update etcher-sdk from 5.2.2 to 6.1.0 [Alexis Svinartchouk] </summary>
> 
>> ### etcher-sdk-6.1.0
>> #### (2021-02-03)
>> 
>> * Prefix temporary decompressed images filenames [Alexis Svinartchouk]
>> 
>> ### etcher-sdk-6.0.1
>> #### (2021-02-02)
>> 
>> * Ignore ENOENT errors on unlink in withTmpFile [Alexis Svinartchouk]
>> 
>> ### etcher-sdk-6.0.0
>> #### (2021-02-01)
>> 
>> * Export tmp and add prefix and postfix options [Alexis Svinartchouk]
>> 
>> ### etcher-sdk-5.2.3
>> #### (2021-01-26)
>> 
>> * upgrade lint [Zane Hitchcox]
>> 
> </details>
> 
> * Revert "Change some border colors to have higher contrast" [Alexis Svinartchouk]
> * Update electron to v9.4.1 [Alexis Svinartchouk]
> 
> <details>
> <summary> Update etcher-sdk from 5.2.1 to 5.2.2 [Alexis Svinartchouk] </summary>
> 
>> ### etcher-sdk-5.2.2
>> #### (2021-01-19)
>> 
>> 
>> <details>
>> <summary> Update drivelist from 9.2.2 to 9.2.4 [Alexis Svinartchouk] </summary>
>> 
>>> #### drivelist-9.2.4
>>> ##### (2021-01-19)
>>> 
>>> * Pass strings between methods as std::string instead of char * [Floris Bos]
>>> 
>>> #### drivelist-9.2.3
>>> ##### (2021-01-19)
>>> 
>>> * Support lsblk versions that do no support the pttype column [Alexis Svinartchouk]
>>> 
>> </details>
>> 
>> 
> </details>
> 
> 
</details>

* Add brightness env variable value for EP screen [Lorenzo Alberto Maria Ambrosi]
* Add config for EP v2.2.2 + balenaOS v2.67.0+rev1 [Lorenzo Alberto Maria Ambrosi]
* Use https instead of ssh for etcher submodule [Lorenzo Alberto Maria Ambrosi]

<details>
<summary> Update balena-electron-env from v1.1.4 to v1.2.1 [Lorenzo Alberto Maria Ambrosi] </summary>

> ## balena-electron-env-1.2.1
> ### (2021-02-01)
> 
> * Always show the ok button and the header in the wifi modal [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.2.0
> ### (2021-02-01)
> 
> * Added screen brightness filter env variable [Lorenzo Alberto Maria Ambrosi]
> * Fix brigtness filter [Alexis Svinartchouk]
> 
</details>

* Document the ETCHER_PRO_VERSION env var [Alexis Svinartchouk]
* Fix zram.sh script when no zram device is available [Alexis Svinartchouk]
* Remove clicklock from screensaver_on, it is spawned by balena-electron-env [Alexis Svinartchouk]
* Create etcher config folder if it doesn't exist [Alexis Svinartchouk]
* Update etcher volumes, /host as tmpfs [Alexis Svinartchouk]
* Reorder env vars [Alexis Svinartchouk]
* Add drives order for EtcherPro 2.3.2 (same as 2.3.1) [Alexis Svinartchouk]
* Keep fan-control service running during screensaver [Alexis Svinartchouk]
* Remove unneded userspace cpufreq governor setting [Alexis Svinartchouk]
* Do not turn cpus 1 - 3 off during the screensaver [Alexis Svinartchouk]
* Only allow updates during screensaver [Alexis Svinartchouk]
* Set screensaver delay to 5 minutes [Alexis Svinartchouk]

<details>
<summary> Update balena-electron-env from 1.0.6 to 1.1.4 [Alexis Svinartchouk] </summary>

> ## balena-electron-env-1.1.4
> ### (2020-12-30)
> 
> * Run BALENAELECTRONJS_SCREENSAVER_OFF_COMMAND command on start [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.1.3
> ### (2020-12-30)
> 
> * Don't minify js [Alexis Svinartchouk]
> * Revert "Turn the screen off and on on start" [Alexis Svinartchouk]
> * Run BALENAELECTRONJS_SCREENSAVER_ON_COMMAND on start [Alexis Svinartchouk]
> * Spawn clicklock when the screensaver is on [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.1.2
> ### (2020-12-29)
> 
> * Turn the screen off and on on start [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.1.1
> ### (2020-12-29)
> 
> * Update webpack to v5 [Alexis Svinartchouk]
> * Remove bluebird [Alexis Svinartchouk]
> * Use fs promises interface [Alexis Svinartchouk]
> * Update @balena/lint to to v5.3.0 [Alexis Svinartchouk]
> * Update file-loader to v6.2.0 [Alexis Svinartchouk]
> * Update react to v17 [Alexis Svinartchouk]
> * Only log dbus errors if debug is set to balena-electronsjs:dbus [Alexis Svinartchouk]
> * Update rendition to v19 [Alexis Svinartchouk]
> * Update ts-json-schema-generator to v0.82.0 [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.1.0
> ### (2020-12-24)
> 
> * Only allow updates while the screensaver is on [Alexis Svinartchouk]
> * Allow overriding the screensaver delay from settings with BALENAELECTRONJS_SCREENSAVER_DELAY_OVERRIDE [Alexis Svinartchouk]
> * Use settings instance singleton [Alexis Svinartchouk]
> * Add ipc methods to temporarily disable the screensaver [Alexis Svinartchouk]
> * Fix electron warnings in sample app [Alexis Svinartchouk]
> * Improve sample app start script [Alexis Svinartchouk]
> * Don't scan wifi networks if wifi is disabled [Alexis Svinartchouk]
> * Fix electron warnings [Alexis Svinartchouk]
> * Match dbus errors with single quotes [Alexis Svinartchouk]
> * Add debug in screensaver and updates-lock [Alexis Svinartchouk]
> * Don't wait for screensaver on/off command to finish [Alexis Svinartchouk]
> * Remove no longer used utils exec funciton [Alexis Svinartchouk]
> 
> ## balena-electron-env-1.0.7
> ### (2020-12-18)
> 
> * Update README instructions for building and using [Alexis Svinartchouk]
> 
</details>


<details>
<summary> Update etcher from 1.5.113 to 1.5.115 [Alexis Svinartchouk] </summary>

> ## etcher-1.5.115
> ### (2021-01-18)
> 
> * Update etcher-sdk from 5.1.12 to 5.2.1 [Alexis Svinartchouk]
> 
> ## etcher-1.5.114
> ### (2021-01-15)
> 
> * Disable screensaver while flashing (on balena-electron-env) [Alexis Svinartchouk]
> * docs: fix quote marks [Aaron Shaw]
> * Fix typo in webpack.config.ts comment [Alexis Svinartchouk]
> * Update webpack to v5 [Alexis Svinartchouk]
> * Update @balena/lint to 5.3.0 [Alexis Svinartchouk]
> * Update dependencies [Alexis Svinartchouk]
> * Update rendition from 18.8.3 to 19.2.0 [Alexis Svinartchouk]
> * Update etcher-sdk from 5.1.11 to 5.1.12 [Alexis Svinartchouk]
> * Remove libappindicator1 debian dependency [Alexis Svinartchouk]
> 
</details>

## 1.0.0 - 2020-12-17

* Initial release [Alexis Svinartchouk]
