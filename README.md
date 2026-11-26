# ✊✋✌️ Rock Paper Scissors

A classic Rock Paper Scissors game you play against the computer, built with vanilla HTML, CSS and JavaScript. Click your move, see who wins, and keep a running score. No frameworks, no build step, no dependencies.

**[Play it live](https://YOUR-USERNAME.github.io/rock-paper-scissors/)** <!-- replace after enabling GitHub Pages -->

<!-- Add a screenshot: save it as screenshot.png in the repo and uncomment the line below -->
<!-- ![Rock Paper Scissors screenshot](screenshot.png) -->

---

## ✨ Features

- Play against a computer opponent that picks randomly each round
- Click-to-play interface with large, round image buttons
- Live scoreboard tracking your wins and the computer's wins
- Color-coded result messages: green for a win, red for a loss, black for a draw
- Hover highlight on the choice buttons
- Zero setup: open `index.html` and play

## 🎮 How to Play

1. Click **Rock**, **Paper** or **Scissors**.
2. The computer picks its move at random.
3. The result appears below the scoreboard and the score updates.

| Your move | Beats |
| --- | --- |
| Rock | Scissors |
| Paper | Rock |
| Scissors | Paper |

Same move on both sides is a draw, and nobody scores.

## 🛠️ Built With

- **HTML5** for the page structure
- **CSS3** (Flexbox) for layout and styling
- **Vanilla JavaScript (ES6+)** for game logic and DOM updates

## 📁 Project Structure

```
rock-paper-scissors/
├── index.html        # Page markup
├── style.css         # Layout and styling
├── app.js            # Game logic and scoring
├── images/
│   ├── rock.png
│   ├── paper.png
│   └── scissors.png
└── README.md
```

## 🚀 Getting Started

### Run locally

```bash
# 1. Clone the repository
git clone https://github.com/YOUR-USERNAME/rock-paper-scissors.git

# 2. Move into the folder
cd rock-paper-scissors

# 3. Open index.html in your browser
```

You can also double-click `index.html`, or use any local server:

```bash
# Python
python -m http.server 8000

# Node
npx serve
```

### Deploy with GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. Save. Your game will be live at `https://YOUR-USERNAME.github.io/rock-paper-scissors/` within a minute or two.

## 🧠 How It Works

- `genCompChoice()` picks a random move for the computer using `Math.random()`.
- `playGame(userChoice)` compares the two moves, decides whether it's a draw, a win or a loss, and hands the outcome off.
- `showWinner()` and `drawGame()` update the scoreboard and result message in the DOM.
- Each choice button is wired up with a click listener that reads the button's `id` (`rock`, `paper` or `scissors`) and starts a round.

## 🗺️ Roadmap

- [ ] Reset button to clear the score
- [ ] Best-of-5 / first-to-N game mode
- [ ] Subtle animation when a round is played
- [ ] Show the computer's choice as an image
- [ ] Sound effects
- [ ] Keyboard controls (R, P, S)
- [ ] Dark mode

## 🤝 Contributing

Contributions, issues and feature requests are welcome.

1. Fork the project
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE). <!-- add a LICENSE file, or remove this section -->

---

Made with ❤️ by [YOUR NAME](https://github.com/YOUR-USERNAME)
