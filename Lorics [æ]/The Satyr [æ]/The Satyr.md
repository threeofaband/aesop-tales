## The Satyr (Loric)
> There is a publicly known win/loss condition in play.

*“I've seen enough. A fellow that blows hot and cold in the same breath cannot be friends with me!”*

### Overview
The Satyr allows for a team to win or lose, if a condition is met.
- Use the Satyr for scripts with an otherwise repetitive goal of reaching final 2. This allows for greater depth during gameplay.
- Script writers may request for a specific win/loss condition. Follow this win/loss condition.

### How to Run
At the start of the game, declare that the Satyr is in play.

**After the first night**, announce the win or loss condition you or the script writer have chosen to be in play.

You may use the WORL reminder tokens for the win or loss condition if you need to.

### Examples
At first dawn, the Storyteller announces that Alyssa's team wins if she gets executed before the final 5. When she is executed, it is after final 5, so the game continues.

At first dawn, the Storyteller announces that the evil team loses if the Demon did not kill a Minion before final 2. The Demon is unable to kill a Minion due to the Monk, and Good wins.

At first dawn, the Storyteller announces that the evil team wins if the Demon executes their neighbour to the left. The Demon doesn’t even bother doing this, as the paranoia from this win condition works anyhow.

### Clarifications and Tips
*I recommend having the baseline middle ground: conditions achievable, but not overwhelmingly game-contorting. Executing the Demon still be the main way for the good team to win. Final 2 should still be the main way for evils to win. I believe the purpose of win/loss conditions is to further develop a script's play and change how players interact with the game.*

*For reference, think about how much win/loss conditions affect the base scripts (TB’s Saint, BMR’s Mastermind, SNV’s Evil Twin), along with how experimental win/loss characters play on other scripts (Damsel, Alsaahir, Cult Leader).*

### Character JSON
{
  "id": "satyr_aesoptales",
  "name": "The Satyr [æ]",
  "team": "loric",
  "ability": "There is a publicly known win/loss condition in play.",
  "firstNightReminder": "Announce the additional win condition that is in play.",
  "reminders": \[ "WORL", "WORL" \],
  "image": "https://raw.githubusercontent.com/threeofaband/aesop-tales/refs/heads/main/Lorics%20%5B%C3%A6%5D/The%20Satyr%20%5B%C3%A6%5D/satyr.png",
  "flavor": "I've seen enough. A fellow that blows hot and cold in the same breath cannot be friends with me!",
  "firstNight": 204
}
