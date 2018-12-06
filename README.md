# Natural Language Processing Repo 

Key features: Tensorflow implementation of 

## 1. Seq2Seq (machine translation)
       
    encoder: LSTM
    
    decorder: LSTM with beam search
    
    dataset: Eng-french translation dataset
    
## 2. Show attend and tell (Image Captioning) Attention modelling 	 
    
    encoder(Convnet-VGG),
    
    attention model: Bahdanua Attention, 
    
    decoder: LSTM with beam search     
    
    dataset: COCO 

## 3. Sentiment Analysis

     encoder: multilayer LSTM 
     
     decoder: Classification Dense Layer
     
     dataset: Imdb-dataset

## 4. Loading pre-trained word embeddings 
    
    facebook: multilingual embeddings: MUSE 
    
    stanford: glove 
    
## 5. Template for flask API to hosting trained model on AWS  
