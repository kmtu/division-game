# Division Practice Game

A web-based educational game to help children practice finding the quotient in long division problems.

## How to Play

1. Open `index.html` in a web browser
2. Select a level from the main menu
3. For each problem, enter the quotient (a single digit 1-9)
4. Press Enter to submit your answer
5. The game shows the calculation (product and remainder)
6. Correct if: `0 <= remainder < divisor`
7. Wrong answers add a 10-second penalty
8. Complete 10 questions per level

## Features

- 6 difficulty levels with increasing digit counts
- Long division visual format
- Timer with best time tracking per level
- Multiple player profiles with individual records
- Sound effects for correct/incorrect answers
- 10-second time penalty for wrong answers
- Prevents consecutive duplicate questions

## Levels

| Level | Dividend | Divisor |
|-------|----------|---------|
| 1 | 1 digit | 1 digit |
| 2 | 2 digits | 1 digit |
| 3 | 2 digits | 2 digits |
| 4 | 3 digits | 2 digits |
| 5 | 3 digits | 3 digits |
| 6 | 4 digits | 3 digits |

## Technology

- Pure HTML, CSS, and JavaScript
- No external dependencies
- Data stored in localStorage
- Web Audio API for sound effects

## License

MIT
