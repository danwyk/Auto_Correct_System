# Auto-correction system for English sentence

---

### Background
<b>LING 193 - F22<br>
This is the my implementation of the auto-correct system<br></b><br>

Big shout out to my instructor - ***Andrew McInnerney***<br>
He led me through every linguistic concepts I learned in Ling 193.<br>
**"Download dictionary"** and **"1st Layer of Correction: Minimum edit distance"** are modefied based on the code from Andrew.

---

### About this project
This system will pinpoint misspelled word in a given sentence and then replace it with the most appropriate word from a given dictionary based on “Minimum edit distance”, “Word frequency“, and “Bigrams frequency”.

---

### Example1:
> s1 = "The manager hired ths employees"\
> s2 = "John will not buy anu tomatoes"


#### Min Distance + Frequency Result:
> s1 = "The manager hired **this** employees"\
> s2 = "John will not buy **an** tomatoes"

#### Determiner & Noun Phrase Result:
> s1 = "The manager hired **the** employees"\
> s2 = "John will not buy **any** tomatoes"


### Example2:
> It is widelly taugt that parts of speech are definned in terms of sinple defimitions. For example, "a noun is a person place or thinge." But in reality, simple defintions like that are not very usefful. For exampe, is it not true that everthing is a "thing"? Then in wghat sense can we deffine nouns as "thngs"? We need moree rigorouss teckneques to define these notioms.

#### Final Result:
> It is widely taught that parts of speech are defined in terms of simple definitions. For example, "any noun is any person place or thing ." But in reality, simple definitions like that are not very useful. For example, is it not true that everything is any "thing"? Then in what sense can we define nouns as "things"? We need more rigorous techniques to define these notions.

---

### Shortcoming
The current system can only spot misspelled words. In other words, if the misspelled word happen to be another word in the dictionary, this system will not able to correct it. Future improvements includes pinpoint and correct the logical mistakes like we just mentioned.
