# NLP course

To set virtual environment you should stay on root folder and run next command: `python3.6 -m venv venv`.  
Then you have to active virtual environment with `source venv/bin/activate`.  
After activation install packages from `requirements.txt`. Just run `pip install -r requirements.txt`  
To work comfortably with jupyter notebooks you should install kernel for your environment:
```bash
ipython kernel install --user --name=nlp-course
```

## Lectures

1. [Into to NLP. Word Vectors](https://docs.google.com/presentation/d/1xFc0h9nrc1lrAHKsRC3WHWrA9RxVW6J5BqdWvM-16Lk/edit?usp=sharing)
2. [Recurrent neural networks](https://docs.google.com/presentation/d/13ar7A9MWugvGeD-07FhRR8UVPs7JZrQhM4xuKsU0oW8/edit?usp=sharing)
3. [Into to language models. Transformer architecture](https://docs.google.com/presentation/d/1KprnkUt1b8feQhCySrSEdu9qkHE8P4OnpcpZ9wIWNqk/edit?usp=sharing)
4. [Model architectures based on transformers](https://docs.google.com/presentation/d/18BXSICqYYu1ymAOqaHMhqB1z85vVwpZHWiWxIdaOG5c/edit?usp=sharing)
5. [Transfer learning in NLP](https://docs.google.com/presentation/d/1BcIBxfrEK_H6q2iZ5Aotzi6pZljIAYgWH2rtOLWRmhc/edit?usp=sharing)

## Workshops
1. [Into to NLTK](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/NLTK.ipynb), 
[Word2Vec](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/Word2Vec.ipynb), 
[Simple NN](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/Simple%20NN.ipynb)
2. [RNN](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/RNN.ipynb)
3. [Transformers by HuggingFace](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/Into%20to%20transformers%20by%20HuggingFace.ipynb). [Language modeling practical examples](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/Language%20models.ipynb).
4. [Training pipeline improvements](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/Training%20tricks.ipynb)
5. Transfer learning on GLUE tasks

## Homework
1. Into to NLP. Word Vectors:<br>
    Word Vectors
    
        1. Download english word2vec and glove vectors. 
        2. Provide 5 equations for country, person, animal, etc
        3. (Optionally) Train your own word2vec model 

    NN
    
        1. Train simple FCNN using word vectors as embeddings
        2. Use different configurations for word2vec (different embedding size) and compare model performance
        3. Try to change NN architecture based on what you have learnt on other courses.

2. RNN
    Improve accuracy on IMDB sentiment dataset:
        
        1. Compare accuracy for RNN, GRU and LSTM architectures
        2. Compare accuracy for mono- and bi-directional RNNs
        3. Try multilayer RNNs
        4. Experiment with changing batch size, maximum sequence length, dropouts and other hyperparameters.
        5. Implement max and average pooling with masking
        6. Compare accuracy and performarce for different configurations: max sequence length, number of layers, RNN hidden size etc.
        
3. Text generation

    Compare different techniques for text generation
    
        1. End penalty for repeating words
        2. Implement sampling with temperature
        3. Implement top k sampling
        4. Implement top p sampling (nuclear sampling)
        5. Compare baseline, topK and topP sampling technique results.
       
4. Fine-tuning transformers

    Fine-tune transformer for IMDB reviews classification
    
        1. Create data preprocessing pipeline using only tokenizers from `transformers`
        2. Use pre-trained transformer and add classification head for multiclass classification
        3. Compare results for different BERT sizes

    
