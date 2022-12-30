# Auto-correction system for English sentence

### Background
<b>LING 193 - F22<br>
This is the my implementation of the auto-correct system<br></b><br>

Big shout out to my instructor - ***Andrew McInnerney***<br>
He led me through every linguistic concepts I learned in Ling 193.<br>
**"Download dictionary"** and **"1st Layer of Correction: Minimum edit distance"** are modefied based on the code from Andrew.

### About this project
This system will pinpoint misspelled word in a given sentence and then replace it with the most appropriate word from a given dictionary based on “Minimum edit distance”, “Word frequency“, and “Bigrams frequency”.

### Shortcoming
The current system can only spot misspelled words. In other words, if the misspelled word happen to be another word in the dictionary, this system will not able to correct it. Future improvements includes pinpoint and correct the logical mistakes like we just mentioned.
