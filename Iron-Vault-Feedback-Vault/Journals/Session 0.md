# Session 0

## Background
I was lucky enough to have been raised by **[[The Seekers of the Shattered Pact]]**. One of the largest (if not the largest) faction in the forge. Conscripted at the age of 4, I was named after one of the ships that brought our people to the forge. The Valenus. Argus was supposedly a name of one of the old gods. Everyone in the pact was named like that, for our exodus ships and for the old gods. 

For thirty years I’ve gone where “The Pact” sent me. The Forge was dangerous and the countless sectors are still unexplored, as vanguard, my charge was to assess and determine sectors for potential expansion. 

## Character
[[Argus Valenus]] Age: 34
First Look: Ill-equipped, distracted, imposing. Argus is large. Doubly large when in his armor. While in perfect working order, the armor itself is worn, with parts clearly having been replaced in field. Out of the armor, he often appears distracted and looks past you. Long hair on his left side is kept pulled back, while clean shaven on the right. 

Aspect: Obsessed. Raised by the Pact means that Argus is obsessed to a fault. When sworn to iron he cannot be dissuaded. He sees only a future that brings safety through the Pact, the noble ends of a “made vow” give wide latitude to any “means”. 

Background Vow:
```mechanics
track name="[[Progress\/I will see the Pact forge an empire.md|I will see the Pact forge an empire]]" status="added"
```

![[I will see the Pact forge an empire]]


## Starship
History: The Kestral is an Arclight class ship, which means it has what almost look like feathered wings that bend, twist, and shift as it flies. The wings themselves are attached through arclight connections. A bit of old world tech. [[Annora Pearson]] is my companion and pilot. She and I relieved a field commission during the battle of [[Fool’s Shoal]] (the previous sector), and through that, the ship is now registered to me. It has seen better days. The outside of the ship is marred with scorch marks, battle damage, and has several field repairs.

## Location Generation
First we create the sector:
```mechanics
oracle name="[Space Encounter Oracles \/ Sector Name \/ Prefix](oracle:starforged\/oracles\/space\/sector_name\/prefix)" result="Lacuna" roll=61

oracle name="[Space Encounter Oracles \/ Sector Name \/ Suffix](oracle:starforged\/oracles\/space\/sector_name\/suffix)" result="Anvil" roll=3

```
[[Lacuna Anvil]] it is. 

## NPCs
Who do I know in this sector? Well, since I have a sidekick, [[Annora Pearson]] for sure. Her role will be pilot, and I have a picture of her in mind so I’ll envision that. I’ll use oracles to generate the rest.

But I need another connection (per standard Starforged rules), so let’s generate one. 
```mechanics
oracle-group name="Character Oracles > Character Name: New Character Oracles > Character Name" {
    oracle name="[Character Oracles \/ Character Name \/ Given Name](oracle:starforged\/oracles\/characters\/name\/given)" result="Faye" roll=34
    oracle name="[Character Oracles \/ Character Name \/ Callsign](oracle:starforged\/oracles\/characters\/name\/callsign)" result="Packrat" roll=64
    oracle name="[Character Oracles \/ Character Name \/ Family Name](oracle:starforged\/oracles\/characters\/name\/family_name)" result="Frost" roll=70
}
```
[[Faye Frost]]… I like it. I wonder what their deal is. Details for this connection will be in her note. 
