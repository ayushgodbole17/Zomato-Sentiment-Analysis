# Zomato-Sentiment-Analysis
This project contains notebooks that help in predicting the rating for a restaurant based on its reviews  
It consists of three notebooks:  
- zomato_create_tokenizer_pickle: Since the tokenizer takes a long time to train, I've created a notebook to create a tokenizer pickle file which can be loaded when needed into the program according to a given configuration  
- zomato_transform_data: This notebook uses the original dataset and performs pre-processing to create a final dataset, which is saved as a new csv file and used for prediction  
- zomato_prediction: This notebook trains a model based on the new dataset and predicts ratings.  


Link to original dataset: https://www.kaggle.com/code/sjk714/zomato-bengaluru-analysis  
  
The pickle file, new dataset, old dataset and saved .keras model are saved in the drive folder below. You can download it and upload it to your drive to use the notebooks without change, since they were written in a colab environment.
Drive: https://drive.google.com/drive/folders/1YJHBdUKehkwT-3JBxYBhYS1cPL0LC36L?usp=sharing
