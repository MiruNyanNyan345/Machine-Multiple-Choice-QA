# Machine-Multiple-Choice-QA
**COMP5423 Group Project**

## Project Requirements
Please read "COMP5423-Group-Project.pdf"

1. Conventional Feature-based
  * Based on traditional mathematics and statistical methods
3. Transformer Learning Bert-based
  * Only applying Bert Encoder to train the model
  * No Fine-Tuning
4. Bidirectional Encoder Representation with Transformer-based
  ⭐️ My responsible task
   * QA Dataset
    * MC Test
    * RACE
    * Dream
   * Differnet transformers are applied on different dataset
    * Depends on the dataset size and the type of the questions and answers
   * Involving Fine-Tuning

## Bidirectional Encoder Representation with Transformer-based
# Sentence Emotion 

## Environment
1. Colab

# Data File
1. MCTEST
2. RACE
3. DREAM

# Program File
1. Bidirectional Encoder Representations from Transformers
   1. mctest_bert_large.ipynb
   2. mctest_albert.ipynb
   3. race_distilbert.ipynb
   4. race_albert.ipynb
   5. dream_albert.ipynb

## Installation
1. Go to Google Colab and upload the program file that you would like to run on it.
<img src="https://i.imgur.com/ZTLpr4i.png" width="500">

1. Drag and drop datasets to Colab and open it \
<img src="https://i.imgur.com/CVsQBza.png" width="200">

3. Replace the dataset paths to yours storing location \
**⭐️ Important ⭐️** \
🙀 If you follow the above step to open the program file and uploads the datasets to colab, the dataset's location in program file does not need to be changed.
🙀 Different task depends on different dataset and program. 
    1. mctest_bert_large.ipynb == MCTEST
    2. mctest_albert.ipynb == MCTEST
    3. race_distilbert.ipynb == RACE 
    4. race_albert.ipynb == RACE
    5. dream_albert.ipynb == DREAM

* dream_albert.ipynb
<img src="https://i.imgur.com/H22fywN.png" width="600">

* race_distilbert.ipynb & race_albert.ipynb
<img src="https://i.imgur.com/idIUW4E.png" width="600">

* mctest_bert_large.ipynb & mctest_albert.ipynb
For the mctest dataset, please only replace the path of the file, if you are not storing the same the dataset in the same location as the original program file.
<img src="https://i.imgur.com/ibxSbhY.png" width="600">


1. After that, you are able to run the program \
<img src="https://i.imgur.com/o6vvsea.png" width="500">

