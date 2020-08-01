#### PugLoot provides commands for assisting the master looter with distributing items in PUGs.
This addon does not automatically distribute loot to winners, but makes the process easier.


##### UI
PugLoot adds 2 buttons to the master looter frame.  When selecting an item to master loot, you will see a 'Random' and 'Start roll' button.  These buttons map to the commands below.

While a roll is ongoing, the 'Random' button is disabled and the 'Start roll' button will become a 'Cancel' button displaying the time remaining for the roll period.


##### Commands
`/pugloot random [Some Item]`

Rolls between 1 and the number of raid members and informs the raid of which member was chosen.

The list of members is sorted alphabetically to produce consistent results across group rearrangements.

 

`/pugloot start [Some Item]`

Begins an open roll for an item that lasts 15 seconds.  All valid rolls (1-100) are recorded until the roll period ends.

The member with the highest roll is announced along with a summary of all the rolls.  In the event of a tie, all members who rolled the highest number are listed.

 

`/pugloot cancel`

Cancel an ongoing roll.  All rolls from the session are discarded.


##### Links
- CurseForge: https://www.curseforge.com/wow/addons/pugloot/
- GitHub: https://github.com/icheatatlan/PugLoot
