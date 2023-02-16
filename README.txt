-LIVE A LIVE RANDOMIZER V1.0-  1/10/2023

Welcome to the Live A Live SFC Randomizer! The randomizer is a modification to the base game allowing for randomization of the game's various elements. Randomization is handled inside of the ROM itself, with no need for seeded roms or external programs. In order to use the randomizer, you will need FLIPS (Or any program that can patch .BPS files), as well as a copy of the 2.0 English fan translation patch. Simply apply the patch over the fan translation ROM, and play. From the title screen, you will be taken to the Randomizer menu, which can be opened at any time during normal gameplay by going to the [Sound] option from the pause screen, and selecting the [Randomizer] option. The game can only save data for one seed at a time, but this seed will persist between save files and resets until another seed has been generated. Settings can be changed mid-game, though Major Characters will not take effect on the current chapter unless it is restarted. For more information, as well as feedback, bug reports, or if you want to be notified for updates, join the Randomizer Discord here:

[ https://discord.gg/9FYrBNjY2x ]

For more general Live A Live content, join Discord A Live.

[ https://discord.gg/ejFTzQwQYD ]

The 2.0 translation patch can be found here.

[ https://www.romhacking.net/translations/381/ ]

Enjoy! -Pink Switch, 2023

Which patch file should I use?
	(JP) should be patched over the original Japanese rom.
	(EN) should be patched over the english translation.
Some prepatched copies may or may not work. Regardless of which patch is used, the Randomizer will still be in English.


Changes from the base game:

    -Holding B during dialogue will now automatically skip and close the current textbox. This does not work on choice
		prompts, menu text, item pickups, or the Sci-Fi chapter's terminal text.

    -Text prompts during the Sci-Fi chapter will now accept any input as correct regardless of what was entered.

    -The Trial of Technique will now accept any skill usage to break rocks.

    -Files 3 and 4 have been removed to accomodate saved randomizer data.

    -The Music menu has been replaced with the Randomizer menu and is open from the start of the game.

    -[Hard Protect] and [System Recover] have been slightly tweaked to accomodate weaker characters.

    -Some characters in the Wrestler chapter have received slight buffs to be closer to the chapter's expected difficulty.

    -Fighters can now be refought during the Wrestler chapter.

    -The Knight chapter is now available from the start of the game.
      All chapters must be completed including Knight to unlock the Final Chapter.

    -Characters in the Cowboy chapter have received slight buffs to make the chapter more playable.
  
    -[BonkBonk] and [Teh! Teh!] have been slightly tweaked to make Bel more viable as a starting character.

    -All characters can now learn their skillsets from fighters in the Wrestler chapter, even if those skills are not in the
		fighters' moveset. When a character is hit with a skill Masaru could normally learn, that character will learn their
		own skill of that respective level. If a character is hit with a learnable attack, but does not gain a skill, it means
		that character does not have a corresponding skill in their learnset. Taro and Cube can learn the Robotic Accessory
		skills via this method, however they will lose any newly gained skills once the fight has ended. Equipping the
		accessories directly will still unlock the skills as normal in all chapters.

    -If major characters are shuffled, the Inheritors will learn the skill in the same slot that the master's character
		previously used on them, but will not gain any skills if this is a slot they already had or if this slot has no skill
		assigned to it. This will very likely change in the future.
		
	-The item minigame in the Caveman chapter has been slightly changed. The last caveman you need to talk to to receive the materials now
	 has a unique color from the others to stand out more.
	 
	-The scent tutorial in the Caveman chapter can now be skipped by talking to the elder while outside.
	
	-King Mammoth has been made always visible.
------------------------------------------------------------------------------------------------

Features:
   -Major Characters: Randomize the 8 chapter protagonists. This can result in secondary characters replacing main
	 characters. No main characters can be duplicates, however a main character may be a duplicate of an existing secondary
	 character without issue.

   -Character Skills: Randomize which skills each character will learn. Characters will learn one skill on every level, and
	 some characters may have more skills than they would under normal circumstances. All characters are guranteed to have a
	 damaging attack skill in the level 1 slot. A single character can not roll duplicate skills, though multiple characters
	 can potentially share skills.
	 
	-Auxillary Characters: Randomizes the secondary party members for each chapter. With the exception of the chosen Kungfu inheritor, only Major characters can enter the Final chapter.
	  All characters will be guranteed to be unique.
	  
	-Robot Equipment: Randomize which 8 pieces of equipment Cube and Taro will need to equip in order to unlock their extra skills. This will not change which skills they are able to use,
	  even if the equipment normally uses a skill in battle (they won't be able to learn Bang Bang Booom! if one of their skill equipment is the Cola Bottle, as an example).
	  There is a new NPC located in the antique shop during the Mecha chapter, Mock Toei, that will tell you which pieces of equipment will unlock skills for robots.
	  Skill-granting equipment will always be guranteed to be something both Taro and Cube can equip.
	  
	-Character Colors: Menu and battle sprites for characters will be assigned random color sets taken from other characters. Currently, overworld sprites are not affected by this.
	
	-Menu Colors: All menu boxes outside of battle will be assigned a colored theme, ala the box flavors from Earthbound.
--------------------------------------------------------------------------------------
Known Issues:

    -Holding B during chapter intro and ending cutscenes skips displaying the text, but the cutscene time is unchanged.
	
    -The Trial of Mind cannot be entered if Akira is not playable in the Final chapter.
	
    -Sprites on the file menu do not currently match the randomized character.

    -Characters with names longer than 6 characters cutoff Great Asia's prefight text.

    -The Xin Shan Quan master's name overfills the name entry textbox in chapters other than Kungfu.

    -The character on the seed/setting input uses incorrect graphics when loaded from the boot menu.

---------------------------------------------------------------------------------------------
Q/A:

Q: Why do some characters use the wrong colors or appear differently?
	
A: Gori, Bel, Zaki, Taro, and Matsu use color sets that are specific to the Caveman and Mecha chapters respectively. They will still attempt to use their normal colors, but outside of these chapters those colors will be different. Characters that are not in the party, such as in the Final chapter or Auxillary Characters during scenes, load their colors differently from the player party and use their original intended colors. This may be subject to change in the future. Characters will still load the original sprites for special animations, as per the lack of matching animations for a character randomized in their slot.
	
Q: How do I use Power Parts if both Taro and Cube are in my party?

A: Power Parts will be used in formation order- Up, Left, Right, Down. The order can be changed using the [Form] option on the menu.

Q: Why do some characters not learn skills in the Wrestler chapter?

A: Characters that start above level 2 will already have some of the learnable skills unlocked, and will not need to learn them from the wrestler battles.




----------------------------------------------------------------------------------------------
Changelog:

1.0- Initial Release

1.1-

*Fixed a bug where characters and some skills would randomize off an unrelated variable rather than the seed number.
*Fixed a bug causing Wrestler chapter characters to not learn any skills unless they were in the Inheritor's moveset.
	
2.0-

*Fixed a bug where some party members would use the wrong menu background.
*Fixed a bug where Captain Square would appear as Cube on the save/load file screen.
*Fixed a bug where playing more than one level of Captain Square would permanently replace the Sci-Fi character with Captain Square unless the file was restarted.
*Fixed character sprites on the overworld not matching which character they actually were.
*Fixed a bug causing progression to be locked in the Mecha chapter if the skill menu was opened.
*Fixed a bug causing the Final chapter to not unlock unless Knight was the most recently completed chapter.
*Fixed a bug causing the Trial of Technique boulders to always require the unrandomized skill list.
*Fixed a bug where older emulators would crash on the title screen.
*Fixed a crash that would sometimes occur on the Randomizer menu.
*Fixed secondary characters not having animations on the Chapter Selection menu.
	
	
	
*All 3 of the Kungfu inheritors will now learn the same ultimate skill when skills are randomized.
*The caveman minigame to gain crafting materials has been changed to be less tedious.
*King Mammoth has now been made visible.
*The scent tutorial in the Caveman chapter has been made optional.
*The increased running speed will now be applied if the party leader is Oboro, Ryoma, or O-Robo, instead of when the leader was the Ninja character slot.
*Some non-damaging Skills have been added to the safety skill check.
*Kungfu sparring has been completely reworked.
If Character Skills is set to on, when sparring with a character in the Kungfu chapter, when they level up, they will gain the skill that was used on them, replacing the randomized skill they would have otherwise learned in the slot of the skill that was used. If more than one skill has been used, the lower slot takes priority for that level. If the characters has already learned a skill in that slot, the new one will not replace it. If Character Skills is off but Major Characters or Auxillary characters is on, upon level, they will gain the skill in that slot from their normal skill pool.
*Buriki Daioh is now given 4 random enemy skills if the Character Skills option is set to on.
*Progression in the Mecha chapter has been changed. See 'changes from the base game' for details.
