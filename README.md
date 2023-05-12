# Gaussian-CPA
Python code designed for Google Collabs to analyze camera style blinkg data using change point analysis

Features include:
- creating synthetic camera style blinking
- analyzing real and synthetic camera style blinking data

1_Find_QDs: takes PL videos of QDs blinking and selected the QDs from the video and extracts the blinking traces

2_Gaussian_CPA_Fittings: takes extracted blinking traces and fits them using change point analysis

3_Widefield_Post_CPA_Individual_Batch_Processing: crunches the numbers from step 2 and outputs the statistics of the blinking in an individual batch

4_Widefield_Batch_Comparison: compiles and plots the results of 3 run across multiple batches
