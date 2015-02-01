# js-word-frequency-nlp-with-stop-words-and-free-beer

JavaScript Word Frequency Analysis (NLP) with Stop Words and Free Beer!

Accepts input string, cleans it up, then outputs a list of meaningful words within that text, sorted by frequency of occurence within the text.

Example usage:
```
mywords = $('.entry .usertext-body .md p').map(function(i, el) {
    return $(el).text()
}).get();

words = wordfreq(mywords.join(' '));

for (var i=words.length-1; i>=0; --i) {
	console.log(words[i].frequency, words[i].text);
}
```
