# ✧ Playstation®Home Cache Depot ✧ 

> [!IMPORTANT]
> **This archive is located on HuggingFace @ https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot**

## ✧ Repository Overview ✧

This repository is an archive of assets pertaining to **PlayStation®Home**.

PlayStation®Home was an online social world video game that was on PS3. It was closed down by it's creator ( Sony Computer Entertainment ) on April 1st 2015. The PlayStation®Home community strongly feels that PlayStation®Home is an abandonded game and its assets to be lost media.

All assets archived here are deemed to be owned by Sony Computer Entertainment and their third party associates.

These assets are sourced from ...

 - The JohnDrinkWater PlayStation®Home Archive ( [JohnDrinkWater Github Repo](https://github.com/johndrinkwater/ps-home-archive) )

 - Donations made by past PlayStation®Home users that voluntarily retrieved the data off their own PS3s.

## ✧ Projects Involved ✧

This repository is associated with the preservation projects listed below, which are open-sourced, non-profit initiatives operating under the legal framework established for emulation and preservation. The main goal is to preserve and restore PlayStation®Home's content. They have helped keep PlayStation®Home faintly alive, well beyond the days of its prime. None of the preservation projects listed below are affiliated with Sony Computer Entertainment, its developer London Studio, or its third-party developers.

### ✧ Home Laboratory ✧

[Home Laboratory Discord Server](https://dsc.gg/homelaboratory)

This project provides :

 - A more developer-oriented environment that includes, but is not limited to

	- Open source software for an PlayStation®Home online server; either locally and/or public. ( [MultiServer Github Repo](https://github.com/GitHubProUser67/MultiServer3) )

	- Support for getting everything setup and running as well as guidance into how PlayStation®Home works.

	- The PlayStation®Home assets needed to create an Content Delivery Network ( CDN ) in some form or other.

   	- Open source tools for handling PlayStation®Home assets.  ( [✧ Cache Tools ✧](https://github.com/pebxcvi/PSHomeCacheDepot#-cache-tools-) )
	
 	- Transparent, in-depth progress updates on its preservation and restoration efforts for PlayStation®Home. ( [✧ Archive Progression ✧](https://github.com/pebxcvi/PSHomeCacheDepot/#-archive-progression-) )
	
 - Its own dedicated PlayStation®Home public server which supports both QA ( Developer ) and Retail ( Consumer ) builds for version 1.86. It is playable on both a Jailbroken PS3 and the RPCS3 emulator. The server maintains an open stance toward glitching, custom content creation, and in-game modding. ( [https://pshomeologylab.net](https://pshomeologylab.net/) ) 

 - A PlayStation®Home item ( object ) catalogue database and inventory management system for the PSHomeology Lab online server, along with an external command module for the QA ( Developer ) build. ( [https://psho.me](https://psho.me/) )
 
### ✧ PSORG ✧

[PSORG Discord Server](https://discord.gg/psorg-756702841804030052)

Short for **PSOnlineReturnalGaming**, this project provides :

- A centralized revival hub for various publisher released games on the Sony platform :

	- Started as an expansion of the open-source software formerly known as **deadlocked-server-now-horizons** — a PS2 Medius C# server emulator — the project was later extended to support PS3 with additional systems and packet handling, then eventually integrated into the MultiServer suite. ( [Horizon Private Server Github Repo](https://github.com/Jump-Suit/horizon-server-public-extended) )

	- Support for various first-party PlayStation® titles that players may recognize, with gameplay statistics posted as binary data and analyzed using a dedicated external tool. ( [PSORG's Gitub Repo : SVO Stats Analyzer](https://github.com/PSOnlineReturnalGaming/SVO_Stats_Analyzer) )</br>

	- Access multiple smaller online games on consoles and emulators through a unified DNS, bringing together players from different games to connect, converse, and play — all without needing to repeatedly change DNS settings.

	- Frequent updates based on the game currently being restored — all while maintaining responsive support with a minimal team — with openness to community suggestions.

	- Partial collaboration with Home Laboratory on the restoration of PlayStation®Home.

- Its own dedicated PlayStation®Home online public server that supports **Retail**, **QA**, and **HDK** ( Home Development Kit ) developer builds—all running version 1.86—to facilitate content creation within each player’s isolated Content Delivery Network ( CDN ) environment. The server echos the PSHomeology Lab server’s beliefs in openness and post-release exploration. ( [psorg-web-revival.us](http://www.psorg-web-revival.us:15000) )

- Various external support tools for PlayStation®Home online servers, such as the **Surface Support Frontend ( SSF )**—an interface that provides streamlined access to the game's existing Data Capture feature, used to capture and display real-time error logs from currently connected players. It also includes an interface for managing live server-side files such as the TSS ( Title Small Storage ), Message of the Day, Grief Reports, and much more. ( [PSX-Place : Surface Support Frontend](https://www.psx-place.com/threads/pre-release-surface-support-frontend-ssf.47165/) / [SSF Github Repo](https://github.com/Jump-Suit/PSHome-Surface-Support-Frontend ) )

## ✧ How to Clone This Repository ✧ 

There are two ways to clone this repository: using Git's API or using Hugging Face's Python based API. To keep things simple, the below methods will be geared toward Windows machines.   

### ✧ Git ✧

With Git, you can the clone entire repository or clone specific folders. This repository is structured in a certian way to make it easier to clone specific folders.

1) Install Git with the stand alone installer ( [git-scm.com](https://git-scm.com/downloads/win) )

2) Download and run the batch script ( [clone_repo.bat](https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/blob/main/clone_repo.bat) ), located in the root of the repository. You can run the script in any folder of your choice, but ensure you run it as an administrator.

     The script will ...
     
     1 ) Set a PATH environment variable for Git using the default install directory <code>C:\Program Files\Git\bin</code>. If that is not where your Git is installed then ensure you change the variables at the top of the script.
     
     2 ) Set up Git LFS.

     3 ) Give three options. 
     
     Option 1 will clone the entire repository.
     
     Option 2 will clone specific folders based on a text file named FOLDER.TXT. The script creates a default FOLDER.TXT before initializing the Git repository—this default file is set to ignore all folders. Let the script finish. Afterwards, remove the "#" from the entries in FOLDER.TXT and rerun it. Initializing the repository will look something like this :
     
        Initialized empty Git repository in C:/Repos/PSHomeCacheDepot/.git/
        Updating origin
        remote: Enumerating objects: 635590, done.
        remote: Counting objects: 100% (303481/303481), done.
        remote: Compressing objects: 100% (284559/284559), done.
        remote: Total 635590 (delta 11151), reused 51232 (delta 552), pack-reused 332109 (from 1)
        Receiving objects: 100% (635590/635590), 640.76 MiB | 3.71 MiB/s, done.
        Resolving deltas: 100% (99978/99978), done.
        From https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot
         * [new branch]            main       -> origin/main
        sparse-checkout IS EMPTY. UNCOMMENT AN ENTRY IN FOLDER.TXT.
        
      Option 3 will update your local repo folder using the Git command <code>git pull</code>. If any changes are made to your local repo then you'll need to run <code>git stash</code> before you try to pull. 
        
### ✧ HuggingFace ✧

With the HuggingFace Python based API, only the entire repository can be cloned using the deprecated `Repository` class ( [Repository documentation](https://huggingface.co/docs/huggingface_hub/en/guides/repository#clone) ). The Python script below ( [clone_repo.py](https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/blob/main/clone_repo.py) ) will utilize this class until HuggingFace removes it. The documentation states to use the `snapshot_download` function ( [snapshot_download documentation](https://huggingface.co/docs/huggingface_hub/v0.29.3/en/package_reference/hf_api#huggingface_hub.HfApi.snapshot_download) ) in lieu of the `Repository` class but unforunately, it consistently errors out when attempting to clone the entire repository. On the bright side, the `Repository` class clones the repository exceptionally fast.

To clone the entire repository, …

1) Install Python's latest Window Installer ( [python.org](https://www.python.org/) )

2) Install the API. Open a command prompt as administrator then run <code>pip install huggingface_hub</code>

3) Download and run the python script ( [clone_repo.py](https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/blob/main/clone_repo.py) ), located in the root of the repository. You can run the script in any folder of your choice.

## ✧ PlayStation®Home Cache Information ✧ 

### ✧ Cache Overview ✧

PlayStation®Home had a lot of in-game content with a very unique loading system. When a player logged into PlayStation®Home, the game reserved a limited amount of space on the PS3's internal HDD for assets to be downloaded from Sony's server. Whenever a player interacted with an asset ( spaces ( scenes ), items/minigames ( objects ), posters, videos, etc ) in-game, it would download and store the assets temporarily until the reserved space was full. **These are referred to as "caches" and are only obtainable by gaining access to one's internal PS3 HDD via a jailbreak**. 

Caches are needed to restore PlayStation®Home to its fullest. When new content is found, it can be added to the online public servers and thus be restored. A game can't function without it's assets. PlayStation®Home was seperated into four regions and each region had it's own unique content and limited-time events. A large percentage of the content is still missing, most notably that from the Japanese region. This is why it is strongly encouraged for everyone to dust off their PS3 and **check for the PlayStation®Home icon**. It is located under the **PlayStation Network tab and resembles that of a house**. 

If you happen to spot the PlayStation®Home icon on your PS3, press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-triangle-grey.png" alt="plain-triangle-grey.png" width="18"> on the icon to view its information. You should see an **install date ( between 2008 and 2015 ) and a size ( from 3GB to 12GB )**. If the icon meets these criteria, please consider donating the data to one of the projects mentioned above by following the cache extraction guide below. If you cannot press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-triangle-grey.png" alt="plain-triangle-grey.png" width="18"> on the icon, there is no data behind it. Similarly, if the install date is later than April 1st 2015, or the size is under 100MB, it indicates that PlayStation®Home was either installed after its shutdown or was never logged into.

### ✧ Public Cache Archive ✧

> [!NOTE]
> To eliminate a failure point, a mirror of the google drive was uploaded to Internet Archive https://archive.org/details/PSHomeRawCacheDepot 

A vast majority of PlayStation®Home raw caches donated by it's former players are archived publicly in this google drive with logs included. 

> [Google Drive](https://drive.google.com/drive/u/1/folders/1Wuk2GNsXOZ_qLJFqtg0gExRpZqxL3sec)

You can find individual download links here. 

> [Google Sheets](https://docs.google.com/spreadsheets/d/1uR7IRGjkl_n5CMBua6zIQV5EKXdSk8_D-sTDoJGMe7c/edit?usp=sharing)

### ✧ Archive Progression ✧

**```Scenes :```**

A Google Sheets spreadsheet showcasing how many Scenes are archived versus how many are missing, using various data points as references such as Scene lists.

> [Google Sheets](https://docs.google.com/spreadsheets/d/1acznLvA2k4I7yl56i3pCmAhzxG4pPcrx/edit?usp=sharing&ouid=113258013303427394442&rtpof=true&sd=true)

You can also download the excel spreadsheet directly within the repository here :

> [Mapped_Scenes_Query.xlsx](https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/SCENES-MAPPED/Mapped_Scenes_Query.xlsx?download=true)

**```Objects :```**

A snippet showcasing how many Objects are archived verus how many are missing, using the Object Catalogue at Home End as the reference.

> <img src="https://github.com/pebxcvi/PSHomeCacheDepot/blob/main/ObjectProgressJuly112025.png" alt="Objects" width="70%">

A full list of the Objects folder can be downloaded here within the repository :

> [OBJECT_QUERY.txt](https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/OBJECTS/OBJECT_QUERY.txt?download=true)

### ✧ Cache Tools ✧

Here are a few fully open-sourced tools from the Home Laboratory Project :

1) PSHome Cache Extractor
   - This is a Windows batch script for the logging of PlayStation®Home raw caches. It utilizes various scripts/programs such as DEINF2.0. 
   - Compiled : [PSHomeCacheExtractor](https://github.com/pebxcvi/PSHomeCacheExtractor/releases/tag/v3.5.6)
   - Source : [PSHomeCacheExtractor](https://github.com/pebxcvi/PSHomeCacheExtractor)

2) Nautilus
   - This is a stand-alone Windows GUI appliation for handling PlayStation®Home assets using Multiserver's backend.
   - Compiled : [Nautilus](https://github.com/DeViL303/MultiServer3-NuatilusFork/releases)
   - Source : [Nautilus](https://github.com/GitHubProUser67/NautilusXP2024)

### ✧ Cache Icons ✧ 

<table align="center">
  <tr>
    <td align="center" style="padding: 10px;">
      <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons/ICON1.PNG" alt="ICON1"><br>
      <span>Open Beta v1.65 - v1.87<br>-<br>PSN Tab</span>
    </td>
    <td align="center" style="padding: 10px;">
      <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons/ICON2.PNG" alt="ICON2"><br>
      <span>Open Beta v1.03 - v1.61<br>Closed Beta v1.00 - v1.02<br>PSN Tab</span>
    </td>
    <td align="center" style="padding: 10px;">
      <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons/ICON3.PNG" alt="ICON3"><br>
      <span>Closed Beta v0.83 - 0.98<br>v0.83 on PSN Tab<br>v0.94 - 0.98 on Game Tab</span>
    </td>
  </tr>
</table>

<br>

<table align="center">
  <tr>
    <td align="center" style="padding: 10px;">
      <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons/ICON4.PNG" alt="ICON5"><br>
      <span>Developer Beta v1.00<br>-<br>Game Tab</span>
    </td>
    <td align="center" style="padding: 10px;">
      <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons/ICON0.PNG" alt="ICON4"><br>
      <span>Various Developer Versions<br>where Target Manager was used<br>-</span>
    </td>
    <td align="center" style="padding: 10px;">
      <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons/ICON5.PNG" alt="ICON0"><br>
      <span>v0.41 - v0.74<br>GDC 2007 Demo<br>Game Tab</span>
    </td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center" style="padding: 10px;">
      <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons/ICON6.PNG" alt="ICON5"><br>
      <span>Developer Build v1.22<br>-<br>Game Tab</span>
    </td>
  </tr>
</table>

### ✧ Extraction Summary ✧ 

To reiterate, in order to extract the PlayStation®Home cache, it is **required to jailbreak your PS3** to gain access to its internal HDD. You will also **need a USB Stick** that's formated to the **FAT32** format. Most USB Sticks are FAT32 now days but if for some reason it's not, you will need to reformat it using a PC program called Rufus. If you have no USB Stick, do an internet search for "USB Stick 16GB FAT32" then order it.

For newcomers, the PS3 jailbreak community **recommends updating your PS3 to the Hybrid Firmware ( HFW ) then installing the HEN software**. It is a Semi-untethered Jailbreak where the user has to enable HEN to go into a jailbroken state. When rebooting the PS3, it returns to a non-jailbroken state until the user enables HEN again. Because of this, it is considered to be **very safe**. 

Once jailbroken, a **Homebrew application called multiMAN MOD ( mmCM )** can be used to **browse the PS3 directories** via its own File Manager / mmOS. PlayStation®Home's cache folders will be **in the dev_hdd0/game/ directory** and can be **indentified by one of the below folder pairs**. **The objective is to copy the two folders from the PS3 to the FAT32 USB Stick.**

**`NPIA00005`** / **`NPIA00005DATA`** ( **Retail** )  
**`NPIA00010`** / **`NPIA00010DATA`** ( **Developer** )  
**`NPEA00013`** / **`NPEA00013DATA`** ( **Developer** / **Closed Beta** )

The jailbreak should take 10 minutes tops and the data extraction should take 30 minutes to 90 minutes tops depending on the number of files. 

After the PS3 has extracted the data onto your USB stick, insert it into your computer, transfer the data, then **zip the two folders up and upload the resulting file to a cloud service** of your choice (e.g., Google Drive, Mega, etc.). If Google Drive is used, please ensure to set the General Access to Viewer : "Anyone with the link."

Finally, join one of the Discord servers linked above and post the link in the appropriate channel.

Upon request, a comprehensive analysis of the cache—detailing its contents and any new files discovered—is available.

> [!WARNING]
> **Most PlayStation®Home caches are safe to share, but some may contain a file called `DATALOG.DAT`, which can include the original player’s IP address and PlayStation Network ID. If you'd like to remove this file before zipping the folders, you’re welcome to do so. We also remove it before publicly archiving any cache. You can typically find it in a directory such as `/NPIA00005/USRDIR/`.**

> [!NOTE]
> If Google Drive is used, please ensure to set the General Access to Viewer : "Anyone with the link."

### ✧ Extraction Guide ✧

**Prerequisite :** Jailbroken PS3 required. Learn how here : [**`✧ How to Jailbreak ✧ `**](https://github.com/pebxcvi/PSHomeCacheDepot#-how-to-jailbreak-)

With **HEN enabled**, do the following :

1. Install multiMAN MOD 

    - Download package ( .pkg ) @ [**`store.brewology.com`**](https://store.brewology.com/get/homebrew.php?id=24&fid=2412)
  
    - Copy the **`multiMAN MOD package`** onto a **`FAT32 USB Stick`**, then insert it into the **`rightmost USB port`** on the PS3.

    - On the **`Game`** tab, go to **`Package Manager → Install Package Files → Standard`** then select a package to install.

2. Open multiMAN MOD

    - After installation, an icon titled **`multiMAN MOD`** ( looks like a bomb with glasses ) will appear on the **`Game`** tab. Launch it. You will be prompted with a four-page binding agreement. To proceed with using the application, you must select 'Yes' on each of the four pages.

    - Once accepted, you will enter an interface resembling the PS3 XMB. Navigate all the way to the left to the **`mmCM`** tab, where you will find the option **`File Manager / mmOS`**. Press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-cross-grey.png" alt="plain-cross-grey.png" width="18"> to open it.

3. Extract the Cache with multiMAN MOD's File Explorer

    - The **`File Manager / mmOS`** resmembles a typical OS desktop. Use <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/outline R-grey.png" alt="outline R-grey.png" width="15"> to move the cursor, and double-tap <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-cross-grey.png" alt="plain-cross-grey.png" width="18"> to launch applications and open folders. Knowing this, launch the main file explorer titled **`PS3™ Root`**.

    - Once opened, navigate to the **`/dev_hdd0/game/`** directory. This is where the PlayStation®Home cache was stored. Look for one of the following folder pairs:

      **`NPIA00005`** / **`NPIA00005DATA`** ( **Retail** )  
      **`NPIA00010`** / **`NPIA00010DATA`** ( **Developer** )  
      **`NPEA00013`** / **`NPEA00013DATA`** ( **Developer / Closed Beta** )

    - Copy both cache folders ( from any pair you see ) to the connected **`FAT32 USB stick`**. To do this:

      - Hover over one of the folders, press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-circle-grey.png" alt="plain-circle-grey.png" width="18">, then press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-cross-grey.png" alt="plain-cross-grey.png" width="18"> on **`Copy`**.

      - Navigate back to the root directory using <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/outline-left-grey.png" alt="outline-left-grey.png" width="18"> / <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/outline-right-grey.png" alt="outline-right-grey.png" width="18"> .

      - Enter the **`dev_usb000`** folder, press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-circle-grey.png" alt="plain-circle-grey.png" width="18">, then press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-cross-grey.png" alt="plain-cross-grey.png" width="18"> on **`Paste`**.

## ✧ How to Jailbreak ✧ 

**`HFW 4.92 w/ HEN 3.4.0`**

**Download required files @** [**`JailbreakTools_4.92.1`**](https://drive.google.com/file/d/1DWJTZ3gwBmSa1aj0ieZo3YsSmCk3NjiI/view?usp=sharing)

### ✧ Updating Your PS3 ✧ 

> [!WARNING]
> **Please ensure the PS3’s Wi-Fi and Bluetooth are working BEFORE updating!**	
> **You WILL get stuck in an update loop if either of these are broken!**

> [!NOTE]
> **If you do not see the "Update via Storage Media" option under System Update, you MUST reboot your PS3 into Safe Mode and perform the update from there.**

Use the **`PS3UPDAT.PUP`** in the PS3 folder to update your PS3 onto **`HFW`** firmware. Follow these steps:

1. Copypaste the folder named **`PS3`** and the two **`PKG`** files onto a **`FAT32 USB Stick`**
2. Insert the USB Stick into the **`rightmost USB port`** on the PS3.
3. Go to the **`Settings`** tab on the PS3 XMB.  
4. Select **`System Update`**.  
5. Choose **`Update via Storage Media`** then run the update.

### ✧ Setting up the Browser ✧

After updating your PS3 to **`HFW 4.92`**, connect your PS3 to the internet (but **don't sign in**). Follow these steps:

1. Open the browser on your PS3.  
2. Press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-triangle-grey.png" alt="plain-triangle-grey.png" width="18"> and do the following:  
   - Tools → Cookies → Allow  
   - Tools → JavaScript → On  
   - Tools → Confirm Browser Close → Off  
   - Tools → Home Page → Blank  
   - Tools → Delete Cookies → Yes  
   - Tools → Delete Cache → Yes  
3. Press ▻ to bring up the Address Bar.  
4. Type in **[`http://ps3xploit.me`](http://ps3xploit.me)** then press ▻ again. This will take you to the ps3xploit website.

### ✧ Installing HEN 3.4.0 ✧ 

1. On the top left of the ps3xploit page, go to **`PS3HEN → HEN Installer/Enabler`**. This opens the HEN Installer page at
   **`http://ps3xploit.me/hen/installer/index.html`**  
2. Assign the HEN Installer page as your homepage. Press <img src="https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot/resolve/main/DEV/Icons-Symbols/plain-triangle-grey.png" alt="plain-triangle-grey.png" width="18">, then go to 
   **`Tools → Home Page → Use Current → OK`**.  Exit and reopen the browser.  
3. When you reopen the browser, it will download the **`PS3HEN.p3t`** payload. 
4. Once downloaded, click **`Initialize HEN installer`**. *( It may fail the first time. If so, exit browser and try again. )*  
5. Once initialized, click **`Install HEN`**. The system will reboot. After reboot, go to the **`Game`** tab on the PS3 XMB and press **`enable HEN`**. 

## ✧ Notable Mentions ✧ 

The following individuals are key figures spearheading the revolution of PlayStation®Home Online as a fully open-source environment :

- **AgentDark447** ( [github](https://github.com/GitHubProUser67) )
- **Jumpsuit** ( [github](https://github.com/Jump-Suit) )
- **Devil303** ( [psx-place](https://www.psx-place.com/members/devil303.22544/) )
- **Rew** ( [twitter](https://x.com/pebxcvi) )
- **Pongo** ( [twitter](https://x.com/Pongo86_) )
- **Spookysniper**
- **Cade**
