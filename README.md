# 🎲 Minecraft Stat Poker
Minecraft Stat Poker is a fun game where players use their Minecraft statistics as a form of betting. Instead of traditional cards, you're wager with in-game statistics like distance walked, mobs killed, number of jumps, and more!

## 📔 Table of Contents
- [How to Play](#-how-to-play)
- [Rules](#-rules)
- [Features](#-features)
- [File Locations](#-file-locations)
- [Feedback or Ideas?](#-feedback-or-ideas)
- [License](#license)

---

## 🎰 How to Play
1. Add Players
   - Enter each player's username. Their Minecraft skin will automatically appear next to their name.
  
2. Place Initial Bets
   - Everyone must place in the initial bet to participate in the round. 1 diamond is recommended.
     
2. Roll for a Statistic
   - Click the **Next Statistic** button to choose a statistic to be on (like highest distance walked or lowest mobs killed).
   - Tell everyone which stat was selected. If a player doesn't have that stat in their statistics menu, it means their value is zero for that statistic.
     
3. Place Bets
   - The player whose turn it is can **check** (pass without betting), **bet** (add more diamonds)m or **fold** (quit this round).
   - If a player checks, the turn moves to the next player who can also check, bet, or fold.
   - If a player bets, the following player must either **call** (match the bet), **raise** (increase the bet), or **fold**.
   - Players who fold are out of the current round and cannot win this round.
   - Once betting goes around the table without any new bets or raises, the betting phase ends and everyone reveals their stat.
     
4. Repeat
   - After the winner collects their winnings, have everyone put in their initial bets, roll for a new statistic, and repeat the betting round!

---

## 📜 Rules
1. Initial Bets
   - The starting bet for each round should be at least 1 diamond (or an agreed-upon currency/item).
   - Players are not allowed to bet above the initial bet until the statistic is revealed.
2. Turn Order
   - Players take turns in a fixed order (e.g. clockwise). Only the player whose turn it is may take action (bet, check, fold).
   - This player order should be reflected in the player list.
3. Betting Limits
   - Set maximum bet or raise limits to prevent runaway bets and keep the game fun and fast paced. A 64 diamond cap per player per round is recommended.
   - A player is not allowed to bet more than twice in a row. This means if they raised the bet the previous two times, they are not allowed to raise again. However, if someone else raises the bet, they are allowed to raise during their turn.
4. Folding Means Out
   - Once a player folds during a round, they cannot win that round, even if they have the winning statistic.
5. Stat Reveal
   - At the end of each betting phase, all players must reveal their current value for the chosen statistic, but only those who didn't fold can win the round.
6. Ties
   - In the case of a tie, the pot is split equally among the winners.
7. All-In
   - If a player is not able to match the bet, they are allowed to go **All-In** (put in their remaining diamonds). A side pot will be started for those who are able to match the full amount. If the All-In player wins, they win the main pot. The side pot goes to the winner of those active in the side pot.
8. Fair Play
   - Don't spoil the game by revealing known statistics from prior knowledge (like stat farming). Keep it fun by playing fair and guessing like everyone else.
---

## 🛠 Features
- Add Players - Keeps track of who is in the game and adds their skin to the player list.
- Roll for Stats - Randomly selected from available Minecraft stats like mobs killed, distance traveled, and more.
- Select Stat Pool - Customize which stats are included in the game.
- Track Player Turns - Automatically tracks which player starts the betting process.
- Easy Updates - When a new statistic or block is added to the game, an updated stat list can be downloaded directly from the statistics menu in the application.

---

## 📂 File Locations
- App configurations and downloaded stats: **C:/Users/YourUser/AppData/Roaming/StatPoker/**
- GitHub-hosted stat files: {add path here}

---

## 💬 Feedback or Ideas?
Open an issue or send a pull request!
I would love to hear your ideas for new features or improvements!

---

## License
This project is open-source under the MIT License.
