🧠✨ Natural Language Processing (NLP) Overview
This project leverages key NLP techniques to process and analyze text data. Here are the core NLP concepts and preprocessing steps:

1️⃣ Tokenization ✂️
Splits raw text into smaller units called tokens (words, sentences, or subwords).
Transforms text into a format suitable for analysis or machine learning.

Example:
Input: "NLP is fun!"
Output tokens: ["NLP", "is", "fun", "!"]
2️⃣ Lemmatization 🌱
Reduces words to their base or dictionary form (lemma), so different forms of a word are treated as one.

Example:
Input: "running", "ran", "runs"
Output lemma: "run"
3️⃣ Stop Words Removal 🚫🗣️
Removes common words (like "the", "is", "and") that may not carry useful info.
Helps focus on more meaningful words.

Example:
Input: "This is a sample sentence."
After removal: ["sample", "sentence"]
4️⃣ One-Hot Encoding (OHE) 🔢
Represents words as binary vectors.
Each word has a unique spot in the vector.

Example:
Vocabulary: ["cat", "dog", "fish"]
"dog" → [0, 1, 0]
5️⃣ Word Embeddings (WE) 🧩
Dense vector representations of words that capture their meanings.
Similar words are close together in the vector space.

Example:
"king" 👑 and "queen" 👸 have similar vectors, reflecting their semantic similarity.
6️⃣ Word2Vec (W@V) 🤖
Popular technique to create word embeddings using shallow neural networks.

How it works:

CBOW: Predicts a word from its context.
Skip-Gram: Predicts context words from a given word.
Example:
Training on "The cat sits on the mat" helps Word2Vec learn that "cat" and "mat" often share contexts and should have similar vector representations.

🚀 Explore & Experiment!
All examples and live models are right here in the repo!
Dive in, experiment, and have fun with NLP! 🧑‍💻📚✨
