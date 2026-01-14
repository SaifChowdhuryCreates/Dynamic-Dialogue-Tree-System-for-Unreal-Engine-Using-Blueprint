Utilizing custom structures, data tables, csv, to program branching dialogue tree that can also execute custom code based on the dialogue options that occur.

A video demo of the system can be found here:
https://youtu.be/5cc-4PJm-58

The system is meant to reflect a similar one found in games like Mass Effect where what the player says affects are said to them. Throughout this demo, you are introduced to types of dialogue where NPC's talk without optional choices (information based), talk where their answers are definitive (concequential), as well as talk to NPC's who provide information and to which you can respond with you opinions but it does not affect the story (flavor text).

This is an expansion of the traditional dialogue system which uses strings of text. Each npc has a reference to a data table, using row names and integers, each text can point to various other text lines and even loop back on itself. Custom code is also possible to be written. For example, when the following row name is called "SHOP" the item shop will appear. When the following row name is titled "ACTION" the NPC holding that dialogue will execute their prewritten action script, whether that be walk to a location, start attacking, or simply play a specific animation.

All information is handled via data tables which are easily customizable and reimportable through CSVs, making the process even faster for typing dupblicated information, infering falseness for blanked out values, and using Excel style row math to automatically generate unique id names for every row. 

If it was done in Unreal Engine alone, adding such items would result in perpetually closing and opening menues that close every time you add a new entry, reducing the speed at which these dialogue trees can be produced.

Using this dialogue system, artists and writters can easily express their opinions and sculpt their own narratives, without having to touch a single line of code.
