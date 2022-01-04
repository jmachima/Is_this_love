A Transformer model for a sentiment analysis of Thai text segments on the subject of romantic relationships.
Written with TensorFlow 2.7

AttaCut will be used to segment Thai alphabets into separate words. 
AttaCut: A Fast and Accurate Neural Thai Word Segmenter at arxiv.org/ftp/arxiv/papers/1911/1911.07056.pdf
by Pattarawat Chormai, Ponrawee Prasertsom, Attapol Rutherford

Word tokenization for the Thai language is not straightforward due to the fact that 
words are written without spacing between them. For example, 'ความรักเป็นเรื่องซับซ้อนและละเอียดละอ่อน', 
in Thai, is a whole sentence meaning 'Love is a complicated and delicate matter.'

This dataset was manually curated from the popular Thai-language Pantip.com web forum, 
consisting of short text segments on the subject of romantic relationship experience. 
The set is divided into two classes of sentiments: positive or negative.

This basic Transformer model is built with elements from "Transformer Model for Language Understanding" at TensorFlow.org. 
The code in this exercise does NOT use any of the models available at TensorFlow Hub so that hyperparameters can be freely tuned.
