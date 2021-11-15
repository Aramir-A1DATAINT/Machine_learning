# https://pub.towardsai.net/recommendation-system-in-depth-tutorial-with-python-for-netflix-using-collaborative-filtering-533ff8a0e444
'''
Recommendation system
- system generates compiled list of items user might interested
- reciprocity of their current selection of item
- doesn't recommend item that user already knows
'''

# Complication of Recommend sys
'''
Real-time prediction
Old users can have an overabundance of info
it shoul not show items that are very differnet or too similzr
user can change the rating of items on change of his/her mind
'''

# Types of Recommendation systems
'''
content filtering recommender sys
Collaborative filtering based recommeder systems
'''

# Content Filtering
'''
expects the side information, eg : properites of song(name, siger name, language.. etc..)
system perform well, even new items are added to the library
system algorithm expects to include all sife properties of its library's itmes
Expects item info
Item information should be in a text document 
'''

# Collaborative Filtering
'''
Consider usr opinions on different videos and recommend the best video to each user
based on the user's previous rankings and opinion of othe similar tpes of user 
Pros
Does't need movie's side knowledge like genres
Uses infomation collected from other users to recommend new items to current user
Cons
Not achieve recommendation on a new movie or shows have no ratings
Requires the user community can have sparsity pronblem
'''

# Collaborative filtering techniques
'''
Non probabilistic algorithm
User-based nearest neighbor
Item based nearest neighbor
Reducing dimensionality

Probabilistic algorithm
Bayesian-network model
Em algorithms
'''

