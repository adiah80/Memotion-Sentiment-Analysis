# Memotion-Sentiment-Analysis

My work on Multimodal Memotion sentiment analysis done on the [Sem-Eval dataset](https://competitions.codalab.org/competitions/20629).

I combined a pre-trained [BERT](https://arxiv.org/pdf/1810.04805.pdf) and [ResNext](https://arxiv.org/pdf/1611.05431.pdf) model, making some changes to model architecture and fine-tuned the resulting model on the sem-eval dataset. The inputs to the model consisted of [Memes](https://en.wikipedia.org/wiki/Internet_meme) along with their OCR texts. The task of the model was to classify sentiments across different categories in the image. 

This work was part of a larger group work with [Rishabh Bajpai](https://github.com/CodeSeeker99) and [Shubhad Mathur](https://github.com/frontseat-astronaut) (who built their own model), and was done partly as the course project for BITS-F312 - Neural Networks and Fuzzy Logic. The project report can be found at [here](https://github.com/adiah80/Memotion-Sentiment-Analysis/blob/master/FinalReport.pdf).


