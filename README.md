## ZELDA GAME

## PROJECT OVERVIEW
In the text-based adventure game "Zelda," you set out on a heroic quest to free
the princess of CPeria from the evil wizard's grasp. Navigate through nine
mysterious rooms filled with monsters, treasures, and challenges. To obtain
necessary items like a magical shield and a silver dagger, overcome strong
opponents like Medusa and Dracula, and eventually save the princess, using
strategic thinking and thoughtful planning. 
Downloaded from open source project available on github inorder to carry out our task.

## PROJECT FEATURES
# 1 Text-Based Interface
 Text-based commands (such as MOVE, PICK, DROP, ATTACK, and
LOOK) entered by text input.
 An iconic interactive fiction experience was created by using text output
to convey responses and the current state of the game.
# 2 File-Based Storytelling
 The narrative and descriptions of the rooms are kept in external text files
called Start.txt, Rooms.txt, EndWin.txt, and EndLose.txt.
 Makes it simple to expand and modify game material without changing the
core code.
# 3 Validation and Parsing of Commands
 Robust input handling to evaluate the syntax and validity of player
commands and understand them.
 Handling of errors resulting from improper instructions or actions (such as
trying to PICK an object that isn't there).
# 4 State management
 Refers to the process of dynamically updating and maintaining game state
(such as inventory, room transitions, and monster status) in response to
player actions.
 Keeping track of player actions and game results to identify endings (such
as saving the princess or failing to do so.
# 5.Item Management and Inventory System
 Putting in place an inventory system to keep track of goods that are
utilized, dropped, or picked up during gameplay.
 Putting a cap on inventory capacity (e.g., 10 items maximum) to improve
decision-making and strategic depth.
# 6 Room and Object Interaction
 Parsing and presenting room descriptions, items, monsters, and exits
according to the player's current position.
 Allowing object interaction in order to advance the game (such as picking
up, dropping, and battling enemies).
# 7 Dynamic Control of Room and Path
 Room connections are dynamically created and managed as new paths
become available after defeating monsters.
 Ensures that player activities and game events result in a logical
progression through the castle's rooms.
# 8 Closing and Display of Results
 Presenting story conclusions (such as EndWin.txt and EndLose.txt) in
accordance with the successes or failings of the player.
 Presenting suitable text messages and results that take into account the
choices made by the player to end the game session.
