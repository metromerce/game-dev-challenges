Unity Assignment
=============================

Language: Unity C#
Time: 3 days

Assignment:
- Rune Tapper Game
- No graphics are required
- Display current score
- Display current combo
- Display time countdown as a time bar
- Start game scene, Gameplay scene, Score conclusion scene.

Explanation:

You have to create a game called “Rune Tapper”.
The objective of this game is to tap falling runes as much as possible in a limited time to get the highest score.

Common Rules:
- Default time limit: 40 seconds / round
- 3 columns of dropping runes
- No con-current dropping runes
- No score/combo will be deducted if the rune drops out at the bottom.

Rune Type (You DON’T need to implement all of these.)
- Normal rune: [REQUIRED]
   - Tap 1 time and get score.
- X rune: [REQUIRED]
   - If tapped, accumulated combo will be reduced to 0.
   - No score for this rune.
- Iced rune: [1 point]
   - After tapped 1 time, the rune will become a normal rune.
- Slow rune: [2 points]
   - If tapped, all dropping runes will be 2 times slower.
   - Time countdown will be 2 times slower.
   - Effect last: 8 seconds [real time]
- Haste rune [2 points]
   - If tapped, all dropping runes will be 2 times faster.
   - Time countdown will be 2 times faster.
   - Effect last: 4 seconds [real time]
- Fade Out rune [3 points]
   - If tapped, all dropping runes will start to fade out at the centre of the screen and disappear at the bottom (visibility distraction only).
   - During fade out effect, all runes can be tapped as usual.
   - Effect last: 8 seconds [real time]
   - Override Fade in if Fade in is in play.
- Fade In rune [3 points]
   - If tapped, all dropping runes will start to fade in at the centre of the screen and fully appear at the bottom (visibility distraction only).
   - During fade in effect, all runes can be tapped as usual.
   - Effect last: 6 seconds [real time]
   - Override Fade Out if Fade Out is in play.
- Score rune [2 points]
   - If tapped, all dropping runes will provide x2 more score.
   - Effect last 10 seconds [real time]
- Bomb rune [1 point]
   - If tapped, the game is over.
   - No score for this rune.

Dropping probability:
- Normal : 60%
- X : 10%
- Else: sum prob = 30%

Game score rules:
- <100 x current combo> per 1 rune tapped.
- <combo increased> (before calculating score) per 1 rune tapped.

Assignment Criteria:
- Code quality
- Class structure design
- Unity object design
- Rune type: more than 7 points from 14

BONUS:
- Some rough graphics
- Particle effect
- Implement all rune types
- Leaderboard (does not disappear after quit the game)

REF
https://youtu.be/xhBxGrpuw-g?t=2m
From 2:00 to 2:20
