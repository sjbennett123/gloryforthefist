---

title: "Writing"
date: 2022-11-10T10:33:21-05:00
draft: false
weight: 1
---

- If you have an idea that you just want to get off your chest, submit it [here](https://forms.gle/j3n8CiwL9dvjQNsL9).
- Use the standard write-up format that we all use for your write-ups.
- Don't submit too much at once for review; finish one thing at a time.
- Once you are confident with your work, we will add it to the website and get it printed.

## Parts of Write-ups

All of the write-ups need to be written in a similar way to this. If there is a change to the format that we need to make, we can discuss it, but all modules will need to adapt to use it.

To set this up on your local computer, follow these steps: [Website How-to]({{< ref "/website_howto" >}}).

Confirm that your code between the --- parses at <https://www.yamllint.com/>

**If you get errors, these are the most common issues:**

*Mapping values are not allowed in this context* -- you have a colon in the value section of the YAML.

### Plotline Overview

```yaml
---
title: 
layout: plotline_overview
---

```

Similar to the module overview, it will pull the roles underneath it.

#### Title

This needs to match the plotline name.

### Module Overview

```yaml
---
title: 
Layout: module

author: 
reviewer: 
# "friday" "friday night" "saturday" "saturday morning" "saturday early afternoon" "saturday early evening" "saturday night" "reaction" "tavern setup" "townsfolk" "randoms"

schedule:
weight: 
plotline: 
requirements: 

description:
synopsis:   
outcomes: 


number_of_cast_members: 
Roles: 

props: 
makeup: 
treasure: 
magic_items:
  - 
    name: 
    description:  
    duration: 
    effects: 
      - 

rumors: 

hook: 
scenes: 
  - 
    oog: 
    ig: 
    flee_point: 

non_standard_effects: 
rules_clarifications: 
craftsman_information: 
transformations: 
running_notes: 


---
```

If there is something that you are not using, don't populate it; the system will handle it.

#### Title

A distinctive title for your module. It should be something that can be talked about around the shack and that evokes the feel of your module.

*This is bad "Crab People 3" or "Sneaking Module".*

#### Brief/Description

**Enter this as description in your code.**

This is a one- or two-sentence description of the module. Don't put any mystery in here; be as simple and direct as possible.

*This is bad "The adventurers discover that all that glitters is not gold when the Crab People are involved".*

*This is good: "The adventurers try to find a buried treasure but are attacked by the Crab People."*

#### Schedule

Friday, Saturday, Random, Townsfolk, or unsorted. If this is left blank, it will go to unsorted.

#### Weight

This will need to be tinkered with so that it shows up in the list in a reasonable place. Higher weights go to the bottom.

#### Plotline

The name of the plotline that this relates to.

#### Requirements

The conditions that need to be met for the module to run, such as whether the module needs to run at night or after another module.

#### Background

Information that leads up to the module. Often, you will have bits of lore that the runner should know and might otherwise get tripped up on.

#### Synopsis

The meat and potatoes of the write-up. Be as verbose as you can, and explain all the ins and outs of the adventure. Someone should be able to run the module with just the information here. The rest of the write-up will make it really shine, but you will need to spell it out here.

#### Outcomes

The things that can come from the module. Think about things such as how the players can lose and how they might not follow what you have planned. This section is really important when you have a bunch of modules that you string together or a pitched battle.

#### Hook

This is how the players get into the module. All modules need a hook of some sort, even if it is the players finding an "Adventure Card" in the woods or telling the game master that they are going to "The Forgotten City."

#### Page

If the module doesn't outwardly contain any combat, marking it as a "Page" module is a good idea. Add some notes about where violence can break out so that the NPCs know how to deal with it.

#### Number of Cast Members

Give a range. The fewer cast members who can run a module, the better. Don't get too ambitious and write a module that requires 10-15 NPCs. Often, you will have "mooks" who can be added to a scene to flesh it out. Do the work before the event and optimize your design so that it uses fewer resources from the backend.

#### Roles

These are the different roles that the cast members will play for the encounter. Each role will be given the module sheet and the role card. Remember that the hook needs a role card, too.

#### Props

These are the props that are needed for the module to run. Before the event, we will check to make sure that we have all these things in the NPC Shack. If we don't have them, we will either make them or change the module. If special props are needed for the encounter, make them as easy as possible to use. Have checklists to make sure you get all the props, along with descriptions of them. Also, have notes about which props are essential and which are optional for the encounter to be successful.

#### Tags and Treasure

List any tags that are needed for the encounter. Generally, you will divide the treasure among the different roles; if this is not the case, mark it down. Remember that the treasure for a module is often the MOST important thing for the players, even though it can be easy to forget about.

#### Scenes

List all of the scenes that will be used in the module. If there is a cave with five rooms, write out five scenes. Detail any setup that is needed. Detail both the out-of-game setup and what the scene is in the game. If appropriate, provide a description that the runner can read as "box text." Don’t detail “the Tavern” or “the Town” as scenes. It is assumed that part of the module will interact with players who are away from the module area. Set the scene and be clear about boundaries. Often, you will be using things that don't mean what they say they mean.

#### Flee Point

Every module will need a way for someone to get out and get back to town. Detail both what the way out is out of game, such as "the door to the Module Shack," and in game, such as "the entrance to the cave that leads back to the surface." If there is not a way out, make it very clear that there is no escape.

#### Non-Standard Effects

Anything that does not conform to the NERO rules goes here. These deviations will be detailed at the start of the module.

#### Rules Clarifications

What rules are heavily used in the encounter and would benefit from clarification?

#### Craftsman Information

What information do you give to people who have craftsman skills?

#### Transformations

Do transformations go up? Which ones?

#### Running Notes

This is the guidance that you would give a runner. Often, the things you want to put there belong in the Synopsis or the Background. Try to reserve this for advice about how to make the encounter run smoothly.

#### Rules Clarifications

Most people who play NERO haven’t read the rules. They are playing based on what they see, and they reference the PDF when they get home. To help keep the game from becoming anarchy, we go over the rules that are immediately important when they come up in our encounters. For instance, if you are going to use a bunch of monsters with waylay, go over the waylay rules at the start of the encounter. Calling a hold for odd effects before the module, if done for every module, would be standard and would feel less like a verbal bashing if done consistently.

---

If you think that a bit of information might be useful, put it in the write-up. One of the things that I often see is people stopping me during the read-through of the write-up to give me information about the setting or the encounter. Put that information in the write-up.

When writing a module, try to ensure that the basics are handled well before you add "crazy" elements. Make sure all monsters have cards and costumes, etc.

When you are doing a write-up, many small details that seem superfluous are exactly what is needed to make it shine. The standard format is just the bare minimum for the work to be usable. Try to capture as much of your vision in your writing as you can. The best write-up is like having the writer there to explain the plan to you.

Read the write-up aloud before giving it the thumbs-up. The cast will be reading it aloud, and you don't want to look unprepared.

### Role

[Monster Manual]({{< ref "/monster_manual/homegrown/" >}})

```yaml
---
title: 

description: 
Layout: role

introduction: 
motivation: 
tactics: 
movement:
speech:

body:
defenses: 
weapons: 
damage:
magic: 
abilities:
killing_blow: 

costuming: 
makeup:
props: 

reset:
---
```

#### title

#### description

#### Layout

#### introduction

#### motivation

#### tactics

#### movement

#### speech

#### body

#### defenses

#### weapons

#### damage

#### magic

#### abilities

#### killing_blow

#### costuming

#### makeup

#### props

#### reset

---

If there is something that you are not using, don't populate it; the system will handle it.

Often, there are parts where the cast needs to add their own little something to a role. Give them some guidance so that they can be more confident in their performance.

Try to give the cast some guidance on making the characters come alive. What exactly do you say, and how do you say it? What mannerisms will make the characters work?

Remember to give your characters names. Use name lists such as the [Storygames Name Project](http://eakett.ca/sgnp/).

### National Monster Card

[Monster Manual]({{< ref "/monster_manual/national/" >}})

```yaml
---
title: 
layout: national_monster_card
monster_manual: 

Name: 
Body_points: 
Strength_bonus:
threshold: 
rips_from:
Descriptive_Phrase:
Type:
APL:
Movement: 
Intelligence: 
Society: 
Motivation: 
armor: 
offensive_abilities: 
defensive_abilities: 
vulnerabilities: 
spells: 
pyramid: 
rec_treasure: 
notes: 
weapon_use: 
claws: 
base_damage_call: 
at_death: 
healed_by: 
immune_to: 
Protectives: 
Zone: 

quantity:
costuming:
reset:

---
```

## Writing Tips

Always remember that the cast is playing, too. This goes contrary to the adage that only the player characters are "customers" and the NPCs are there to entertain them. The truth is that both parties are customers, and the runner needs to structure the encounter so everyone is playing. I think the core of this is clearly defining the boundaries of the encounter and giving many of the characters in the backend "agency" to do things.

Use the existing setting whenever possible. Don't create a new setting if an existing one will do. We must build on each other's work.

## Reviewing Tips

- You don't need to correct anything if it's not broken.
- The first priority is spelling and grammar.
- Are there any props that are mentioned in the write-up but not in the list?
- Can you visualize the module?
- Say nice things, too; remember that they tried their best.
- Look for tentative language.
  - should
  - Almost
  - Just
  - Will
  - essentially

- Props that are not detailed. Notes that don't include the text.

```yaml
---
title: "Feedback: Cryptic Wishes"

layout: feedback
author: Scott Bennett
---
```

## POLAR Event Directors Requirements

1. You must work with your reviewer.
2. No non-standard effects. If you want to try something that could be non-standard, please reach out to Clinton Snyder or Donnie Leight, and they will find a way to make it standard.
3. Your full event must be reviewed two weeks before the event. Your event must have a minimum of 30 encounters. An encounter can be as simple as an NPC who entertains multiple PCs at a time.
4. Events should include:
   1. puzzles
   2. ciphers
   3. non-combat skill usage
   4. transform acquisition modules.
5. Use Donnie Leight's standard mod sheet.
   1. The mod sheet makes it easier for a shack person, or anyone who has permission to run a mod for you, to pick it up, set it up, and run it quickly.
