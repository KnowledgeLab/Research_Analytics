# This Research Analytics Repo

This is the repository for the Author-Topic Model visualization.

# Introduction 
There are three main step to generate the D3 visualization for the author topic model
  * pre-process the corpus data to the a bag-of-words format, then fit the author topic model
  * Analysis the theta and phi generate from the author topic model
  * Generate the D3 network visualization 

# Data pre-process 

Generate_Cpp_Tsv_From_Corpus.ipynb is a python notebook contains all the necessary python code to transfer the corpus data into the data that can be recognized by the cpp code (fit the author topic model, the cpp code can be found on the turingcomput.net).

# Generate html and analysis
Analysis_and_Generate_html.ipynb is a python note book contains all the necessary python code to analysis the result generate from the cpp code and generate the html file. By analysis, here means that this python notebook will use knn algorithm and KL-divergence to classify the researches and color the network vertex.



