# Somali NLP Data 

## Description
This is the sister repo of [Somali_NLP](https://github.com/apjama/SOMALI_NLP).  The data here has been collected from a range of different places. We have sometimes gone to great lengths to clean them up. For project aims and milestones, please see the Somali NLP repo linked above. 

If you’ve any ideas about how to clean up the data, make it better, please get in touch. I can be reached on [Twitter](https://twitter.com/apjama).

## Here’s a quick overview of the data so far. 

### The Wikipedia folder
Here you’ll find three csv files. These are about 8mb each. Which is huge (not that huge!). Between these three files you’ll find the entire Somali Wikipedia corpus. There are two headings. One for the title of the articles, and the other the actual text containing them. 

### The Masaryk University folder 
We took [this corpus by Masaryk University](http://habit-project.eu/wiki/SetOfEthiopianWebCorpora) | which supposedly comprised of over 80 million tokens (individual words). We cleaned up these tokens, removed xml data around them, and removed duplicates. We then sorted the tokens into grammatical categories (is it a word a verb, an adjective, a noun, etc). These categories still need a LOT of work because many are still uncategorized but the foundation is there. 

### The Hadrawi folder
The Hadrawi data were contributed by [Mohamed Ainab](https://twitter.com/mohamedainab). 
They can be found in the [original repo here](https://github.com/codeforsomalia/hadrawi). 
