# Always Be Climbing (ABC) Prototype

A web-based betting and racing game prototype built with vanilla HTML, CSS, and JavaScript. 

## Overview
"Always Be Climbing" is a fast-paced virtual racing game where players start with a virtual wallet and place bets on one of five climbers. Each climber has a defined win probability and a distinct variance profile; the posted odds are derived from those probabilities plus a configurable house edge, so payouts are honest and the model is demonstrable.

## Features
- **5 Unique Climbers:** Monkey, Dwarf, Goblin, Robot, and Jester, each with a named variance profile (Steady, Bursty, Wildcard, Clumsy, Trickster) that shapes how often they slip, boost, stall, or surge.
- **Honest odds model:** Each climber has a true win probability (summing to 100%). Fixed-odds prices are computed from those probabilities with a target RTP (~92% / 8% house edge) and snapped to a real betting-shop fractional ladder. The winner is drawn from the same probabilities, so the displayed odds genuinely reflect the chance of winning.
- **Two bet types:** Toggle between **Fixed Odds** (price locked when you bet) and **Parimutuel** (a live, illustrative tote pool where crowd money sets the odds and an 18% takeout applies).
- **Bells & finish line:** The first climber to the top rings the bell, flashes the finish line, and triggers the payout.
- **Sportsbook placement demo:** A "View" switcher shows how the game would be surfaced inside a sportsbook — **Standalone**, **In-frame** (an embedded widget in a mock racing feed with a live "next race" countdown), **Overlay** (a slide-up bottom sheet over the racing page), and **Pop-up** (a centred dialog). Switching views moves the same game node, so play is preserved.
- **Reskinnable themes (one engine, many games):** Switch event themes live — Night Carnival (painted characters), Neon Circuit and Golden Festival (emoji rosters), and **Balloon Cup**, which renders the *same* race as inflating team-colour balloons with pumper characters instead of climbers. Themes change palette, title, characters and even the game's visual metaphor while the odds engine underneath is unchanged.
- **Dynamic Betting System:** Stake $5, $10, $25, or $50 from your virtual wallet.
- **Live Race Events:** During the race, climbers experience bursts of speed ("WOOSH!", "ZOOM!"), slip backwards ("OOPS!", "SLIP!"), stall, or get a crowd hype boost.
- **Responsive UI:** A fully responsive interface with custom CSS animations, real-time race logging, and a satisfying race finish.
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
