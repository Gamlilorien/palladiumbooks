# palladiumbooks
This is an unofficial Foundry VTT game system for playing Tabletop RPG titles from [Palladium Books®](https://palladiumbooks.com/) like: Rifts®, After the Bomb®, Heroes Unlimited™ and more!

## Disclaimers
1. This project is NOT offically sanctioned by Palladium Books in any way, and therefore does not include anything but the bare bones framework needed for playing Palladium Books games in Foundry VTT. 

2. This is a work in progress provided to you as-is, with known bugs and limited functionality that is provided to you for FREE AND PERSONAL USE ONLY. Furthermore, this is my first attempt at Foundry VTT system development, which I am learning and developing soley in my spare time via trial and error. You are free to use, copy, or modify this work as you see fit as long as it used for non-commercial & personal use only and you honor Palladium Books Copyright, Trademark, and Internet Policies respectively (see below).

3. Please know that while I continue to learn and work on this project, future updates, espically ones that alter the underlying data model of the system, may cause breaking changes from previous versions. Therefore, please USE THIS CODE AT YOUR OWN RISK. I will obviously do what I can to avoid drastic updates or breaking changes, and make note of such changes if I can, but I also want to be 100% transparent as I don't know what I don't know!

## Palladium Books System Entities
Foundry VTT breaks up systems into different ENTITIES of information. Actors, Features, and Items are default entities used by the sample Foundry VTT system template from which most of the Palladium system specific entities have been derived. Below is a hierchary of these entities used in this system with any relevant notes on their: Current Functionality (C), Planned Functionality (P), or Bugs & Issues (B) respectively.

- Actor
  - Character Sheet
    - (C) Can enter basic info like: name, age, level, alignment, character portrait etc
    - (C) Can enter and track basic changing stats like: health, energy, credits and experience
    - (C) The 8 character attributes will auto calculate bonuses based on input (where appropriate)
    - (C) Simple listing of most common combat bonuses like: strike, parry, dodge etc
  - NPC Sheet
    - (C) A no frills version of the main character sheet for GM goons and NPCs that don't require as much detail
    - (P) This template may be rebuilt when the main character sheet is built out further
- Features
  - (C) Used currently to record basic or miscelanous special abilities like: nightvision, claws, or predator burst etc.
- Items
  - Skills
    - (C) Can manually create, edit, and delete skills of various types including: single % skills (most), double % skills (like Horsemanship or Climbing), SPECIAL skills (ie ones without skill %s, like most physical, HTH, or WP skills), and Focused skills (ones that can be taken multiple times and/or require that you specify a specality like Language, Art, or History etc).
    - (C) Skills added to the skill compendium can be dragged onto a character sheet
    - (C) Skills added to a character sheet will auto calculate the skill percentages based on level and the level the skill was aquired as well as sort them by category.
    - (C) Skill check rolls can be made automatically by clicking on the skill percentage from the skill list on a character sheet
  - Spells
    - (C) Can manually create, edit, and delete
  - Psionics
    - (P) Coming soon...
  - Equipment
    - Armor
    - Weapons
    - Misc
- Combat


## Installation
Coming soon...

## LEGAL
Rifts®, The Rifter®, RECON®, Splicers®, Palladium Books®, Phase World®, The Palladium Fantasy Role-Playing Game®, Megaverse®, Nightbane®, The Mechanoids®, The Mechanoid Invasion®, Coalition Wars® and After the Bomb® are Registered Trademarks of Palladium Books Inc. Heroes Unlimited, Beyond the Supernatural, and other published book titles, names, slogans and likenesses are trademarks of Palladium Books Inc. and Kevin Siembieda.
See Palladium Book's offical [internet policy here](https://www.palladiumbooks.com/index.php/component/content/article/47-submission-info/523-palladium-booksr-internet-policy).
