# NLP course

To set virtual environment you should stay on root folder and run next command: `python3.6 -m venv venv`.  
Then you have to active virtual environment with `source venv/bin/activate`.  
After activation install packages from `requirements.txt`. To do it run `sh requirements_installation.sh`.  
To work comfortably with jupyter notebooks you should install kernel for your environment:
```bash
pip install ipykernel
ipython kernel install --user --name=nlp-course
```

## Lectures

1. [Into to NLP. Word Vectors](https://docs.google.com/presentation/d/1xFc0h9nrc1lrAHKsRC3WHWrA9RxVW6J5BqdWvM-16Lk/edit?usp=sharing)
2. [Recurrent neural networks](https://docs.google.com/presentation/d/13ar7A9MWugvGeD-07FhRR8UVPs7JZrQhM4xuKsU0oW8/edit?usp=sharing)
3. [Into to language models. Transformers](https://docs.google.com/presentation/d/1KprnkUt1b8feQhCySrSEdu9qkHE8P4OnpcpZ9wIWNqk/edit?usp=sharing)
4. Transfer Learning for classification
5. Transfer learning for different NLP tasks

## Workshops
1. [Into to NLTK](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/NLTK.ipynb), 
[Word2Vec](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/Word2Vec.ipynb), 
[Simple NN](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/Simple%20NN.ipynb)
2. [RNN](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/RNN.ipynb)
3. Transformers by HuggingFace. Language modeling practical examples.
4. Transfer learning for classification
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

