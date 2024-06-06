<!-- PROJECT LOGO -->
<br />


   <img src="https://i.imgur.com/9w4rsiv.png" width="80" height="80">


  <h3 align="center">Debloat Samsung with ADB & Shizuku </h3>

  <p align="center">
    A list of bloatware packages that samsung phones have with instructions to remove them
    <br />
    Author:(https://github.com/Achno/)

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Getting Started">Getting Started</a></li>
    <li><a href="#Prerequisites"> Prerequisites</a></li>
    <li><a href="#Usage">Usage</a></li>
    <li><a href="#Installation">Installation</a></li>
  </ol>
</details>

<!-- GETTING STARTED -->

## Getting Started

You can debloat your phone either by gaining root access but as that is a hasle we will use shizuku and with the help of an ADB shell we will remove unwanted packages

### Prerequisites

- Shizuku
  ```sh
  You can install Shizuku from the Google Playstore(FREE),FDROID (FREE)
  ```

* Ashell
  ```sh
  You can install Ashell from the Google Playstore(2.99€),Fdroid(FREE)
  ```

### Alternatives

If your goal is only package management you could use a different gui tool like [this](https://github.com/SmartPack/PackageManager) instead of Ashell.

Here i proceed with Ashell

### Installation

Ashell is free only on Fdroid in order to download Fdroid :\_

1. [Visit here](https://f-droid.org/)
2. Click on `download Fdroid`
3. Make sure you enable the trust downloads from your browser in your settings
4. Install the APK

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

1. Open Shizuku and click on `pairing`
2. Head to Developer options and enable `USB debugging` & `wireless debugging`
3. click on `wireless debugging` and tap on `pair device with pairing code`
4. Enter the code into shizuku and click on `start` on the app

If you have done everything correct your Ashell will work correctly.

> **Warning** ⚠️
 If you see a red screen saying that you need shizuku and the server is not on just repeat the steps again.

- Open your Ashell and type:

```shell
pm uninstall --user 0 <package>
```

- `<package>` will be replaced by the packages in the list below

**Bloatware List**

```shell
 com.android.bookmarkprovider
 com.samsung.android.game.gametools
 com.samsung.android.game.gamehome
 com.samsung.android.game.gos
 com.google.android.syncadapters.calendar
 com.google.android.syncadapters.contacts
 com.samsung.android.app.spage
 com.sec.android.app.billing
 com.google.android.tts
 com.sec.android.daemonapp
 com.google.ar.core
 com.samsung.android.samsungpassautofill
 com.samsung.android.livestickers
 com.samsung.android.app.cocktailbarservice
 com.samsung.android.themestore
 com.google.android.googlequicksearchbox
 com.microsoft.appmanager  | link to windows
 com.google.android.feedback
 com.samsung.android.service.peoplestripe | people
 com.samsung.android.app.taskedge
 de.axelspringer.yana.zeropage | upday (news)
 com.google.android.projection.gearhead | android auto
com.samsung.android.mobileservice | group sharing
com.google.android.apps.turbo | Device Health services
com.sec.android.widgetapp.webmanual | User manual
com.samsung.android.authfw | Samsung Authentication Framework
com.samsung.android.forest | Digital Wellbeing
com.samsung.android.themecenter |Galaxy themes services
com.samsung.android.mdx | Link to Windows Service
com.samsung.android.app.sharelive | Quick share
com.samsung.android.aware.service | Quick share (service)
com.samsung.android.app.settings.bixby | Settings Bixby
samsung.android.beaconmanager | User tracking app (sensitive)
com.sec.android.app.quicktool | Tools
com.samsung.android.calendar | Calendar
com.samsung.providers.calendar | Calendar Storage
com.sec.android.easyMover.Agent | Smart switch Agent
com.samsung.android.app.appsedge | Apps Edge panel
com.sec.android.widgetapp.easymodecontactswidget | Favourite contacts
com.samsung.android.app.galaxyfinder | Finder (notification menu next to setting )
com.sec.samsung.android.widgetapp.samsungapps | Galaxy Essentials Widget
com.samsung.android.mdx.quickboard | Media and Services - Edge panel
com.samsung.android.app.reminder | Reminder
com.osp.app.signin | Samsung account
com.samsung.android.kgclient | Device Services (samsung pay garbage)
com.samsung.android.da.daagent | Dual Messenger
com.samsung.android.fmmm | Find my mobile (system)
com.samsung.android.rubin.app | Customization Service (system ~ tracking ~bloat)
com.samsung.android.allshare.service.mediashare | Nearby Service (system)
com.samsung.android.game.gos
com.sec.enterprise.knox.cloudmdm.smdms | Knox enrollment services
com.samsung.android.knox.analytics.uploader | Knox analytics uploader
com.android.dreams.phototable | Photo screensavers
com.android.backupconfirm |restores google settings with google-backup restore fun
com.android.dreams.basic | Support for screensaver mode in display settings
com.android.egg | Android builds easter egg feature
com.android.managedprovisioning | Work setup (corporate restrictions)
com.android.providers.partnerbookmarks | Provides bookmarks,about,partners,inChrome
com.samsung.android.app.simplesharing | link sharing
com.samsung.android.privateshare | private share
com.samsung.knox.securefolder | secure folder (garbage)
com.samsung.android.scloud | Samsung Cloud
com.samsung.android.game.gos
com.facebook.appmanager
com.facebook.services
com.facebook.system
com.facebook.katana
com.microsoft.appmanager
com.microsoft.skydrive
com.samsung.android.bixby.agent
com.samsung.android.bixby.service
com.samsung.android.bixby.wakeup
com.netflix.mediaclient
com.android.chrome


EXTRA
com.google.android.onetimeinitializer - Provides first time setup, safe to remove.
com.google.android.setupwizard | first boot stuff configs
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>
