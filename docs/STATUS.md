# Project status

[Documentation index](README.md)

**Phase** — Design and research

**Current milestone** — Agree on the starting power model and define the smallest playable sequence around one testable question. Godot development requires explicit approval.

## Confirmed direction

- Original single-player, third-person superhero sandbox with Saints Row IV as the main gameplay reference. Satisfying superhuman movement and combat drive play in a persistent city.
- The player starts as an inexperienced superhuman in a contemporary city with established heroes, villains, and institutions that have adapted to supers. The player can act heroically, criminally, or somewhere in between.
- The sandbox drives progression. Players can pursue goals while ignoring the story. Conventional weapons, vehicles, and human-scale activities have distinct roles alongside powers. Character, power, vehicle, and property customization are design priorities.
- PC is the primary platform. Steam Deck usability and performance matter. Keep the scope achievable for solo development.

### Starting power baseline

Supers have human-scale physical capabilities by default. A power can create a specific exception. Direct street-to-rooftop shortcuts belong to powers that enable them and distinguish mobility specialists. This keeps ordinary routes and vehicles useful and gives each specialty a distinct way through the same block.

Starting powers should feel like Witcher Signs in scale and immediate utility. Examples include a short-range fire blast for a pyro, a brief burst of speed for a speedster, and a jump onto a one-story roof for a mobility specialist. These illustrate the starting scale. The power roster and exact mechanics remain open.

## Provisional direction

- A compact, reactive city with a small cast of recognizable supers, systemic encounters and progression, and styling that draws selectively on Silent Hill. Godot is the intended engine.
- Optional or sandbox-integrated narrative. Factions, businesses, property, reputation, and relationships are candidates for long-term progression.
- Environmental damage should create gameplay consequences such as new routes or changed cover. Scope, persistence, and repair are open.

## Open decisions

- **Next task** — Decide how much a starting specialty can broaden over progression. Compare deepening one specialty, pairing a defining specialty with a few secondary abilities, and acquiring multiple specialties that can be swapped or combined. Use the same city-block encounter to compare routes, the role of ordinary tools, and the cost of supporting combinations. Then agree on the first prototype question and its success criteria.
- Decide how established supers act independently, what public reputation tracks, and how central factions and territory are. City layout, tone, narrative structure, and the complete 1.0 experience remain open.

## Deferred

- Roguelite structure, universal building collapse, and citywide persistent damage. Revisit destruction scale after assessing local effects on navigation, activities, and Steam Deck frame times.

## Known risks and issues

- Unrestricted powered travel could crowd out everyday driving. Broad power sets and widespread destruction multiply the traversal, encounter, and NPC states that need to work together.
- There is no playable build or measured performance budget yet.

**Last consistency audit** — Initial repository baseline `de93f391e386ba975e78aa74ec1ba732a856675f`. The baseline contained only the root README.
