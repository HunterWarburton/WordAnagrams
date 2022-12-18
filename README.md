# WordAnagrams
Function to spit out all anagrams of an entered word

This function works by using a recursive approach. It breaks the input word down into smaller and smaller pieces, and uses those pieces to build up the anagrams. The base case is when the input word is empty, in which case there are no anagrams. The recursive case is when the input word has at least one character. In this case, the function finds all of the anagrams of the word without the first character, and then adds the first character to each of those anagrams in every possible position.
