# 2023-DTU-Computational-Tools-For-DS-Amazon-Food-Reviews

This repository is a part of the DTU's Computational Tools for Data Science project. The project "Amazon Fine Food Reviews Analysis" applies Data Science tools to analyze potential improvement opportunities for the Amazon portal. The conclusions are presented in the report (not part of this repository). Data for this project are from a public source: [https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/data](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/data).

## Table of content

* Data
  * `data/sample_no_agg.csv` <br>
    5% of the data
  * `data/sample.csv` <br>
    `sample_no_agg.csv` aggregated by user ID
  * `data/text_df_1/2/3.feather` <br>
    Processed texts in three batches for limited transfer purposes
  * `data/no_text_df.feather` <br> 
    Data without text
  * `data/database.sqlite` <br>
    Main, raw data for the project - it is too big to get on GitHub - needs to be downloaded from [here](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/data)
* Preprocessing
  * `ProcessData.ipynb` <br>
  Processing texts and saving to feather
* Time series
  * `TimeSeries.ipynb` <br>
    Time series analysis without Sentiment part
  * `Sentiment.ipynb` <br>
    Change of sentiment in time and many more
* Graphs
  * Graphs with connections based on ID
    * `graphs/product_product_graph.pickle` <br>
      Saved Product-Product graph
    * `graphs/user_product_graph.pickle` <br>
      Saved User-Product graph
    * [`user_user_graph.pickle`](https://drive.google.com/file/d/1x4EKxJjlEmsimqgxqIRjWBBMULFHF7xk/view?usp=sharing) <br>
      Saved User-User graph (on Google Drive - too big for GitHub)
    * `graphs.ipynb` <br>
      Creation of User-Product, Product-Product and User-User graphs
    * `ID_Graph_analysis_I.ipynb` <br>
      Analysis of User-Product and Product-Product graphs
    * `user-user_graph.ipynb` <br>
      Analysis of User-User graph
  * Graph of similar reviews
    * `data/similarity_dict.json` <br>
      The jacquard similarity between users
    * `signatures.ipynb` <br>
      Creating similarity_dict
    * `signatures_utils.py` <br>
      Helper functions for computing similarities
    * `signatures_graph.ipynb` <br>
      Analysis of the graph of similar reviews
