<div align="center">

# $ TypeGhost

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=24&pause=1200&color=39FF7A&center=true&vCenter=true&width=640&lines=A+retro+terminal+typing+speed+test;Normal%2C+Expert%2C+and+Master+modes;Type+fast.+Stay+accurate.+Don't+blink.)](https://abhi-y-diord.github.io/TypeGhost/)

[![Live Demo](https://img.shields.io/badge/live%20demo-open%20the%20site-39FF7A?style=for-the-badge&labelColor=0B0F0A)](https://abhi-y-diord.github.io/TypeGhost/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dependencies](https://img.shields.io/badge/dependencies-none-39FF7A?style=flat-square&labelColor=0B0F0A)
![Hosted on GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-181717?style=flat-square&logo=github)

</div>

---

## About

**TypeGhost** is a typing speed test with a green-on-black retro terminal look. It is a single `index.html` file with no frameworks and no build step, so it loads instantly and runs on any device.

**Try it here: https://abhi-y-diord.github.io/TypeGhost/**

```
$ typeghost
  
  30                                  [ normal | expert | master ]

  the quick brown fox jumps over the lazy dog and keeps typing
  until the timer runs out
```

## Features

- **Three difficulty modes** on a sliding selector (click it or drag it):
  - **Normal:** mistakes only lower your accuracy.
  - **Expert:** you cannot move to the next word until you fix every mistake in the current one.
  - **Master:** a single mistake ends the test and shows your score.
- **Three test lengths:** 15, 30, or 60 seconds.
- **Clean test screen:** only the countdown is shown while you type, so there are no distractions.
- **Result screen** with your wpm, accuracy, raw wpm, correct and wrong characters, and your best score.
- **Speed graph** showing your speed second by second, with red marks where you made mistakes.
- **New text or same text:** press `Tab` for fresh words, or `Esc` to retry the same text.
- **Best scores saved** in your browser for every mode and test length.
- **Works on phones** with the on-screen keyboard.
- **Custom green cursor** to match the terminal theme.
- Small, subtle animations that turn off automatically if your device prefers reduced motion.

## Controls

| Key | What it does |
| --- | --- |
| Start typing | Starts the timer on your first key |
| `Backspace` | Fixes the last character |
| `Tab` | New text |
| `Esc` | Restart with the same text |

## Run it locally

No install needed.

```bash
git clone https://github.com/abhi-y-diord/TypeGhost.git
cd TypeGhost
```

Then open `index.html` in your browser.

## Tech

Plain HTML, CSS, and JavaScript. The speed graph is drawn on a `<canvas>` without any chart library. The only outside resource is the JetBrains Mono font from Google Fonts, with a monospace fallback.

## Roadmap

- [ ] Ghost racer: race against your own best run
- [ ] Word-count mode
- [ ] Class leaderboard

---

<div align="center">

Made by [@abhi-y-diord](https://github.com/abhi-y-diord)

</div>
