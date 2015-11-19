## Exercise 10

Write a MapReduce program in Hadoop that implements a simple “People You Might Know” social network friendship recommendation algorithm. The key idea is that if two people have a lot of mutual friends, then the system should recommend that they connect with each other.

### Input

Download the input file from the [link](https://github.com/tonellotto/PAD-LABS/tree/master/data/soc-LiveJournal1Adj.txt).
The input file contains the adjacency list and has multiple lines in the following format:

Use a simple algorithm such that, for each user U, the algorithm recommends N = 10 users who are not already friends with U, but have the most number of mutual friends in common with U.


The output should contain one line per user in the following format:


It is possible to solve this question with a single MapReduce job. But if your solution requires multiple map reduce jobs, then that’s fine too.