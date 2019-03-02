# latin-sentences-js
Library of latin sentences in javascript.

Very simple library that provides access to the list of latin sentences. List is based on Wikipedia page:
https://en.wikipedia.org/wiki/List_of_Latin_phrases

# Usage
## Generating random sentence
```javascript
import {LatinSentences} from './js/libs/latin-sentences.js' 
var latinSentences = new LatinSentences();
var sentence = latinSentences.draw();
```
## Getting en meaning or description for a sentence in latin
```javascript
import {LatinSentences} from './js/libs/latin-sentences.js' 
var latinSentences = new LatinSentences();
var description = latinSentences.describe('ab uno disce omnes');
var meaning = latinSentences.meaning('ab uno disce omnes');

```
