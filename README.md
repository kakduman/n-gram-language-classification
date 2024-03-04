Main results/writeup is in /results.ipynb. Code is in /code-project-1/main.ipynb. It is also available at https://github.com/kakduman/cs482/. To begin running the code, you will need to download the Tatoeba Sentences dataset into the data/tatoeba/ directory: https://downloads.tatoeba.org/exports/sentences.tar.bz2

# Character-based N-gram Modeling Predicts Language Groups and Evolution
Koray Akduman | March 3, 2024

# Introduction
The study of language evolution and grouping is a pivotal area of research that delves into the origins, development, and classification of languages. Understanding unlocks the mysteries of human communication, social dynamic, and even biological evolution (Dunbar, 1997). Languages serve as a mirror reflecting the socio-political changes, migratory patterns, and cultural interactions of different communities. By tracing the genealogy and transformation of languages, researchers can piece together the puzzle of human civilization and its diverse manifestations.

In this paper, as a proof-of-concept, we implement a simple character-based n-gram approach that successfully predicts commonly recognized language families (e.g. "West Germanic," "Romance," etc.) in a completely unsupervised manner, using k-means clustering and Uniform Manifold Approximation and Projection (UMAP) to visualize the vectors. Further, our character-based n-gram approach classifies languages like "Old German" and "German" into the same language group, demonstrating an ability to trace backwards in time to determine the evolution of language through machine learning. Our results also show that a character-based n-gram approach is able to find the relationships between different language groups, predicting, for example, that West Germanic and North Germanic languages are similar.