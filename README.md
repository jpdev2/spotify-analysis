# Netflix Advanced Data Science and Engineering Bootcamp: Final Project

The purpose of our project is to predict the popularity of a song based on its audio features. Popularity is determined by the number of plays a song has. The audio features include energy, valence, danceability, and more.

We looked at songs released from 2010 to 2020. Each song received a popularity score from 0 to 100, 100 being the most popular. We separated the songs into five bins based on their popularity. Due to the distribution of the songs, we had to resample our data. We also used polynomial features to expose better critical relationships between input and target values. This changed our 16 original audio features to 135 features.

## Model

85% is the accuracy of our model by using the Random Forest Classifier when paired with all of the polynomial features and by resampling our data with the RandomOverSampler. Our model had the highest precision and recall when predicting the top 20% of songs and the least popular songs.

## Conclusion

The model acts like a great filter that will find the songs with a good chance of being popular. This allows us to help promote potential up-and-coming stars to reach the top charts, which will grow subscribership, allow for new stars to be born, and provide a tool artists can use to ride the current trend waves to boost their platform.
