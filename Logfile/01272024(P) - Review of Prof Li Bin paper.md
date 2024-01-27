1. Analysis of this paper

1.1. Useful information/method
- The cited SEG annotation tool can be useful for identifying NER in Chinese texts, but I was unable to retrieve the paper from a Google search.

1.2. Improvements that could be made:
- Automated recognition of persons with the same name (somehow, with some confidence level). This is similar to our objective of identifying the same concept in many documents, but we want to do that manually (possibly using BERT to extract semantic meaning)

1.3. Some points for reflection
- Do we really want to automate the identification of similar concepts, or is manual tagging for large-scale analysis (like what Prof Li Bin did) valuable enough? We may also need this as a kind of ground truth.

2. Details of the paper (it is concise, but here are some points for quick reference)
2.1. General approach
- Segment each word and tag as noun, verb, adjective, person name, place name - SEG annotation tool [1] (Unable to access this)
- Person is given a unique ID (including other names) - manually assigned
- Place is given a unique ID and locational information - GIS coordinates using Baidu map

2.2. Subject
Scope:
- Basic Annals (first twelve chapters Shiji)
Eventual goal:
- Make comparisons between the Zuozhuan and Shiji database

2.3. Analysis:
Place
- Showing a state or country based on the places mentioned within it (important since places did not have clear boundaries)
- Heat maps for the places where each of the basic annals occured
Social relationships
- Co-occurrence of persons in a text (separated by commas or periods)
- Manually checked if this indicated a social relationship, with accuracy of ~84.73%.

Citations:
[1] Shi, M., Li, B., & Chen, X. (2010). CRF based research on a unified approach to word segmentation and POS tagging for Pre-Qin Chinese. Journal of Chinese information processing, 2(24), 39-45.