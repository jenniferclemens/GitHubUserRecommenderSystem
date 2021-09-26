# GitHubUserRecommenderSystem
An attempt at creating a smaller scale User-Profile Recommender System for GitHub based on second degree connections between the users.

GitHub Users API can be found [here](https://api.github.com/users).

The API has limited access and, hence, the data of 60 users is saved as [dataset.txt](https://github.com/jenniferclemens/GitHubUserRecommenderSystem/blob/main/dataset.txt) file.
The code can be found in [getDataset.ipynb](https://github.com/jenniferclemens/GitHubUserRecommenderSystem/blob/main/getDataset.ipynb).

[SmallScaleRecommender.ipynb](https://github.com/jenniferclemens/GitHubUserRecommenderSystem/blob/main/SmallScaleRecommender.ipynb) is the jupyter notebook containing the code for the final recommender system. The final recommendations are given as ranks.
