# ✧ Playstation®Home Cache Depot ✧ 

> [!IMPORTANT]
> **This archive is located on HuggingFace @ https://huggingface.co/datasets/pebxcvi/PSHomeCacheDepot**

## ✧ Repo Overview ✧

This repository is an archive of assets pertaining to **Playstation®Home**. 

Playstation®Home was an online social world video game that was on PS3. It was closed down by it's creator ( Sony Computer Entertainment ) on April 1st 2015. The Playstation®Home community strongly feels that Playstation®Home is an abandonded game and its assets to be lost media.

All assets archived here are deemed to be owned by Sony Computer Entertainment and their third party associates.

These assets are sourced from ...

 - The JohnDrinkWater Playstation®Home Archive ( [johndrinkwater github repo](https://github.com/johndrinkwater/ps-home-archive) )

 - Donations made by past Playstation®Home users that voluntarily retrieved the data off their own PS3s.

## ✧ Projects Involved ✧

This repository is associated with the preservation projects listed below, which are open-sourced, non-profit initiatives operating under the legal framework established for emulation and preservation. The main goal is to preserve and restore Playstation®Home's content.

### ✧ Home Laboratory ✧

[Discord Server](https://discord.gg/NAUttdtPS5)

This project provides :

 - a more developer-oriented environment that includes, but is not limited to

	- open source software for an Playstation®Home online server; either locally and/or public. ( [MultiServer3 Github Repo](https://github.com/GitHubProUser67/MultiServer3) )

    - open source tools for handling Playstation®Home assets; either PC tools and/or Web tools. 
       <br>Compiled: [Nautilus](https://github.com/DeViL303/MultiServer3-NuatilusFork/releases) / 
       Source: [Nautilus](https://github.com/GitHubProUser67/NautilusXP2024)

	- support for getting everything setup and running as well as guidance into how Playstation®Home works.

	- the assets needed to create an Content Delivery Network ( CDN ) in some form or other.
	
 	- transparent, in-depth progress updates on its restoration efforts.
	
	- a Playstation®Home scene database ( [google sheets](https://docs.google.com/spreadsheets/d/1acznLvA2k4I7yl56i3pCmAhzxG4pPcrx/edit?usp=sharing&ouid=113258013303427394442&rtpof=true&sd=true) ) 
	
 - it's own Playstation®Home public server which supports both QA ( Developer ) and Retail ( Consumer ) builds for version 1.86. It is playable on both a Jailbroken PS3 and the RPCS3 emulator. ( [pshomeologylab.net](https://pshomeologylab.net/) )

 - a Playstation®Home item ( object ) catalogue database and inventory management system for the PS®Homeology Lab online server, along with an external command module for the QA ( Developer ) build. ( [psho.me](http://psho.me/) )

## ✧ Playstation®Home Cache Information ✧ 

### ✧ Cache Overview ✧

Playstation®Home had a lot of in-game content with a very unique loading system. When a player logged into Playstation®Home, the game reserved a limited amount of space on the PS3's internal HDD for assets to be downloaded from Sony's server. Whenever a player interacted with an asset ( spaces ( scenes ), items/minigames ( objects ), posters, videos, etc ) in-game, it would download and store the assets temporarily until the reserved space was full. **These are referred to as "caches" and are only obtainable by gaining access to one's internal PS3 HDD via a jailbreak**. 

Caches are needed to restore Playstation®Home to its fullest. When new content is found, it can be added to the online public servers and thus be restored. A game can't function without it's assets. Playstation®Home was seperated into four regions and each region had it's own unique content and limited-time events. A large percentage of the content is still missing, most notably that from the Japanese region. This is why it is strongly encouraged for everyone to dust off their PS3 and **check for the Playstation®Home icon**. It is located under the **Playstation Network tab and resembles that of a house**. 

If you happen to spot the Playstation®Home icon on your PS3, press the **Triangle button** on the icon to view its information. You should see an **install date ( between 2008 and 2015 ) and a size ( from 3GB to 12GB )**. If the icon meets these criteria, please consider donating the data to one of the projects mentioned above by following the cache extraction guide below. If you cannot press Triangle on the icon, there is no data behind it. Similarly, if the install date is later than April 1st 2015, or the size is under 100MB, it indicates that Playstation®Home was either installed after its shutdown or was never logged into.

### ✧ Icons ✧ 

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
      <span>v0.41 - v0.73<br>GDC 2007 Demo<br>Game Tab</span>
    </td>
  </tr>
</table>

### ✧ Extraction Summary ✧ 

To reiterate, in order to extract the Playstation®Home cache, it is **required to jailbreak your PS3** to gain access to its internal HDD. You will also **need a USB Stick** that's formated to the **FAT32** format. Most USB Sticks are FAT32 now days but if for some reason it's not, you will need to reformat it using a PC program called Rufus. If you have no USB Stick, do an internet search for "USB Stick 16GB FAT32" then order it.

For newcomers, the PS3 jailbreak community **recommends updating your PS3 to the Hybrid Firmware ( HFW ) then installing the HEN software**. It is a Semi-untethered Jailbreak where the user has to enable HEN to go into a jailbroken state. When rebooting the PS3, it returns to a non-jailbroken state until the user enables HEN again. Because of this, it is considered to be **very safe**. 

Once jailbroken, a **Homebrew application called multiMAN ( mmCM )** can be used to **browse the PS3 directories** via its own File Manager / mmOS. Playstation®Home's cache folders will be **in the dev_hdd0/game/ directory** and can be **indentified by one of the below folder pairs**. **The objective is to copy the two folders from the PS3 to the FAT32 USB Stick.**

        NPIA00005 & NPIA00005DATA ( Retail )
        NPIA00010 & NPIA00010DATA ( Developer )
        NPEA00013 & NPEA00013DATA ( Developer / Closed Beta )

The jailbreak should take 10 minutes tops and the data extraction should take 30 minutes to 90 minutes tops depending on the number of files. 

After the PS3 has extracted the data onto your USB stick, insert it into your computer, transfer the data, then **zip the two folders and upload the resulting file to a cloud service** of your choice (e.g., Google Drive, Mega, etc.). Then, **join one of the Discord servers** linked above and post the link in the appropriate channel.

Upon request, a comprehensive analysis of the cache—detailing its contents and any new files discovered—is available.


### ✧ Extraction Guides ✧

 Guide #1 - ( [https://pshomeologylab.net/Cache](https://pshomeologylab.net/Cache) )
 
### ✧ Public Archive ✧

A vast majority of Playstation®Home raw caches donated by it's former players are archived publicly in this google drive with logs included. ( [Google Drive](https://drive.google.com/drive/u/1/folders/1Wuk2GNsXOZ_qLJFqtg0gExRpZqxL3sec) )

You can find individual download links here. ( [Google Sheets](https://docs.google.com/spreadsheets/d/1uR7IRGjkl_n5CMBua6zIQV5EKXdSk8_D-sTDoJGMe7c/edit?usp=sharing) ) 

## ✧ How to Clone ✧ 

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

## ✧ Notable Mentions ✧ 

The following individuals are key figures spearheading the revolution of Playstation®Home Online as a fully open-source environment :

- **AgentDark447** ( [github](https://github.com/GitHubProUser67) )
- **Jumpsuit** ( [github](https://github.com/Jump-Suit) )
- **Devil303** ( [psx-place](https://www.psx-place.com/members/devil303.22544/) )
- **Rew** ( [twitter](https://x.com/pebxcvi) )
- **Pongo** ( [twitter](https://x.com/Pongo86_) )
- **Spookysniper**
- **Cade**
