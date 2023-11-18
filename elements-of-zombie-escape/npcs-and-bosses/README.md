# NPCs and Bosses



On some maps, you will encounter NPCs and boss fights that you will have to fight. They will attack you in many different ways whether it be running into you, shooting projectiles at you or performing some sort of attack that you'll have to be mindful of to avoid. Note that these NPCs and boss fights are **different** from your typical TF2 Halloween bosses and are essentially giant objects that you have to break.&#x20;

{% hint style="warning" %}
## Some bosses <mark style="color:red;">**disable**</mark> or nerf <mark style="color:green;">healing</mark> which also results in Zombies being unable to use their Enzymes.
{% endhint %}

Coupled with that being out of the way, here is a list of things you should be aware of when dealing with them.

* They are unaffected by damage rampup or damage falloff.
* They are unaffected by minicrits or crits.
* Arrows will not damage them.
* On hit effects do not work on them.
* Fire will essentially do no damage to them.

## Differentiating between an NPC and a Boss

NPCs are enemies that may spawn in maps. Sometimes they are not necessary to kill whereas other times they must be killed to progress. Bosses are also enemies that may be found in a map but arrive in specific areas like special events in your typical video game. Either one or multiple will spawn in a round with an entire section dedicated to fighting them in order to progress. They will primarily be denoted with health bars to allow you track your progress fighting against them. More times than not, you're expected to survive against NPCs and deal with them as they come. Against bosses, it's up to everybody to do what they can to survive.



## NPC and Boss Health

![](<../../.gitbook/assets/Capture (9).PNG>)

It was mentioned earlier that NPCs and bosses are "giant objects that you have to break." Deconstructing them, they are indeed just objects you can break but are built with different methods of breaking them. Two primary ways of damaging them tie into the usage of func\_breakables and math\_counters. Without any mapping knowledge, just know that _one application_ of these is for NPCs and bosses that can be destroyed either by **actual damage** or by the **amount of bullets that hit.**\
\
This creates **two different approaches of damaging NPCs and bosses.** While the stats pages above may have shown what weapons have the highest DPS, they are not _necessarily_ the best for breaking objects. For example, if a boss were made with a func\_breakable, we could take into consideration the actual damage of a weapon. Suppose we were using a sniper rifle. A fully charged shot on a func\_breakable would deal 150 damage. However, if this boss were made using a math\_counter, then that 150 dmg shot would do a measly 1 dmg. Of course, scaling would be adjusted in both scenarios, but it demonstrates a concern for the amount of bullets we can put into an object versus the actual damage a weapon can do depending on the scenario.\
\
So, when fighting NPCs or bosses, aside from just straight DPS, **try considering other factors like bullet spread, bullets per shot, and Attack Interval.** You might want a tighter spread if you have to shoot far way, which makes weapons like revolvers actually more effective than Scout's Back Scatter due to its greater precision. This advantage lessens the closer a boss is fought at. If you want to know what damage system the boss is based off of, try asking around on the server as it can vary from map-to-map or even boss-to-boss on the same map.\


{% hint style="info" %}
<mark style="color:yellow;">**Note:**</mark> There is a custom server plugin that causes math\_counters to subtract health in a fashion similar to func\_breakables. This may or may not be implemented into a map as it depends on the mapper or person who ported the map. In this case, you need only concern yourself with DPS.
{% endhint %}



