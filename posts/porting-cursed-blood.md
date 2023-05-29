---
title: Cursed Blood, part 5 - Porting Cursed Blood to B/X
description: Stepping back
date: 2023-05-18
eleventyExcludeFromCollections: true
tags:
  - Cursed Blood
---

As I've written about [before](/tags/cursed-blood), Cursed Blood is a setting I used for a homebrew campaign. We used [Miserable Secrets by Rose Bailey](https://www.drivethrurpg.com/product/245941/Miserable-Secrets) as a jumping off point, mainly because I wanted a Castlevania setting specifically, but by session #2 we were essentially in uncharted territory.

The original game uses an interesting combination of DnD style tactical play/grid combat, a rigid turn cycle, and a playing card resource management economy. While I definitely think it'd have been a sound and interesting experience, my play group largely didn't respond to the board-gamey aspects or the difficulties making the playing cards work in Roll20.

So I threw together a homebrewed system that essentially ignored the grid/tactical aspects and replaced the resorce management aspect with a dice pool economy. It worked just fine, but I kind of hated it the entire time.

Looking back, I think I should have switched to OSE immediately, because as we moved out of the structured style of play Miserable Secrets uses, we fell into the most common play pattern I understand, which is alternating between exploring locations and investigative/political role playing.

In addition, as soon as we dug in, we essentially discarded much of the world building in the Miserable Secrets corebook. The reason for that is - I like to make stuff up. I've never used a book completely straight, I don't think, especially something in the realm of fantasy.

This is all to say, I feel like converting the custom classes and worldbuilding into an OSE framework. And I'm going to start with the following fighter-style class, The Doomed.

<div class="ose-class">
<h2 class="ose-class-title">The Doomed</h2>
<div class="ose-class-stats">
  <p><strong>Requirements</strong><span>None</span></p>
  <p><strong>Prime requisite</strong><span>STR or DEX</span></p>
  <p><strong>Hit Dice</strong><span>1d8</span></p>
  <p><strong>Maximum level</strong><span>13</span></p>
  <p><strong>Armor</strong><span>Any, including shields</span></p>
  <p><strong>Weapons</strong><span>A mythic weapon (roll on the table below)</span></p>
  <p><strong>Languages</strong><span>Common, Hunter's Code</span></p>
</div>

<ul>
<li>The Doomed are inheritors of an ancient lineage of protectors and monster-slayers.</li>
<li>They did not refer to themselves as Doomed, but as members of The Order.</li> 
<li>They are regarded as a necessary evil by the Nobility, as they eliminate the threat from demons and mutated creatures.</li>
<li>There are 12 in the Order at any given time, one for each of the mystical weapons possessed by the original 12 hunters.</li> 
<li>They are indoctrinated as children and if chosen to wield a weapon, are gifted with magical golden eyes and burning toxic blood.</li>
</ul>

|     | Legacy weapon (1d6 DMG)       | Bonus                                                                                                   |
| --- | ----------------------------- | ------------------------------------------------------------------------------------------------------- |
| 1   | Bloodfarmer (Kusuri-gama)     | Can be used as a ranged or melee weapon. Damage and bonuses remain the same.                            |
| 2   | Starfall (Broadsword)         | _Two-handed_ Can be used as an implement to cast _Light_                                                |
| 3   | Old Silver (Quarterstaff)     | +1d4 damage against undead foe. The sight of this staff causes lesser undead creatures to flee          |
| 4   | Starwatcher (Helm)            | +1 to INT. Can be used as an implement to cast _Contact Higher Plane_                                   |
| 5   | Hand of Doom (Cestus)         | +1 to STR.                                                                                              |
| 6   | Demon's Tongue (Whip)         | +1 to DEX. Can be used to start a small fire (i.e a campfire)                                           |
| 7   | Thunder (Warhammer)           | _Two-handed_ Damage die is 1d8                                                                          |
| 8   | The Gentle Reminder (Longbow) | Impart your arrows with psychic messages that are communicated when the arrow pierces the skin (on hit) |
| 9   | The Raven's Kiss (Crossbow)   | Impart your bolt with a curse that on hit causes the victim to empty their pockets                      |
| 10  | The Tower (Cuirass)           | +1 to CON.                                                                                              |
| 11  | Lightning (Mace)              | _Two-handed_ Damage die is 1d8                                                                          |
| 12  | Dandy Johnny (Spider amulet)  | Damage is 1d4. The wearer learns the spells _Read Languages_, _Read Magic_, and _Detect Invisible_      |

<div class="ose-class-feature">
<h3>Combat</h3>
<p>The Doomed can use all weapons and armor. When using their magical weapon, they deal bonus damage equal to their level.</p>
</div>

<div class="ose-class-feature">
<h3>Magic</h3>
<p>As a result of their training and weaponry, the Doomed may have the ability to access certain spells. They cannot learn to cast spells but they can and do wield magical weaponry.</p>
</div>

<div class="ose-class-feature">
<h3>Hunter's Code</h3>
<p>Hunter's Code is a pictographic language that only the twelve members of the Order understand fully.</p>
</div>

<div class="ose-class-feature">
<h3>Toxic blood</h3>
<p>The Doomed are physically transformed by their indoctrination. Their blood is magically infused with toxins and acidic compounds. If they are reduced to half of their hitpoints, they roll all damage die twice and choose which to apply.</p>
</div>

<div class="ose-class-feature">
<h3>Hunter's eyes</h3>
<p>The Doomed have one physical trait in common; their unearthly glowing eyes. They can make an INT test to cast Detect Magic at will.</p>
</div>

<div class="ose-class-feature">
<h3>A terrible destiny</h3>
<p>The Doomed are taught from a young age that they will die in the service of their creed. This belief is so pervasive that at a certain point,
they come to believe that outlive their usefulness and start to behave with an incredible disregard for their safety. After level 11, they become more fragile, both hit protection and saving throws start to decline.</p>
</div>

<div class="ose-class-feature">
<h3>Story hooks</h3>
<ul>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
</ul>
</div>

<div class="ose-level-progession">
  <h3>Level progression</h3>

| Level | XP     | HD    | THAC0  | D   | W   | P   | B   | S   |
| ----- | ------ | ----- | ------ | --- | --- | --- | --- | --- |
| 1     | 0      | 1d8   | 19[0]  | 12  | 13  | 14  | 15  | 16  |
| 2     | 2000   | 2d8   | 17[+2] | 12  | 13  | 14  | 15  | 16  |
| 3     | 4000   | 3d8   | 17[+2] | 12  | 13  | 14  | 15  | 16  |
| 4     | 8000   | 4d8   | 14[+5] | 10  | 11  | 14  | 13  | 14  |
| 5     | 16000  | 5d8   | 14[+5] | 10  | 11  | 14  | 13  | 14  |
| 6     | 32000  | 6d8   | 12[+7] | 10  | 11  | 14  | 13  | 14  |
| 7     | 64000  | 7d8   | 12[+7] | 8   | 9   | 10  | 10  | 12  |
| 8     | 120000 | 8d8   | 10[+9] | 8   | 9   | 10  | 10  | 12  |
| 9     | 240000 | 9d8   | 10[+9] | 10  | 9   | 10  | 10  | 12  |
| 10    | 360000 | 9d8+2 | 19[+7] | 10  | 9   | 8   | 13  | 14  |
| 11    | 480000 | 9d8+4 | 19[+5] | 12  | 9   | 8   | 13  | 14  |
| 12    | 600000 | 9d8+6 | 17[+2] | 12  | 9   | 8   | 13  | 14  |
| 13    | 720000 | 10d8  | 19[+0] | 15  | 11  | 6   | 15  | 16  |

D: Death / poison; W: Wands;
P: Paralysis / petrify; B: Breath attacks; S: Spells / rods / staves.

</div>

</div>
