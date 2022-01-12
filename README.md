# data-science-python-coding

Python coding challenges (non-leetcode type problems) commonly asked in data science interviews. 
They include random variable sampling, statistical simulation, ML and statistical model implementation, etc.


The title of each problem directs to the notebook file. Texts below title are the description of the problem.

## 1. [weighted sampling](/solutions/weighted_sampling.ipynb)

You are given n numbers in an array `nums`, as well as probabilities <img src="https://render.githubusercontent.com/render/math?math=p_0, p_1, ..., p_{n-1}"> which sum up to 1 in an array `probs`. How would you generate one of the n numbers according to the specified probabilities?

For example, if the numbers are 3, 5, 7, 11, and the probabilities are 9/18, 6/18, 2/18, 1/18, then 1000000 calls to your program, 3 should appear roughly 500000 times, 5 should appear roughly 333333 times, 7 should appear roughly 111111 times, and 11 should appear roughly 55555 times.
