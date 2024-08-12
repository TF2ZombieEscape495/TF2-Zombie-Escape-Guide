---
description: Skial's Zombie Escape Mod Overview
cover: ../.gitbook/assets/Team_Fortress_2_Zombies.png
coverY: 156.11128553985702
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Mod Mechanics

### <mark style="color:blue;">Humans</mark>

* Have access to weapons modified from base-game TF2
* Different classes with unique playstyles, strengths, and weaknesses
  * HP and Speed are modified from base-game TF2
  * Many mechanics have been modified or disabled (e.g. ÜberCharge and explosive-jumping)

Round is won when the Human team has "escaped" the map, survived long enough, or completed all objectives. Round is lost when all humans become infected, die or they fail one of the map's conditions.

### <mark style="color:red;">Zombies</mark>

* Have tremendously increased HP
* Have a near-instant respawn
* Have access to weapons modified from base-game TF2
* Can _usually_ infect humans in one-shot
* Different classes with unique playstyles, strengths, and weaknesses
  * HP and Speed are modified from base-game TF2
  * Some mechanics have been modified
  * Have unique abilities called ~~**Mutations**~~** Enzymes**
* Round is _not_ lost when all zombies are dead

Round is won when all the humans have died. Round is _not_ lost when all zombies die unless during map-specific sections.

### Class Change

As a human, you can only change classes for a few seconds **before** the round starts. If the duration is too short or non-existent, **you may need to preemptively change classes before the end of the current round.** As a <mark style="color:red;">**zombie**</mark>, you will have to have either just joined, left **`Spectator`**, or died. To maneuver around this, you can set an [<mark style="color:purple;">**Advanced Setting**</mark>](#user-content-fn-1)[^1] in TF2 to force death on class change, allowing you to swap classes throughout the round. _This won't affect you as a <mark style="color:blue;">**human**</mark> thus preventing you from changing classes during the round._

### Round Start

* Everyone will start on the <mark style="color:blue;">**Human**</mark> team until the warmup timer ends.
* The auto-infect system will pick humans to become zombies until <mark style="color:yellow;">**15%**</mark> of the amount of players on the server are <mark style="color:red;">**Zombies.**</mark>
* _A <mark style="color:yellow;">**32**</mark> player server will have <mark style="color:yellow;">**\[27]**</mark>_ _<mark style="color:blue;">**Humans**</mark> and <mark style="color:yellow;">**\[5]**</mark>_ _<mark style="color:red;">**Zombies.**</mark>_
* _A <mark style="color:yellow;">**64**</mark> player server will have <mark style="color:yellow;">**\[51]**</mark>_ _<mark style="color:blue;">**Humans**</mark> and <mark style="color:yellow;">**\[10]**</mark>** **<mark style="color:red;">**Zombies**</mark>._
* **`Spectators`** will be placed at the front of the queue, meaning that the more recently you joined as <mark style="color:blue;">**BLU;**</mark> _or if you AFKed too long enough to be moved into spectator_; the more probability there is in being autobalanced.

{% hint style="info" %}
<mark style="color:yellow;">**Why am I Zombie Twice sometimes?**</mark> After being picked as a _**starting zombie**_**,** you will be placed at the back of the queue and will not have to worry about auto-infection for some time. <mark style="color:red;">**If**</mark> <mark style="color:red;">**you've late-joined into an ongoing round; you are very likely to be selected as starting zombie a**</mark><mark style="color:red;">** **</mark>_<mark style="color:red;">**second**</mark>_ _<mark style="color:red;">**time**</mark>_<mark style="color:red;">** **</mark><mark style="color:red;">**for the following round.**</mark>

_Check or bind the_ [_**ze\_queue**_](useful-commands.md) _command to know whether or not you'll be zombie next round._
{% endhint %}

### Round Timer

At the top of the screen during rounds, you'll notice a timer. When it reaches <mark style="color:yellow;">**zero**</mark>, the Human team will automatically lose. In most cases, it will be unreasonable to reach this since you would have to stall out at certain areas for an exceedingly long time. Some maps, however, have timers that may just _barely_ be enough to complete the stage.

### Map Votes

* A vote will be triggered for the next map at <mark style="color:yellow;">**6:00**</mark> on the **Map Timer** viewable on the Scoreboard _**(Not to be mistaken with the Round-Timer)**_&#x20;
* Players will be able to either extend the current map or vote for the next map among a selection that has been randomly selected or player-nominated.
* Humans losing <mark style="color:yellow;">**3**</mark> times in a row disables the map extension. It can be regained by Humans winning the round _after_ the 3rd loss in a row before the automatic vote has been triggered. Each map is typically limited to <mark style="color:yellow;">**2**</mark> extensions.
* If the team restarts a round before reaching <mark style="color:yellow;">**5:00**</mark> on the Map Timer, they will be able to play a round of the map before leaving.
* After a map has been played, it will be on cooldown. Players will not be able to nominate and play that map until enough other maps have been cycled through. _<mark style="color:yellow;">**(Currently 3 Map CD)**</mark>_
* Players may also force a map vote if enough people use the **RTV** command after <mark style="color:yellow;">**600 seconds (10 minutes)**</mark> of a map have passed; or through the usage of Skial Credits _(That method will always show a 'Don't Change' option to extend.)_

### Modes

<mark style="color:orange;">**Normal Difficulty**</mark> - _The standard way to play._

* As the standard difficulty, it's the **only** way _(new)_ map records/progress will count towards being completed. View [**Map Records**](../highlights/map-list-+map-records/) notes additional requirements.
* **-40% Map Damage Reduction at all times. (**_Less boss damage, trap damage, etc...Stackable with Battalions too.)_

\
<mark style="color:green;">**Casual Difficulty**</mark> - _A more relaxed take on the game mode, useful for learning or practicing a map:_

* Humans take less damage, _(**-70% Map Damage Reduction**; Stackable with Battalions.)_
* More damage is dealt to NPCs and bosses. _(Unverified.)_
* Zombies are slowed for much longer, _(**+1 second** to slow duration.)_
* Even individual _**pellets**_ will slow and push zombies from afar, granting _**solo-stalling capability almost exponentially.**_

_The server will automatically engage a vote for <mark style="color:green;">**Casual Difficulty**</mark> after <mark style="color:yellow;">**(2)**</mark> consecutive losses at the start of the following round; until a win is achieved._

## Sidenote

There _are_ other zombie-esque game modes available on TF2. Years ago, it was primarily <mark style="color:orange;">**Zombie Fortress**</mark>. Now, the zombie genre has branched out into <mark style="color:orange;">**Super Zombie Fortress**</mark><mark style="color:orange;">,</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**Zombie Escape**</mark><mark style="color:orange;">,</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**Zombie Riot**</mark>, and _a few others_, each having their own unique spin on things.&#x20;

Other servers do host ZE, such as Otaku.tf. Do note that while some of the things discussed here may be applicable to both, versions of ZE for Skial and Otaku vary _**significantly**_ in gameplay, map rotation, and the tools available for use on the server.

### Comparisons to other games

Those familiar with Zombie Escape on CS:S, CS:GO, and GMod may find many similarities between the three. While TF2 _does_ share a few elements, the mechanics of TF2 ZE make for a very different yet interesting experience when compared to them. There are different classes, movement is always fast-paced, and combat is a lot more close-range. You'll even notice that strategies for a map could differ drastically in contrast to what's usually done elsewhere. This all contributes to a different feel to the game mode that one may or may not find pretty exciting.

### Healing?

* Mostly to nudge away at the ignorant misconception of TF2 Healing mechanics nullifying the balance of a boss or map; <mark style="color:yellow;">**healing mechanics are commonly disabled by maps that are typically newer ports**</mark> _**(eg,**** **<mark style="color:yellow;">**Santassination, Mako V6, Djinn**</mark>**, etc...)**_
* _Some of the <mark style="color:yellow;">**older ports**</mark>_ _<mark style="color:red;">**or TF2-made maps**</mark> might be balanced around keeping healing on specifically and instead, bosses will do higher damage or still have their insta-kills to compensate enough. **(**<mark style="color:yellow;">**Uchiha, Offliner**</mark>**,**** **<mark style="color:red;">**Sandstone, Breezy**</mark>**, etc...)**_

### List Of Healing Options...

Although this could probably go into the weapon pages - I did want to make a list of ALL usable  healing methods for the maps that actually can make use of them, **as some boss arenas that do allow this might let you hit zombies for health too.**

_Color coded a bit here._\
<mark style="color:orange;">**Orange**</mark>** meaning that **<mark style="color:red;">**Zombie Interaction is required**</mark>** to make use of its healing.**\
<mark style="color:green;">**Green**</mark>** meaning that the weapon can provide healing at **<mark style="color:green;">**All Times**</mark> **where Zombies can't be hit.**

* <mark style="color:blue;">**Scout**</mark>
  * **Mad Milk**  <mark style="color:orange;">**(On Zombie Hit: Self**</mark>** + **<mark style="color:orange;">**Team Heal)**</mark>
  * **Pretty Boy's Pocket Pistol **<mark style="color:orange;">**(On Zombie Hit: Self Heal)**</mark>
  * **Candy Cane** <mark style="color:green;">**(WHEN HELD: Self Heal)**</mark>
* <mark style="color:blue;">**Soldier**</mark>
  * **Black Box** <mark style="color:orange;">**(On Zombie Hit: Self Heal)**</mark>
  * **Concherer** <mark style="color:orange;">**(On Zombie Hit: Self**</mark>** + **<mark style="color:orange;">**Team Heal)**</mark>
  * **Concherer **<mark style="color:green;">**(PASSIVE:**</mark> <mark style="color:green;">**Self Heal)**</mark>
* <mark style="color:blue;">**Pyro**</mark>
  * **Airblast/Mannmelter **<mark style="color:orange;">**(On Burning Teammate: Self Heal)**</mark>
  * **Powerjack **<mark style="color:orange;">**(On Zombie KILL: Self Heal)**</mark>
* <mark style="color:blue;">**Demoman**</mark>
  * <mark style="color:red;">**\[NO HEALING OPTIONS]**</mark>
* <mark style="color:blue;">**Heavy**</mark>
  * **All Sandviches **<mark style="color:green;">**(ON CONSUME: Self**</mark>** + **<mark style="color:green;">**Single Team Heal)**</mark>
  * **Warrior's Spirit** <mark style="color:green;">**(WHEN HELD: Self Heal)**</mark>
* <mark style="color:blue;">**Engineer**</mark>
  * **Dispensers **<mark style="color:green;">**(Self**</mark> **+** <mark style="color:green;">**Team Heal)**</mark>** - **<mark style="color:red;">**\[**</mark>_<mark style="color:red;">**requires compatible map geometry]**</mark>_
* <mark style="color:blue;">**Medic**</mark>
  * **Medic Class** <mark style="color:green;">**(PASSIVE: Self Heal)**</mark>
  * **Blutsauger **<mark style="color:orange;">**(On Zombie Hit: Self**</mark>** + **<mark style="color:orange;">**Team Heal)**</mark>
  * **All Mediguns** <mark style="color:green;">**(On Beam: Single Team Heal)**</mark>
  * **Amputator** <mark style="color:green;">**(MOSTLY BUGGED: Team Heal)**</mark>
* <mark style="color:blue;">**Sniper**</mark>
  * **Cozy Camper** <mark style="color:green;">**(PASSIVE: Self Heal)**</mark>
* <mark style="color:blue;">**Spy**</mark>
  * **Kunai** <mark style="color:orange;">**(On Zombie Backstab: Self Heal)**</mark>
  * **Red Tape Recorder** <mark style="color:green;">**(WHEN HELD: Self Heal)**</mark>

[^1]: **Options > Multiplayer > Advanced >Ensure** `Suicide after choosing a player class` **is** **checked.**



    ![](<../.gitbook/assets/Capture (6).PNG>)



