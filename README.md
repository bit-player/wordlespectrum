# The Wordle Spectrum

The code in this repository accompanies the essay "Words for the Wordle-Weary," by Brian Hayes, published 1 June 2022 at [http://bit-player.org/2022/words-for-the-wordle-weary]([http://bit-player.org/2022/words-for-the-wordle-weary](http://bit-player.org/2022/words-for-the-wordle-weary)). 

In Wordle every guess is "scored" by coloring the letter tiles. A letter in the guess word is green if the same letter appears in the same position in the target word. It's gold if the letter is present elsewhere in the target word. The tile is gray if the letter is absent from the target word. For a five-letter word there are 3^5 = 243 possible colorings. This program scores a guess word against each of the 2,315 target words and constructs a bar chart showing how many of the words are classified in each of the 243 categories.