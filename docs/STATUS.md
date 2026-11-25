# Project status

[Documentation index](README.md)

**Phase** — Design and research

**Current milestone** — Define the smallest playable free-roam block for the human-scale GTA-lite sandbox. Godot development requires explicit approval.

## Confirmed direction

- Original single-player, third-person superhero sandbox with Saints Row IV as the main gameplay reference. Satisfying superhuman movement and combat drive play in a persistent city.
- The player starts as an inexperienced superhuman in a contemporary city with established heroes, villains, and institutions that have adapted to supers. The player can act heroically, criminally, or somewhere in between.
- The sandbox drives progression. Players can pursue goals while ignoring the story. Human-scale activities have distinct roles alongside powers. Character, power, and vehicle customization are design priorities.
- Favor believable physical behavior and city reactions across the sandbox. Driving should feel weighty and have practical uses throughout progression. Keep routine upkeep simple and use realism where it improves feedback or choices.
- Story serves the sandbox through milestones and major mechanic introductions. When practical, teach mechanics through a story situation or a discovery the player can act on.
- PC is the primary platform. Steam Deck usability and performance matter. Keep the scope achievable for solo development.
- The [power progression decisions](POWER-PROGRESSION.md#confirmed) cover the starting baseline, character XP and power points, the speedster capstone, and the roles of guns and cars.

## Provisional direction

- A compact, reactive city with a small cast of recognizable supers, systemic encounters and progression, and styling that draws selectively on Silent Hill. Godot is the intended engine.
- Optional or sandbox-integrated narrative. Reputation and relationships are candidates for long-term progression.
- Environmental damage should create gameplay consequences such as new routes or changed cover. Scope, persistence, and repair are open.

## Immediate scope

**Confirmed** — Build a working, fun, human-scale GTA-lite sandbox first. The first playable is a free-roam block. Ordinary movement, driving, human-scale encounters, and city responses should work together so players can discover situations and see the consequences of their choices.

**Provisional** — A repeatable incident can test the transitions between on-foot play, driving, and a police response. Evaluate how ordinary vehicles feel and how clearly the city reacts. Choose the initial destruction test once the core loop is defined.

### Baseline candidates

**Confirmed** — Replace all assets bundled with any adopted baseline. Preserve the copyright and license notices for reused code and include applicable notices for retained dependencies.

- [Night Drop's Harbor scene](https://github.com/alexbieber/GTA-mini/tree/cfb1f29586886704f44293ff196567bb53e6164d) is a candidate source for MIT-licensed vehicle entry and exit, incident reporting, and pursuit logic. Its Harbor scene launched in Godot 4.7.2 headless, and its game integration test passed 14 checks. The car controller scripts motion with a character body.
- [Godot Easy Vehicle Physics](https://github.com/frepiso/Godot-v4.x-Easy-Vehicle-Physics-addon/tree/38fd296aaa199211f9ee21a2d5cc6570c9a3a4cf) is a candidate for the player car. Its MIT-licensed controller uses a rigid body with raycast suspension and tunable assists. The demo launched on 4.7.2 headless, with a resource cleanup warning at exit. Driving feel, controller integration, and the recommended 120 Hz physics tick need evaluation on the target hardware.
- [Open Theft Auto](https://github.com/mehulkapadia5/open-theft-auto/tree/b37e7f3070501dd90353c250e9ad90dffdf4c8b2) is a larger Godot 4.7 reference. Its MIT-licensed code uses scripted vehicle movement and separate asset licenses. The main scene launched in 4.7.2 headless.

### Proposed mechanics

Revisit these proposals once the immediate sandbox scope is defined.

- Faction mechanics, hero or criminal empire-building, and map and territory control.
- Buying and customizing homes and businesses.
- Recurring rivals inspired by the Nemesis system, with personal histories, changes in behavior, and rematches. The specific design and its overlap with patent claims are open.

## Opening job

Use both driving and on-foot play before the first power purchase. The proposed tutorial is one vehicle recovery job with three beats.

1. Drive to the site and learn basic driving, navigation, and exploration.
2. Reach the target vehicle using stealth or gun combat. Introduce both options when the player arrives.
3. Drive the vehicle back and experience a police pursuit that introduces the wanted system.

**Confirmed** — Every approach leads to a pursuit on the return drive. The player can reach the car undetected, and the unauthorized removal is reported as it leaves the site.

**Provisional** — Set the job at an impound lot or a comparable supervised facility where staff would report the vehicle removal to police.

**Provisional** — A short cinematic establishes supers as a familiar part of the city, may introduce a widely known hero and villain, and sets up the player's initial role. A separate explanatory event accompanies the first level-up and first power point, following the [human-scale opening](POWER-PROGRESSION.md#confirmed). Its cause, setting, and connection to a longer story are open. Waking up at a government lab is one candidate.

## Open decisions

- **Next task** — Agree on the first repeatable incident in the block and the behavior it should test. Define what playtest result would justify expanding it. Use the [power fantasies](POWER-PROGRESSION.md#power-fantasy-candidates) and their combinations to guide the later 1.0 roster, scaling stats, and first-power reveal.
- Decide how established supers act independently and what public reputation tracks. City layout, tone, narrative structure, and the complete 1.0 experience remain open.
- Multiplayer is a possible addition. Its format and release scope are open.

## Deferred

- Roguelite structure, universal building collapse, and citywide persistent damage. Revisit destruction scale after assessing local effects on navigation, activities, and Steam Deck frame times.

## Known risks and issues

- Unrestricted powered travel could crowd out everyday driving. Broad power sets and widespread destruction multiply the traversal, encounter, and NPC states that need to work together.
- There is no playable build or measured performance budget yet.

**Last consistency audit** — 2026-11-24 at `b95ad4ade18345df5942dab34b5ef0948caac63d`. Reviewed project docs, internal links, dependency scope, and consistency across design decisions.
