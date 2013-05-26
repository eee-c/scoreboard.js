scoreboard.js
=============

Simple JS class to keep time and score (used in 3D Game Programming for Kids)



## Scoring

This feature of the scoreboard keeps track of the number of points the player has earned in the game.

If you create a scoreboard with `var scoreboard = new Scoreboard()` then the following methods are available:

 * `scoreboard.score(42)` — sets the current score in the game. This will replace any existing score. If no number is supplied, then zero is used. If the score section of the scoreboard is not shown already, this will show it.
 * `scoreboard.showScore()` — shows the score section of the scoreboard.
 * `scoreboard.hideScore()` — hides the score section of the scoreboard.
 * `scoreboard.getScore()` — returns the current score in the game.
 * `scoreboard.addPoints(10)` — increases the score in the game by the specified amount.
 * `scoreboard.subtractPoints(10)` — decreases the score in the game by the specified amount.

## Timer

This feature keeps track of the total time that has gone by in the game.

If you create a scoreboard with `var scoreboard = new Scoreboard()` then the following methods are available:

 * `scoreboard.timer()` — starts the timer in the game. If the timer section of the scoreboard is not shown already, this will show it.
 * `scoreboard.showTimer()` — shows the timer section of the scoreboard.
 * `scoreboard.hideTimer()` — hides the timer section of the scoreboard.
 * `scoreboard.stopTimer()` — stops the timer from counting any more.
 * `scoreboard.startsTimer()` — starts the timer counting.
 * `scoreboard.resetTimer()` — restarts the timer from zero.
 * `scoreboard.getTime()` — returns the number of seconds that have elapsed in the game.

## Countdown

This feature keeps track of the total time that has gone by in the game.

If you create a scoreboard with `var scoreboard = new Scoreboard()` then the following methods are available:

 * `scoreboard.countdown(60)` — starts the countdown in the game with the number of seconds supplied.  If no time is specified, then 60 seconds will be used. If the countdown section of the scoreboard is not shown already, this will show it.
 * `scoreboard.showCountdown()` — shows the countdown section of the scoreboard.
 * `scoreboard.hideCountdown()` — hides the countdown section of the scoreboard.
 * `scoreboard.stopCountdown()` — stops the countdown from counting any more.
 * `scoreboard.startsCountdown()` — starts the countdown counting.
 * `scoreboard.resetCountdown(60)` — resets the countdown to the specified number of seconds.
 * `scoreboard.getTimeRemaining()` — returns the number of seconds left in the game.
 * `scoreboard.onTimeExpired("Time expired message")` — sets the message to be shown when time expires.
 * `scoreboard.onTimeExpired(function() { ... })` — if a function is supplied to the `onTimeExpired()` method, then the function will be called when time runs out.

## Scoreboard Messages

Use messages to provide in-game messages to the game player. If you create a scoreboard with `var scoreboard = new Scoreboard()` then the following methods are available:

 * `scoreboard.message('your message here')` — sets the current scoreboard message. This will replace any existing messages. If the message section of the scoreboard is not shown already, this will show it.
 * `scoreboard.addMessage('your message here')` — adds more messages to the current scoreboard message.
 * `scoreboard.showMessage()` — shows the message section of the scoreboard.
 * `scoreboard.hideMessage()` — hides the message section of the scoreboard.
 * `scoreboard.clearMessage()` — erases the message section of the scoreboard.

## Help

Scoreboard help provides a way to give instructions to the player without cluttering up the message section of the scoreboard. Players need to type the question mark to see the help on the scoreboard.

If you create a scoreboard with `var scoreboard = new Scoreboard()` then the following methods are available:

 * `scoreboard.help('your help instructions here')` — sets the scoreboard help. This will replace any existing help. If the help section of the scoreboard is not shown already, this will show it.
 * `scoreboard.showHelp()` — shows the help section of the scoreboard.
 * `scoreboard.hideHelp()` — hides the help section of the scoreboard.
