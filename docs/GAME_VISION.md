# Game vision — confirmed user questions and answers

Read before designing or changing this game. Recorded from the October 16, 2026 conversation; uploaded October 18. These are requirements, not completed features.

## Core experience
1. What do you love about the pack? Always something different/new to do, a fun grind, and constant meaningful progression.
2. Which version? Society Sunlit Valley 4.1.5A; keep that version as the reference.
3. Change frustrating mechanics? Bring problems and proposed solutions to the user first. Preserve earned tool/weapon upgrades; the user likes having to upgrade rather than simply craft a stone sword.
4. First ten minutes? Not independently specified. Research source starting progression and propose any necessary Roblox onboarding.
5. Starting items, quests, unlocks, recipes and prices? Match the pack as closely as possible. Development supplies are temporary shortcuts.
6. Main activity? Players choose which part of the game to master; preserve multiple worthwhile progression paths.
7. Difficulty? Same as the pack.

## World and presentation
8. Layout? Original blocky Roblox landscape with Minecraft-like random generation. A menu must let players create worlds and return to saved worlds.
9. Essential locations? All source locations.
10. Travel? Walking and running/sprinting like Minecraft. Research source travel progression instead of inventing arbitrary shortcuts.
11. Building? Whatever adapts best to Roblox; players should be free to shape terrain. Exact controls and terrain representation remain to be designed.
12. Character? Regular Roblox avatars. Slower, grounded Minecraft-like walking and separate sprinting (explicitly confirmed in follow-up). Numeric speeds require playtesting.
13. Visual references? The modpack first; 3D Pokemon and Palworld also fit. Ark Survival Evolved is somewhat too serious. Keep the world blocky/stylized, with some realistic sky, lighting and shader-like effects.
14. Animals? All source animals. Preserve the earlier approved cute, less-blocky rounded-animal adaptation.

## Multiplayer and simulation
15. Farm permissions and friends? Use the installed pack chunk-claim/force-load mod as the reference. Research the actual mod/configuration, not assumed defaults. Teams can share claims just like the pack. Fixed prototype farm slots are not the final claim design.
16. Shared world/resource changes? Follow Minecraft/the pack; research terrain persistence, resources, regeneration and loaded chunks.
17. Offline behavior? The creator must be in the world. Follow-up: when the world creator leaves, everyone disconnects and simulation stops. No offline crop growth is intended. Research additional claim-owner/force-load details rather than silently assuming they equal host presence. Save safely before closing.
18. Time, sleep and seasons? Exactly as Minecraft/the modpack; trace multiplayer sleep rules.
19. Combat, death and losses? Keep the pack rules.

## Devices, release and monetization
20. Devices? PC, phone/tablet and console; research current Roblox device/input constraints.
21. Release? Small/private testing until the complete game is ready for launch. Do not describe partial builds as full parity.
22. Revenue? Add an extra villager selling OP items for Robux. Follow-up explicitly permits skipping normal upgrades. Specific products, prices, repeatability and purchase persistence are NOT decided. Propose useful products; research platform requirements before implementing charges. This is a requested exception to source parity.
23. Name/music? Decide the title later. Chill, calming, Minecraft-like musical mood using original or licensed audio.
24. Avoid? Excessive realism, overly serious visuals and fast typical Roblox movement. Realism in sky/lighting is acceptable within the stylized look.

## Follow-up answers
- Creator leaves: everyone disconnects.
- Inventory, money and skills: separate per world, like separate Minecraft saves.
- Access: let players choose public OR invite-only. Default visibility is undecided.
- Movement: yes, Minecraft-like walking/sprinting pace.
- Paid items may skip upgrades: yes; exact products/prices remain proposals.
- Seeds: allow chosen seeds; the same seed should reproduce the landscape under the same generator version. Preserve player terrain edits and plan generator versioning.
- Teams/shared claims: yes, just like the pack.

## Questions still needing research or user decisions
- Exact claim/team/force-load rules and conflicts with creator-hosted simulation.
- World visibility default, player/world limits, reconnect/crash grace periods and ownership transfer.
- Paid catalog/pricing, teammate effects and account-level purchase entitlements versus per-world progression.
- First-session sequence, terrain controls, movement tuning and any necessary departures from source behavior.

## Instructions for BOTH Codex and Claude Code
Read this document before any design task. Target a 1:1 gameplay recreation of the installed modded experience, with the user-approved Roblox adaptations above. Research assigned systems using installed scripts/configs/quests, official Roblox documentation and relevant accessible developer videos/transcripts; record evidence and gaps, never pretend to have watched unavailable material. Ask the user about important unresolved mechanics or appearance, presenting source behavior, the problem, options and a proposed solution. Continue independent work while waiting.

Proposed split: Codex handles server gameplay/progression/economy/ownership/saves/tests; Claude Code handles client UI/controls/animals/animation/environment presentation. Agree assignments before editing, use separate task branches/checkouts, and coordinate shared-file/interface changes. This split is a proposal until acknowledged by both.

Review each other’s meaningful changes before merge. Each finding needs file/behavior, evidence/reproduction, player impact/severity, proposed fix and verification. Authors respond with fixes or evidence; reviewers recheck revisions. Record assignments, findings, responses and handoffs in the repository/PRs. Do not claim a review or conversation happened unless it did. Keep unresolved serious defects visible. Work toward the fastest reliable, polished delivery; do not sacrifice saves, ownership or source fidelity to claim completion. Publishing still requires the user’s instruction.

## Prototype status
V4 is incomplete: fixed terrain/farm slots, development starter supplies and partial progression. Random saved worlds, editable terrain, full claims/force-loading, all locations/species and complete parity remain unfinished. The last reported V4 Studio tests passed 25/25 on October 15; this is historical evidence, not release certification. Live saves and the full new-shop walkthrough remain unverified. Game source/place files have not yet been uploaded to this repository.
