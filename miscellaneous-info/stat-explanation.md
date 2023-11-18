---
description: Information about various mechanics and TF2 weapon stats.
cover: ../.gitbook/assets/maxresdefault (1).jpg
coverY: 363
---

# Stat Explanation

Special thanks to **Tranquility** for compiling much of the mechanics and weapon stat information.\
\
These weapon stat changes can be observed in-game with the <mark style="color:yellow;">**Inspect Target**</mark> or Item function `(default key is`` `**`F`**`)` while in Skial ZE servers.

* Other changes are collected from [**TF2 Wiki**](https://wiki.teamfortress.com/wiki/Main\_Page) or in-game observations.
* Final stats are calculated from each weapon's base TF2 stats in the TF2 Official Wiki
* As such, treat the DPS calculations as _approximations_ at best; the weapon stats from TF2 Wiki may be inaccurate.\


<mark style="color:yellow;">**Notes**</mark> about calculating new stats from weapon base stats:

* Stat increases (like slower \[more] reload time, clip size, etc.) are _additive_
* Stat decreases (like faster \[less] reload time, damage penalty, etc.) are _multiplicative_
* &#x20;Increased firing speed scales exponentially (e.g. +90% firing speed shoots twice as fast as +80% firing speed)
* Same with decreasing reload time (e.g. +75% faster reload is twice as fast as +50% faster reload)

\
<mark style="color:yellow;">**Attack Interval**</mark> = ceil(Old Attack Interval \* (1 - Inc. firing speed %) / 0.015) \* 0.015\
\* Additional steps are taken to account for TF2's tick rate rounding. View the [**TF2 Systems**](tf2-systems.md) section for more information.\
\
<mark style="color:yellow;">**Clip DPS**</mark> (_or <mark style="color:yellow;">**Burst DPS**</mark>_<mark style="color:yellow;">**)**</mark>: DPS assuming infinite clip size.\
\* Clip DPS = Base Damage / Attack Interval\
\
<mark style="color:yellow;">**Time to Empty Clip**</mark> (<mark style="color:yellow;">**TEC**</mark>): The maximum duration a weapon can fire before reaching 0 clip size\
\* TEC = Clip Size \* Attack Interval\
\
<mark style="color:yellow;">**Full Reload Time:**</mark> Time to reload from an empty clip back to a full clip.\
\* Full Reload Time = Reload Time (F) + Reload Time (C) \* (Clip Size - 1)

* Reload Time (F) -> Time to reload the first shot
* Reload Time (C) -> Time to reload consecutive shots
* Where New Reload Times = Old Reload Times \* (1 - Faster RT %)

<mark style="color:yellow;">**Real DPS**</mark> (or Sustained DPS): DPS over time, taking clip size and reload time to consideration.\
\* Real DPS = Clip DPS \* \[TEC / (TEC + Full Reload Time)]\
\* Is the optimal DPS; actual in-game DPS may be lower due to accuracy, human reaction times, or other factors.\
\
Base damage does <mark style="color:red;">**not**</mark> account for damage fall-off/ramp-up\
(which do not affect breakable objects, including NPCs and bosses).
