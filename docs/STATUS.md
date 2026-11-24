# Project status

[Documentation index](README.md)

**Phase** — Design and research

**Current milestone** — Agree on the starting power model and define the smallest playable sequence around one testable question. Godot development requires explicit approval.

## Confirmed direction

- Original single-player, third-person superhero sandbox with Saints Row IV as the main gameplay reference. Satisfying superhuman movement and combat drive play in a persistent city.
- The player starts as an inexperienced superhuman in a contemporary city with established heroes, villains, and institutions that have adapted to supers. The player can act heroically, criminally, or somewhere in between.
- The sandbox drives progression. Players can pursue goals while ignoring the story. Human-scale activities have distinct roles alongside powers. Character, power, vehicle, and property customization are design priorities.
- Story serves the sandbox through milestones and major mechanic introductions. When practical, teach mechanics through a story situation or a discovery the player can act on.
- PC is the primary platform. Steam Deck usability and performance matter. Keep the scope achievable for solo development.
- The [power progression decisions](POWER-PROGRESSION.md#confirmed) cover the starting baseline, character XP and power points, the speedster capstone, and the roles of guns and cars.

## Provisional direction

- A compact, reactive city with a small cast of recognizable supers, systemic encounters and progression, and styling that draws selectively on Silent Hill. Godot is the intended engine.
- Optional or sandbox-integrated narrative. Factions, businesses, property, reputation, and relationships are candidates for long-term progression.
- Environmental damage should create gameplay consequences such as new routes or changed cover. Scope, persistence, and repair are open.

## Opening job

Use both driving and on-foot play before the first power purchase. The proposed tutorial is one vehicle recovery job with three beats.

1. Drive to the site and learn basic driving, navigation, and exploration.
2. Reach the target vehicle using stealth or gun combat. Introduce both options when the player arrives.
3. Drive the vehicle back and experience a police pursuit that introduces the wanted system.

**Confirmed** — Every approach leads to a pursuit on the return drive. The player can reach the car undetected, and the unauthorized removal is reported as it leaves the site.

**Provisional** — Set the job at an impound lot or a comparable supervised facility where staff would report the vehicle removal to police.

**Provisional** — A short cinematic establishes supers as a familiar part of the city, may introduce a widely known hero and villain, and sets up the player's initial role. A separate explanatory event accompanies the first level-up and first power point, following the [human-scale opening](POWER-PROGRESSION.md#confirmed). Its cause, setting, and connection to a longer story are open. Waking up at a government lab is one candidate.

## Open decisions

- **Next task** — Agree on the target number of [power paths for 1.0](POWER-PROGRESSION.md#open), then choose the roster and the stat that scales each path. Use those choices to define starter interactions, the first-power reveal, and the smallest playable opening sequence.
- Decide how established supers act independently, what public reputation tracks, and how central factions and territory are. City layout, tone, narrative structure, and the complete 1.0 experience remain open.
- Multiplayer is a possible addition. Its format and release scope are open.

## Deferred

- Roguelite structure, universal building collapse, and citywide persistent damage. Revisit destruction scale after assessing local effects on navigation, activities, and Steam Deck frame times.

## Known risks and issues

- Unrestricted powered travel could crowd out everyday driving. Broad power sets and widespread destruction multiply the traversal, encounter, and NPC states that need to work together.
- There is no playable build or measured performance budget yet.

**Last consistency audit** — Initial repository baseline `de93f391e386ba975e78aa74ec1ba732a856675f`. The baseline contained only the root README.
