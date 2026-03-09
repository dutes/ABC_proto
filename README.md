# Always Be Climbing (ABC) Prototype

A web-based betting and racing game prototype built with vanilla HTML, CSS, and JavaScript. 

## Overview
"Always Be Climbing" is a fast-paced virtual racing game where players start with a virtual wallet and place bets on different climbers. Each climber has unique odds, base speeds, and dynamic crowd sentiment that affects their payout. 

## Features
- **5 Unique Climbers:** Choose from Monkey, Dwarf, Goblin, Robot, and Jester, each with their own baseline speeds and changing odds.
- **Dynamic Betting System:** Stake $5, $10, $25, or $50 from your virtual wallet. Payouts are calculated based on the climber's current odds.
- **Live Race Events:** During the race, climbers can experience sudden bursts of speed ("WOOSH!", "ZOOM!"), slip backwards ("OOPS!", "SLIP!"), or stall. 
- **Responsive UI:** A modern, fully responsive interface with custom CSS animations, real-time race logging, and a satisfying race finish experience.
- **No Dependencies:** The entire game runs in a single `index.html` file using standard web technologies.

## How to Play
1. Open `index.html` in any modern web browser.
2. Review the climbers and their current odds. Shorter odds mean a more reliable climber, while longer odds are riskier but offer a higher payout.
3. Select your stake amount ($5, $10, $25, or $50).
4. Click on a climber to place your bet.
5. Hit **Start Race** and watch the climbing action! 
6. If your climber wins, your wallet is credited based on the odds. Try to grow your wallet as much as you can!

## Development
This is a self-contained prototype meant to test the core loop of betting, race visualization, and dynamic event generation. All logic, styling, and markup are contained within `index.html`.
