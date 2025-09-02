---
description: Breakdowns of what a Leader does.
---

# Leading

## The Leader Plugin

{% hint style="info" %}
#### Skial's Zombie Escape server offers a leader plugin in the form of...

#### <mark style="color:yellow;">**`/vl [Player Name] for Primary Leader`**</mark>&#x20;

#### <mark style="color:yellow;">**`/addleader [Player Name] for Mini Leaders`**</mark><mark style="color:yellow;">**` `**</mark>_<mark style="color:yellow;">**`via`**</mark>_<mark style="color:yellow;">**` `**</mark><mark style="color:yellow;">**`Primary Leader.`**</mark>

#### <mark style="color:yellow;">**`/setleader [Player Name] to transfer Primary Leader`**</mark>

#### <mark style="color:yellow;">**`/quitleader to remove primary leader from self.`**</mark>

You need <mark style="color:yellow;">**5**</mark> <mark style="color:yellow;">**people**</mark> to type this command with the player they would like to vote to be leader so they may have access to the leader commands. In the package comes a neat little tag above their head to indicate that they're in charge of the ~~sh‎it~~show!


{% endhint %}

## Markers

<figure><img src="../.gitbook/assets/leader tag.png" alt=""><figcaption></figcaption></figure>

To activate leader actions, you must use TF2's voice commands. Each action below will indicate which voice-line to use.&#x20;

Additionally, a distance parameter is shown underneath the action name that changes depending on how far away one is from a marker.&#x20;

Markers can also be used on most **entities** to **Highlight** them a certain color - for example a specific trap, door, etc.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
If you don't have any of these hotkeys binded or find it easier to have them all in one area, you can bind the <mark style="color:yellow;">**!leadermenu**</mark> chat command to open a panel that will allow you to place them.
{% endhint %}

*   <mark style="color:yellow;">**Voice Command:**</mark> **Help!**

    This action places a <mark style="color:green;">**"Defend Here"**</mark> marker with a green ring, indicating where teammates should fend off the zombies.

<figure><img src="../.gitbook/assets/Defend Here.PNG" alt=""><figcaption><p>Help!</p></figcaption></figure>

*   <mark style="color:yellow;">**Voice Command**</mark><mark style="color:yellow;">:</mark> **Incoming!**

    This action places a <mark style="color:red;">**"Danger Here"**</mark> marker with a red ring, indicating spots teammates should be wary of.&#x20;

    **• e.g. environmental dangers, zombie TPs, etc.**&#x20;

    <figure><img src="../.gitbook/assets/Danger Here.PNG" alt=""><figcaption><p>Incoming!</p></figcaption></figure>
*   <mark style="color:yellow;">**Voice Command:**</mark> **Go! Go! Go!**

    This action places a <mark style="color:blue;">**"Fall Back"**</mark> marker with a blue ring, indicating spots teammates should retreat to.&#x20;

    <figure><img src="../.gitbook/assets/Fall Back.PNG" alt=""><figcaption><p>Go! Go! Go!</p></figcaption></figure>
*   <mark style="color:yellow;">**Voice Command:**</mark> **Move Up!**

    This action places a <mark style="color:purple;">**"Follow Me"**</mark> marker **above the leader's head**, indicating that your teammates should come to you. The marker will remain active for a few seconds.&#x20;

    <figure><img src="../.gitbook/assets/Follow Me.png" alt=""><figcaption><p>Move Up!</p></figcaption></figure>

## Custom Markers!!

{% hint style="info" %}
<mark style="color:purple;">**Leaders**</mark><mark style="color:purple;">**&#x20;**</mark>_<mark style="color:purple;">**(and mini-leaders)**</mark>_**&#x20;can now customize their own markers via specific text AND&#x20;**<mark style="color:$primary;">**s**</mark><mark style="color:$info;">**p**</mark><mark style="color:$success;">**e**</mark><mark style="color:$warning;">**c**</mark><mark style="color:$danger;">**if**</mark><mark style="color:blue;">**ic**</mark> <mark style="color:purple;">**c**</mark><mark style="color:orange;">**o**</mark><mark style="color:yellow;">**l**</mark><mark style="color:green;">**o**</mark><mark style="color:red;">**r**</mark>**.**&#x20;

~~_**Effectively, you \*could\* make a boss callout centered bind layout for push, pull, etc, but who would dedicate that many bind keys? Haha...**_~~\
\
<mark style="color:red;">**Through chat commands you can't use spaces in custom text - so REALLY recommend using these in your console sm commands;**</mark>

**placeleadermarker markername** <mark style="color:red;">**R**</mark> <mark style="color:green;">**G**</mark> <mark style="color:blue;">**B**</mark> <mark style="color:yellow;">**Duration**</mark>\
&#xNAN;**`(Console)`** **sm\_placeleadermarker "**<mark style="color:$danger;">**zombie shortcut**</mark>**"** <mark style="color:red;">**255**</mark> <mark style="color:green;">**192**</mark> <mark style="color:blue;">**203**</mark> <mark style="color:yellow;">**10**</mark>&#x20;

* Quotes " are **required** for console if your custom text has spaces - the above color code example should give you a <mark style="color:$danger;">**pink marker**</mark>- and places the marker for <mark style="color:yellow;">**10 seconds.**</mark>
* **Duration Default is 5, Minimum is 3, Maximum is 10**
* **Character limit for custom text is around 150**&#x20;
* **Custom Symbols&#x20;**_**(that are compatible with TF2 chat)**_**&#x20;work too, including;**
  * &#x20;ඞ
  * ( ͡° ͜ʖ ͡°)
  * ♕
  * ᗜˬᗜ

[**(Redirect for a simple RGB color picker site.)**](https://rgbcolorpicker.com/)

[**(Redirect for Custom Symbols that work in TF2.)**](https://steamcommunity.com/sharedfiles/filedetails/?id=3304832814)

\
&#xNAN;_**\*Selfish note for own edit later that these will soon™ become sm\_leadermarker**_&#x20;
{% endhint %}

## Mini Leaders

#### <mark style="color:yellow;">**`/addleader & /removeleader [Player Name] for mini leaders - must be done by the primary Leader.`**</mark>

<mark style="color:yellow;">**`Mini leaders can be removed via /removeleader [Player Name] by primary Leader.`**</mark>

Mini leaders are effectively co-leaders _(cap of 4_) assignable by the main leader that can place markers _(shared on a global cooldown)_ for people to stick around in case the map has several splits.

Mini leaders are not immune to starting auto-infect.

## How do I efficiently lead?

Most of the time, leading will play part in parcel with going with the flow of the team. You can either lead dominantly or be laid-back, depending on the players on the server. <mark style="color:yellow;">**Whatever extent you want to lead will require you to "read the room" and try and establish a general sense of what people want to do.**</mark> _For example,_ most people don't need or may not care for a leader in simple maps like **`ze_atix_panic`** or **`ze_defense3002;`** but, for maps like **`ze_shroomforest3`** or **`ze_dark_souls,`** _assuming people want to beat them,_ then a leader might be appreciated.

Regardless, it doesn't hurt to have a leader, even if you don't use your mic for simpler maps. Take this as your opportunity to experiment and learn how to use the Leader plugin. So long as you communicate properly with markers and text chat, that is sufficient enough to try and push your team in the right direction while not being as intrusive as voice chat. In both instances, you will still need to understand the map, where to go, and what to do. You don't necessarily need to know **all** the best or the safest strategies, although they will most certainly aid in the survivability of your team, and you can just rely on a general sense of how to get through things.

If you want to lead a map but are not sure how to lead, see ﻿how others do it! Once you get familiar with the timings and strats of a map, it's time to actually lead. To be an _effective_ leader, there are some things you should be wary of. Remember, **not everyone** is as experienced as you are, so your job as a leader is to make sure people are aware of crucial information to help them survive!&#x20;

### **This includes:**

* <mark style="color:yellow;">**When and where zombies teleport;**</mark> _"Zombie Tele on the danger marker when second door is triggered, at 10 seconds on next timer" etc,_
* <mark style="color:yellow;">**When and where to fall back;**</mark> _"Go middle gate after timer ends" etc,_
* <mark style="color:yellow;">**Any traps to avoid;**</mark> "_C4 bomb at door, pizza, holes in the floor" etc,_
* <mark style="color:yellow;">**Boss Fight Callouts;**</mark> _"Hug the walls or you'll die, stay in the middle, go backwards" etc._

Due to the fast-paced nature of Zombie Escape, you won't have much time to speak before a crucial event pops up, so be sure to be quick and straight to the point! As you play more and more, you'll get better and more familiar with the map and become a more effective leader as a result!

## Cool, but do we always need a leader?

While leaders may be useful, you may encounter teammates **uninterested** in beating the map or maps simple enough to play without one. You might even find teams already familiar by heart with the more complex maps, allowing them to just play at their own pace. In most cases, though, you'll find that not everybody knows the map, and you might even have some players completely new to ZE overall. Maybe you'll even come across players that _do_ know the map but need the assistance of a leader to tie things together. **If there's an expressed desire to learn or push through the map, it may require a leader to step up and guide everyone through the chaos.**

## Can't hear the Leader!

This is actually less of a note for leaders and more or less for the players _listening_ to voice-comms generally speaking - the command known as [**voice\_overdrive**](../miscellaneous-info/useful-console-commands-and-keybinds.md#commands) can **REALLY** help alleviate some of the typical problems of voice-chat being being drowned out by gunshots or map sound effects.&#x20;

It won't adjust _their_ audio levels however - so a quiet mic will still be very quiet unless you delve into using `voice_scale` _(careful setting this value too high)_ otherwise that person will probably have to fix their gain whereas applicable.

## Overtalking

Culturally throughout Zombie Escape servers - this isn't a do or die sort of thing, and **heavily depends** from person to person on leading styles on whether they even care or not - but in the more difficult to coordinate maps like split defense or item-heavy maps; _ex **`ze_visualizer`** or **`ze_serpentis_temple`**_ where communication will be absolutely key, it's recommended to keep any _**extra**_ voice-chatter to a minimum unless **integral** to the map like calling out a losing defense, item usage, and so forth.&#x20;

Going on a _<mark style="color:red;">**30 minute rant of how you're evading taxes, and that CSS is better than CS2, I soloed your mom last night;**</mark>_ might just get you ignored in VC by the leader or a few other people there to try and fish out a victory as it could drown out any important callouts. The same can really be said for **backseat leading** or **double leading** - unless the current leader has forgotten something or needs any confusion cleared up on a tactic.

Again though, this isn't like _**"always be silent during leading hours forever"**_ - but is just more another pointer to read the room!&#x20;

{% hint style="info" %}
### _<mark style="color:yellow;">Note:</mark>_ In the event of problematic vocal players over-speaking leader constantly, you can opt into Leader VC priority - _(this will disable all other mics except leader when they're speaking)_

## _<mark style="color:yellow;">This can function toggled by the leader via the</mark><mark style="color:yellow;">**`!leadermenu`**</mark> <mark style="color:yellow;"></mark><mark style="color:yellow;">command.</mark>_
{% endhint %}
