# Traits of War Tutorial


 
<p align="center">
<img width="150" height="150" src="https://i.imgur.com/0sgNizi.png">


<p align="center">
This is a small tutorial for the discord bot "Traits of War", inspired by the old school browser game "Tribal Wars".
</p>

<p align="center">
For questions: Kiba#7956
</p>

## Goal

The goal of the game is to build up your village, recruit troops and raid other villages.

## Start

To start playing type the command <code>!play</code>. It will create a new village with 300 clay, 300 wood and 300 iron. It also comes with pre-built buildings that are required to play the game.

<img width="400" src="https://i.imgur.com/RXv7vRs.png">

## Resources

Theres 3 key resources in the game:
<p>-wood</p>
<p>-clay</p>
<p>-iron</p>

You automatically gain all 3 resources at all times. The higher your timber camp, claypit or iron mine level is the more resources you get. To see your resources type <code>!village</code>.

<img width="400" src="https://i.imgur.com/3PPxYZP.png">

Aside from these resources theres also the population which is calculated by your farm level. Upgrading Buildings and recruiting units for your troops will increase your total population. When your maximum population is reached you can no longer build or recruit units.

## Building

In order to build you first need to figure out what you wanna build. It is recommended to upgrade timber camp, claypit and ironmine a lot in the beginning to get more resources.

The command <code>!buildinfo</code> shows you all available upgrades and their cost.

<img width="400" src="https://i.imgur.com/FABBDVS.png">

With the command <code>!build building</code> you can upgrade a building. Once the upgrade started it will take some to complete. The build duration depends on the level of the building and your HQ level. If your HQ level is higher, you can build faster.

<img width="400" src="https://i.imgur.com/rdP3m3W.png">


### The Buildings

Use the command <code>!buildings</code> to see all buildings and what they do.

## Recruiting

Once you have unlocked and built barracks(Level 3 HQ requirement) you get access to your first unit the spear fighter. You can recruit units by typing <code>!recruit unitname amount</code>. Keep in mind each unit has a value for attack and defense. You can find out more about units with the command <code>!units</code>.

<img width="400" src="https://i.imgur.com/ux3wfJ1.png">

## Attacking

You can attack other players by mentioning or using their Disocrd-ID. Before you attack though, you need to select your units that you wanna use for your attack. once you start the attack it will calculate the duration for the attack based on the cordinates of both villages. Only the attack value of each unit matters for attacking.

<img width="400" src="https://i.imgur.com/TQBBVfm.png">

### Preparing the Attack

With the command <code>!rally</code> you can select troops that you wanna send to the attackcamp. Those troops will get used to in your next attack.

<img width="400" src="https://i.imgur.com/87FJjJk.png">

You can also attack NPC-Vilalges with <code>!attack barbarian</code>.

### Winning the Attack

If you win the attack your haul gets calcualted by the amount of troops that survived. Keep in mind that each unit has a different haul capacity. You can only loot as much as your enemy has resources.

### Losing the Attack

All attacking troops will die if you lose the attack.

## Defending

Your village has a basic defense that will will protect you from small attacks. Their are specific defense units that exceed at defense. Your combined troops defense value(not the ones that are in the attack camp currently) will result in your defense. These defenses then get boosted by roughly 4% per wall level(see your village overview). 100 defense will turn into 104 defense with a wall level 1 wall.

To move your troops from the attackcamp backt to the village in order to defend you can use <code>!defense</code>.

## Other Commands
To see other commands type <code>!help</code>.
