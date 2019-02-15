Essentially, the app randomly picks a letter, and the user has to guess which letter the app chose. Put the following text on your page:
Guess what letter I'm thinking of
Wins: (# of times the user has guessed the letter correctly)
Losses: (# of times the user has failed to guess the letter correctly after exhausting all guesses)
Guesses Left: (# of guesses left. This will update)
Your Guesses So Far: (the specific letters that the user typed. Display these until the user either wins or loses.)
When the player wins, increase the Wins counter and start the game over again (without refreshing the page).
When the player loses, increase the Losses counter and restart the game without a page refresh (just like when the user wins).

This application uses javascript to pick a random letter at the start, and the user has a limited amount of guesses to guess that letter correctly. The application keeps track and lets the user know how many guesses they have left, if the user gets it right, the number of guesses resets and they get a point, if they fail to guess the right letter, guesses resets and they get a point in the losses section.
