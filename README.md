# Extractive-text-summarization-of-Amazon-reviews1. First make sure Jupyter Notebook is installed on the system.

Project was done as a part of the Information Retrieval course. The goal is to summarize Amazon reviews of top 10 movies using extractive summarization techniques. We use a form of hierarchical clustering to efficiently summarize various reviews and use PageRank based algorithms like LexRank and TextRank along with Latent Sematinc Analysis and SumBasic algorithms to sumarize reviews and generate gold summaries as well. We also pre-classify each review as either positive or negative using sentiment analysis to make the summaries more robust and devoid of false positives. We compare the performance of the 4 algorithms and achieve a ROUGE score 0f 0.5 on avearge with the highest of 0.81 for LSA. 

Details of the pre-processing and the the algorithm adopted for hierarchical clustering can be found in detail in the the report. 

To run the code. please follow below steps and feel free to get in touch in case of errors, bugs or improvements:

1. First make sure Jupyter Notebook is installed on the system.
2. In the terminal go to the directory containing main.ipynb.
3. Run jupyter notebook main.ipynb.
4. Run all cells in notebook.

Dependencies - 
 a) numpy
 b) matplotlib
 c) seaborn (for better plotting)
 d) pandas
 e) textblob (for trained naive bayes classifier and text processing)
 f) sumy (https://github.com/miso-belica/sumy)
 g) re (for regular expressions)
 h) tqdm (for progress bar)
