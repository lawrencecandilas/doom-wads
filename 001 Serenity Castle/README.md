# serenity-castle
 Serenity Castle DooM WAD (for GZDoom and compatible)
 Version Two.  Originally released in 2020.

![Title Image](https://github.com/lawrencecandilas/doom-wads/blob/main/001%20Serenity%20Castle/Assets/v2/SCV2TIT1.png?raw=true)

The original release of this WAD was in 2020.  

## Version Two Update

Welp, it's 4 years later.  I've made more WADs since then, and have learned some things:

 - Too many monsters make things tedious.
 - This level is too damn big.

Now honestly, it is too big.  It could easily be 3 or 4 separate WADs.  But, I still like the design of it.  Some "quality of life" improvements have been done to make it funner and I did some floor detail.  I am hoping the player is not as tired once exiting the castle's "front door."

This WAD took me 45 minutes to complete during testing.  For someone new to the WAD, I would expect at least 1 hour and 30 minutes of solid gameplay.

### Quality of life improvements:

GENERAL:

- I did a full sweep through the WAD and removed many monsters where I felt they were just too much and made the game too tedious.  Especially once you are outside the castle after running through it (the "front" of the castle).

- I did not remove monsters in what I call the "choke points" - a few spaces where a bunch attack you at once.  I did try to establish a better rhythm of "ambush--relax--ambush--relax" instead of just a constantly increasing stream of monsters.

- Additional ammo has been provided in spots where I was running low (and annoyed) during additional testing.

- A few secrets have been added.

- A useless super-secret has been added.

OUTSIDE:

Outside - General:

- There are now 3 teleport circles.  They will teleport you to other places outside and are not necessary to finish the level.  Two are accessible before you go into the castle, and one when you exit the castle.

- The ridge with the BFG9000 has been made super obvious (turned red and in a 255-brightness sector).  After you go through the castle you may be tired so I decided to not torture the player here.

Outside - North Rocky Path:

- The north rocky path, after you get through the big "baron of knight" gate, now has:

  - nukage
 
  - interesting colors

  - some monsters removed,
 
  - barrels placed near enemies,
 
  - cell packs everywhere.  

 ... so you can blast through it.  You still need to be careful, but it's less tedious and much more fun.

CASTLE INTERIOR:

Castle Interior - Northwest Dark Room

- Barrels have been added.  Snipers in here should bother you less.

- A window has been added.

Castle Interior - Southwest Blue Key Room:

- Made the blue key brighter and it more visible from the window.

Castle Interior - Southeast Electrical Room:

- A teleporter has been installed in the "electrical room."  This will take you close to the blue key after you hopefully press the switch to lower its platform (which is also in that "electrical room" - nowhere near the key, lol)

Castle Interior - Big Central Arena.

- Another teleporter has been installed in the big arena in the center of the castle, and will open once you cross a line that leads to the "electrical room."  This teleporter takes you to a high ledge right outside said room.

  - So, if you forget to press the switch lowering the blue key platform, you can get right back to the electrical room and press it.

  - Less tedious and less searching for the blue key and/or how to get it, hopefully.

- Barrels have been added in the surrounding mezzanine and in front of the big door back into the castle.  This makes it less tedious (and honestly fun, yet challenging) to deal with the flood of monsters that teleport there.

- Trigger lines have been added to make sure two holding pens release their monsters when you are on your way to get the blue key - whether you get there by the teleporter, the door from the big main room, or even if you try to go back through the gate above the big fiery pit.

OUTBUILDINGS:

Outbuilding - Northern Guard Hall Across The Big Fiery Pit

- The interior is brighter and a big light has been added making the switch inside more obvious and easier to find.
  
- Added some radiation suits.

### Bug fixes:

Anywhere:

- The brightness of the entire map has been bumped up 32 points, except for some spaces that are supposed to be near pitch-black.

- Many texture misalignments were fixed.

Outside Lake (South):

- It was possible to jump around the rocky barrier and cross over to the eastern side of the map, skipping the castle entirely.  The mountains have been rearranged to where this is not possible anymore.

Big Central Arena:

- There was a section of fence in the middle arena that the player could walk through.  This is fixed.

- Additional triggers have been added to make sure the monsters teleport into the mezzanine areas no matter how you get near the western door of the arena.

Eastern Front Parlor (Contains Stairs To Arena):

- Not sure the door in the northeast guard hall (with an invulnerability sphere) ever worked.  It's a normal door now.

Northern Blood Pit Room:

- The emergency switch in the "blood pit" room, used to escape if you fall in before the bridge is there, is now an SR instead of an S1.  So you cannot be permanently trapped there anymore.

- The switch in the "blood pit" room was able to be triggered without being on the "bridge" (summoned by another switch) up from the pit.  This was fixed by moving the switch back into the wall and making the surrounding wall come forward.  You can't cheat here anymore.

- It was also possible to jump to the switch there.  Safety pylons and a fence have been added to prevent accidental or intentional slippage into the pit.

Classic Rendering:

It is not recommended you play with Software Rendering as this map depends on verticality and Software Rendering is a little weird there, but some issues with Software Rendering were fixed anyway:

- The fence in the room with the first Soul Sphere (secret area before reaching the big "Front Room" with all the rugs) had lower unpegged enabled and was visible through the floor.  The fence has been moved upward and given a pole on the right side to attach to.

- HOM was observed outside when looking at the mountains from far distances.  This was remedied by encasing the whole map in a thin border of sectors with floor height 0 and ceiling height 8, making sure F_SKY1 is plotted everywhere it should be.  If you enable flying and fly up to the top of the mountains you will see rendering issues but you shouldn't be able to get there without cheating.

## Requirements

This WAD initially was developed on an old PC (AMD Athlon dual-core with 6GB of RAM), using GZDoom 1.8.1, Brutal Doom v19, and Doom Builder 2, with SLADE to assemble assets.  The WAD ran slowly on this system, and got unplayable in parts.  

Later development was done with DBX2019.1 on a newer system - my current HP laptop (from Wal-Mart) with a quad-core Intel CPU, 8GB of RAM and Intel integrated graphics.  The WAD runs decently on this system but does drop to 20fps in places.  Really though any system manufactured in the last 10 years or so should run this fine.

It does seem some combination of DBX2019.1, Brutal Doom v21 and GZDoom 1.8.1 causes an error about unrecognized NOAUTOMAP tags at startup.  This does not happen with Brutal Doom v21 and GZDoom 4.5.0, so please use GZDoom 4.5.0 or higher.

### Brutal Doom v21 Recommended  

Serenity Castle was designed with Brutal Doom in mind--the lighting definitely enhances the experience throughout the dark Serenity Castle, but it is playable without it.

### Freelook Recommended, Jumping/Crouching Optioal

You will want to enable freelook because verticality is definitely a factor in this map.  You can enable/use jumping/crouching if you want but it will not help you very much.


## Hints

- You will need ALL THE AMMO you can get your hands on.

- Look behind boxes.

- There are no Cyberdemons, Archviles, Spider Masterminds, or actual serenity in this WAD.

- If you get overwhelmed with monsters at certain points, keep moving and come back later to kill everything if you're trying to get 100% kills.  I can't get 100% kills so it may not be possible and I need to fix that.

- Explore the mountains for soul spheres. 

- Walking over pools of water in the castle opens doors or lowers platforms.

- You'll visit the big central "arena" twice.  You'll have a second opportunity to kill all the monsters there.

- Watch out for crushers.  There is one and it may surprise you.

- The Baron of Hell block, if touched, will lower a platform, and you'll find it useful.

- After you exit the castle, head to the right towards the lake to get the BFG.  You don't want to pass it up.

- The switch that opens the big "Baron of Hell" door is in an outbuilding near the pit.  Follow the health bonuses.

## License and Copyright

WAD and music are copyright 2020, 2024 Lawrence Candilas

WAD and music are released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license.

- [Human-readable summary of (and not a substitute for) the license](https://creativecommons.org/licenses/by-nc-sa/4.0/)

- [License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

Links to and PDF copies of the above documents in the "License" folder of this distribution.

DOOM is a registered trademark of Id Software, Inc.
