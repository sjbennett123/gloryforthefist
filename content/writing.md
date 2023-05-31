---
title: "Writing"
date: 2022-11-10T10:33:21-05:00
draft: false
weight: 1
---

- If you have an idea that you just want to get off your chest submit it [here](https://forms.gle/j3n8CiwL9dvjQNsL9). 
- Use the standard writeup format that we all are using for your writeups. 
- Don't submit too much at once for review finish one thing at a time. 
- Once you are confident with your work we will ingest it into the website get it printed up. 

## Parts of Writeups

All of the writups need to be written in a similar way to this. If there is a change to the formats that we need to make we can discuss it but all modules will need to adapt to use that.

to set up on your local computer follow these steps. [Website Howto]({{< ref "/website_howto" >}})

Confirm that your code between the --- parses at https://www.yamllint.com/

**if you get errors these are the most common issues**

*mapping values are not allowed in this context* --     you have a colon in the value section for the yaml.
    

### Plotline Overview

```yaml
---
title: 
layout: plotline_overview
---

```

Similar to module overview it will pull the roles underneath it. 

#### Title

This needs to match the plotline name in 

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
If there is something that you are not using don't populate it the system will handle it. 



#### Title

A distinctive title for your module. Something that can be talked about around the shack that evokes the feel of your module. 

*This is bad "Crab People 3" or "Sneaking Module".* 

#### Brief/Description

**Enter this as description in your code.** 

This is a one or two sentence description of the module. Don't put any mystery in here be as simple and direct as possible. 

*This is bad "The adventurers discover that all that glitters is not gold when the Crab People are involved".* 

*This is good. "The adventurers try to find a buried treasure but are attacked by the Crab People"*

#### Schedule

Friday, Saturday Random,Townsfolk or unsorted. If this is left blank it will go to unsorted. 

#### Weight

will need tinkered with so that it shows up in the list in a reasonable place. Higher weights go to the bottom. 

#### Plotline

The name of the plotline that this relates to. 

#### Requirements

The conditions that need met for the module to be ran. If the module needs run at night or must be ran after another module.

#### Background

Stuff that leads up to the module. Often you will have bits of lore that the runner should know and would get tripped up on. 

#### Synopsis

The meat and potatoes of the write-up. Be as verbose as you can and explain all the ins and outs of the adventure. Someone should be able to run the module with just the information here. The rest of the writeup will make it really shine but you will need to spell it out here. 

#### Outcomes

The things you can see coming of the module. Think about stuff like how the players can lose and how the players might not follow what you have planned. This section is really important for when you have a bunch of modules that you string together or a pitched battle.

#### Hook

This is how the players get on the module. All modules need a hook of some sort even if it's the players find an "Adventure Card" in the woods or the players tell the game master that they are going to "The Forgotten City".

#### Page

If the module doesn't outwardly contain any combat then marking as a "Page" module is a good idea. Put some notes on where violence can break out so that the NPC's know how to deal with it.

#### Number of Cast Members

Give a range. The fewer cast members that CAN run a module the better don't get too ambitious and write a module that requires 10-15 NPC's. Often you will have "mooks" that will be able to be added to a scene to flesh it out. Do the work before the event and optimize your design so that it uses less resources from the backend 

#### Roles

These are the different roles that the cast members will be playing for the encounter. Each role will be given the module sheet and the role card. Remember that the Hook needs a role card too.

#### Props

These are the props that are needed for the module to run. Before the event we will check to make sure that we have all these things in the NPC Shack and if we don't have them we will either make them or change the module.  If special props are needed for the encounter, make it as easy as possible to use them. Have checklists to make sure you get all the props with a description of the props. Also have notes about what props are essential and which props are optional for the encounter to do down successfully.

#### Tags and Treasure 

Any tags that are needed for the encounter, generally you will divvy the treasure for each of the different roles if this is not the case mark it down. Remember that the treasure for a module is often the MOST important thing for the players even though it can be easy to forget about.

#### Scenes

List out all of the scenes that will be used in the module. If there is a cave with 5 rooms write out 5 scenes. Detail any setup that is needed. Detail both the Out of Game setup that is needed as well as what the scene is in the game. Possibly give a description that the runner can read as "Box Text". Don’t detail “the Tavern” or “The Town” as a scene. It is assumed that part of the module will interact with the players that are away from the module area due. Set the scene and be clear about boundaries. Often you will be using things that don't mean what they say they mean. 

#### Flee Point

Every module will need a way for someone to get out and get back to town. Detail both what the way out is Out of Game ie "The Door to the Module Shack" and in game "The entrance to the cave that leads back to the surface". If there is not a way out then you will want to make it very clear that there is no escape. 

#### Non-Standard Effects

Anything that does not conform to the NERO rules will go here. These deviations will be detailed at the start of the module.

#### Rules Clarifications

What rules are heavily used on the encounter that would do with some clarification. 

#### Craftsman Information

What information do you give to people that have craftsman skills. 

#### Transformations

Do transforms go up? Which ones?

#### Running Notes

This is the guidance that you would give a runner. Often the things you want to put there belong in the Synopsis or the Background. Try to reserve this for advice about how to make the encounter run smoothly.

#### Rules Clarifications

Most people that play NERO haven’t' read the rules. They are just playing it by what they see and they reference the PDF when they get home. To help keep the game from being anarchy we go over the rules that are immediately important when they come up on our encounters. For instance if you are going to be using a bunch of monsters with waylay go over the waylay rules at the start of the encounter. Calling a hold for odd effects pre module if done every module would be standard and would feel less like a verbal bashing if done consistently. 

---

If you think that a bit of information might be useful, put it in the write-up. -- One of the things that I often see if people stopping me when I do the read through of the write-up to give some information about the setting or the encounter. Put that in the write-up.

When writing a module try to ensure that the basics are handled well before you get "Crazy" monsters all have cards and are costumed etc.

When you are doing a writeup many small details that seem superfluous are just the thing that is needed to make the thing shine. The standard format is just the bare minimum for the thing to be usable. Try to capture as much of your vision in your writing as you can. The best writeup is like the writer being there explaining the plan to you.

Read the write-up aloud before giving it the thumbs up. The cast will be reading it aloud you don't want to look like an asshole. 

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

If there is something that you are not using don't populate it the system will handle it. 

Often there are bits where the cast need to add their own little something to a role. Give some guidance for this so that they can be more confident in their play.

Try to give the cast some guidance on making the characters come alive. What do you say exactly how do you say it. What mannerisms will make the characters work. 

Remember to give your characters names. Use name lists such as the [Storygames Name Project](http://eakett.ca/sgnp/)  

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
Inteligence: 
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

Always remember that the cast is playing too. -- This goes contrary to the adage that the only the Player Characters are "customers" and the npc's are there to entertain the customers. The truth of it is that both parties are customers, and the runner needs to structure the encounter so everyone is playing. I think the core of this is clearly defining the boundaries of the encounter and giving many of the characters in the backend "Agency" to do things. 

Use the setting that exists if at all possible. Don't create new setting if an existing bit will do. We must build on each other's work. 

## Reviewing Tips

- You don't need to correct anything if it's not broken. 
- First priority is spelling / grammar. 
- Are there any props that are mentioned in the writeup but not in the list.
- Can you visualize the module. 
- Say nice things too remember they tried their best. 
- Look for tentative language. 
  - should 
  - Almost
  - Just
  - Will
  - essentially

- Props that are not detailed. Notes that don't have the text.

```yaml
---
title: "Feedback: Cryptic Wishes"

layout: feedback
author: Scott Bennett
---
```



## POLAR Event Directors Requirements

1. You must work with your Review. 
2. No non-standard effects. Anything you want to try to do that could be non-standard please reach out to Clinton Snyder or Donnie Leight and they will find a way to make it standard. 
3. Your full event must be reviewed 2 weeks in advance before your event. Your event must have a minimum of 30 encounters. An encounter can be can be as simple as an NPC that Entertains multiple PCs at a time.
4. Events should include 
   1. puzzles
   2. ciphers
   3. non-combat skill usage
   4. transform acquisition modules.
5. Use of Donnie Leight's standard mod sheet. 
   1. The mod sheet makes it easier for a shack person or anyone who has permission to run a mod for you can pick it up and set up and run quickly.