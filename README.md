# Ultra-Violence Mod

For all the Descent players out there:  This repository contains a source code fork of DXX-Rebirth with TheMarkitecht's Ultra-Violence modification.

This mod adjusts game balance to make the player's ship much tougher and more powerful.  The effect is to enable an average player to play aggressively, even on the higher skill settings.  Then he can see all the mines, in all their glory, the way their designers intended, minus the many, many player deaths, and flying all the way down to collect your stuff again, and the tedious repeated peek-a-boo's required to kill the many, many tough robots.  The original design becomes even more tedious when the extreme difficulty of the mines forces you to play on "Rookie" skill, because then you have to wait so long for the robot's shots to clear out of your way.  The game flows better and is much more exciting on the higher skill settings, and this mod makes those accessible to more players.

List of changes:

* Player shields are **much tougher** - all damage is only 20% of stock!
* Raised initial shields and energy to 200.  That is also the level you can recharge to in the orange "fuel center" areas.
* Raised max shields and energy to 999.  But you are unlikely to ever see that level without cheating.  That would take a LOT of shield orbs!
* Raised initial life count to 99, so nobody's game ends before they're ready to quit.
* Raised cloak and invulnerability duration to 90 sec.
* Fusion cannon is worth using!
    * Fusion cannon does twice as much damage.
    * Fusion cannon charging up bumps the player around less - only 12% of stock.  So it's easier to aim now.
    * Fusion cannon overcharging damages the player less - about 25% of stock.
    * Fusion cannon charging no longer alerts robots while player is cloaked.  This makes it one of the best weapons to use while cloaked.
* Mega Missile does double damage and double blast radius now.
    * Note: The minimum safe distance from the detonation is about 4 seconds worth of straight-line flight of the player's ship.
    * Note: Blast is powerful enough to destroy a fresh red hulk nearby, or every scout anywhere in a medium sized room.  Often it will not, however, destroy the reactor with one shot in the later mines.
* Increased max ammo storage for all types of missiles to 255.  These are carried into the next mine, but as usual only the first 10 to 20 are ejected by a dying player ship.  The rest are lost.
* Increased max ammo storage for vulcan.  The max is at least 100,000 rounds; I'm not sure exactly.  Note that the ammo display rolls over at 65,536, starting again at zero, but none are lost; all are still usable then.  All are carried into the next mine, but as usual only the first few are ejected by a dying player ship.  The rest are lost.
* Flares last longer.

I know what you're thinking:  "With all that help, it's gonna be a cakewalk.  Boring."  NOPE!  Guess again.  You still have to stay on your toes or they'll lay the smack down!  The mines are just that brutal!

This mod is focused on Descent and its original mission.  I have not tested it in Descent 2 at all.  It's probably playable in D2.  It does at least build D2 from the source code if you want to try it.  The same disclaimer too for multiplayer.  This is only tested in single player.

Speaking of testing, I have played this mod for several days with no crashes or other unusual problems.

Have fun, and remember:  Be aggressive;  BE-E AGGRESSIVE!  :-)

\- TheMarkitecht



---
Below is the README from the upstream repository: https://github.com/dxx-rebirth/dxx-rebirth
---


```
                         __________
__________/ DXX-Rebirth /
```

https://www.dxx-rebirth.com


## 0. Introduction:

DXX-Rebirth is based on the late D1X and D2X source ports (which, in turn, were based on the original Descent source and LDescent). The Rebirth Team has spent a lot of time working to improve the source code by fixing old bugs and adding some improvements, while always staying true to our philosophy: Keep it Descent!

It is the goal of DXX-Rebirth to keep Descent 1 & 2 alive and well, updating them for modern PCs while also keeping them the same games you remember playing back in 1995!

If you have any questions, comments, or suggestions, contact zico [at] dxx-rebirth [dot] com, or come to our forum: https://forum.dxx-rebirth.com/

> Now Material Defender...Prepare for Descent!

## 1. Features:

DXX-Rebirth has every little feature you may remember from the original Descent 1&2 and much more.

For example:

* Full compatibility with Descent and Descent 2, including all expansions and third-party levels.
* DXX-Rebirth runs on your favourite Operating System. We officially support Linux (and other \*NIXs), Mac OS X and Windows. The source code can also be compiled on many other systems!
* OpenGL provides fast and smooth rendering - even on low-end systems.
* Optionally you can enable several effects like Transparency, Colored Lighting, Texture Filtering, FSAA, etc.
* Thanks to SDL, a wide variety of Joysticks are supported. Also you can use more Joysticks, buttons and axes than you can ever operate in your state of evolution.
* Joystick, Keyboard and Mouse can be used simultaneously.
* The games can display all resolutions and aspects supported by your monitor, including an option for VSync.
* Besides MIDI and CD-Audio (Redbook), you can play your own custom Music from your hard drive or a separate AddOn.
* Both games can utilize special AddOn packs to replace or expand the original game content.
* Multiplayer via UDP protocol provides a fast and easy-to-use LAN and Online action. This includes reliable communication causing less glitches due to lost packets.
* The ingame Demo-recording system has been improved. Demos are less glitchy and smaller while still still being backwards-compatible to earlier versions of the games.
* Higher game speed will not cause glitches such as unacceptable fast homing projectiles, incredible high damage caused by several collisions or Fusion cannon, etc.
* Player files, Savegames, Demos and Missions from DOS-Versions of the games can freely be used in DXX-Rebirth and vice versa.
* Mac Command keys are now working - see F1 Help. Command-Q works much like a normal Mac program
* Even more ...


## 2. Installation:

See [INSTALL.markdown](INSTALL.markdown).


## 3. Multiplayer:

DXX-Rebirth supports Multiplayer over UDP/IP.Using UDP/IP works over LAN and Internet. 

By default, each game communicates over UDP-Port 42424. This can be changed via the menus, command-line argument or .ini files. 

Please be aware that if you host a game and players want to join your game online via direct IP connection, your specified game port should be forwarded on your router. 

If you host your game on the Online Tracker and other players join via this method, port forwarding should not be necessary.

If you only want to join a game, or host a game on LAN (not online), port forwarding should not be necessary. If you do experience problems, please check your NAT settings and/or Firewall.


## 4. Legal stuff:

See [COPYING.txt](COPYING.txt) and [GPL-3.txt](GPL-3.txt)


## 5. Contact:

- https://www.dxx-rebirth.com/
- [Forum](https://forum.dxx-rebirth.com/)
- zico [at] dxx-rebirth [dot] com
   
## 6. Issue Reporting

Use GitHub issues tab report a [new issue](https://github.com/dxx-rebirth/dxx-rebirth/issues/new), be sure to add as much detail as possible in the template provided.
