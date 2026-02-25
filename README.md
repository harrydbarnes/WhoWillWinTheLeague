# 🏆 Will Arsenal Bottle It (Again?!)? 🍼

Oi! Welcome to the **Premier League Title Race Simulator 2025/26**! 🏟️

It's happening again. They're so close. But the question on everyone's lips is: **Will Arsenal bottle it?** 😰 Or will **Man City (cheat)** their way to another title? 🤖💸

This tool lets you play Mystic Meg 🔮 and predict the run-in for the ultimate title scrap!

## 🎯 What's the Point?

The Premier League season is squeaky bum time! 🍑 This site focuses on the title battle involving **Arsenal** 🔴 and **Man City** 🔵.

Will the Gunners finally get their hands on the trophy? Or will the City machine crush their dreams once more? It's all in your hands! 🙌

## 🕹️ How It Works

You've got two ways to play the gaffer:

### 1. 📋 Fixture List Mode
For the tactical geniuses who like to see the whole board.
- Scroll through the remaining fixtures for Arsenal and Man City.
- Click **W** (Win), **D** (Draw), or **L** (Loss) for each game.
- Watch the **Live Standings** update instantly! 📊
- Includes a **Fixture Difficulty Rating (FDR)** so you know if it's a walk in the park 🌳 or a trip to Anfield 🏟️.

### 2. 👆 Swipe Mode
For the Tinder generation!
- Focus on one game at a time.
- **Swipe Right** for a Win! 👉✅
- **Swipe Left** for a Loss! 👈❌
- **Swipe Up** for a Draw! 👆🤝
- Or use the big buttons if your thumb is tired.
- Get a dramatic **FINAL TABLE REVEAL** at the end! 🥁

## 📸 Share Your Predictions

Once you've sealed their fate, generate a snapshot of the final table!
- **Share Prediction**: Creates a slick image of the table to roast your mates in the group chat. 📱💬

## 🛠️ Under the Bonnet (Open Source)

Big shout out to the open source wizardry that makes this tick:
- **[html2canvas](https://html2canvas.hertzen.com/)**: The absolute legend that takes the screenshot of your prediction. 📸 Thanks for making us look good!

Everything else is good ol' **Vanilla JS**, **HTML**, and **CSS**. No frameworks, no nonsense. Just like 4-4-2. 🇬🇧

## 🍴 Fork It like a Sunday Roast

Want to make this for your own relegation battle? Or maybe next year's title race?

1.  **Fork this repo** 🍴
2.  Open `index.html`.
3.  Look for the `TEAMS_DATA` object in the `<script>` tag.
4.  Swap out the teams, points, and fixtures.
    ```javascript
    const TEAMS_DATA = {
        'your-team': {
            name: 'Your Team FC',
            currentPoints: 68,
            currentGD: 48,
            fixtures: [ ... ]
        },
        // ... add more teams
    };
    ```
5.  Update the CSS variables in `:root` to match your team colours. 🎨
6.  Deploy to GitHub Pages and become the oracle! 🧙‍♂️

---

Made with ❤️, 🍺, and a lot of anxiety.
Come on you Gunners! (Or City, if you're into that sort of thing) 🔴🔵
