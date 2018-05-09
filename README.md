Helper tool for Yu-Gi-Oh! Legacy of the Duelist. It allows for custom duels to be configured including features not available in the regular game such as tag / speel duels.
The save file can also be modified to 100% the content, reset parts and unlock all cards.

# Duel Starter

![alt text](screenshots/DuelStarter.png)

The left side displays a list of available decks in the game. Use the dropdown to select between user decks / game decks / exported decks.
The export button exports the selected deck to a file. View will view the selected deck in the deck editor (cannot use this whilst in a duel).
P1/P2/P3/P4 buttons sets the given player index to the selected deck. (P1 = player, P2 = AI).

Speed: Used for speeding up the game. This may cause crashes at higher values. May cause issues if this tool is reopened and a different speed is applied.

Tag Duel: A tag duel consisting of four total players (all four players must have a deck assigned)
Match Duel: A best of three duel
Speed Duel: Speed duel format consisting of 3 monster/spell zones (4000 LP must be set manually)
Skip Rock Paper Scissors: This will skip the rock paper scissors screen
Full Reload: This will go to the main menu before loading which reduces rendering issues but can increase loading times. Generally this should always be enabled to avoid issues.
Rewards: Rewards will be given for this duel (win cards / duel points)
Starting Player: Who starts the duel
Duel Arena: The duel arena to play on
Life Points: The number of starting life points for this duel
Start Hand: The number of starting hand cards
P1/P2/P3/P4: The name of the deck assigned to each player
PXAI: If checked that player will be controlled by the AI

# Modify Save

![alt text](screenshots/ModifySave.png)

Campaign: Sets the completion percentage of each part of the campaign. Setting everything to 0% available means all content will be playable not complete. 0% regular means some content will be locked and must be completed sequentially.
Challenges: Sets the completion percentate of challenges.
Available Shop Packs: Sets the availability of packs in the "Card Shop" menu.
Available Battle Packs: Sets the availability of the battle packs in the "Battle Pack" menu.
Deck Recipes: Sets the unlocked deck recipes to be used in the "Deck Edit" menu.
Avatars: Sets the unlocked avatars to be used in the "Deck Edit" menu.
Cards: Sets the card count for every card (All 3x = unlock all cards with 3 available for each).
Duel Points: Sets the number of duel points.
Remove default cards: Removes the cards given to you by default when you first start the game (reset when the game is reopened)
Unlock buttons: Unlocks all menu buttons such as "Card Shop" / "Deck Edit" / "Duelist Challenges".

# Animations Blocker

![alt text](screenshots/BlockAnimations.png)

This can be used to block many animations / actions which are played during a duel. This is useful for animations which take a long time to complete and make things less fun. Blocking some animations / actions will softlock the duel or cause side effects so be careful.
Use the log checkbox to log animations. Click an animation and click block / unblock to block the selected animation.
TODO: Create a list of animations which are useful to block.