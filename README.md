# Netflix Advanced Data Science and Engineering Bootcamp: Final Project

The purpose of our project is to predict the popularity of a song based off of its audio features. Popularity is determined by the number of plays a song has. The audio features include things like energy, valence, danceability, and more.

We looked at songs that were released from 2010 to 2020. Each song received a popularity score from 0 to 100, 100 being the most popular. We separated the songs into 5 bins based on its popularity. However, due to the distribution of the songs, there was an imbalance between the bins so we had to resample our data. We also used polynomial features to better expose the important relationships between the input and the target values. This changed our 16 original sudio features to 135 features.

## Model

85% is the accuracy of our model by using the Random Forest Classifier when paired with all of the polynomial features and by resampling our data with the RandomOverSampler. Our model had the highest precision and recall when predicting the top 20% of songs as well as the least popular songs.

## Conclusion

The model acts like a great filter that will find the songs that have a really good chance of being popular. And this is important because it will allow us to help promote potential up and coming stars to reach top charts which will grow subscribership, allow for new stars to be born, as well as provide a tool that artists themselves can use to ride the current trend waves to boost their platform.
