# Modeling individual attention dynamics on online social media
Jaume Ojer, Filippo Radicchi, Santo Fortunato, Michele Starnini, and Romualdo Pastor-Satorras


- `individualAttention_model.ipynb`: code for the model.
- `days.npy`: number of threads' days sampled from the spline interpolation of $P(T)$ observed in ChangeMyView (CMV).
- `comments.npy`: number of threads' comments sampled from the spline interpolation of $P(N)$ observed in CMV.
- `activity.npy`: number of comments posted by users sampled from the spline interpolation of $P(\eta)$ observed in CMV.
- `discussionTree.zip`: number of comments posted in threads throughout the days. The temporal decay follows the empirical thread-specific time series $\tilde{n}_i (t)$. In order to be read in the notebook `individualAttention_model.ipynb`, one must decompress it to the original `discussionTree.json` file.
- `fitness.npy`: fitness of users sampled from the posterior distribution given by the Bayes' rule.
