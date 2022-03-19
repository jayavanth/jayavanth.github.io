---
title: "The Wordle Trap"
layout: post
---

Ever fell into this trap in Wordle?

You guess a word with 3 or 4 letters in the right place but you're left with a lot of words that match that exact pattern. Example:

![trap](/assets/wordle_trap.png)

## Average number of words with same n letters

This situation commonly occurs with 3 or 4 letters in my experience. Turns out the average number of words with the same 4 letters is 3.048 and for 3 letters it's 8.044.

You can try it out here: https://github.com/jayavanth/wordletrap

## What should you do?

1. Break the trap: If you think there might be a lot of guesses, try to see if a completely different word with different letters with the one you got the hit reveals anything. For example, instead of continuing with ALLO words, try something like GUILT
2. If you don't want to do that, for 4 letter traps, if you have 3 attempts left, you should keep guessing since the average is 3.
3. For 3 letters, it's better to just break it since the average is 8.

--------
