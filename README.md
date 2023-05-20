# Specific-skill-mining-in-Github
In recent days, the need for fast and efficient data mining in social networks has
become increasingly important to ensure users can quickly access their desired
information. The field of social network research is continuously evolving, with new
methods and approaches being developed to enhance the efficiency of social
network mining. In this context, we will focus on mining data from a specific social
network, GitHub, using an advanced method known as the Graph Convolutional
Network (GCN) algorithm. Our aim is to extract information in a more productive
manner, thereby improving the overall mining process.

# Project Problem Description
For our project we will mine on github information, this is basically a graph-based
problem involving nodes and edges .
• Our task is to look into github users repositories and predict whether the user fits
in a specific category or not. In this case we will determine if a user is a web or
machine learning developer
• Our primary dataset consists of social network of GitHub developers which was
collected from the public API in June 2019.
• This problem related to binary node classification.
• Nodes are developers who have starred at least 10 repositories and edges are
follower relationships between them. features are based on location, starred
repositories, employer, and email.

# Motivation 
• Most of the Algorithms we found are involved clustering, eccentricity and
centrality measure of the nodes, skim-gram node embedding etc.
• These measures are not inherently designed for node classification tasks
• It increases complexity in processing features as more computation and
normalization of data is required
• Redundancy occurs when two or more features provide almost the same
information, leading to an unnecessary repetition of information in feature set.
• For larger data or graph scalability issue happens while calculating centrality
and eccentricity measures as it has high computational complexity.
• These measures provide global information about graph structure but do not
fully captures local information about immediate neighbourhood nodes.
