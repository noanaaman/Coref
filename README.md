# Coref

This script does the following (I hope):
1. collects all the files you need
2. splits each file into documents and the documents into sentences and the sentences into tokens.
3. each token has its annotations
4. it locates all the mentions and their cluster ID
5. it collectes all the mention-pairs for training/predicting
6. once you have predictions from your classifier, it can cluster pairs and then write back the IDs with brackets in the write format
7. then you can output your results like the evaluation script requires