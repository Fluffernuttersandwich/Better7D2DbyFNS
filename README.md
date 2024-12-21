# Better 7D2D by FNS
This is an Overhaul ModList for the game 7 Days to Die using the Wabbajack and ModOrganizer2 (MO2) applications.

![fluffernutter-2](https://github.com/user-attachments/assets/92b104e5-8d0c-4e5d-986a-90219d0b91fd)

## Vision for this ModList (aka Overhaul ModPack)

### It's 7 Days to Die, *only better.*

When people think of a stable Vanilla+ mod pack that enhances the original game, I want them to think of this ModList.

This list is friendly to a more casual play style for people who want a relaxed game experience.  

If you are a hardcore gamer, this pack is _probably_ not for you.


______________________________________________________________________________________________________________________



## Description

Most of the mods in this collection are Quality of Life (QoL) improvements to give the players a nice Vanilla+ experience without any game breaking balance issues you see in some other mod lists.  

This ModList is not about overhauling major systems, nor adding too many new features.  

This list is all about improving dozens of small details that as a whole make for a better overall experience of the original game.  

Unlike other Overhaul ModPacks, you are _not_ learning a new game. 

**Balance is subjective.**  
Some people think this Collection makes the game too easy.  
If you feel that way, disable the mods you don't like, and/or play with harder difficulty settings.  

If you are seeking a more challenging brand new Overhaul experience, I'd recommend Darkness Falls, or Rebirth. 

If you are brand new to Modding, and Wabbajack/MO2 in particular, start here for an overview: 

https://www.youtube.com/watch?v=c9jDnjSRqOE

The YouTube Content Creator **DroppedIceCream** does a lot of reviews of ModLists for games like Skyrim and Fallout.  

So check out his reviews if you are interested in learning about some of the best mods for those games.    


--- 

### Why you should consider using this Wabbajack-MO2 ModList?

- For users with a Premium NexusMods account, it is damn-near a "one-touch" modding solution to give you the best 

- Even if you only have a Free NexusMods account, I've done all the work of collecting these mods and testing their Load Order for you.  
So, even though you need to click through to download each mod, one-at-a-time, it's still faster than you doing it yourself, and with no wasted time spent troubleshooting the Load Order to sort out mod conflicts.  

______________________________________________________________________________________________________________________

# Contents

**WIP!!!**

[Title](#better-7d2d-by-fns).
     
[Description](##description).

[Requirements and Recommended Hardware Specs](##Requirements-and-Recommended-Hardware-Specs).


          

     


## Requirements and Recommended Hardware Specs


1. Hardware capable of running the base game of 7D2D.

If you can run the base game, you can run this ModList without any issues.

You can see this at the Steam Store page for the game.

Some of the mods will lower FPS (2-10) somewhat, if you are experiencing issues, you could lower your Graphic Settings from Ultra to High or lower as needed depending on your hardware constraints.  

Do not make maps larger than 10k if you are running on potato-grade hardware!  Even if you are able to generate the map, the game could become corrupted after several hours into a playthrough.  


2. The latest version of Wabbajack.

https://www.wabbajack.org/ 

3. Storage consideration: currently the collection is about 16Gb.
"What, but 7D2D mods are small?!"
Yes, generally, but mods like: the CompoPack, Izy's AIO Gun Pack, Bdub's vehicles, and all the Decor mods add up.
Do you want to play a nice list or not?


______________________________________________________________________________________________________________________


# **Commandment Zero: Thou shalt read the Assumptions, Installation Directions, and Troubleshooting sections prior to asking for technical assistance.  There's a 99% chance your issue is covered there.**  

## Assumptions 


A. You have already installed 7D2D, using the latest *stable* version of the game.  Currently, this is: **1.2b27**

_This list is exclusively compatible with this version!_

---

B. EAC has been disabled from the Game Launcher.  Not just temporarily muted for a session, but actually disabled so it will not attempt to launch!

---

C. You did *not* delete the "0_TFP_Harmony" folder in the base game's Mods folder!

---

D. You ran the vanilla game to the main start-up menu once.  *This is so it can build out folder directories.*
_This is considered best practice/mandatory for modding most games._

---

E. You are not running Mods out of any other folder that could cause a potential Mod Conflict.
If you have Mods running out of the base game Mods folder, or Vortex Mods folder, remove/disable them!
If you have Mods in a self-contained system like ModLauncher, that's fine, it won't interact.

> [!WARNING]
> Please save yourself hours of aggravation and double-check that you have **Removed all mods from the Mods folder:**
> C:\Users\YourUserName\AppData\Roaming\7DaysToDie\Mods

![image](https://github.com/user-attachments/assets/5dc12ac2-57aa-4e6a-8ce7-efc9cbaf5d85)

---

_Assumptions continued..._

F. You are literate, and have basic computer literacy to figure simple things out for yourself.

---

G. If you edited or added _ANYTHING_ to the main game folder directory, you will _probably_ need to performa a full uninstall and reinstall of the base game.  

"But why?!" you ask?  
Because Wabbajack will compare the hash files of your base game files to it's vanilla base game hash values, and if they are off, it _might_ cause errors in installing your ModList.

> [!TIP]
> **It's always considered best practice to use a fresh clean vanilla install for _any_ Overhaul ModPack**

... examples of you molesting base game files include: adding a ReShade, injecting the SkipNews Mod into base files, same for the Skip TFP Loading Screen Mod, adding additional folders, in-file gfx tweaks, making changes to vanilla folders/files, etc.  

**If you feel like getting this installation right the first time, perform a full uninstall/reinstall.**

---

H. Best Practice for all PC Gaming, and especially Modding: **Store Mods and Mod Applications in the correct locations!**

**In Windows, you should _avoid_ storing mods on your system drive (usually labeled as "C:"),**

particularly in locations like the "Program Files" folder, 
as this can cause potential issues with game updates, compatibility problems, 
and might even lead to your mods being accidentally deleted during system maintenance or updates. 

Here are a few specific places to _avoid_ storing mods on Windows:

Program Files folder: This directory is designed for system files and applications, not user-generated content like mods.

Windows directory: Similarly, the core Windows directory should not be used for storing mods.

Temporary folders: Avoid storing mods in temporary folders as they may be deleted automatically by the system.

**Where _to_ store Mods, Modding Applications, folder paths, and folders instead:**

**Dedicated drive:**
Ideally, you have a separate hard drive for Modding.  
If so, consider storing your mods on that drive to maximize space and avoid potential conflicts with your system files.
If you have a spare drive (like a D Drive), store Mod Applications, file paths, and folders there!!!  This is best practice for modding any game!  

Example:

![image](https://github.com/user-attachments/assets/87030c6e-60de-4921-9cd0-5cca3f885389)

If you only have one drive, like C, and the OS is on it, then create your own Modding folder on the OS Drive like this example:
_This is the second best option if you don't have a spare drive._

### C:\Modding

![image](https://github.com/user-attachments/assets/93b78bfe-12f6-4a76-aa55-423fc7ac73ea)

---

I. **Do not install/use your own MO2!**

> [!WARNING]
> This ModList uses it's own modified instance of MO2, and it is part of the download of this Wabbajack list.  
> Do not use a standard MO2 install downloaded from other locations, it will not work!
> Again, this Wabbajack list download process will include it's own modified instance for MO2.  Use this one!


______________________________________________________________________________________________________________________

# Installation Directions


## Step 0: You must have a Nexus Mods account.

Either Free or Premium will work.  

If you have a Free account, prepare to do _a lot_ of clicking.  
For Free accounts, Wabbajack will open one browers tab at a time, for you to manually download each mod. 

Premium accounts will click once to download all of the Nexus mods, and download them at a higher speed.  

If you don't already have an account, you can register here:
https://users.nexusmods.com/register

Remember these login credentials, as you will need to use them to connect the Wabbajack application to the NexusMods page later.

---

## Step 1: 

To get ModOrganizer2 (MO2) to work, you will need:
Windows 10 1809+ or Windows 11 are now required due to the upgrade to Qt 6 and Python 3.11.
Microsoft Visual C++ Redistributable 14.40.33810.0 required, install from https://aka.ms/vs/17/release/vc_redist.x64.exe if needed.

If you are not sure you have it, downlaod and install it now.

---

## Step 2.  Download/update to the latest version of Wabbajack: https://www.wabbajack.org/

If you already have Wabbajack installed, you _must_ update it to the most current version.

Older versions of Wabbajack do not support 7D2D!  

7D2D only recently received Wabbajack support! 

Chances are, you are running an older version.  

It won't prompt you to update from within the application, so go download the new version.

https://www.wabbajack.org/ 

Wabbajack will store multiple versions of itself on your system if you don't do housekeeping, so make sure you are launching the _newest_ version. 

_*cough *cough, update the shortcut/pin on your taskbar._

_If you are new to modding, please see the "Assumptions" section of this write up above, bullet point "H" for where/where-not-to store things when modding._


Before going any further, connect your Login from Nexus Mods to Wabbajack in the Wabbajack application.
From the Wabbajack application main screen, press the settings "gearwheel" icon on the top right.
Login to your Nexus Mods account from inside of the Wabbajack application, and enter your credentials.

**If you successfully entered your login username, password, captcha, and (optional) MFA token; it will look like this screenshot.**

![image](https://github.com/user-attachments/assets/d7197a91-44ba-4c5c-ba03-59ea4279c000)

---

### Step 3. Find the "Better 7D2D" by FNS Overhaul ModPack in the Wabbajack Gallery of ModLists.  

From the Wabbajack Appliction, Browse Modlist:

You can press the "Game" dropdown arrow and select 7 Days to Die.  Make sure "Show Unnofficial Lists" is also checked.  

At the time of this writting, my ModPack is the first and only Wabbajack list for the 7D2D game.

Download the "Better 7D2D" Overhaul ModPack.

The Wabbajack Application will prompt you to input an Installation Location folder:

As an example, I made a New Folder, in my Modding Folder, called: "WJ_MO2_7D2D_Installation"

![image](https://github.com/user-attachments/assets/9681a93c-77d5-4f39-8ae5-cc6c7a23ea5d)

_If you are new to modding, please see the "Assumptions" section of this write up above, bullet point "H" for where/where-not-to store things when modding._   

Here's what it looks like as Wabbajack is downloading and installing the ModList:

![image](https://github.com/user-attachments/assets/99c3626c-8735-4bdc-acd2-b16e11419ee3)

![image](https://github.com/user-attachments/assets/3e459127-0ce9-41d2-b89c-185cc861b846)

![image](https://github.com/user-attachments/assets/8c395d4b-7890-45d2-9828-f18119963a39)

![image](https://github.com/user-attachments/assets/6797a7ba-23b9-44ed-a8b9-d9eea8d68214)

---

## Step 4. Open MO2 launcher for "Better 7D2D".

When Wabbajack has finished the download, unzipping, and installation of the ModList, Launch the MO2 application ModList for "Better 7D2D".  

Launch this MO2 instance from where you installed the Wabbajack files for this ModList.

> [!TIP]
> It would be prudent of you to make a shortcut, or pin to taskbar of this "Better 7D2D" MO2 instance.

When you open up MO2, you might see this pop-up.  Just hit "Yes".

![image](https://github.com/user-attachments/assets/65cfab71-5be8-4598-b668-f0da4eb48fb4)

---

## Step 5. Customize the ModList in MO2 to suit your personal preferences.  

> [!CAUTION]
> Do _not_ rearrange the Priority (Load Order) unless you know what you are doing.  

I hand-tailored the priority (Load Order) to avoid mod conflicts.  

If you mess that up, I cannot/will-not fix it for you, and you will need to uninstall/reinstall the ModList.  

_The following screenshots in this section were uploaded from Revision version 56.0 of this Overhaul ModPack._  

## Do not disable **Framework/Requirement Mods** (unless you are an advanced modder and you know what you are doing).
![image](https://github.com/user-attachments/assets/07fed2a2-1379-4cc7-8c13-f06d4c307889)


### **Prefabs and POIs.**  
If you want to add _and_ enable, or disable any prefab/POIs, do it here _prior to making a new world_.  
**DO NOT DISABLE PREFABS/POIs MID-SAVE!**
![image](https://github.com/user-attachments/assets/12161046-e02b-49f2-9b8f-a5141c956e07)


### Standard Mods are what I (FNS) imagined as integral to this modpack.  
_Most_ of the mods can be disabled here, but you should start a new game if you do so.
We have a saying in my house when children are skiddish to trying new foods: "Trust the Chef!".  
What I mean is: Try playing the list _as is_ before monkeying around with the Standard Mods.  

![image](https://github.com/user-attachments/assets/857bd756-de35-420b-92b9-c8ec248b4cfd)


### Optional Quality of Life (QoL) Mods are to be enabled/disabled as you so choose for your personal preference.  

But again, it's best practice to start a new game anytime you alter mods.  

![image](https://github.com/user-attachments/assets/8e5a4b37-03e1-4b5b-bad6-d702667f1d44)

_It's unwise to disable/enable mods midgame unless you know what you are doing as it could corrupt your save._  


### I also left a separator/section for you to add your own mods.  

I populated it with "Less Annoying Slower Vultures" (disabled) just as a reference.  
![image](https://github.com/user-attachments/assets/be21bd28-f205-4aed-86c0-47625c72cf46)

Here are some popular off-site (not included in the list) mods that are compatible with this ModList if you want to add them to your own game:

https://7daystodiemods.com/tuk-throw-stuff-mod/

https://7daystodiemods.com/double-g-zombies/

https://7daystodiemods.com/non-script-radios-video-games/

https://7daystodiemods.com/trader-quest-preview/

You can download these mods, drag the zip folders into the Downloads folder within the MO2 folder for this ModList.  
Then drag them from there into MO2, in the Yellow "Where you may choose to add compatible Mods..." section in the MO2 ModList.  
If Mods are double-nested, you will need to fix that yourself.  
Depending on the mods, you might need to place them somewhere else in Priority (Load Order).  

## Optional Overpowered Mods are to be enabled/disabled at a players discretion.  
But again, it's best practice to start a new game anytime you alter mods. 

The deselected mods in this screenshot are the ones I disable for my own playthroughs. 

None of the "OP" mods listed here are aggregiously OP, except for "Legend Perks".  
That one is Game-Breakingly OP because it grants you two perks at every level on top of giving you more perks to choose from!

![image](https://github.com/user-attachments/assets/92de5741-a517-44d0-9ba3-cf13bbd55760)


### Finally, there is a small handfull of Requirement Mods that must load last.  
Do not move these mods, nor add mods after these, or you will probably break these mods and possibly your save.  
If you want to play without the mods from this section, you MUST start a new game save with these mods disabled!

![image](https://github.com/user-attachments/assets/b829bc8f-260c-4a36-b26b-95dd1a997cb0)



---

## Step 6.  Launch the game from MO2.  

To play the modlist of this game, you hit the "Run" (Play) button from inside the MO2 application.   

![image](https://github.com/user-attachments/assets/0ebb9b69-0be8-4adc-89e9-b4fc3bf47882)

> [!WARNING]
> Do not mess with MO2, or the MO2 files for this ModPack while the game is running!!!
> Exit the game completely before altering MO2!

---

## Step 7.  Random World Generation (RWG) 

> [!NOTE]
> You might need to delete worlds to make room for new ones:
```C:\Users\UserName\AppData\Roaming\7DaysToDie\GeneratedWorlds```

Once inside of the Game, at the start up screen, you will want to create a new game.
When you go to create a new game, create a new map!  
Create a new world with advanced generation.  I recommend 8-10k sized maps to see all of the Community made POIs.  
Random World Generation (RWG) will take much longer than vanilla.  2-60 minutes depending on hardware and map size.  
NASA boys in 2-3 minutes, potato-bros in 10-40 minutes.  

"Why does it take so long to RWG in this list compared to Vanilla?!" 
Becaue several of the Framework mods make significant changes to RWG.  
... increase city size, more POIs, less wasted space between POIs (compared to empty maps like Navezgane), etc.

Do not make maps larger than 10k if you are using potato-grade hardware.  
It could crash in RWG, or worse, mid-game.  
Know your limitations, or upgrade your potato, don't blame me because you haven't upgraded your hardware in 12 years!  

Recommended RWG Settings for this modpack if you want to see a better variety of the Community Made POIs:
![image](https://github.com/user-attachments/assets/c318e31b-4926-45fe-8a97-edd045927889)

---

## Step 8.  Recommended Game Settings

Play with Loot Abundance set to 75% or lower.  There is more than enough loot from the "FNS's Loot All the Things" (LAtT) mod.  
![image](https://github.com/user-attachments/assets/a541ac67-95b3-4d67-a6a2-9e92d7b260d5)


______________________________________________________________________________________________________________________



# Troubleshooting

1. Are you sure you are on the correct game version?  Currently this is 7D2D game version: **1.2b27**
![image](https://github.com/user-attachments/assets/7b908b39-5b5a-4012-bc6a-9b638bebd593)

---

2. Is EAC off?  
Run the Game Launcher from Steam, and make sure you disable EAC.  
It CANNOT be set to ask if you want to turn it off at each launch, it must be disabled!
![image](https://github.com/user-attachments/assets/c5862c19-6d78-4670-aaf4-7c38c2d6cf88)

   ![image](https://github.com/user-attachments/assets/f18cab91-3e23-44fa-aa2d-1e6d214b0e49)

---

3. Are you sure you didn't delete "0_TFP_Harmony" from the base game files?

Typically here:  
```C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods``` 
If you did accidentally delete that file, run a File Integrity check from Steam.

![image](https://github.com/user-attachments/assets/e86cbc48-27e8-4302-a38c-8fd607dbd0e0)

> [!WARNING]
> The "0_TFP_Harmony" is a required reference other Mods will point to.  
> If you delete it, or do something dumb like rename it, the other mods in this list will not be able to reference it, and will not work!


---

4. You are using the most up-to-date version of Wabbajack right?
If not, update Wabbajack, by downloading the latest version.
https://www.wabbajack.org/ 

---

5. Have you reset your Wabbajack files in a while?
   
If not, you should do the following:

Close out of Wabbajack.

Press WindowsKey+R, to bring up the Run prompt box.

Type (or copy+paste) the following: %localappdata%

Hit enter.

You will now be in a Windows Explorer Folder directory named "C:\Users\YOURUSERNAME\AppData\**Local**", delete the "_**Wabbajack**_" folder in that **Local** folder.

Now open the Wabbajack Application, Settings gear wheel, log into NexusMods from Wabbajack. 

Sometimes Wabbajack, gets _Wabbajacked_.  No?  I'll see myself out.

---

6. Are you logged into NexusMods from Wabbajack?

![image](https://github.com/user-attachments/assets/baea7e05-d215-459f-b9c3-fbfe936a31dc)

---

7. When in doubt, **Nuke it from orbit**.  Perform a full uninstall and reinstall of the base game, Wabbajack, and the MO2 ModList from Wabbajack.  

![image](https://github.com/user-attachments/assets/fef51abe-817e-4a3a-a722-62b9539e7f9e)

---

8. **Graphic Errors and Unexplainable game freezes:**
   
My game was crashing, but it wasn't directly caused by Mods. 

I looked at the Logs, no (unexpected) Mod Errors, but there were issues at the end time of crash:

d3d11: failed to create staging 2D texture w=128 h=2 d3dfmt=10 [887a0005]
d3d11: failed to create staging 2D texture w=128 h=2 d3dfmt=10 [887a0005]
d3d11: failed to create buffer (target 0x5 mode 1 size 864) [0x887A0005]
d3d11: failed to create buffer (target 0x2 mode 1 size 72) [0x887A0005]

A. Update your GPU Drivers.

B. Consider changing your Video Setting Graphics to a lower grade like "High" or lower. 

C. Also, don't go monkeying around with graphic settings if you don't know what you're doing, or you will create errors.  

For most players, turn off Dynamic Mesh, play on "High", and leave the rest alone!  

Just because one set of settings works for your friends hardware, doesn't mean the same graphics settings will work for your system!  

No guarantee that game/world save can still be played in, you might need to start a new game/world.  

---

9. A note for Super Ultrawide monitor users: 

I'm sorry, you won't want to hear this, I know you want to make full use of your beefy rig and awesome monitor, but this game hates playing even at "High" with 5120x1440 resolution.  

The Samsung Odyssey series of monitors do not play well at 5120x1440 resolution with 7D2D, and it's even worse when you add mods and try to run with Ultra settings.  

This game is just not optimized for it.  Play with a more modest resolution like 2560x1440, or use a different monitor.  

I don't care what your GPU/CPU is, how much RAM you have, I'm trying to save you from the aggravation of the dreaded monitor-flicker black screen game freeze.  

I have one of these monitors, and I have tried EVERY troubleshooting trick under the sun.  

Nothing will fix it!  This game with that monitor is cursed!  

> "I'm not trying to rob you, I'm trying to help you!" - Gandalf

---

10. Two common problems, same troubleshooting steps.
   
**Stuck on the in-game world loading screen where it says "Building environment..."**

**Crafting bug:  "My crafting queue won't complete?!"**

Press F1, you probably have an endless wall of Red Error text dropping down like a waterfall.  

This is preventing the game from loading/working.  Ctrl+Alt+Del, Task Manager, end the 7D2D game task. 

The ModList is temperamental to the following conditions:  

**A. Did you add mods that weren't part of the ModList?**

I cannot vouch for compatibility for mods that weren't part of the List.    

If you added untested mods not from the list, disable the new mods.  

Maybe your existing game save/world will load in, but it's possible that world/save is ruined.

Example: You tried to add incompatible mods that weren't on the Collection list.  

NPC mods can be buggy with this ModList, which is why I haven't included any. 

**B. Did you disable/remove mods mid-play through on an existing world/save?**  

That world/save is probably ruined.  Start a new world without enabling/disabling mods mid-play.

Example: If you remove SCore, Quartz, IDC Core, or other support/framework/requirement mods, it will destabilize your save.

**C. Are you sure the Priority (Load Order) is correct?  MO2 keeps the Priority (Load Order) I (FNS) set... if you screwed it up, reinstall the ModList from Wabbajack.**

**D. This is probably your problem:**

Remove all mods from Mods: C:\Users\YourUserName\AppData\Roaming\7DaysToDie\Mods

If you see this in the (F1) Console:

![image](https://github.com/user-attachments/assets/00b09726-c6f0-4097-9625-48623b7b831e)

Or this:

![image](https://github.com/user-attachments/assets/3f7a520c-2732-4995-80c2-454ffc0ff5af)

**You have to remove all mods from: C:\Users\YourUserName\AppData\Roaming\7DaysToDie\Mods**



______________________________________________________________________________________________________________________

# How do we update the ModList?

First: You should not try to update my list piecemeal in MO2.  
As much as I love MO2, it has one deficiency: Versioning
MO2, it's weird about versioning updates.
If a Mod Author is sloppy about versioning, MO2 will tell you there is a more current update available, 
even though you have the latest one, and it is trying to imply you should download the older-mislabeled-as-newer version.
So, this is why I don't recommend you DIY Nexus updates from the mods in MO2.

_Just wait for me to update the ModList._ 

**I will post update notifications to Guppy's 7D2D Modding Discord Server, on my #fns-wabbajack channel.**  

> [!CAUTION]
> Sometimes you can keep using the same save-world and safely update to a new version of a ModList.  
> However, there are no guarantees this will be safe.
> It's considered best practice to start a new world-save when you move to an updated version of a ModList.  
> So, if you want to keep playing in an existing save, wait until you are done with that playthrough prior to updating the ModList in Wabbajack.

Always exit MO2 prior to updating your ModList with Wabbajack!

If you cursor-hover over the picture of the ModList in the Wabbajack application gallery, you'll see which version is available.

![image](https://github.com/user-attachments/assets/3cf5544e-a59d-495f-8443-a9e7fdec0536)


When a new version is available in the Wabbajack application Gallery, you simply download the list again, overwriting the existing installation. 


Check the Overwrite Installation box.  Then hit the play button in Wabbajack to update to the latest ModList version.

![image](https://github.com/user-attachments/assets/e6b1a2c3-e081-4ae5-b4de-0fb13fb2265e)



______________________________________________________________________________________________________________________


# On getting assistance from FNS:

> [!IMPORTANT]
> No Logs = No Assistance!

### You must send me your logs if you expect help.  

I am currently unable to troubleshoot via telepathy, so you must send logs!  

Screenshots of the (F1) console are not logs, so send logs!
If you send me screenshots of the console, I am just going to tell you to send logs!

> [!IMPORTANT]
> When you use MO2/Wabbajack, your game logs go to a unique location:
```C:\Users\YourUserName\AppData\LocalLow\The Fun Pimps\7 Days To Die```

![image](https://github.com/user-attachments/assets/40b8efd2-11dd-4eec-a24d-0457b0ad6f4d)

If you have read through everything here carefully, tried it all, and still cannot get it to work, 

please hit me up on **Guppy's 7D2D Modding Discord:  https://discord.gg/fxkW8QvR**  

I have my own channel there, #fns-wabbajack.  I'm fairly quick to respond, and can usually get you sorted out.  

______________________________________________________________________________________________________________________



## FAQs

**1. Why did you leave the Vortex Collection Nexus Mods Manager system?**
   
After a recent Vortex update, it broke the stability of Load Orders.

If you're new to modding, Load Order (mod priority) is sacred!

You can't use an application that regularly messes up established Load Order, because it causes mod conflicts, errors, and crashes.

I care about game stability first and foremost.  

Users kept complaining that the Load Order would randomly rearrange itself between sessions when playing the Vortex Collection.

You need like a damn PHD to understand all of Vortex's quirks.  

It became too time consuming to help users troubleshoot, and I didn't like people bad-mounting my hard work because the tool was screwing up.  

So, it was get the ModList to work in MO2/Wabbajack, or quit providing the list for users entirely.

Thankfully, the Wabbajack community was extremely helpful in getting 7D2D to work in their ecosystem.  

---

**2. "Why didn't you include _fill-in-the-blank-popular-mod_?" and "Why only include mods from Nexus?"**

A. It's my list, I added what I like, feel free to add more, but do so with care so as not to break the ModList.

If you have a good mod suggestion, and have tested it works with the list, please hit me up on the Guppy's Discord #fns-wabbajack channel.  https://discord.gg/fxkW8QvR

B. Mods from NexusMods are automatically whitelisted for support with Wabbajack/MO2.  It makes for less work, and less hassle for me as a ModList curator.
Including mods from other sources adds more work for me as the curator, and also adds points of failure for users using the list. 
KISS!

---

**3. Is this for just single player, or could it be multiplayer, or on a dedicated server?**
 
This list is designed for single player and small groups.

There are several users playing multiplayer with friends and family using this ModList.
I regularly host multiplayer games with my sons, brother, and friends using this ModList.  

This list is not ideal for a dedicated server, but you could cannibalize the mod list for ideas.

_Caution: Some mods like IDC's Nomad do not work in multiplayer!_

---

**4. Do both the server and all clients need to download this entire ModList for it to work on multiplayer?**

Yes!  The community-made POIs need to exist on both server and all clients.  

Additionally, some of the mods likely also require installation on both client and server.

I don't keep track of which mods are server side or client side, so don't ask me.  

I don't have experience with dedicated servers, so I am the wrong person to ask you to troubleshoot that area.  

A general rule of thumb I learned is this; simple xml mods are generally server side. 

Anything that adds something beyond a Config folder, such as; textures, icons, new items, UI Atlas changes, dll, meshes, **localizations**, animations, new sprites, POI, etc., will need to be on both server and client.  

EAC can stay on for pretty much anything other than when mods start adding in dll files. 
Then EAC has to be off.    
_EAC must be disabled prior to launching this ModList!_

YES, I AM AWARE THERE ARE EXCEPTIONS TO THESE RULES.

---

**5. No, you should not add this ModList to an existing save/world!  Start a new save/world!**

---
   
**6. No, this ModList is not compatible with other Overhaul ModPacks.**

No, I will not make you a version compatible with Darkness Falls, nor Rebirth, nor any other Overhaul Pack.

Not my circus, not my monkies.  

Both Khaine and FuriousRamsey do their own thing, and don't like people adding crap to their packs.  

---

**7. Why don't you use ModLauncher, bundle everything under one zip-file, or make a "real" Overhaul Mod like Darkness Falls and Rebirth?**

A. ModLauncher (ML) won't work for my needs in using so many other authors mods in a collated list like this.  
I tried, it's just not for this use case.  
ML is for "real" pre-bundled Overhaul ModPacks.  

B. This list uses nearly 200 mods from about 100 different Mod Authors.  
I cannot bundle their works into one zip file without each and every mod authors permission... see "herding cats".
People who bundle other authors mods without permission/credit are seen as scum, and generally get banned from nicer modding communities.
I don't want to piss off my fellow mod authors, they're good people!  

C. Khaine and FuriousRamsay have more time and talent to dedicate to their own "real" Overhaul ModPacks than I do.  
They make almost everything themselves in-house for their Overhaul ModPacks, or only use a handful of community-made framework mods.



---

8. **"I don't like the ____ Mod!"**

Disable it, and move on with your life.  No seriously, don't complain, just disable it!

FNS Special Requirement POI Pack, Izy's AIO, Lazy POI Pack, and IDC's Nomad have a few requirement mods (see those mod pages for details), but most mods in this List are optional!

Caution: If you remove a "big" mod mid-game, you might have to start a new game world/save, or you will have game breaking errors.  

Example: Don't enable/disable FNS LAtT nor FNS Self-Planting Trees in the middle of a save.

---

9. **This is not a "lightweight" mod list!**  

If you delete this whole ModList, or disable it in parts, you will need to start a new save/world.

Trying to play a heavily modded save/world, after removing big mods will cause you errors... just start a new world/save! 

---

10. **What about normal Trader Progression for RWG?**
    
On the Generate World settings page, TFPs included a disclaimer that generating a world may break quest progression. 

If you start a new game, and see "NO TRADER" on the top right of your screen, here are your options, pick one:

A. Keep trying a different seed until you get what you want.  

Keep each Biome to at least 14% to have better results of every Biome generating a trader.  

Don't play with maps under 4k in size, or traders might not spawn at all.  

6-10k sized maps are good, 10k+ is best if you want to see more of the Community made POIs. 

B. Walking in to a new Biome will often locate a new Trader for you.  

You could manually find a Trader and complete the first quest missions... 

Since in the base game, the progression starts with a trader, it may work that way on the generated worlds as well.

C. Easiest Method: You could start your world with the creative/debug menus on, find/teleport to your trader of choice, then turn off those menus.  

"How do I use the Creative and Debug Menus?"

In the game world, hit the F1 key to open up the console.  

In the console, type "cm" and hit Enter.  This will turn the Creative Menu on.

Now type "dm" and hit Enter.  This will turn the Debug Menu on.

Hit the Escape key once to back out of the console.

Hit the Escape key again to open up the "Pause/Menu Screen".  

Now you can open up the POI Teleporter.  From the POI Teleporter, you can type the word "trader" in the search box.  

Now double-click Trader Rekt if that's what you want to do.    

To remove the Debug and Creative Menus, simply go back into the (F1) console and type those two commands again to disable them.

---

11. Interesting information about MO2 for 7D2D:  **It's a self-contained ModList!**

This means it shouldn't stop you from having a concurrent game of Darkness Falls, Rebirth, Vanilla, and Better 7D2D by FNS.  

I would not use Vortex, or run Mods out of other not-self-contained packs because they will mess with other ModPacks.      

ModLauncher can also be self-contained so long as you set it up correctly.  

---

12. "Hey, does this Wabbajack MO2 thing bundle other people's mods without giving them the credit and Donation Points?!"

No, that would be unethical.  This system does _not_ bundle their work in a zip and pass it off as mine.  

From a credit and Donation Point aspect, it's no different than a user going and manually downloading each of these mods one-at-a-time on NexusMods.

The Wabbajack and MO2 applications connect the API to NexusMods, so it downloads each mod individually.

Mod Authors still get download credit, complete ownership of their mods, and Donations Points (if they opted in) every time a player installs the mods from this ModList.

Wabbajack and MO2 work in harmony to provide curators like me (FNS) the ability to create ModLists for users to efficiently download and run with.

It's like paying for someone else to do the grocery shopping.  
A ModPack curator provides the ModList. 
The user just swings by and picks up the groceries that the Wabbajack-Store workers have already bagged. 
That's it.

---

13. "Does a Wabbajack/MO2 ModList require permission from the others mod authors?"

No, because again, as far as Nexus Mods sees it, it's no different than a user going and downloading each of the mods from the ModList independantly and stringing them together exactly as I did.
All the Wabbajack/MO2 applications do is make the process more efficient to use someone else's list.  It does **_not_** rebundle/repackage mods!  

---

14. "Is Wabbajack/MO2 complicated to use... do I have to use that command-line thing?"

Nope, it's the easiest method to enjoy other people's ModLists.  No CLI, just a simple GUI.

---

15. Is it difficult to make your own ModList for 7D2D?

That depends how IT-savvy you are.  

The Wabbajack Wiki on how to Compile your own ModLists is great, but it requires you to read and follow directions.

Additionally, the Wabbajack Discord group is extrememly helpful in making ModLists.  

If you want to make one, hit me up on Discord, and I can show you some of the pitfalls not addressed in the wiki specifically for 7D2D.  

---

16. "Hey FNS, could you make this ReadMe any longer?  I'm really looking for something beefy after finishing <ins>War and Peace</ins>."

It's long because it's comprehensive.  

For people who have been modding this game for years, they already know most of this stuff.  

The more self-service users are with troubleshooting their own problems, the less work and aggravation there is for me!  

It's always someone's first day, so I assume anyone reading this could be entering the world of game modding with an empty cup.  

![image](https://github.com/user-attachments/assets/9394e729-c90e-448a-90f6-f5e1111a779b)


______________________________________________________________________________________________________________________

## Known Issues

**2. CAT UI additional toolbelt slots UI issue.**

![image](https://github.com/user-attachments/assets/fc29e78d-0c19-412d-9ed3-5c2280bd103b)


There is a workaround for now, but it's manual.
From NexusMods User: AkosEquilibrior
Regarding the CATUI_toolbelt_more_slot mod.  
The additional hotbar comes from CATUI (for 1.1 stable) - ZZZ_CATUI_toolbelt_more_slot
It bothered me, because the extra hotbar interfered with the crafting interface so i found a solution:
Open the mod folder there should be a folder "Config" then another "XUi" and in there a "windows.xml". 
Open this file with a text editior and change the value from 12 to 10. 
Or to something higher but under 24 if you want to use the additonal hotbar slots.

Or you could live it, or you could just disable the mod, your call.

---

**2. These are some Warnings and Errors you will see when you load into the world.**

They can be safely ignored.  

Yes, I am working on fixing them eventually.  

However, I have played this ModList for hundreds of hours with these issues without catastrophic failures.  

![image](https://github.com/user-attachments/assets/a01bea39-653a-4c2d-83cf-144bb9213f6e)

![image](https://github.com/user-attachments/assets/43ce3c23-d97b-4009-9e4b-5dfb211560b3)

![image](https://github.com/user-attachments/assets/607d1919-409b-4942-b65f-5ec78d04c35f)


______________________________________________________________________________________________________________________

## Mod Notes

**CAT UI and Health Bars**: CAT UI is the standard for this Collection and comes with Health Bars turned on.  
There is no way to cut the Health Bars out without causing the whole CAT UI to error.  
So, if you don't like seeing Health Bars, and/or don't like the CAT UI mod, disable/remove the CAT UI Mod and use the AGF HUD instead.  
I have confirmed the AGF HUD is compatible with this ModList.  Additionally, the AGF HUD has an add-on for health bars if you like theirs.   

---

**"Tool Time"** mod: DO NOT ENABLE/DISABLE THIS MOD IN AN EXISTING SAVE OR IT WILL BREAK YOUR GAME!!!  
This mod makes tools viable weapons... Ever wished axes and tool-hammers actually did real damage?  Well, here you go.    

---

**IDC's Nomad**

This is a mobile RV base with crafting workstations.  

This mod requires IDC Core and Quartz.  

It is not for multiplayer.  

It does not currently work for 1.2b27, so not currently part of this ModList.  I'll bring it back into the ModList once IDC updates it.

---

**Vehicle Cruise Control**: When mounted in/on a vehicle, cycle the Q-key on the keyboard to switch from Slow, Sprint, and Off.

---

**OCB's Parachute**: You need the Parachute item mod installed on your chest armor, and a single use parachute item in your tool belt for it to work.  
When falling from a great height, cycle to the parachute item in the toolbelt, and use it with the item use button.  
You will have limited control of the parachute, and still might take a minimal amount of falling damage.  
It's a test mod, not 100% perfect, but it's super fun!  

______________________________________________________________________________________________________________________


## Mods to consider avoiding while using this ModList:

A. **Firearms Expansion 5 (FE5)**

FE5 has a conflict with LittleRedSonja's ammo recycling mods.  

FE5 also has conflicts with Izy's AIO Gun Pack mod, causing problems with 5.56 ammo.  

---

B. **NPC Mods** can be buggy in this ModList, which is why I don't include them.  

I'll wait for TFP to provide their Bandit update next year before I try messing with it again.

______________________________________________________________________________________________________________________


# Additional Links

1. If you would like to see videos of me plyaing through this ModList, or showcasing my POIs and mods, **check out my YouTube channel**.

**https://www.youtube.com/@FlufferNutterSandwich**

2. Article: **How to create and include your own POIs into 7D2D**
  
https://www.nexusmods.com/7daystodie/articles/790

3. Article: **Performance Tuning your Graphic Settings for better FPS in 7D2D**

https://www.nexusmods.com/7daystodie/articles/792

4. Article: **The Social Contract of Mod Authors and Users**

https://www.nexusmods.com/7daystodie/articles/806


______________________________________________________________________________________________________________________


# Credits and Thanks

- YOU for reading this.

- Users like you who provide feedback, endorse mods on Nexus, and help troubleshoot bugs.

- JanuarySnow from the Wabbajack Discord: Thank you for all of your assistance, patience, and time in making 7D2D compatible with Wabbajack.  MVP!

- EzioTheDeadPoet, and Dace from the Wabbajack GitHub/Discord for your support.

- All of the Mod Authors for making the great mods included in this list.  

- StallionsDen for allowing me to include the CompoPack in this ModList, and being a good bro helping me tidy up my POIs.  

- The good folks at Guppy's 7D2D Modding Discord Server, with particular gratitude to: LittleRedSonja, Emu, GoblinRemovalist, creepers152, AM1908, and many others. 


![image](https://github.com/user-attachments/assets/b06dbf93-7271-4f97-833a-140f6efbc7ce)





