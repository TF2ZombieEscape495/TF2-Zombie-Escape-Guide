---
description: >-
  A place to quickly find gamemode to Skial ZE changes by date of known changes.
  Note that some changes under the radar might happen, so the page might
  stagnate sometimes.
---

# Gamemode Changes 12/24/2025

## 2025&#x20;

### 12/24/2025 - Bhop Adjustment

Bhop timing made more strict - you can't auto-hop by spacebar spamming it now, you'll have to time it now for consistency.

### 7/31/2025 Leader Rework

_<mark style="color:$danger;">(these weren't done today, just recap of recent stuff)</mark>_

Leaders can now put custom text, color, and duration for their markers. (See [_Leading)_](../general-overview/leading.md)

Markers can also be placed on any entity to highlight it a specific color - like a trigger door, zombie flank door, trap, or boss.

Co-leaders (mini leaders) can be assigned by primary Leader via /addleader (up to 3)

### 7/11/2025 - Pandemic Mode addition

* **New modifier-based difficulty added; you can vote for it after the end of a map vote to apply some 'kickers' to the next map (non-leader only) entirely.**&#x20;
* <mark style="color:yellow;">**At the start of the round 2 kickers are chosen randomly out of this list - these will change randomly between every round reset:**</mark>
  * **Low Gravity**
  * **All mobility enabled&#x20;**_**(Rocket jumping, demo jumping, etc.)**_
  * **Faster Enzymes**
  * **1 Touch Infect**
  * **Tiny Zombies**
  * **Low Friction**
  * **Faster Zombies**
  * **Exploding Zombies**
  * **Faster Bunny Hopping**
* <mark style="color:red;">**There is a small chance that ALL of the above can be applied to a round simultaneously.**</mark>

### 7/10/2025 - Leader System Tweak

* Global whistle sound on leader marker placement
* (ADMIN ONLY) Admin can make another player co-leader

### 6/30/2025 KB + Scorch Shot Adjust

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

### 6/25/2025 Legacy Anti-Boosting code re-added

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

### 6/25/2025 Leader Map CD

* 2 Map Shared Cooldown added for all leader maps - you must play 2 normal maps in-between each leader map.

### ~~6/20/2025 - /vl Requirement Bump~~

* ~~**/vl now needs 7****&#x20;**_**(formerly 5)**_**&#x20;****Human players to vote a leader in.**~~
* **reverted**

### 5/20/2025 Hide Adjustment

* Auto Hide Team implemented (this hides people VERY close to you; within 100 units, basically have to be standing on you or next to you)
  * Is always on regardless of **hideteam** command being toggled.
  * hides **item users and leader too** _(does not hide the item itself if it has an icon/model)_

### 1/22/2025 Weapon KB Fixes

* universal weapon grouping knockback adjustments
  * this should 'fix' knockback across the board that was intended to be higher for specific weapon groups eg, Pistols, Rockets, Miniguns - _(this is not a revert to old KB._)
  * **many weapons almost have no damage fall-off** _(this doesn't make weapons kb from 500 miles, instead just brings more consistency, Widowmaker can take advantage of this much better by not needing pointblank range to get more bullet refunds, Soldier rockets still need close range to build banners, etc)_
  * _possibly might write out a more detailed explanation on this later depending on how much impact this has, adjustments are still ongoing though_
* [<mark style="color:green;">**Casual Mode**</mark>](../general-overview/mod-mechanics.md#modes) now disables friction - _tl;dr_ allowing zombies to get knocked back more, makes switching between difficulties more impactful than a simple slowdown.

### 1/20/2025 minor qol

* screen shake effect upon taking damage removed _(you'll still see the red indicators of damage)_
* machina penetration kill sound blocked

### 1/17/2025 Minigun Inf Ammo + Sentry Slow

* [**Heavy minigun 'reload' mechanics**](balance-changes-11-18-2023.md#id-12-18-2024-weapon-tweaks) **reverted** - they now have infinite ammo again and no dispenser penalty. _(minus Huo Long which intentionally had it)_
  * pending further tweaks to give additional knockback as currently miniguns are weakened defending-wise
* Sentry snare mechanic re-added _(as sentries apply slowdown on hit,&#x20;_~~_this was turned back on way earlier but forgot to mention it was re-enabled_~~_)_

### 1/12/2025 !zload, soldier enzyme rework, !noshake

{% hint style="info" %}
<mark style="color:yellow;">**!zload**</mark> mechanics!! _(eventually this might get its own page for every specific)_

tl;dr this is your weapon buy system integrated into TF2 ZE and will mitigate you being stuck on a 'bad' loadout, & being able to switch playstyle depending on weapon.

* EX: <mark style="color:yellow;">**!zload Liberty**</mark> _(to play defensive Soldier)_ -> <mark style="color:yellow;">**!zload Mangler**</mark> _(to play as banner/boss support Soldier)_
* EX 2: <mark style="color:yellow;">**!zload Baby**</mark> _(to play trigger Scout_ _or grab an item) -_> <mark style="color:yellow;">**!zload Scattergun**</mark> _(to switch to general use defense/boss support)_
* <mark style="color:red;">**You have a limited use of 3 !zload usages in a round.**</mark>
*

    <figure><img src="../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>
{% endhint %}

* <mark style="color:yellow;">**!bhop**</mark> made opt-in **and now is off by default for everyone** unless they !bhop or sm\_bhop bind
* <mark style="color:yellow;">**!noshake**</mark> command added - **this will disable screen-shaking mechanics** on maps like Best Korea, Cosmo Canyon, etc...
  * _(added all the new commands to_ [_**Useful Commands**_](../general-overview/useful-commands.md)_)_
* <mark style="color:yellow;">**Zombie Soldier Enzyme**</mark> now instead shrinks the user _(and kills them if on any odd geometry)_

## 2024...

### 12/26/2024 Round-end Stats, Return of PKP, Leader-noms...

<div align="left"><figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure></div>

* New scoreboard tracking _(displayed at round end)_ for top infections and damage.
* **Addtional adjustment to Heavy Miniguns&#x20;**_**(they now reload in the background so you're not stuck at 0 ammo)**_
* Several existing maps made <mark style="color:purple;">**leader-only:**</mark>
  * **Dodge Or Die**
  * **Sandstone**
  * **Parkour Paradise&#x20;**_**(yes its back)**_
  * **Raiin**
  * **Night Cinema**
* **DOOM** leader-requirement removed
* **Surf Sahok** removed from nominations

### 12/19/2024 - Class Cap + KB Adjust

* Class cap for heavy has been removed.
* Class cap for engineer has been removed.
* **Additional adjustments to knockback on non-heavy weapons adjusted/fixed to compensate heavy being weakened.**&#x20;
  * **Sniper headshot sources now launch zombies away rather than stunning, giving him a different niche than sharing a cooldown with Demoman stun mechanics.**
  * **Melee Knockback to Zombies has also been increased.**
  * Higher firerate, pinpoint weapons _(pistol, SMG, family business etc)_ are more likely to knockback individual zombies upon hitting their shots consistently without spreading too much.

### 12/18/2024 - Weapon tweaks

{% hint style="info" %}
_(NOT FINAL; SUBJECT TO ADDITIONAL CHANGES)_ _**This doesn't mechanically change weapon gimmicks across the board**_ - instead just makes most sources of bullet damage/knockback rely less on heavies. _(A lot of weapon DAMAGE stats changed specifically.)_
{% endhint %}

* Miniguns now have a **4 second reload time** _**(they need to be un-revved to reload; no animation but you'll reset to 140 ammo)**_
  * Miniguns now have a 15 second uptime&#x20;
  * To reload, press your R key _(this should visually show on HUD)_
  * **Miniguns also all have a No Ammo From Dispensers When Active** trait to lean towards use of reload mechanic.
* **Many weapon damage stat**s **increased by 25-50%** across the board _(varies, <mark style="color:red;">**currently have not re-calculated the exact stats for many of these; this will make a lot of the DPS calculations off**</mark>_ _<mark style="color:red;">**on the stat pages**</mark> depending on the scope of changes done - giving this time to settle before comprehensively writing down every adjusted weapon stat.)_

### 12/16/2024 - Crouching + Jump

* **More bhop adjustments/fixes&#x20;**_**(may not be final)**_
* _Normally_ in TF2, you can't hold crouch _and then_ jump _(not to be mistaken with jumping and tapping crouching for more height)_
* **As of now on ZE servers, you can now 'crouch-jump' without having to sit through an awkward un-crouch animation.**

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### 12/9/2024 - Bhopping Update

* **Bhopping mechanics enabled on both Zombie Escape servers&#x20;**_**(capped to 500 at max, momentum should also be capped at stairs and ramps)**_
* **Bhopping momentum halted upon being shot/can't boost yourself by getting shot in specific ways.**
* **Bhopping velocity limited to 250 upon using Zombie Enzymes.**

### **11/26/2024 - General**

* **Map RTV Cooldown reduced back to global 3 map cooldown**
* **Adjustments made to sources of zombie boosting&#x20;**_**(this will probably throw off a lot of mention of boosting mechanics throughout the whole guide depending on whether or not it's adjusted any further)**_

### **11/6/2024 - Leader Nominations**

* **Specific maps can now&#x20;**_**only**_**&#x20;be nominated by an in-game** [**leader**](../general-overview/leading.md) **but are guaranteed to show on nom-list if it's a leader-map (A-Z)**
* **Nomination-stacking a map also now prioritizes whichever maps have the highest nom-counts into showing up on the RTV screen - but there is now a cap of 3 possible maps max (and 4 maps if leader nomination is there)**

{% hint style="info" %}
_<mark style="color:yellow;">**Note:**</mark>_ **You can view what Leader maps are tagged as&#x20;**<mark style="color:purple;">**(LEADER)**</mark>**&#x20;@** [**Map List**](map-list-+map-records.md) **or can view them in-game at the end of the nomination list.**
{% endhint %}

### **10/24/2024 - Maps re-added + Map CD Increase**

* [16 Maps Re-Added ](recent-maps-11-13-2023/#id-10-24-2024-16-maps-re-added)
* ~~Map CD increased to **20 map cooldown**~~
* **Map RTV timer lowered to 30 seconds (no longer have to wait 10 minutes to RTV on a map)**

### **9/21/2024 - Normal Mode Change**

* ~~_**(Unknown specific date)**_~~**&#x20;Universal 40% map damage reduction reverted/removed on** [<mark style="color:orange;">**Normal Mode.**</mark>](../general-overview/mod-mechanics.md#modes)
* &#x20;_tl;dr a lot of intended 1-shot mechanics like map traps/zombie items were 'broken' prior to this, and could just be tanked/or healed off without punishment; but should work again now. As a result, many maps will feel 'harder' again as you'll be taking lots more damage generally._

### **9/14/2024 - Leader Changes**

* **Leader functionality (markers and leadermenu) will be disabled upon Leader's death - they will still retain the role and can !transferleader to another player or hold it until next round.**
* _**(Admin only/event only?)**_**&#x20;Leader vip mode toggle added to leader options (round will instantly end on leader death)**

### 8/24/2024 - 23 maps purged

putting it on the forefront _outside a subpage_ since <mark style="color:red;">**>23 maps were removed**</mark> and [legacy maps](recent-maps-11-13-2023/legacy-maps.md) is a bit far too messy messy to find a way to organize into it.

_(A-Z)_

1. ze\_aooka
2. ze\_aot\_trost
3. ze\_atix\_apocalypse
4. ze\_atix\_panic
5. ze\_bowser\_in\_the\_fire\_sea
6. ze\_ffxii\_westersand
7. ze\_ffxiv\_wanderers\_palace
8. ze\_lotr\_helms\_deep
9. ze\_lotr\_mines\_of\_moria
10. ze\_obj\_filth
11. ze\_oot\_shadowtemple
12. ze\_persona
13. ze\_predator\_ultimate
14. ze\_raiin
15. ze\_rooftop\_runaway2
16. ze\_saw
17. ze\_sorrento\_escape
18. ze\_subway\_escape
19. ze\_space\_station
20. ze\_swamp\_facility
21. ze\_tesv\_skyrim
22. ze\_timesplitters
23. ze\_warlab

### 8/7/2024 _Comma > 3 Warriors, Rest Now.._.

* ZM Pyro enzyme explosion fixes: Changed from dmg\_blast > dmg\_burn, removed damage multiplier
* _tl;dr no longer singlehandedly nuking entire teams at mid-range/point-blank (must be alive up to 5 seconds **post-use** to charge full blast radius and damage.)_

### 7/21/2024 Casual Mode Adjustment

* Casual Mode Zombie melee damage reduction removed.

### 2/17/2024 Noob Mode Adjustments

* **Noob Mode renamed to Casual difficulty.**
* **Map Damage Reduction Universally changed to 40% on Normal Mode, additive with Casual Mode (70% total)**
* **Overall Zombie Slowdown via being shot on Normal reduced&#x20;**_**(exact value currently unknown)**_

### 2/07/2024 Balance Change

* **\~Maps that disable Healing (on bosses etc) no longer completely disable Enzyme mechanics simutaneously.**

## 2023...

### 11/18/2023 Balance Change

<mark style="color:yellow;">**\~Human Demomen now have 200 HP with sticky/scottish/quickie equipped, still 175 if using a shield or jumper!**</mark>**&#x20;(This generally brings them up to par on NPCs/bosses with being able to take the same amount of hits as most other people.)**

### 11/7/2023 Enzyme Change

#### <mark style="color:red;">Zombie Engineer</mark>

* #### _(-Unknown actual date of when this was implemented, likely snuck in during ZI/Halloween)_ <mark style="color:yellow;">Zombie Engineer's Enzyme can now EMP sentries to stop them from firing for a few seconds \[at a moderate range] and still can stun a single Human within melee range.</mark>

### 10/14/2023 Enzyme Change&#x20;

#### <mark style="color:red;">Zombie Medic</mark>

* <mark style="color:yellow;">**Enzyme damage reduced by 50%**</mark>**&#x20;(averages to about \~20 raw damage on successful hit.)**

### 9/24/2023 Balance & Enzyme Change

<mark style="color:yellow;">**-Enzyme**</mark><mark style="color:yellow;">**&#x20;**</mark>_<mark style="color:yellow;">**only increases**</mark>_<mark style="color:yellow;">**&#x20;**</mark><mark style="color:yellow;">**upon taking damage and decays after a while;**</mark>**&#x20;**<mark style="color:orange;">**(Enzyme count decays after \[30] seconds)**</mark> **(In other words; you can't indefinitely hold onto an enzyme activate them en masse after being jailed a long time.)**

<mark style="color:yellow;">**-Correlating with the above; Enzyme on being hit increased by around \[6-8?] per damage tick**</mark>**&#x20;(Build enzyme much faster against damage.)**

<mark style="color:yellow;">**-Human melees no longer do increased damage and instead will do a sizeable knockback.**</mark>**&#x20;(Still damages heavy enzymes greatly.)**

### 7/28/2023 Enzyme Changes

#### <mark style="color:red;">Zombie Medic</mark>

<mark style="color:yellow;">**-Given a**</mark> [_**new ability**_](../human-zombie-guides-stats-here/meet-the-zombies/zombie-medic.md) <mark style="color:yellow;">**that allows the Zombie Medic to do an instant 30-60 damage to Humans in an AoE on activation; damage depending on range (and weapon interaction.) Does not infect upon kill as it deals crit damage.**</mark> (_**Prior enzyme was functionally broken.**_)

### 5/12/2023 Enzyme Changes

#### <mark style="color:red;">Zombie Scout</mark>

<mark style="color:yellow;">**-Only visually changed, grants the Zombie Scout a conch-like banner effect underneath themself.**</mark> _**(No longer gives speed line particles.)**_

#### <mark style="color:red;">Zombie</mark> <mark style="color:red;">Soldier</mark>

<mark style="color:yellow;">**-Grants Zombie Soldiers a mini-crit buff to melee for \[8] seconds.**</mark> _**(No longer creates smoke clouds on use.)**_

#### <mark style="color:red;">Zombie Pyro</mark>

<mark style="color:yellow;">**-Zombie Pyros now gain a giant bomb head upon enzyme, does immense damage at close range; has a wind-up AoE explosion that launches zombies forwards if not shot before it times out.**</mark>**&#x20;**_**(No longer has the flame particles around him visually.)**_

#### <mark style="color:red;">Zombie Demoman</mark>

<mark style="color:yellow;">**-Refills charge meter to \~roughly \[95%] on use, allowing Zombie Demomen to do another follow-up charge. Does nothing if charge meter already full.**</mark> _**(Gives demoman an enzyme to begin with.)**_



