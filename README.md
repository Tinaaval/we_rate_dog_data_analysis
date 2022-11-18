# (Dataset Exploration Title)
## by Tina RAZAFINDRAKOTO


## Dataset

The dataset that will be processed in this project concerns data from the archive of tweets from Twitter user @dog_rates, 
also known as WeRateDogs. 
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 
These ratings almost always have a denominator of 10 and numerator almost always higher than 10

this includes 3 datasets which contains:
- mainly the tweets with the notes of each dog
- Additional data with the number of retweets and the number of favorites
- Image prediction file table filled with image predictions (the first three only) with the ID of each tweet, 
  the URL of the image and the number of the image corresponding to the most reliable prediction 

## Summary of Findings

1- Which dog breeds appeared most often in the tweets

2 - Which dog breeds are most likely to be recognized by the breed prediction tool

3- Is there a correlation between the number of appearance of races on tweets and the ability of the prediction tool to recognize them 

In the exploratory part, we found that :
the more we have tweets with dog images, the more the prediction tool will accumulate good dog breed predictions
the golden retriever breed is the most tweeted breed,
the less the breed of the dog is tweeted, the less the algorithm will be able to predict its breed, 

## Key Insights for Presentation

The main thread from this exploration is based on analysis of these relationship:
- number of dog in the tweets and their breed
- number of dogs and the probability of recognition of breed
- the number of appearance of breed on tweets and the prediction

the step that have been made are the creation of bar and scatter plot to display:
number of probable breeds that appeared in the tweets,
number of dogs with a probability of recognition > 50%
correlation between the number of appearance of races on tweets and the prediction