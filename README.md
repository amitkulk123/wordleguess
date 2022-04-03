# wordleguess
 A simple python program that suggests a list of possible guessing words from the popular game wordle
 
## Usage
Simply download the wordleguess.py file 
Then run it with:

**python3 wordleguess.py**

Then just put in your first guess and whether each letter was shown to be green, gray, or yellow

Here's an example with the starting word of "adieu":
<img width="691" alt="Screen Shot 2022-04-03 at 1 41 03 PM" src="https://user-images.githubusercontent.com/9218849/161440855-7aa4ce9e-1ac4-45ac-a099-632398c2f37a.png">

The program will keep prompting until there's only one word remaining in the possible list (which was obtained from the wordle source code). 

## Future Updates
- I'm planning on making this project more expansive with better visualized output and potentially a GUI or a Discord bot that can be implemented in servers.
- Also trying to find a better way to order the word based on whichever ones have more distinct characters rather than the order presented on Wordle's source code. 
  - Perhaps I can try reordering with Google's ngram viewer or a Twitter call that searches hashtags for word popularity
- Also want to expand the word list to include more than just what's presented in the source code in case more words are added to the list later on.


