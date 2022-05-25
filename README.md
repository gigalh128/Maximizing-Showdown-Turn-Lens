# Maximizing-Showdown-Turn-Lens
Feel free to send a PR if you think you can optimize a method I currently have listed. This repo will have scripts associated with the methods I come up with so that you can run these without any effort for yourself.

## Goal
The goal is to create a turn that has the maximum number of protocol lines (and then the max length of text shown in the client screen) after the "skip turn" button is pressed. This means that creating a scenario where a pokemon gets switched out & the player needs to make a choice again resets the length. (Ex. after you use u-turn, all the lines from before using u-turn and all the lines afterwards are separate). The idea here is that this would create the most obnoxious portion of a turn in a cartridge battle in which you had to sit and just watch text scroll by, which is pretty funny to think about.

Also this obviously means that chat, join/leave logs/any other system logs are not counted.

Optimize first for # of protocol lines, then for length of text seen.
