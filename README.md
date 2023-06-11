# DM-Algorithms
Data Mining Algorithms Implementations

This repository includes:
- SMOTE (Synthetic Minority Over-sampling Technique): An algorithm used in machine learning to generate synthetic samples of minority class data points by interpolating between existing instances, helping to address the class imbalance problem.
- CURE (Clustering Using Representatives): A clustering algorithm that identifies representative points to represent clusters, compresses the data, and iteratively refines the clustering process, making it suitable for large-scale data sets.
- Similar-items, which contains:
  - Shingling: A technique used to represent documents as sets of overlapping consecutive tokens (or "shingles") to capture local textual information and facilitate similarity analysis between documents. 
  - MinHashing: A technique used to estimate the similarity between sets by hashing their elements and comparing the resulting hash values, providing an efficient approximation of the Jaccard similarity.
  - Local Sensitive Hashing (LSH): A method that hashes high-dimensional data points in a way that similar points are likely to end up in the same or nearby hash buckets, enabling efficient approximate nearest neighbor    search and similarity retrieval. This method is being used by Google for tasks like detecting duplicate articles, similarity search, recommendation systems, and large-scale data analysis.
- Frequent-items, which contains:
  - A Priori: An algorithm that efficiently discovers frequent itemsets in a dataset by utilizing an iterative approach based on the "apriori" property.
  - PCY (Park-Chen-Yu): An efficient variant of the Apriori algorithm that uses hash-based counting techniques to identify frequent itemsets, reducing the need for multiple passes over the data and improving performance.
