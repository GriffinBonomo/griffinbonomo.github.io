---
title: "AirStrafer"
date: 2025-12-21 12:00:00 +0000
pin: true
categories: [portfolio]
tags: [project, gamedev]
---
## Overview
AirStrafer (working title) is a Quake and Counter-Strike inspired first-person shooter developed in the Godot engine. It's stealth game with a strong emphasis on fear and intimidation in combat, as well as authentic Source-like movement such as bunnyhopping. 

## My Inspiration
I was heavily inspired by the original 1996 Quake, Half Life speedruns, and bunnyhop servers in the various Counter-Strike games. I wanted to combine immersive simulation mechanics of Dishonored with a completely different movement system.

## What I Built
AirStrafer is currently in early development and is subject to change in just about every way.

### Authentic Counter-Strike Recoil and Weapon System
I've implemented pattern-based recoil for all the weapons in my game, following a predictable pattern that the player can learn and account for over time. Patterns are easily adjustable, and custom to every weapon in the game.

On top of the recoil system, a bloom/spread system was implemented to emulate the accuracy penalty of moving in the Counter-Strike games.

### Enemies / Enemy AI
Enemies in AirStrafer use fear as a core mechanic. Their current fear value impacts their accuracy, behavior and general predictability. The AI system for enemies was developed from the ground up for this purpose. Enemies in game can communicate with each other, allowing the player to sow fear through their ranks.


## Technical Overview
Airstrafer is developed using component based design, to allow for increased flexibility.

I use a Kanban board to manage my issues and tasks. Issues in GitHub are automatically imported and added to the board, allowing me to focus on small and manageable tasks.

The game uses the Forward+ renderer to enable more advanced graphical effects in the future, such as complex shaders and advanced lighting.

All components are written in GDScript, Godot's native scripting language and make heavy use of signals.

## Design Decisions

### Godot Instead of Unity
I chose Godot instead of the Unity engine, mostly because I found it very welcoming as a beginner to game development. It was simple, and most importantly, VERY lightweight. It being a young, evolving engine, has forced me to create my own systems that might be standard in other engines like Unreal or Unity. 

It's been really enlightening, and I've learned a lot about the inner workings of game engines, particularly the asset pipeline and terrain creation. I'm glad in a way that I have to work more for these features, so I don't take them for granted in the future.

---

### Composition Over Inheritance 
Something I learned early on in Godot is that composition is the way to go. Especially as a solo game dev, time is precious and component based  design allows for reusable pieces that you can import into other projects.

Composition has another purpose, which is that it makes for really intuitive design once you get used to it. You can just drag in the components you want for an enemy, and they mostly just work on their own.

### Stimuli and Enemy Memory
Something that I decided on early into development was to create realistic enemies, with their own memories. I never liked how npcs in video games could frequently alert everyone nearby without actually communicating. I implemented a memory system for enemies and explicitly require they meet up in person to transmit what they've observed in the world.

The big picture goal of this is to encourage the player to engage in isolated attacks, allowing fear to spread naturally to all the enemies in the level. 

This is a mechanic that I've never really seen before, and I thought it would be an interesting challenge to force the player to engage with the level in a unique way.

## Problems I Encountered
Naturally, by using the Godot engine which is new and changing every month, I ran into a TON of issues.

---

### Lack of Good Documentation
While the actual Godot docs are pretty good, it's really tough to find accurate and up-to-date tutorials on stuff like importing level kits from Blender, animation retargeting, ragdoll physics, and much more.

A lot of features which were just built-in for engines like Unity and Unreal, required days of troubleshooting and custom solutions. 

I remember in particular writing my own import script for level kits, to separate meshes into their own scenes with automated collision shapes. It's a staple feature of other engines but in Godot, that had to be done by hand.
### Learning to Use Composition and Ditching Inheritance
Like many programmers, inheritance is our go-to for organizing data in our programs, but it doesn't work so well in game development. 

It's really easy to get caught up in who inherits what and whether a door is technically the same type of entity as a bullet. Composition fixes that by using components to define WHAT something is instead of interfaces.

This is not without its problems though, it was really tough to change how I think about organizing data and sometimes you just get stumped, wondering how you're supposed to know what behavior an object has without interfaces and inheritance. 
## Goals for the Future
AirStrafer is in VERY early development, and predictably, developing the game as a full-time student has been challenging. Progress is slow but steady and I hope to have the following features implemented in the near future.

- AI System including enemy communication and fear
- An overhauled movement implementation to closer match Quake's
- A fully textured and completed first level, to show off all the mechanics at once.

