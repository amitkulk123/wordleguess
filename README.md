# wordleguess
 A simple python program that suggests a list of possible guessing words from the popular game wordle
 
## Usage
Simply download the wordleguess.py file 
Then run it with:

`python3 wordleguess.py`

Then just put in your first guess and whether each letter was shown to be green, gray, or yellow

## Examples
Here's an example with the starting word of "SALET" and ending word of "TWINE":

<img width="678" alt="Screen Shot 2022-10-02 at 1 27 59 PM" src="https://user-images.githubusercontent.com/9218849/193467637-80f668db-2912-40a9-ade1-c229fbd74071.png">

As shown in the image above, instead of putting in one of the top 10 words as my guess, I guessed "write" instead. However, even if one of the top 10 suggested words aren't inputted, the algorithm will still remove cases from the list depending on which letter were green, yellow, or gray.

The program will keep prompting until there's only one word remaining in the possible list (which was obtained from the wordle source code). 

## Possible Features
- I'm planning on making this project more expansive with a potential GUI or a Discord bot that can be implemented in servers.
- Also trying to find a better way to order the word based on whichever ones have more distinct characters rather than the order presented on Wordle's source code. 
  - Perhaps I can try reordering with Google's ngram viewer or a Twitter call that searches hashtags for word popularity
- Also want to expand the word list to include more than just what's presented in the source code in case the NY Times adds more words to the list later on.


