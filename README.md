## titan.tf DLC
This is the optional content pack for Titan.tf servers. The installation of this pack is required in order to see and hear custom content on our servers. Content includes all items found in the Titan universe and Mann vs Machine icons, sounds and models.

### Installation
---
#### Tutorial: How to find your `tf/custom` folder
If you already know how to do this, skip ahead.
1. Go to your Steam library and right-click on Team Fortress 2.
2. Click properties and a small window will appear.
3. Go to the `Local Files` tab.
4. Click `Browse Local Files`.

#### ~~Automatic (Recommended)~~
~~If you would like an easy one-click installation process, connect to our content distributor server (IP: **download.titan.tf:11111**). To connect to a TF2 server via the IP address, type `connect download.titan.tf:11111` into your Team Fortress 2 developer console.~~

> [!WARNING]  
> The content distributor server has been deprecated. **Why?** TF2 limits the speed at which custom content can download, this causes a significantly longer time to download content through the automatic process as compared to manually installing it yourself.

#### Manual via GitHub #1
1. Download [GitHub Desktop](https://desktop.github.com/) and install it.
2. Launch GitHub Desktop.
3. Press `CTRL + SHIFT + O`.
4. You will see 3 tabs (GitHub.com, GitHub Enterprise Server, and URL). Click on `URL`.
5. Enter `TitanTF/Titan-DLC` under the first "Repository URL or GitHub username and repository" entry.
6. Find your tf/custom folder location and place it in the second entry below. For example, the standard Team Fortress 2 installation on a 64-bit OS under the C drive looks like this: `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom`
7. Make sure the entry ends with a new folder name such as `Titan DLC`. For example, `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom\Titan DLC` so that it will install into a new folder within tf/custom. Mods will not work when they are solely placed into the tf/custom folder!
8. Click on `Clone` and the content will start downloading.
9. Go to [titan.tf Settings](https://titan.tf/settings/game#sounds).
10. Check the `Custom Item Sounds` checkbox.

#### Manual via GitHub #2
1. Click [here](https://github.com/TitanTF/Titan-DLC/archive/master.zip) to download the whole pack from this repository.
2. Find your `tf/custom` folder location. For example, the standard Team Fortress 2 installation on a 64-bit OS under the C drive looks like this: `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom`
3. Create a folder inside your tf/custom folder named `Titan DLC`.
4. Extract the contents of the zip file into the newly created `Titan DLC` folder.
5. Go to [titan.tf Settings](https://titan.tf/settings/game#sounds).
6. Check the `Custom Item Sounds` checkbox.

#### Manual via Google Drive
1. Click [here](https://drive.google.com/file/d/1KtpJMRXtONS_ZC06o5l57xxyXKcCj_jl/view?usp=sharing) to download the whole pack compiled in VPKs via Google Drive.
2. Find your `tf/custom` folder location. For example, the standard Team Fortress 2 installation on a 64-bit OS under the C drive looks like this: `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom`
3. Extract the contents of the zip file into your `tf/custom` folder.
4. Go to [titan.tf Settings](https://titan.tf/settings/game#sounds).
5. Check the `Custom Item Sounds` checkbox.

### Updating
---
When there is an update to the content pack, this repository will update. Our servers and website will also notify you about the update when you play.

#### Automatic
The process is the same as the installation. Simply connect to the content distributor server to automatically download updates.

#### Manual via GitHub #1
1. Launch GitHub Desktop.
2. Under the "Current Repository" option at the top left of the interface, make sure it is set to `Titan-DLC`. If it is not, click on it and change to the DLC repository.
3. You will see "Fetch Origin" or "Pull Origin" 2 options to the right of Step 2.
4. If it says "Fetch Origin", click on it and it should show "Pull Origin" if there is an update.
5. If it already says "Pull Origin", click on it and it will start updating.
6. Go to [titan.tf Settings](https://titan.tf/settings/game#sounds).
7. Check the `Custom Item Sounds` checkbox.

#### Manual via GitHub #2
1. Click [here](https://github.com/TitanTF/Titan-DLC/archive/master.zip) to download the whole pack from this repository.
2. Find your `tf/custom` folder location. For example, the standard Team Fortress 2 installation on a 64-bit OS under the C drive looks like this: `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom`
3. Go to your `tf/custom` folder named `Titan DLC` you created during installation.
4. Wipe all files inside your `Titan DLC` folder.
5. Extract the contents of the zip file into the `Titan DLC` folder.
6. Go to [titan.tf Settings](https://titan.tf/settings/game#sounds).
7. Check the `Custom Item Sounds` checkbox.

#### Manual via Google Drive
1. Click [here](https://drive.google.com/file/d/1KtpJMRXtONS_ZC06o5l57xxyXKcCj_jl/view?usp=sharing) to download the whole pack compiled in VPKs via Google Drive.
2. Find your `tf/custom` folder location. For example, the standard Team Fortress 2 installation on a 64-bit OS under the C drive looks like this: `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom`
3. Go to your `tf/custom` folder named `Titan DLC` you created during installation.
4. Wipe all files inside your `Titan DLC` folder.
5. Extract the contents of the zip file into the `Titan DLC` folder.
6. Go to [titan.tf Settings](https://titan.tf/settings/game#sounds).
7. Check the `Custom Item Sounds` checkbox.

## Troubleshooting
There may be some issues with your installation preventing you from seeing and hearing the custom content. But before that, make sure the `Custom Item Sounds` checkbox is checked in your [titan.tf Settings](https://titan.tf/settings/game#sounds).

#### Simple Solution
Type ```snd_restart``` into your Team Fortress 2 developer console.

#### Guaranteed Solution
If the first method didn't work, try the following.
1. Close Team Fortress 2.
2. Go to ```C:/Program Files (x86)/Steam/steamapps/common/Team Fortress 2/tf/sound``` (may or may not have (x86) depending on your computer).
3. Delete the file named ```sound.cache```.
4. Go back to the ```tf/``` folder and go into ```downloads/sound```
5. Delete the file named ```sound.cache```.
6. Boot up Team Fortress 2.
7. If you still cannot hear it, type ```snd_restart``` into your Team Fortress 2 developer console.

## VPK Validation
If you wish to verify that the VPK you currently have was directly obtained from us and was not modified, you may use [this public key](https://github.com/TitanTF/Titan-DLC/blob/master/titan.publickey.vdf).

1. Download the public key file and extract it to your ```C:/Program Files (x86)/Steam/steamapps/common/Team Fortress 2/bin``` directory.
2. Extract the contents of the VPK content zip file to your ```C:/Program Files (x86)/Steam/steamapps/common/Team Fortress 2/bin``` directory.
3. Click on the folder address on your Explorer window and type `cmd` to open the command prompt.
4. Type `vpk -k titan.publickey.vdf checksig titan_dlc_12aug2020.vpk` and enter.
5. It should reply with the following message below. If it failed, the vpk was modified and you should reobtain the package from our platform.

```
Loaded public key file titan.publickey.vdf

SUCCESS
VPK signature validated using the specified public key.
```
