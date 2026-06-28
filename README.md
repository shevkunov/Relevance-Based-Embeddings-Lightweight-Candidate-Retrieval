# Relevance-Based-Embeddings-Lightweight-Candidate-Retrieval
Code and data for Relevance-Based Embeddings: Lightweight Candidate Retrieval via Heavy Ranker Calls

**Disclaimer:**

1. This code is not a source of pride, as the project was quite lengthy, and I find it difficult to remember where everything is located.

2. If you want to conduct additional experiments, I suggest that writing a new implementation from scratch will be easier than reusing the current one, especially since the underlying rbe idea is quite simple.

________________

## Hints where to find exps data:

Table 1. Support item selection - 

./proof-of-concept-open-data-round4-clustering.ipynb + other (below);

Table 2. Evaluating neural relevance-based embeddings - 

./exps/proof-of-concept-open-data-round5-5-parallel.ipynb - kmeans approach

./exps/proof-of-concept-open-data-round6-greedykey.* , ./exps/proof-of-concept-open-data-popular-as-a-key-ksdev.ipynb - l2_greedy approach

./exps/proof-of-concept-open-data-round_music.*

./exps/proof-of-concept-open-data-round7-ms-query.*
;

Table 4. DE vs RBE on RecGames, Table 7. DE vs RBE on RecGames1 (extended) - 

./exps/proof-of-concept-open-data-round9-anx-bubo.ipynb

./exps/new_proof-of-concept-open-data-round10-eval-anx-comp-data-bubo.ipynb

./exps/new_proof-of-concept-open-data-round10-prepare-anx-comp-data-bubo.ipynb;

Table 8. QA sample, different heavy ranker - 

./exps/proof-of-concept-open-data-round7-ms-query-ce9650.ipynb

;

Table 9. Category prediction on RecGames1 -

./exps/proof-of-concept-open-data-round10-mlp-classifier.ipynb ;

________________

(yet to be found)

Table 5. DE vs RBE on RecMusic - (tbd);

Table 10. Average and standard deviation for AnnCUR over 15 launches - (tbd);

Table 11. Popular as support items selection - (tbd);

Table 12. Support items selection on downsampled data; HitRate(100) is reported (larger is better) - (tbd);

