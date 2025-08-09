# 🎰 Advanced Blackjack — Windows 10 Themed, £ Currency, Fully Featured 🃏

---

## 🔍 Overview

Advanced Blackjack is a fully featured, browser-based blackjack game built using pure **HTML**, **CSS**, and **JavaScript**. It provides a realistic and immersive blackjack experience without the need to install anything — simply open the `index.html` in any modern browser and play immediately.

This project embraces the sleek Windows 10 color palette, blending deep blacks, various shades of grey, and crisp blue highlights to create a calm yet professional casino atmosphere. The currency system uses British Pounds (£) and maintains your balance persistently using your browser’s `localStorage`, allowing you to keep playing over multiple sessions.

Whether you're a beginner learning blackjack basics, a casual player looking for fun, or a developer interested in card game mechanics and UI design, this project offers an accessible yet deep blackjack simulation.

---

## ✨ Features

- 🃏 **Multi-Deck Shoe:** The game uses six combined standard decks (312 cards) shuffled every round, closely mimicking real casino blackjack rules and preventing easy card counting.

- 🎯 **Authentic Blackjack Rules:**  
  - Dealer hits until reaching 17 or higher and stands on all 17s, including soft 17 (Ace + 6).  
  - Blackjack (Ace plus 10-value card) pays 3:2 immediately unless the dealer also has blackjack, which results in a push.  
  - Players can split pairs up to 3 hands total (two splits maximum).  
  - Doubling down is permitted only on the first two cards, allowing players to increase their bet with one additional card before standing.  
  - Aces are valued at 1 or 11 to prevent busts, with all scoring handled dynamically.

- 💰 **Realistic Currency & Betting System:**  
  - Start with £1000 saved locally in `localStorage`.  
  - Bets range from £1 to £500 or your current balance, whichever is lower.  
  - Quick bet chip buttons allow you to add preset amounts to your bet quickly.  
  - A “Top Up £500” button lets you add more funds anytime.

- 🎨 **Windows 10 Themed User Interface:**  
  - Backgrounds and tables use dark black and deep greys for a calming feel.  
  - Buttons, highlights, and accent colors use Windows 10 signature blue (#0078d7).  
  - Cards show crisp, readable suits and values with white backgrounds and red/black suits.  
  - Layout is responsive and mobile-friendly, adapting seamlessly to smaller screens with larger tap targets.

- ⌨️ **Keyboard Shortcuts:**  
  - Hit: `H`  
  - Stand: `S`  
  - Double Down: `D`  
  - Split: `P`  
  These speed up gameplay for experienced players and help accessibility.

- ♿ **Accessibility Features:**  
  - Proper ARIA roles and labels are applied for screen readers.  
  - Clear focus outlines for keyboard navigation.  
  - Good contrast ratios to meet WCAG AA standards.

- 🚫 **Zero Dependencies:**  
  - Pure vanilla web technologies ensure no frameworks or external libraries slow down the game or cause compatibility issues.

---

## 🎮 How to Play

### 💷 Placing Bets

Use the input box or quick chip buttons (£1, £5, £25, £100, £500) to set your bet amount. Your bet must be at least £1 and can’t exceed £500 or your current balance. Click **Deal** to start a new round and place your bet.

### 🃏 Player Actions

- **Hit (H key):** Draw a card to improve your hand total.  
- **Stand (S key):** Keep your current total and end your turn.  
- **Double Down (D key):** Double your bet, get exactly one more card, then stand automatically. Available only on the first two cards.  
- **Split (P key):** If your initial two cards are the same rank, split them into two separate hands with equal bets and play each hand independently. Up to two splits (3 hands total).

### 🏆 Dealer Play

After the player finishes all hands, the dealer reveals their hidden card and draws according to standard rules: hits until 17 or more and stands on all 17s including soft 17.

### 🎉 Winning Conditions

- You win if your hand’s total is higher than the dealer’s without busting (going over 21). Your bet pays 1:1.  
- A blackjack (Ace + 10-value card on the first two cards) pays 3:2 immediately.  
- If both dealer and player have blackjack, the result is a push (bet returned).  
- If the dealer’s total beats yours or you bust, you lose your bet.  
- Ties (push) return your original bet.

### 🔧 Additional Controls

- Use the **Top Up £500** button anytime to add funds to your balance.  
- Keyboard shortcuts let you play quickly without needing to click buttons.

---

## ⚖️ Game Mechanics & Rules

### 🃏 Deck & Shoe

The game simulates a casino-style shoe containing six standard decks (312 cards). The shoe is shuffled freshly before each round, ensuring unpredictability and fairness.

### 📊 Card Values & Scoring

- Number cards 2-10 carry their face value.  
- Face cards (Jack, Queen, King) are worth 10 points each.  
- Aces count as 11 or 1 depending on which keeps the hand value ≤ 21.  
- Hands with multiple aces are calculated dynamically to maximize score without busting.

### 🔄 Splitting

- When you’re dealt two cards of the same rank, you can split them into separate hands.  
- Each split hand receives one additional card.  
- You can split up to twice, playing three hands simultaneously.

### 💵 Doubling Down

- Doubling your original bet on your first two cards only.  
- You receive exactly one card and your turn ends immediately afterward.

### 🃏 Dealer Behavior

- Dealer reveals one card initially and keeps the other hidden until your turn ends.  
- Dealer must hit on 16 or less and stand on all 17s including soft 17.

### 💷 Betting Limits

- Minimum bet: £1  
- Maximum bet: £500 or your current balance (whichever is less)

---

## 💰 Currency System & Betting

The game features a simple but robust currency system that mimics real gambling scenarios.

- You start with a balance of £1000 saved in your browser’s `localStorage`.  
- When you place a bet and hit **Deal**, your bet amount is deducted from your balance immediately.  
- If you win, your winnings (bet + payout) are added back to your balance.  
- Blackjack pays 3:2 (e.g., £10 bet returns £25).  
- A push (tie) returns your bet without profit or loss.  
- The **Top Up £500** button adds £500 instantly to your balance so you can keep playing without refreshing or losing progress.

---

## 🎨 User Interface & Theme

The UI embraces the Windows 10 design language and color scheme:

- **Background:** Solid black (#000000) for a casino-like feel without distractions.  
- **Table Surface:** Dark grey (#1e1e1e) to differentiate the play area clearly.  
- **Buttons and Highlights:** Windows blue (#0078d7) for emphasis and interactive elements.  
- **Text:** Crisp white and light grey for readability and contrast.  
- **Cards:** Classic white backgrounds with bold, easily readable suits and numbers. Hearts and diamonds in red, clubs and spades in black.

### Layout Details

- Dealer’s cards appear centered at the top, followed by your cards below.  
- Your balance and bet controls are at the bottom right for quick access.  
- Action buttons (Hit, Stand, Double, Split) are large and distinct, positioned intuitively.  
- Status messages update dynamically below the dealer’s cards, keeping you informed.  
- Responsive design adapts to smaller screens, enlarging buttons and spacing for easy tapping on mobile devices.

---

## ⌨️ Keyboard Shortcuts

For power users and better accessibility, the game supports keyboard controls:

| Key | Action         |
|------|----------------|
| H    | Hit            |
| S    | Stand          |
| D    | Double Down    |
| P    | Split          |

Shortcuts are only active when it’s your turn to play, preventing accidental inputs during other times.

---

## ♿ Accessibility & Responsiveness

- All interactive controls have proper ARIA roles and labels for screen readers.  
- Keyboard focus outlines ensure users navigating with keyboards can track where they are.  
- Color choices maintain strong contrast ratios to comply with accessibility standards.  
- The layout adjusts fluidly on phones, tablets, and desktops, providing a consistent experience on any device.

---

## 🛠️ Development Details

This project is a showcase of clean, modular, and maintainable code built without dependencies.

### Technologies Used

- **HTML5** for semantic and accessible markup.  
- **CSS3** using Flexbox and Grid for responsive layout and theming.  
- **JavaScript (ES6)** with modern syntax for game logic and UI updates.  

### Code Organization

- The entire game lives in a single `index.html` file for simplicity.  
- Game logic is modularized into functions handling shuffling, dealing, scoring, and UI updates.  
- Persistent balance stored via `localStorage` enables seamless user experience across sessions.  
- Event listeners manage button clicks and keyboard shortcuts with clean state transitions.

### Configuration Constants

- `DECKS_COUNT = 6`  
- `BLACKJACK_PAYOUT = 1.5` (3:2 payout)  
- `MIN_BET = 1`  
- `MAX_BET = 500`  

These constants can be adjusted easily inside the script for different rule variations or testing.

---

## 🚧 Planned Enhancements

The game is designed with future features in mind, including:

- Smooth animations for dealing cards and flipping.  
- Sound effects for chips, dealing, wins, and losses to enhance immersion.  
- Optional insurance and surrender gameplay mechanics.  
- Side bets like Perfect Pairs and 21+3 for added complexity.  
- Player statistics tracking, history, and leaderboards.  
- Mobile app wrapper to enable offline play.  
- AI opponents and multiplayer support for social gameplay.

---

## 🐞 Testing & Debugging

For developers and testers:

- Open the browser DevTools console to monitor game state and logs.  
- Use keyboard shortcuts to quickly test game mechanics.  
- Adjust configuration constants to simulate edge cases.  
- Report bugs or suggest features via GitHub issues.

---

## 🤝 Contributing

Contributions are welcome and appreciated!  

- Fork the repository and create feature branches.  
- Include clear commit messages and documentation.  
- Test your changes on multiple devices and browsers.  
- Submit pull requests with descriptions of what you’ve done.  

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

Special thanks to open source contributors who make projects like this possible. Inspired by classic casino blackjack games and the Windows 10 UI design principles.

---

## 📬 Contact

Created and maintained by **Your Name** — reach out via your.email@example.com or open an issue on GitHub.

---

*Enjoy your game and good luck at the tables! 🎲🃏*
