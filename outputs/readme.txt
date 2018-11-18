CSE487-Lab5-Readme

Partner1: Der Shen Tan
Partner2: Bin Li

How to run:
1)Load file onto pyspark jupyter notebook(place into the directory that your jupyter notebook access)
2)Run All
3)2 excel csv files will be produce that show the n-gram co-occurance for both n=2 and n=3.(Name tells it all)

Platform:
We choose pyspark on jupyter notebook because it was the easiest way to setup and get all the document
running.

Output Explanation
ngram_2: Show the co-occurance for all the word pairs inside a line without it order preserve(as bina instructed).
	 It show the word pair keys and their corresponding Document.chap#.line#(no position as order not preserved)
	 that they appear in the corpus(some appears once,some more times).

ngram_3: Show the co-occurance for all the word triplet inside a line without it's order preserve. It show the word
	 triplets keys and their corresponding Document.chap#.line#(no position as order not preserved) that they 
	 appear in the corpus(some appears once,some more times).