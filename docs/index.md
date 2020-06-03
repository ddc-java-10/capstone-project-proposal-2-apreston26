---
title: Flipp Flopp
description: "A fun platformer to kill time"
layout: default
---

## Summary

A platformer that has unique objects that will make platforms either disappear or appear and as standard in these games they get progressively harder as the user progresses. The player will have to use Flipps and Flopps to reach the end of each level. A Flipp would make the platforms disappear and a Flopp would make objects appear. Along with the base game, the players are also timed and racing against each other for a spot on the leaderboard.

## Intended users

* People who need a time waster 
	> As someone who rides public transport fairly often I need something to do to kill the time inbetween my destintations. 

* People who need a challenge 
	> As someone who is very competitve and needs a new challenge I want to find more apps that I can climb the leaderboard and this is the perfect app for me!

## Client component

* **Functionality**

    There will be four screens one is the leaderboard screen which shows all the players and their times. The second screen is the actual play screen where the user will have five buttons to move in four directions and jump. The next screen would be a level selection screen where the player can return to previous levels or there current level, and the third screen is the menu screen where the user can pick between the leaderboard

* **Persistent data**

    On the client side it should save the level progression and allow you to return to past levels and remember what level you where last in, but not the exact position of the player. 
	
* **Device/external services**

    N/A 
    
## Server component

* **Functionality**

	The server is in charge of keeping the time and position on the leaderboard

* **Persistent data**

	On the server side it'll keep a record of the player's time to beat a level then store it in a database then sort that into the leaderboard and keep up the position. 
    
* **External services**

    From an API standpoint I think the main API needed are for the timer on each level.
    
## Stretch goals/possible enhancements 

* Ghost of either the fastest attempt, slowest attempt, or even just the players last attempt.
* Every 5-10 levels a boss level or even just an extra challenging to bridge into a new "environment" that's just a new backaround.
* Depending on the player's position on the leaderboard you could get rewards along with a fifth screen to show rewards.
* Music in the background
