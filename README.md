# Minesweeper - Webgame
#### Author: Bocaletto Luca

[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-E34F26?logo=html5)](https://www.w3.org/html/)  
[![Made with CSS3](https://img.shields.io/badge/Made%20with-CSS3-1572B6?logo=css3)](https://www.w3.org/Style/CSS/) 
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E?logo=javascript)](https://developer.mozilla.org/docs/Web/JavaScript)  
[![GitHub followers](https://img.shields.io/github/followers/bocaletto-luca?label=Follow&style=social)](https://github.com/bocaletto-luca)

[![Test Online](https://img.shields.io/badge/Test%20Online-Click%20Here-brightgreen?style=for-the-badge)](https://bocaletto-luca.github.io/Mine-Sweeper/)

**Minesweeper 2.0** is a modern, fully responsive, single-page web version of the classic Minesweeper game. This version not only captures the nostalgic charm of the original game but also adds modern functionalities and polish:

- **Difficulty Selection:** Choose among Easy, Medium, and Hard, with different grid sizes and mine counts.
- **Timer & Best Time Record:** The game starts a timer at the beginning of each game. When the game ends, your time is compared with your best time (stored per difficulty in localStorage). You can also reset your best time.
- **Animated Reveal & Flood Fill:** Cells reveal with a smooth fade-in animation, and empty areas are automatically revealed using a flood-fill algorithm.
- **Flagging System:** Right-click (or long-press on touch devices) to place flags on suspected cells.
- **Help Modal:** A built-in Help modal explains the game rules and controls.
- **Responsive & Modern Design:** Designed with a sleek dark theme and fixed cell dimensions that adapt gracefully across desktops, tablets, and smartphones.
- **Classic Game Logic:** When a mine is clicked, all mines are revealed and the game ends. Victory is achieved when all non-mine cells are revealed.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Developer](#developer)

---

## Overview
Minesweeper 2.0 reimagines the classic game for a modern audience. Whether you're playing on a desktop or a mobile device, the game offers responsive design, smooth animations, and useful game enhancements like a timer and best time tracker. The player selects a difficulty level which affects the grid size and mine density:
- **Easy:** 9x9 grid with 10 mines.
- **Medium:** 16x16 grid with 40 mines.
- **Hard:** 30x16 grid with 99 mines.

The objective is simple: reveal all the cells that do not contain mines. A left-click reveals a cell while a right-click (or long-press) toggles a flag. When you inadvertently click on a mine, the game ends by revealing all mine positions. If you reveal every safe cell, you win!

---

## Features
- **Difficulty Selection:** Customize your challenge with three rigorously defined difficulty levels.
- **Smooth Animations:** Cells reveal with a fade-in effect to make gameplay visually appealing.
- **Timer & Best Time:** Your game time is tracked. Best times for each difficulty are stored in localStorage, and you have a button to reset these records.
- **Flagging Mechanism:** Easily mark cells with potential mines using right-click or long-press (on touch devices).
- **Responsive Design:** The grid layout uses CSS Grid to maintain fixed cell sizes across various devices.
- **Help Modal:** Get complete instructions on gameplay, controls, and rules via the Help modal.
- **Classic & Fun:** Enjoy the original Minesweeper logic—with flood fill for empty cells and instant game over upon clicking a mine.

---

## Technologies Used
- **HTML5** – Structure and semantic markup.
- **CSS3** – Styling, responsive design (with CSS Grid and media queries), and animations.
- **JavaScript (ES6)** – Game logic, event handling, timer functionality, and localStorage for best times.

---

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/bocaletto-luca/Mine-Sweeper.git
2. Start Server example Apache2 and open index.hmtl in Web Browser

#### Enjoy Game - By Bocaletto Luca

#### License: GPLv3
