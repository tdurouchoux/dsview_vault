---
already_read: false
link: https://marc.ai/probabilistic-chess.html
read_priority: 1
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2024-07-10'
---

https://marc.ai/probabilistic-chess.html
## Summary

**Key Points:**

- **Game Concept:** Probabilistic Chess introduces a twist to traditional chess by adding success probabilities to each move, determined by a dice roll.
- **Rules:**
  - Movement success is based on the probability of the destination square.
  - Checkmate does not guarantee a win; the king must be captured.
  - All games end in a win due to the probabilistic nature of the board.
  - Variants include different rules for king moves to balance gameplay.
- **Implementation:**
  - The game is built with HTML, CSS, and JavaScript for fast loading and low server costs.
  - The AI combines chess.js and stockfish.js, with an alpha-beta search algorithm and expectation-maximization to consider board probabilities.
  - The AI has limitations due to the slow performance of running a large search tree in JavaScript.
- **Status:** The game is in an experimental 'alpha' version, with ongoing development and room for feedback.
- **Credits:** Created by Marc Stogaitis and Guy Stogaitis, inspired by Cameron Sun’s probabilistic tic-tac-toe.
## Links

- [Doodlecast for Chromecast](https://marc.ai/doodlecast-for-chromecast-android-app.html) : An Android app that allows users to create and share doodle videos using Chromecast.
- [Gmote](http://www.gmote.org) : A remote control application for Android that allows users to control their computer from their mobile device.

## Topics

![](topics/Concept/Probabilistic%20Chess)

![](topics/Concept/Alpha%20Beta%20Search%20Algorithm)

![](topics/Concept/Expectation%20Maximization%20EM%20Algorithm)

![](topics/Library/chess%20js)

![](topics/Library/stockfish%20js)