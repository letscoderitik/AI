# Tokenization

Tokenization is a fundamental step in Natural Language Processing (NLP). 
It involves dividing a Textual input into smaller units known as tokens. 
These tokens can be in the form of words, characters, sub-words, or sentences.

Involves dividing a string or text into a list of smaller units known as tokens.


<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/151a826e-72e2-44e8-8c5f-fcc88590a530" />


# Types of Tokenization

1. Word

Word tokenization is the most commonly used method where text is divided into individual words.

Input before tokenization: ["Machine Learning is fascinating"]

Output when tokenized by words: ["Machine", "learning", "is", "fascinating"]

2. Character

the textual data is split and converted to a sequence of individual characters.

Input before tokenization: ["You are helpful"]

Output when tokenized by characters: ["Y", "o", "u", " ", "a", "r", "e", " ", "h", "e", "l", "p", "f", "u", "l"]

3. Sub-word

This strikes a balance between word and character tokenization by breaking down text into units
that are larger than a single character but smaller than a full word.

["Time", "table"] 
["Rain", "coat"] 
["Grace", "fully"] 
["Run", "way"] 

4. Sentence

Sentence tokenization is also a common technique used to make a 
division of paragraphs or large set of sentences into separated sentences as tokens.
This is useful for tasks requiring individual sentence analysis or processing.

Input before tokenization: ["Artificial Intelligence is an emerging technology. Machine learning is fascinating. Computer Vision handles images. "]

Output when tokenized by sentences ["Artificial Intelligence is an emerging technology.", "Machine learning is fascinating.", "Computer Vision handles images."]

5. N-Gram 

N-gram tokenization splits words into fixed-sized chunks (size = n) of data.

Input before tokenization: ["Machine learning is powerful"]

Output when tokenized by bigrams: [('Machine', 'learning'), ('learning', 'is'), ('is', 'powerful')]
