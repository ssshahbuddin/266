# Final Project Readme

## Less is More: Data Augmentation Through Summarization for Sentiment Analysis Prediction
This repo is the culmination of my efforts on the w266 final project. The research paper along with all notebooks, saved models, and additional files can be found here. Here is a breakdown of all the files and folders contained in this repository.

shahbuddin_w266_final_project_less_is_more_final_paper.pdf: The full report PDF.

summarization: Folder contains all contents related to the summarization task.
- summmarization_training: Contains notebooks with the code totrain the summarization models.
-- pegasus_amazon_training.ipynb: The first training of the summarization model.
-- finetuned_pegasus_amazon_training.ipynb: The finetuned training of the summarization model.

- model_weights: Folder containing the saved model weights including the configuration files, tokenizers, and training argument. 
-- pegasus-amazon: The first training of the summarization model. Related to the pegasus_amazon_training.ipynb notebook.
-- pegasus-amazon2: The finetuned summarization model. Related to the finetuned_pegasus_amazon_training.ipynb notebook.

- generated_summaries: Folder containing all the the notebooks to create the summaries as well as the outputs of those notebooks.
-- imdb_test_set_summarization_generation.ipynb: The notebook to create the summaries for the IMDB test set for all models.
-- pegasus_amazon_finetuned_summarization_generation.ipynb: The notebook to create the summaries from the finetuned summarization model.
-- pegasus_amazon_summarization_generation.ipynb: The notebook to create the baseline summaries from the pre-trained model as well as the first trained summarization model.
-- test_data: Folder containing the csvs of the test set summaries for all three models.
-- training_data: Folder containing the csvs of the training set data.

sentiment_analysis: Folder containing all contents related to the sentiment analysis task.
- saved_models: Folder containing compressed files of the trained sentiment analysis models. 
- test: Folder containing notebooks to run the Sentiment Analysis Prediction on the test set.
-- distilbert_sentiment_analysis_test_set.ipynb: Notebook to run all the sentiment analysis models on the test set data.
-- imbalanced_dataset_distilbert_sentiment_analysis_test_set.ipynb: Notebook to run the sentiment analysis models on the imbalanced training dataset.
- validation: Folder containing the notebooks on the training and validation set.
-- distilbert_amazon_trained_sentiment_analysis.ipynb: Predicitons using the first trained summarizations.
-- distilbert_CNN_pegasus_trained_sentiment_analysis.ipynb: Baseline predictions using the pre-trained summarizations
-- distilbert_finetuned_amazon_trained_sentiment_analysis.ipynb: Predictions using the finetuned summarizations

