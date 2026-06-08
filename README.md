# 032 • Duck Season

**AppADay** — App #032  
**Category:** Games (G)  
**Built:** 2026-06-08  
**Live:** <https://augustineiacopelli.github.io/appaday-032-duck-season/>  
**Portfolio:** <https://augustineiacopelli.github.io/appaday/>

-----

## What It Does

A Duck Hunt–style browser game built in vanilla HTML/CSS/JS with pixel-art sprites drawn on Canvas 2D. Ducks fly across the screen in erratic, randomized patterns — tap or click to shoot them before they escape. Three shared shots per wave, five waves per round, 24 rounds total across three difficulty tiers. Miss over 50% of your shots in a round and the game ends.

## Features

- Pixel-art duck and dog sprites rendered with Canvas 2D (no images)
- 8 weather scenes cycling round by round: Sunny, Golden Hour, Overcast, Rainy, Night Hunt, Stormy, Foggy Dawn, Blizzard
- Animated canvas weather effects: drifting clouds, rain, snow, stars/moon, lightning, fog
- Erratic duck flight with wall bouncing, vertical turbulence, and speed scaling per round
- 3 shared shots per wave — hit any duck or miss into the sky, same ammo pool
- 5 waves per round, 24 rounds total
- Rounds 1–8: 1 duck per wave | Rounds 9–16: 2 ducks | Rounds 17–24: 3 ducks
- Miss rate game over: >50% missed shots in a round ends the game
- Dog laughs when all shots miss — and can be shot for a score penalty
- Win screen for clearing all 24 rounds; game over screen with miss percentage
- Session high score tracked and shown on start screen
- Wing-flap animation, falling duck animation, dog laugh animation with squinting eyes

## Definition of Complete

- [x] Functional — ducks spawn, move, can be hit or escaped, rounds advance, win/lose conditions work
- [x] Single Purpose — shoot the ducks
- [x] Mobile Friendly — touch events, tap targets sized correctly, tested at mobile viewport
- [x] Visually Polished — pixel art sprites, animated weather, retro typography
- [x] Published — live GitHub Pages URL, numbered and named

## Stack

Single-file vanilla HTML/CSS/JS. No dependencies, no build step, no frameworks.

-----

*Part of the [AppADay](https://augustineiacopelli.github.io/appaday/) project — one app shipped every day.*
