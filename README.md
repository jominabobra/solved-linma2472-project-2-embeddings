Download Link: https://assignmentchef.com/product/solved-linma2472-project-2-embeddings
<br>
<h1>Assignment 1: node embedding and clustering</h1>

Take the character co-occurrence network from the previous homework. If you haven’t done it already, then add weights to the edges that represent how many times the co-occurrence happened. Thus the co-occurrence network is a sort of an embedding of the story into the metric space of a graph. The goal is to compare this embedding with the embedding based on text.

Use the partition into communities as computed by the Louvain method as a benchmark.




<ul>

 <li>Train a Word2Vec model on the corpus of your book. Cluster the vectors of characters using k-means clustering algorithm using the same number of clusters as output by the Louvain algorithm. Compare the two clusterings using <strong>Jaccard similarity</strong>. Find the parameters of W2V that best resemble the Louvain clusters and those that produce a completely different clustering. Which clustering, in your opinion, better reflects the real communities from the story?</li>

</ul>




<ul>

 <li>Visualise the embeddings and clusters in 2D using a dimensionality reduction algorithm of your choice.</li>

</ul>




<h1>Assignment 2: text embedding and classification</h1>




Attached you find two real datasets of comments from Reddit – one from the subreddit /r/JoeBiden of supporters of Joe Biden and one from the subreddit /r/The_Donald of supporters of Donald Trump. Both sets were collected in March, 2020. Imagine your goal is to learn if those two groups speak the same type of language.




<ul>

 <li>Perform an embedding of the comments using BERT and Doc2Vec (Word2Vec for sentences). Remember to first do the appropriate text preprocessing.</li>

</ul>




<ul>

 <li>Train a classifier of your choice to separate the comments of one subreddit from another. Perform training on the provided training set. Test your classifier on the provided test set of comments. Achieve and report the best <strong>accuracy</strong> of your classifier on training and test sets. Best results will be announced on the lecture.</li>

</ul>







<strong>Report guidelines (</strong><strong>to add): </strong>




<ul>

 <li>We highly recommend to google about specific terms if they are not clear.</li>

 <li>Write in a concise and structured manner. No long sentences, only relevant information.</li>

 <li>You may present your data and the preprocessing steps, but remember that this isn’t the main goal of the report</li>

 <li>Any numerical results that can be presented in a table should be presented so.</li>

 <li>Round numbers up to 3<sup>rd</sup> digit, unless it’s really necessary. Don’t copy-paste 10 digit floats.</li>

 <li>Plots must be easy-to-read. Must include labels on axes, legend if more than one curve is shown, title or a caption, explaining what the plot is about.</li>

</ul>