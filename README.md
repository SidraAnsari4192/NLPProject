# NLPProject
Regulatory Document Summarization
A summary is a text that is produced from one or more texts, that contains a significant portion of the information in the original text(s), and that is no longer
than half of the original text(s).The purpose of summarization is to make a shorter version of a source text while still keeping the main points and meaning of the 
original. 
A well-written summary can significantly cut down on the amount of work required to understand a lot of texts.Applications for summarization include: outlines 
or abstracts of any document, article, etc.; email thread summaries; meeting action items; and reducing text by condensing sentences.In this project we are working 
on Abstractive summarization.
Abstractive summarization used (at least in part) different words to express the ideas in the source documents.ROUGE is used in this project which is the Recall 
based score to compare system generated summary with one or more human generated summaries.
We introduce BART, a pretraining denoising autoencoder for sequence-to-sequence models. When training, BART corrupts text using a random noise function and learns a 
model to recreate the original text. It makes use of a typical Transformer-based neural machine translation architecture, which, despite its simplicity, generalises 
many other more current pretraining approaches, including BERT (thanks to the bidirectional encoder), GPT (with the left-to-right decoder), and many more. 
The best result was achieved by randomly rearranging the original sentences' sequence as well as by implementing a cutting-edge in-filling strategy in which long 
stretches of text are substituted with a single mask token. BART performs well for comprehension tasks but is especially effective when modified for text production.
BERT, one of the most well-liked deep learning-based language models.
