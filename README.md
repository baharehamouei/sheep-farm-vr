# Sheep Farm — Interactive VR Game
**Course:** Virtual Reality · Bauhaus-Universität Weimar  
**Timeline:** February–April 2025  
**Tools:** Unity · Oculus Quest 2 · C# · XR Interaction Toolkit · NavMesh  
**Role:** VR Developer & Interaction Designer  
**Team:** Bahareh Amouei & Pamoda Rodrigo  
**Status:** Completed ✅

---

## Overview

Sheep Farm is an interactive VR game developed as part of the Virtual 
Reality coursework at Bauhaus-Universität Weimar. The game places the 
player in a peaceful farm environment with one goal: find the lost sheep 
and guide them back to their enclosure before time runs out.

Designing in VR feels fundamentally different from traditional interface 
design. Instead of thinking in screens and buttons, you think in space, 
movement, and embodied interaction — how everything connects and feels 
as one coherent experience. This project was built around that challenge.

---

## Screenshots

![Preview](Preview.png)


---

## Gameplay Concept

The core idea was simple: guide lost sheep back to safety. But making 
this feel natural and intuitive in VR required careful thinking about 
interaction design and user presence.

**Core mechanics designed:**

**Luring System**
Players pick up apples to attract nearby sheep. When a sheep detects 
the apple, it switches from wandering behavior to following the player — 
creating a clear, satisfying interaction loop that feels natural in 3D space.

**Scoring System**
Each sheep safely returned to the pen increases the player's score, 
providing continuous feedback and a sense of meaningful progress 
throughout the experience.

**Environmental Risks**
Poisonous plants scattered across the farm reduce the score on contact, 
introducing spatial challenge and encouraging players to develop 
better environmental awareness and decision-making.

---

## Technical Approach

One of our main goals was to make the environment feel responsive 
and alive rather than scripted and static.

**NavMesh Pathfinding**
Sheep navigate the environment dynamically using Unity's NavMesh system. 
Each sheep has its own state-based behavior: wandering, detecting the 
player, following, and returning — creating believable, lifelike movement.

**State-Based AI Behavior**
We implemented a finite state machine for sheep AI, allowing smooth 
transitions between behavioral states based on environmental triggers 
such as player proximity and apple detection.

**XR Interaction Toolkit**
Core player interactions — grabbing apples, teleportation, and spatial 
navigation — were built using Unity's XR Interaction Toolkit, ensuring 
compatibility and stability on the Oculus Quest 2 hardware.

**Continuous Iteration**
Interactions were tuned repeatedly throughout development based on 
informal playtesting, adjusting detection radii, movement speeds, 
and feedback timing to make behaviors feel natural and responsive.

---

## Design Process

Our design process centered on user-centered thinking from the start. 
We began with a concept focused on interaction and environmental 
immersion, identifying key gameplay elements and user goals early. 
From there we built a basic prototype, experimenting with object 
manipulation, scene design, and player movement.

We applied iterative design throughout — testing usability of navigation, 
clarity of tasks, and responsiveness of interactions at each stage. 
Each round of informal testing revealed new friction points that we 
addressed before moving forward. The result was a game that remained 
intuitive and immersive from the first interaction to the last.

---

## Designing for Presence

A key challenge in VR is maintaining immersion without overwhelming 
the user. We prioritized:
- Keeping interactions simple and discoverable without tutorials
- Using spatial audio and visual feedback instead of UI overlays
- Ensuring smooth locomotion to minimize motion discomfort
- Designing the environment to guide attention naturally

---

## Challenges

- Designing intuitive interactions in 3D space without traditional UI
- Fine-tuning NavMesh AI for lifelike and responsive sheep movement
- Balancing immersion with performance on standalone Oculus Quest 2 hardware
- Integrating spatial UI and feedback without breaking user presence
- Iterating on grab mechanics to feel natural across different hand sizes

---

## What I Learned

This project deepened my understanding of spatial UX and user-centered 
interaction design in XR environments. I strengthened my skills in 
Unity and C#, learned to think critically about how users perceive 
and navigate immersive 3D spaces, and gained hands-on experience 
creating believable AI-driven behavior. Most importantly, it reinforced 
that good VR design is invisible — when it works, users stop thinking 
about the interface and just experience the world.

---


> The full Unity project (Assets, Packages, Scripts) is available 
> on request due to file size limitations.

---

## About Me

I am Bahareh Amouei, a Master's student in Human-Computer Interaction 
at Bauhaus-Universität Weimar, Germany. My work spans UX research, 
spatial interaction design, and data analytics.

[LinkedIn](https://www.linkedin.com/in/bahareh-amouei/)
