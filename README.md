The Original

**The Original** is an Unreal Engine 5 action-survival game in development. Set in a dangerous forest overrun by skeletons, it follows a lone fighter through hostile patrols, a signal-device objective, escalating enemy waves, and a final bare-knuckle encounter with a powerful boss.

The game aims to combine responsive third-person combat with a cinematic sense of escalation: tense encounters build into an alarm-triggered horde, then give way to a personal, close-range boss fight. Its visual direction pairs a moody forest setting with restrained, readable gameplay UI and distinctive character and weapon animations.

## Project at a Glance

| | |
|---|---|
| **Project name** | The Original |
| **Engine** | Unreal Engine 5 |
| **Genre** | Action survival |
| **Setting** | A forest mission with patrol encounters, a signal objective, enemy hordes, and a boss arena |
| **Status** | In development |

## Gameplay Experience

The player advances through a forest mission, confronting skeleton patrols and clearing the route to a signal device. Collecting the device triggers an alarm and brings the horde into the fight. The action escalates over three rounds before the player faces a boss in a weapon-restricted, hand-to-hand encounter.

| Stage | Gameplay focus |
|---|---|
| **Patrols** | Move through the mission, locate patrols, and use melee combat and the silenced pistol to defeat them. The signal device stays unavailable until the patrols are cleared. |
| **Signal device** | Collecting the device advances the mission, sounds the alarm, and equips the Mac-10. |
| **Horde** | Fight waves designed for **50 enemies in Round 1**, **100 in Round 2**, and **150 in Round 3**. The intended pacing brings enemies in quickly enough to feel like a charging horde. |
| **Boss** | Face a powerful skeleton boss in a bare-knuckle fight. Guns are unavailable during this encounter, so the player must block, move, and find openings to counterattack. |

## Combat and Weapons

Combat is built around movement, timing, and clear feedback. The player can attack while unarmed, block while holding the assigned block control, and use firearms where the mission allows them. Enemies can pressure the player in groups, while the boss occasionally blocks to create a more deliberate exchange.

| Weapon or system | Design direction |
|---|---|
| **Silenced pistol** | A precise firearm for the patrol portion of the mission, with aiming feedback, reload behavior, and a visible bullet tracer effect. |
| **Mac-10** | Unlocked and equipped immediately when the signal device is collected. It fires automatically while the fire input is held, uses a **45-round magazine**, and has unlimited reserve ammunition. |
| **Mac-10 damage** | Ordinary enemies are intended to take four successful Mac-10 hits to defeat. Tracers appear intermittently in a regular pattern rather than on every bullet. |
| **Boss encounter** | Both the pistol and Mac-10 are unavailable during the boss fight. The encounter focuses on melee attacks, blocks, and counterattacks. |

## Presentation and HUD

The visual direction uses a moody forest atmosphere and a minimal interface that keeps attention on the action. Gameplay UI is designed to communicate essential information without covering important combat.

- A compact objective indicator sits in the top-left, with a small golden diamond that gently pulses beside the objective text.
- The player health display uses a subtle, square-cornered bar with hit points and a small heart icon. A boss health bar follows its own visual reference.
- The weapon HUD shows the equipped gun and ammunition information, with the Mac-10 replacing the pistol display after the signal pickup.
- The crosshair keeps its red-target feedback and shrinks while aiming.
- Wave-completion messaging identifies each completed non-final wave; the final wave has no completion message.
- The main menu's first screen stays clear. Background blur is reserved for the New Game screen.

## Development Focus

Development work is centered on making the player, enemies, weapons, animations, and mission progression work together reliably.

| Area | Focus |
|---|---|
| **Player character** | Integrate the MetaHuman player with the project's existing locomotion, camera, input, combat, and weapon systems. |
| **Enemy characters** | Use the skeleton character setup across patrol, horde, and boss enemies while preserving each enemy type's movement, combat, and reactions. |
| **Animation** | Check locomotion, combat, aim, reload, hit-reaction, and death animations on their target characters; retarget only when compatibility problems require it. |
| **Weapons and audio** | Refine pickup and equip flow, automatic fire, reload timing, weapon sounds, music, and combat audio balance. |
| **Mission flow** | Connect patrol clearance, signal-device collection, alarm, wave progression, and the boss encounter into a consistent sequence. |
| **Performance and polish** | Investigate texture clarity and streaming behavior, improve presentation, and preserve existing gameplay features while tuning the experience. |

## Project Status

**The Original is a work in progress.** The features and systems described here represent the project's current design direction and may change as development continues. This repository documents and develops the game; it is not a claim that every listed feature is complete.
