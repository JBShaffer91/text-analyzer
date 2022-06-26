Describe: wordCounter()

Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

Test: "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

Test: "It should return 0 for an empty string."
Code: wordCounter("");
Expected Output: 0

Test: "It should return 0 for a string that is only spaces."
Code: wordCounter("            ");
Expected Output: 0

Test: "If an empty string is passed in as a word, it should return 0."
Code:
const word = "";
const text = "red RED Red!";
wordCounter(word, text);
Expected Output: 0

Describe: boldPassage()

Test: "It should return null if no word or text is entered."
Code:
const text = "";
const word = "";
numberOfOccurrencesInText(word, text);
Expected Output: null

Test: "It should return a non-matching word in a p tag."
Code:
const word = "hello";
const text = "yo";
boldPassage(word, text);
Expected Output: <p>yo</p>

Co-authored-by: Spencer Watari<deanwatari@gmail.com>, Justin Shaffer<justinbshaffer91@gmail.com>, <bryce.bresnan@gmail.com>


Describe: repeatedWordCounter()

Test: "It should return 1 if a word is repeated."
Code:

const text = "bing bing";
repeatedWordCounter(text);
Expected Output = 1

Test: "It should return 0 if a word is not repeated."
Code:
const text = "bing pong";
repeatedWordCounter(text);
Expected Output = 0

