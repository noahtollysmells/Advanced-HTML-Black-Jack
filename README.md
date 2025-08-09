# Advanced Blackjack — Windows 10 Themed, £ Currency, Fully Featured

![Blackjack Banner](https://user-images.githubusercontent.com/yourusername/blackjack-banner.png)  
*A sleek, realistic blackjack game inspired by Windows 10’s blue and grey aesthetic, fully playable in your browser.*

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Live Demo](#live-demo)  
- [Installation](#installation)  
- [How to Play](#how-to-play)  
- [Game Mechanics & Rules](#game-mechanics--rules)  
- [Currency System & Betting](#currency-system--betting)  
- [User Interface & Theme](#user-interface--theme)  
- [Keyboard Shortcuts](#keyboard-shortcuts)  
- [Accessibility & Responsiveness](#accessibility--responsiveness)  
- [Development Details](#development-details)  
- [Planned Enhancements](#planned-enhancements)  
- [Testing & Debugging](#testing--debugging)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

Advanced Blackjack is a browser-based blackjack game built using only **HTML**, **CSS**, and **JavaScript**. It provides a fully featured, immersive blackjack experience designed to run smoothly on any modern desktop or mobile browser.

The game is themed to match the familiar look of Windows 10, combining cool blue tones, black backgrounds, and grey accents for a sleek, professional casino vibe. The currency system uses British Pounds (£), with realistic betting limits and persistent balance stored in your browser.

Perfect for casual players wanting to practice blackjack strategy or developers interested in how a full blackjack engine can be implemented in vanilla web technologies.

---

## Features

- **6 Deck Shoe**: Uses a multi-deck shoe with 6 standard 52-card decks, shuffled each round for realism.  
- **Accurate Blackjack Rules**:  
  - Dealer stands on all 17s including soft 17 (Ace + 6).  
  - Blackjack pays 3:2 immediately unless dealer also has blackjack (push).  
  - Player can split pairs up to 3 hands (maximum two splits).  
  - Double down allowed only on first two cards per hand.  
  - Bust detection and proper score calculation with flexible ace values.  
- **Currency System with Realistic Betting**:  
  - Start with £1000 balance, saved locally in browser storage.  
  - Bet between £1 minimum and £500 maximum or your current balance.  
  - Quick bet chips to add preset amounts.  
  - Top up button to add £500 instantly.  
- **Fully Themed UI**:  
  - Inspired by Windows 10’s blue and grey palette.  
  - Clean card designs with suits and values.  
  - Responsive layout adapting to different screen sizes.  
- **Keyboard Support**: Use keyboard shortcuts (H, S, D, P) to speed up gameplay.  
- **Accessibility**: ARIA labels and semantic HTML for screen readers and keyboard users.  
- **No Dependencies**: Pure vanilla web tech, no frameworks or libraries.  
- **Mobile Friendly**: Works well on phones and tablets with touch controls.  

---

## Live Demo

Try the game instantly by opening the `index.html` file in any modern browser, no server required.  

Feel free to fork and customize the code for your own projects.

---

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/advanced-blackjack.git
cd advanced-blackjack
