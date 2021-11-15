>  https://pub.towardsai.net/recommendation-system-in-depth-tutorial-with-python-for-netflix-using-collaborative-filtering-533ff8a0e444

# Recommendation system
- system generates compiled list of items user might interested
- reciprocity of their current selection of item
- doesn't recommend item that user already knows

# Complication of Recommend sys

- Real-time prediction
- Old users can have an overabundance of info
- it shoul not show items that are very differnet or too similzr
- user can change the rating of items on change of his/her mind

# Types of Recommendation systems

- content filtering recommender sys
- Collaborative filtering based recommeder systems


# Content Filtering

- expects the side information, eg : properites of song(name, siger name, language.. etc..)
- system perform well, even new items are added to the library
- system algorithm expects to include all sife properties of its library's itmes
- Expects item info
- Item information should be in a text document 


# Collaborative Filtering

- Consider usr opinions on different videos and recommend the best video to each user
- based on the user's previous rankings and opinion of othe similar tpes of user 
> Pros
- Does't need movie's side knowledge like genres
- Uses infomation collected from other users to recommend new items to current user
> Cons
- Not achieve recommendation on a new movie or shows have no ratings
- Requires the user community can have sparsity pronblem

# Collaborative filtering techniques

- Non probabilistic algorithm
- User-based nearest neighbor
- Item based nearest neighbor
- Reducing dimensionality

> Probabilistic algorithm
- Bayesian-network model
- Em algorithms

# Issues in COllaborative Filtering
- several challenges for collaborative filtering
> Sparseness
- recommendation dataest is extensive and algorithms could be vast and sparse 
- Encounters the probelm of performance
### Sparsity = 1 - |R|/|i|*|U|
- R = Rating
- I = Items
- U = Users

# Cold start 
- How to recommend a new video for users
- what video to recommend to new users

# Solutions 
- Suggest or ask users to rate vides
- Default voting for videos
- Use other techniques like content-based or demographic for the initial phase

# technique
> USer-based Nearest Neighbor
- eg : finds a set of user or nearest neighbors who have liked smae items as user and rated video 'v'
-    : Algorihms predicts
-    : Performs for all items John has not seen and recommends

<img src='https://miro.medium.com/max/607/0*oxYZH7BYScjHHGeQ.png'>
- a,b = Users
- r(a,p) = Rating of user a for item p 
- P = set of item. Rated by both users a and b

<img src='https://miro.medium.com/max/700/0*R_f6Kd-xjbZ1Vn9C.png'>

<img src='https://miro.medium.com/max/577/0*B7WsiPjWBAalw8Gd.png'>


- Cons : coputational expansiceness O 
- Performans can increase by applying the methodology of dimensionality reduction But quality of the recommendation can reduce
