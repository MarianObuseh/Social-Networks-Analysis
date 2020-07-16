# Wikipedia Graph Analysis
Here, I use networkx to retrieve 2 pages - "Aqualung" and "Ian Anderson" (Classic Rock, good stuff!) from Wikipedia. I then compare them using graph analysis by running separate searches. Each search is limited to 2 “layers” deep in terms of traversing their links. Each breadth-first-search (BFS) is also further limited to no more than 50 iterations. Also, each graph built is also  cut down to only include nodes that have degree ≥ 2 and self-loops are discarded. I'm tryna triage my search. I then perform some analysis to compare and contrast both graphs. 

The jupyter notebook uploaded doesn't show the output of each cell because it was a pretty large file. Running the codes took a while, so I advise you run on your machine to see the results.
