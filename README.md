# fa16-honors-project
To start the game, your mission is to retrieve 7 key pieces in order to enter the boss room:
key_piece_1: "pick" in room_2
key_piece_2: "openbrown" chest in room_4 and get bomb for key_piece_3
key_piece_3: "kill" poopy in room_11 to get the coin and "talk" to business man in room_10 and get golden key for golden chest
key_piece_4: solve the "puzzel" in room_6
key_piece_5: go down to the "basement" under room_13 and get tele_machine for key_piece_6
key_piece_6: "opengolden" chest in room_7 and get quantum core for teleportation
key_piece_7: unlock automatically when you have seen over 7 different room.
After you have 7 key pieces, type end to enter the boss room, and you will see that every time you attack the Monstro, it will lose one bloods. After three attacks, you will kill the Monstro.

For the requirement:
(Yep!)At least 15 rooms.
(Got that!)At least 15 commands, not including aliases (e.g., n and north and go north all count as one command).
(Absolutely!)To solve the game, the player must retrieve at least one object that is not obtainable without solving a puzzle of some kind.
(Easy!)At least 10 objects.
(You can kill the Monstro, be gentle will you?)Some of the objects and rooms should have state associated with them, i.e., something about them can change as a result of the player’s actions.


guidebook:

"As a person, you can do:\n
    [north]: Go north.\n
     [east]: Go east.\n
     [west]: Go west.\n
     [south]: Go south.\n
     [back]: Go back to the last room.\n
     [up]: Useful when you want to leave a basement.\n
    [roominfo]: Print the basic information of your 
    current location. (Be sure to use it very often to 
    make sure you are not missing something important.)
    \n[roomcont/roomnpc/roomdir]: Print out the specific 
    infomation of your current location.\n
    [status]: Print out your basic infomation.\n
    [inv/seen]: Print out the specific infomation of yourself.\n
    [basement]: Go to the basement.\n
    [puzzel]: Solve the puzzel.\n
    [teleport]: After you have something, use this command to get a critical stuff.
    [drop]: Drop item.\n
    [shortcut]: Jump to the location you have visited when you have battery.\n
    [pick]: Pick items in the room.\n
    [talk]: Talk to the npc.\n
    [open]: Open the chest in the room.\n
    [kill]: Kill small enemy in the room.\n
    [help]: Open guidebook.\n
    [countkey]: See the mission process.\n
    [end]: When you have everything, use this command to transit into battle model, so called hero.\n
    Once you become a hero, the only mission you have is to kill the Monstro, you can do:\n
    [attack]: -1 in Monstro's lives\n
    [status]: check the Monstro's status
    [exit]: When you see 'Mission complete!', use this command to exit the game. It will cause an error (intentionally) in this game and kick you out immediately. \n
    "
