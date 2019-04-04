# Build-a-model-to-predict-if-a-word-occures-in-randomly-selected-document

So our task here is train a model in such a way that, given any randomly selected document, our model should be smart enough to state if that document contains a certain word, without actually looking for the occurance of that word.

So inorder to do that, I have used an example of wikipedia page https://en.wikipedia.org/wiki/List_of_dinosaur_genera
which gives details of all dinosaur genera, using all data available in it, I have scraped the pages and trained the model,
using TF-IDF to look for words occuring around the word dinosaur.

So that in future if any new document comes in, our model will be effective in detecting the if that document may be related to dinosaur
without actually looking for word dinosaur in it. 

So that even if someone talks of dinosaur, without using the word dinosaur, our model can pick up the document and state the reference in which it is been written.
