# mega65-nomis ![nomis_icon](https://github.com/tonedef71/agon-nomis/assets/3978924/18a23763-fa54-40e9-8d44-6b062499622d)

NOMIS: a clone of the classic game [*Simon*](https://en.wikipedia.org/wiki/Simon_(game)) written for the MEGA65 written with the [Eleven preprocessor](https://github.com/MEGA65/eleven) for [BASIC 65](https://files.mega65.org?id=42d0f1f9-610a-45f9-bad1-9502f0e6eb7d).
* A colorful, musical game of ["Follow the Leader"](https://en.wikipedia.org/wiki/Follow_the_leader_(game))
* Won first place in the [1st Olimex AgonLight Weekend Programming Challenge 2023](https://olimex.wordpress.com/2023/04/21/agonlight-weekend-programming-challenge-issue-1/)
* Was also submitted as an entry for the the [Phaze 101/RPI Simon Game (BASIC Jam)](https://itch.io/jam/simongame)

## Display
NOMIS supports minimum screen dimensions of 40 columns by 25 rows.

## Controls
Use the keys R, F, J, and I keys (comfortably located near the "home row" keys on a QWERTY keyboard) to press the colored light-up sensor pads (Green, Yellow, Blue, and Red, respectively) to correctly repeat a longer and longer series of signals.

## Difficulty
There are four levels of difficulty:
1. The player must correctly repeat eight signals to win the game
2. The player must correctly repeat fourteen signals to win the game
3. The player must correctly repeat twenty signals to win the game
4. The player must correctly repeat thirty-one signals to win the game

## Best Score
* The default best score is six out of eight.
* The best score will be saved to a file named `nomis.hi` on the disk in the same folder as the `nomis.bas` file.
* NOMIS must be run from the exact folder on the disk where the `nomis.hi` file resides in order for the saved best score to be read-in by the game.
