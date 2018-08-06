# ruse

Ruse is a clue hunting game. Solve puzzles by searching for clues in the real world one clue at a time.


## Flow

### Login Page
Simple login page.

**Requirements:**
- User can sign in with popular OAUTH services.

### Feed Page
Feed page displays popular or nearby puzzles. One can select a puzzle to begin searching.

**Requirements:**
- Infinty scrolling list of puzzles
- Can preview, view statistics, and location of puzzles.

### Map Page
Map Page displays starting points for puzzles on a map. 

**Requirements:**
- Immediatly display nearby puzzles
- Lazy load puzzles of different locations.
- When zoomed out, display most popular puzzles by viewable location.

### Puzzle Page
Puzzle Page displays statistics and progress foreach puzzle.
Page is accessable from both the Feed and Map Page.

**Requirements:**
- Display users progress for the viewed puzzle.
- Display amount of __likes__ the puzzle has.
- Display amount of users at each stage of the puzzle / leaderboard.
- Display old and recent clues (using carousel?).

