# js-word-frequency-nlp-with-stop-words-and-free-beer

JavaScript Word Frequency Analysis (NLP) with Stop Words and Free Beer!

Accepts input string, cleans it up, then outputs a list of meaningful words within that text, sorted by frequency of occurence within the text.

Example usage:
```
words = $('.entry .usertext-body .md p').map(function(i, el) {
    return $(el).text().replace(/[^a-zA-Z 0-9]/g, ' ')
}).get();
getWordFrequencies(words.join(' '), 'asc')
console.log('Heck yes!')
```
