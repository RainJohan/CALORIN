# CALORIN
Repository of Programming 2 Finals Project

**Programmers:** Lore Ann Custodio and Rain Johan Ayerass

# Veil of Curses — Jujutsu Kaisen Tower Defense

## Game Title
**Veil of Curses — Jujutsu Kaisen Tower Defense**

## Game Description
**Veil of Curses** is a Jujutsu Kaisen-inspired tower defense game set in the world of cursed energy and sorcery. In this game, players place powerful sorcerers on a grid to defend the barrier from waves of dangerous curses.

The player collects **Cursed Energy (CE)** and uses it to deploy sorcerers such as **Shoko, Yuji, Todo, Gojo, and Sukuna**. Each character has a unique role in battle. Some generate cursed energy, some attack automatically, some defend the field, and some use powerful cursed techniques.

As the game progresses, curses become more difficult and appear in larger numbers, so players must manage resources well, place units strategically, and survive each wave. The game now also includes **lane events**, **Gojo’s Domain Expansion**, **volume control**, and **speed control** to make gameplay more dynamic and interactive.

## Setup Instructions (How to Run the Code)

### Requirements
- Any modern web browser such as:
  - Google Chrome
  - Microsoft Edge
  - Mozilla Firefox

### How to Run
1. Download or clone the project files.
2. Make sure the main game file is named **`index.html`**.
3. Open the **`index.html`** file in your browser.
4. Wait for the game to load.
5. Click anywhere in the game to allow the audio/music to start if needed.

### Optional
You may also run it using **Live Server** in Visual Studio Code for a smoother experience.

## List of Controls

### Mouse Controls
- **Left Click on a sorcerer card** → Select a sorcerer
- **Left Click on the grid** → Place the selected sorcerer
- **Left Click on CE orbs** → Collect Cursed Energy
- **Left Click with Seal ON selected** → Remove a placed sorcerer  
  *(Click again to turn it off so you do not accidentally remove your sorcerers.)*
- **Left Click on Gojo’s small DOM button** → Activate Gojo’s Domain Expansion when available

### Buttons / Controls
- **⏸ Pause** → Pause or resume the game
- **↺ Reset Exorcism** → Restart the game from the beginning
- **Volume Slider** → Adjust the music, sound effects, and voicelines volume
- **− / + Speed Control** → Change the game speed from slower to faster
- **← Menu** → Return to the main menu

## Gameplay Actions
- Select a sorcerer first, then click a tile to place them.
- Manage **Cursed Energy (CE)** because it is needed to deploy units.
- Defend the barrier and do not let the curses pass the left side.
- Survive the opening phase and the incoming waves.
- Use each sorcerer according to their role for better strategy.
- Use **Gojo’s Domain Expansion** wisely because it costs a lot of CE and has a long cooldown.

## Sorcerers and Roles
- **Shoko** — Generates Cursed Energy over time
- **Yuji** — Auto-attacking sorcerer
- **Todo** — Defensive unit with high health
- **Gojo** — Auto-attacking sorcerer with normal shots and a knockback shot cycle
- **Sukuna** — Powerful unit with a destructive cursed technique

## New Features
- **Gojo’s Domain Expansion**
  - Freezes all curses on the whole field for **10 seconds**
  - Costs **320 CE**
  - Has a **2-minute cooldown**
  - Activated using the small **DOM** button on Gojo’s card

- **Lane Events**
  - Starting from **Wave 4**, random lane events may happen:
    - **Cursed Fog** → Sorcerers in that lane attack slower
    - **Barrier Crack** → Curses in that lane move faster

- **More Waves**
  - The game now has **8 waves**
  - The longer the game goes, the harder it becomes

- **Speed Control**
  - Players can increase or decrease the game speed using **− / +**
  - Speed can go up to **5.0x**

- **Volume Control**
  - Music, sound effects, and voicelines can now be adjusted using the volume slider

## Special Notes
- **Shoko, Yuji, Todo, and Gojo** have cooldowns before they can be placed again.
- **Sukuna** has a much longer cooldown compared to the others.
- Sorcerers attack automatically once curses appear on the field.
- Audio includes background music, sound effects, and character voicelines.
- When the player leaves the tab, the music pauses, and when the player returns, it continues.
- The game becomes harder as waves progress because curses spawn in larger and less predictable groups.

## Objective
Protect the barrier by placing sorcerers wisely, collecting cursed energy, and defeating the curses before they overwhelm your defenses.

## Beginner Tip Note
- Start by placing **Shoko** early so you can generate more Cursed Energy.
- Use **Yuji** or **Gojo** first for steady automatic attacks.
- Place **Todo** in important lanes to block curses longer.
- Save **Sukuna** for dangerous situations or heavy enemy groups because of his long cooldown.
- Use **Gojo’s Domain Expansion** only when many curses are already on the field.
- Do not spend all your CE at once. Try to balance attacking, defending, and saving for stronger units.

**GOOD LUCK**

Game Screenshots:

![image Alt](https://github.com/RainJohan/CALORIN/blob/1f4221e01b23058339461af5a0ff62d2122bd89d/Main%20Menu.png)

![image Alt](https://github.com/RainJohan/CALORIN/blob/c7edac794dab004380ff32888851b6045a652236/HTP%20Menu.png)

![image Alt](https://github.com/RainJohan/CALORIN/blob/c7edac794dab004380ff32888851b6045a652236/Main%20Game.png)
