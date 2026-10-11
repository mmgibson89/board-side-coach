# Board-Side Coach

A voice chess trainer for playing on a physical board. Stockfish plays the opponent and judges every move; Claude explains what went right or wrong, out loud.

Live at https://mmgibson89.github.io/board-side-coach/

- Engine: Stockfish 10 (GPL-3.0) via [stockfish.js](https://github.com/niklasf/stockfish.js), loaded from jsDelivr.
- Rules and move legality: [chess.js](https://github.com/jhlywa/chess.js).
- Coaching: Claude via the Anthropic API. Each person enters their own API key in Settings; it is stored only in their browser.
- Voice: the browser's built-in speech recognition and speech synthesis (best in Chrome).
