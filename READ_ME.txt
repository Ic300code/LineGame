The game is fully customizable. To customize it go to ReplicatedStorage>Modules>BackEnd and select Constants. Here you can modify things : 

- MaxBot : The maximum bot count, if you want 30 remove one (so it's 29)
- StartingCash : The starting cash amount for both players and bots
- CutlinesDelay : Delay between all bots start to skip
- CutlineChance :Determines the chance of a bot skipping a line
- CashWaitTime : Delay before both players and bots receive cash
- GivingMoneyMax : (keep the square root) The maximum amount of money players and bots can receive

To create tiles, you just need to place them in Workspace > Map > Lines.
You must also create them in a specific order:
- The first tile you create will be the end tile (the one where you win and restart).
- Then, continue placing them towards the starting point (where you will spawn).