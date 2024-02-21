# spell-check
Suggesting a correct Telugu word from a corpus of Telugu words.

# explaination
We extract the given text from the corpus and store it into a list and then we remove duplicates from it.
We create a directory of ngrams(tri-grams) form the words of corpus and store them along with the words that are present with the tri-gram.
After this we take input from the user if the input word is already present in the corpus list then we will output entered word is correct.
Else we make a list of list of tri-grams by using the dictionary of tri-grams and send them to rank, now we rank them based on the frequency of the words that are present in suggested list and then we sort and select the first top 10 words with hightest frequency later we add some legnthscore to it and sort them again.
Then we display this to the user and allow him to select yes/no if he selects yes then we ask him to pick a refine and then based on some parameters we suggest him a word if he chooses no we don't do anything.
