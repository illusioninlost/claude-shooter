# clod-shooter

A browser-based top-down shooter built with HTML5 Canvas and vanilla JavaScript. No dependencies, no build step — just open the file.

## How to Play

Open `shooter.html` directly in any modern browser.

## Gameplay

You are a white circle with a gun barrel that rotates to face your mouse. Enemies (red circles) spawn from the edges of the screen and charge toward you. Shoot them before they reach you.

**Controls**

| Input | Action |
|-------|--------|
| WASD | Move |
| Mouse | Aim |
| Click / Hold | Shoot |
| ESC | Pause |

**Objective:** Clear all enemies on each level to advance. You have 100 HP — each enemy hit deals 10 damage. Survive all 3 levels to win.

## Levels

| Level | Enemies | Behaviour |
|-------|---------|-----------|
| 1 | 10 | Slow, straight charge |
| 2 | 20 | Medium speed |
| 3 | 35 | Fast + random strafing |

## Powerups

Glowing pickups spawn randomly on the field during play. Walk over them to collect.

| Powerup | Effect | Duration |
|---------|--------|----------|
| RAPID (orange) | 3× fire rate | 8s |
| SPEED (cyan) | 1.65× movement speed | 8s |
| x3 (green) | Triple spread shot | 8s |

Active powerup timers are shown as countdown bars in the bottom-left corner.

## Options

Accessible from the main menu or pause screen (ESC):
- **Sound** — toggle on/off
- **Difficulty** — Easy (0.7×), Normal (1×), Hard (1.4×) — scales enemy speed and spawn rate
