# FragileNER
This is a first novice attempt at NER for NLP.
The Idea is to train a CNN on a annotated corpus and further, it should predict the labels of a given sequence of words post training.

Example:

Input: Germany lost a soccer game to Spain on Tuesday

Output: ['B-LOC', 'O', 'O', 'O', 'O', 'O', 'B-LOC', 'O', 'O']
