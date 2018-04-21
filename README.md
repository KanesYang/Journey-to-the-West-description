install

Option 1:

Directly go to https://journey-to-the-west.herokuapp.com/ 、

Enjoy!



Option 2：

Install Python 3.6 first.

https://www.python.org/downloads/





On the root directory, open Command Line /  PowerShell / Bash, type

    python -m http.server

Then,  open your Chrome Browser, type following in the address bar (may different on different computers, please check the command line console for sure):

    http://localhost:8000/

If the page doesn't render, please refresh several times and wait.

Then select home.html 

Enjoy!



User Manuscript

Important!!!

Whenever you load the game, please use 'F5' to refresh the game.



Due to the bug of external files, network situation as well as some hidden problems in this game, there are some inevitable bugs of this game, those are not confined to:

- Stuck on map and cannot move
- Don't load the correct savepoint
- stuck in battle stage
- ......

What you could do to deal with those issues is just by pressing "F5" on the keyboard to reload this page.



Title state



use  Left arrow and Right Arrow key  to choose different items

use ENTER key to select 

use ESC key to back to the main menu



Credit state



See the development team list.

use ESC key to back to the main menu



Option state



You could choose to open/close music, sound effect

use  Left arrow and Right Arrow key to choose different items

use ENTER key to select 

use ESC key to back to the main menu





Load

Load the previous game records from the database

New

Start a new game, you could see a basic introduction to this game first, then start the game at the beginning.



World Game Stage



use the arrow key to control the player



Press ESC key or click the Purple button to pause the game



You could also use on-screen-control to play by using finger or mouse





There are several objects on the map, enemy, NPC, equipment, Quests, Recoveries and Doors.





- enemy: start a fight with the enemy





- NPC: start a conversation 



press Enter to skip the conversation







- Equipment: pick up to increase stats



press Enter to skip the information





- Quests: pick up to complete quests and get some experience rewards



press Enter to skip the information









- Recoveries: collide to recover HP and MP



press Enter to skip information







- Doors: Move to next scene
  
  

In the map, there is a potential of battle with the randomly generated monster. 



Press ESC to trigger a pause screen



In the pause screen, the player could see the current stats of characters, inventory list and current quests.



And back to the world stage by press 'ESC' or click the screen



Battle Stage



In the battle mode, use the mouse to choose an action, the player could choose  (use MOUSE!)





Attack1: physical attack one single enemy





Attack2: magic attack one single enemy, consume some MP

enemy list:

When choosing attack1 or attack2, the player could choose which enemy to attack (use MOUSE!)









Defense: Increase the Defense of Sanzang







Item: Use HP potion or MP potion to one character

Item list :

When choosing the Item button, the player could choose to use item: (use MOUSE!)









Run: escape from battle, there is a success rate, for an ordinary fight, the rate is 0.75 and for the boss fight, the rate is 0





If Sanzang or all character died., player lose and game over. If all enemy eliminated, the player wins to back to the world.





Appendix



Update for TDD

- add Quests object
- add Recovery object
- External Code: use some code from blogs on https://gamedevacademy.org/  and tutorials made by Renan Oliveira Netto
- The new design of pause screen
- different damage HUD objects 
- different Status HUD objects
