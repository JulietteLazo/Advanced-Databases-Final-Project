# Advanced-Databases-Final-Project

This academic report describes the development of an infrastructure based on Elasticsearch to manage and analyze heterogeneous (unstructured) data from a simulated social network. The summary of key points is as follows:

Objective: The project seeks to demonstrate the capability of NoSQL databases to simultaneously store and query text, images, and social relationships, looking for a correlation between a user's social influence and the emotional polarity of their posts.

Technologies Used: Elasticsearch was used as the search and document storage engine, Python for orchestration and sentiment analysis (using TextBlob), and NetworkX for graph analysis and calculation of centrality metrics.

Key Findings: The system allowed for the processing of heterogeneous data with latencies under 100 ms. A positive correlation was identified between social centrality (influence) and positive sentiments; more influential users tend to generate emotionally more stable content.

Conclusion: The use of NoSQL technologies offers the flexibility and scalability required for Big Data, overcoming the rigidity limitations of traditional relational systems in social media contexts.
