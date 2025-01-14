# SWM Modular Modpack
​
## <span style="color:red"> **Disclaimer** </span>
PLEASE MAKE A POST IN THE REBORN EVO FORUM IF YOU HAVE ISSUES WITH ANY OF THESE MODS.<br />
https://www.rebornevo.com/forums/topic/24930-swm-modular-modpack-e1840
<br />

You can also find this modpack's files versioned on GitHub:<br />
https://github.com/Waynolt/SWM-modular-modpack 
<br />

This modpack is for **Reborn**; if you're looking for a Rejuvenation-compatible version, you can find it here:<br />
http://www.rebornevo.com/forum/index.php?/topic/33807-rejuvenation-modular-modpack-v11-patch-3/
<br />

--------------------------------------------------

<br />

## <span style="color:purple"> **Installation** </span>

To **install**, just drop the folder "**Mods**" into the folder "**[Reborn]\Data**"<br />
(In the end you should have a "**[Reborn]\Data\Mods**" folder with a bunch of files inside.)<br />
This video from **Lostelle** explains it, showing each step required: https://www.youtube.com/watch?v=6hc3Mo432C0
<br />
 
If playing on a **Mac** with **Wineskin**, then, as **Tacos** suggests, do all the modding in a Reborn folder outside of the wrapper and then make a new wrapper with that folder.

Every component is **stand-alone**, and can be used on its own; please refer to the "**brief summary**" below for more info on each one.

<br />

--------------------------------------------------

<br />

## <span style="color:blue"> **Brief summary of each mod component** </span>

 

**(Please remember to check and delete the components you do not want when you are installing this mod pack!)**

 
<details>

* "**SWM - ChooseStarter**": while you are in the starter selection room, you can select your starter (as if you wanted to give it an item) and use the "Change starter" option to randomize or choose its species.
<br />

* "**SWM - EvOverflow**": if your mon's EV in any stat would go over 252, without breaking the 510 overall limit, then you are offered the choice to improve its IV, at the cost of resetting that EV.<br />
If instead you use friendship berries at 0 EV you are offered the choice to reduce the IV.
Use the password "noevcap" to disable EVs being lowered to make room for new gains when reaching the 510 overall limit.
<br />

* "**SWM - ItemRadar**" changes the ItemFinder so that, when activated, it stays on and marks hidden items on the game map.<br />
(Alternative graphics by **Player_Null_Name**  : http://www.rebornevo.com/forum/index.php?/topic/24930-swm-modular-modpack-e18/&amp;do=findComment&amp;comment=808102 <br />
Alternative graphics by **Xander** : https://www.rebornevo.com/forum/index.php?/topic/24930-swm-modular-modpack-e18/&amp;do=findComment&amp;comment=835844 <br />
To use them, download the .png image attached to the linked post and use it to replace the mod's default "SWM - ItemRadar.png" file)
<br />

* "**SWM - LearnEggMoves**" lets the move relearner teach any egg move.
<br />

* "**SWM - MiningForRich**": while mining the wall won't collapse, but mining further costs cumulatively more and more money (spent on materials to build a tunnel, of course :P ).
<br />

* "**SWM - NoTMXAnimations**" hides the TM animations for using Cut, Strength, etc, out of battle.
<br />

* "**SWM - PredictRelationshipValues**" makes the move Psychic usable out of combat, and using it lets you know each npc's relationship value.
<br />

* "**SWM - RestToWait**" makes the move Rest usable out of combat, and using it lets you wait for some simulated time.
<br />

* "**SWM - SharedPC**" makes the last box in the PC shared amongst savegames: mons you put in it will be there if you start a new game or load a different savegame.
If updating from E18: please note that you have to load up your latest savegame and save once in E19 in order to use the Shared Box in a new game.
<br />

* "**SWM - TypeBattleIcons**" shows each mon's type in battle.
<br />

</details>

<br />

--------------------------------------------------

<br />

## <span style="color:green"> **Compatibility with other mods** </span>

<br />

**Known incompatible mods**:
<details>

* None yet

</details> 

<br />

**Already compatible, no patch needed**:
<details>

* Any mod that doesn't add files to the **Mods** folder.
* Any mod that doesn't change the **Scripts.rxdata** file.
* The E19 version of the **Sandbox Mode** is fully compatible.

</details>

<br />

**Probably compatible, or at least they used to be**:
<details>

* **Pyrolusitium Z** is compatible, but you have to follow its install instructions.
* **Plates of Arceus** is fully compatible.

</details>

<br />

If there's any I forgot about, sorry; simply ask about them.
 

--------------------------------------------------


## <span style="color:orange"> **Changelog** </span>
 
<details>

v68
* Updated for E19.

v67
* Added LocalSavegames.

v66
* EvOverflow has been edited to be compatible with Redux.


v65
* UnrealTime no longer blocks the Lottery minigame (there are easier ways to cheat, after all).


v64
* SWM has been updated to 18.4.

* UnrealTime has been split into two components.


v63
* SharedPC should now be compatible with the Mac version of the game.


v62
* Fixed a bug in BagSortByType.


v61
* SharedPC notifies if the game is not updated to Episode 18.2.


v60
* SharedPC is updated to Episode 18.2.


v59
* SharedPC should now be able to detect corrupted SharedPC.rxdata files and prevent them from being loaded.


v58
* ChooseStarter can now be used to get any Drapion form, modded or not.


v57
* Pickup chance can now be changed using another mod.


v56
* Added a check to ItemRadar to prevent an error.


v55
* Added an option for NoTMXNeeded.


v54
* Added NoHpAnimation.


v53
* Mouse can now select/deselect the button for Z moves/mega evolution/ultra burst.


v52
* Added WildEncounterRates.


v51
* UnrealTime's timescale customization is now handled by another mod.


v50
* Changed the order of the TMXs in NoTMXNeeded.


v49
* SetWeather now tries to prevent a crash by resetting the weather calendar before changing it.


v48
* Added EvOverflow.

* ExpShareFullTeam now tries to show the Exp gained only once per defeated foe.


v47
* UnrealTime's timescale can now be customized.


v46
* Added FindInPC.

* Added MultiSelectPC.


v45
* Added PredictRelationshipValues.

* The moves in NoTMXNeeded are now sorted alphabetically.


v44
* ChooseStarter now also checks for the number of badges.


v43
* Removed an unexpected break from NoTmxNeeded.

* Improved bitmaps' creation in ShowStatBoosts.


v42
* LearnEggMoves now lists incense-bred moves too.


v41
* ChooseStarter and NoTMXNeeded are no longer fused together.

* ChooseStarter now accepts partial names when looking for the chosen species.

* NoTMXNeeded's menu entries are now grouped together in a submenu.


v40
* Added ShowStatBoosts.


v39
* Mouse should no longer indirectly overwrite the speed-up key.


v38
* Added a version check to every component of this modpack.


v37
* Updated the modpack to E18.

* Added AAA.

* Added BagSortByType.

* Added Mouse.

* Removed EggPicking (a derivative of it is included in the unmodded E18).


v36
* NoTMXNeeded is now compatible with another mod's option.

* Added MiningForRich.


v35
* EggPicking got polished up a bit.


v34
* Code improvement for ItemRadar.


v33
* PickupQoL now also affects Honey Gather.


v32
* Added InfiniteBackups, and changed SharedPC to accomodate its edits.

* Removed Insurgence (redundant, since another mod offers the same functionality).


v31
* Added Insurgence.


v30
* v29 was a lie.


v29
* ExpShareFullTeam now accepts another mod's option.


v28
* UnrealTime now includes an on-screen clock.


v27
* Fixed interaction between EggPicking and the Follower mod.


v26

* Fixed a crash with ExpShareFullTeam when fighting double battles while having an incomplete party.


v25
* Fixed a typo in EggPicking.
* ItemsBan accidentally banned pokeballs too.


v24
* Slight code improvement for SharedPC, EggPicking, and ExpShareFullTeam.
* Added module ItemsBan


v23
* Started changelog.

</details>
 
 

--------------------------------------------------

 

## <span style="color:brown"> **For previous Reborn episodes** </span>

 
<details>

Episode 18 <br />
* Download: https://drive.google.com/open?id=1iuvk4uLSRV4VEMF0Gp5wdv9d5MmlZ-ez <br />


Episode 17 <br />
* Download: https://drive.google.com/file/d/1pemW487Qt9kMKQnxS4rhdjamnw0pjhAN/view?usp=sharing <br />
* Compatibility patches: (install the mod, then SWM, then the patch)<br />
  * **Personthing**'s **Follower mod**: https://drive.google.com/open?id=1gov02z03QCcFKw42xhklxpO5vQNIm6Yw <br />
  * **DerxwnaKapsyla**'s **Sandbox mod**: https://drive.google.com/open?id=1jTyAkNqMHjuaU6qDMoB893z12ZNZmJK4 <br />


Episode 16 <br />
* Download: https://drive.google.com/open?id=0B4XiRtkwr4blLXdlX29BU3ZZQ0E <br />

</details>
