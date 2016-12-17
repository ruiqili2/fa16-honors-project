# fa16-honors-project
**To start the game, your mission is to retrieve 7 key pieces in order to enter the boss room:**<br />
key_piece_1: "pick" in room_2<br />
key_piece_2: "openbrown" chest in room_4 and get bomb for key_piece_3<br />
key_piece_3: "kill" poopy in room_11 to get the coin and "talk" to business man in room_10 and get golden key for golden chest<br />
key_piece_4: solve the "puzzel" in room_6<br />
key_piece_5: go down to the "basement" under room_13 and get tele_machine for key_piece_6<br />
key_piece_6: "opengolden" chest in room_7 and get quantum core for teleportation<br />
key_piece_7: unlock automatically when you have seen over 7 different room.<br /><br />

**After you have 7 key pieces, type end to enter the boss room, and you will see that every time you attack the Monstro, it will lose one bloods. After three attacks, you will kill the Monstro.**<br />

**For the requirement:**<br />
(Yep!)At least 15 rooms.<br />
(Got that!)At least 15 commands, not including aliases (e.g., n and north and go north all count as one command).<br />
(Absolutely!)To solve the game, the player must retrieve at least one object that is not obtainable without solving a puzzle of some kind.<br />
(Easy!)At least 10 objects.<br />
(You can kill the Monstro, be gentle will you?)Some of the objects and rooms should have state associated with them, i.e., something about them can change as a result of the player’s actions.<br />


**Guidebook:**<br />

"As a person, you can do:<br />
    [north]: Go north.<br />
     [east]: Go east.<br />
     [west]: Go west.<br />
     [south]: Go south.<br />
     [back]: Go back to the last room.<br />
     [up]: Useful when you want to leave a basement.<br />
    [roominfo]: Print the basic information of your 
    current location. (Be sure to use it very often to 
    make sure you are not missing something important.)
    \n[roomcont/roomnpc/roomdir]: Print out the specific 
    infomation of your current location.<br />
    [status]: Print out your basic infomation.<br />
    [inv/seen]: Print out the specific infomation of yourself.<br />
    [basement]: Go to the basement.<br />
    [puzzel]: Solve the puzzel.<br />
    [teleport]: After you have something, use this command to get a critical stuff.
    [drop]: Drop item.<br />
    [shortcut]: Jump to the location you have visited when you have battery.<br />
    [pick]: Pick items in the room.<br />
    [talk]: Talk to the npc.<br />
    [open]: Open the chest in the room.<br />
    [kill]: Kill small enemy in the room.<br />
    [help]: Open guidebook.<br />
    [countkey]: See the mission process.<br />
    [end]: When you have everything, use this command to transit into battle model, so called hero.<br />
    Once you become a hero, the only mission you have is to kill the Monstro, you can do:<br />
    [attack]: -1 in Monstro's lives<br />
    [status]: check the Monstro's status
    [exit]: When you see 'Mission complete!', use this command to exit the game. It will cause an error (intentionally) in this game and kick you out immediately. <br />
    "
