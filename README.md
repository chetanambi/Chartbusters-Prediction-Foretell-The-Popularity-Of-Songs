# Chartbusters-Prediction-Foretell-The-Popularity-Of-Songs
![image](https://user-images.githubusercontent.com/37707687/72431243-5e137680-37ba-11ea-8654-770ece1b9640.png)

One of our customers strongly believes in technology and has recently backed up its platform using Machine Learning and Artificial Intelligence. Based on data collected from multiple sources on different songs and various artist attributes our customer is excited to challenge the MachineHack community.

By analyzing the chartbusters data to predict the Views of songs, MachineHackers would advance the state of the current platform. This can help our customer understand user behaviour and personalize the user experience. 
In this hackathon, we challenge the MachineHackers to come up with a prediction algorithm that can predict the views for a given song.

Can you predict how popular a song will be in the future?

## Files description:
- Data_Train.csv – the training set, 78458 rows with 11 columns.
- Data_Test.csv – the test set, 19615 rows with 10 columns, except the Views column.
- Sample_Submission.csv – sample submission file format for reference.

## Brief Descriptions of Attributes in Dataset
- Unique_ID : Unique Identifier.
- Name : Name of the Artist.
- Genre : Genre of the Song.
- Country : Origin Country of Artist.
- Song_Name : Name of the Song.
- Timestamp : Release Date and Time.
- Views : Number of times the song was played/viewed (*Target/Dependent Variable*).
- Comments : Count of comments for the song.
- Likes : Count of Likes.
- Popularity : Popularity score for the artist.
- Followers : Number of Followers.

## Evaluation Metric
RMSE(Root Mean Squared Error)

## Leaderboard
Rank 4
![image](https://user-images.githubusercontent.com/37707687/72492038-e1c47600-3841-11ea-8cfe-689fa42d631a.png)

## Notes

| File                                                      | Fold     | Score        |
| ----------------------------------------------------------| ---------|--------------|
| chartbusters-prediction-foretell-the-popularity_v54.ipynb | fold_7   | 520151.69581 |
| chartbusters-prediction-foretell-the-popularity_v59.ipynb | fold_3   | 511965.95912 |
| chartbusters-prediction-foretell-the-popularity_v72.ipynb | fold_6   | 525530.79732 |
| chartbusters-prediction-foretell-the-popularity_v85.ipynb | fold_6   | 518122.56894 |
| chartbusters-prediction-foretell-the-popularity_v86.ipynb | fold_5   | 514858.48954 |
| chartbusters-prediction-foretell-the-popularity_v86.ipynb | fold_6   | 505227.74804 |
| final-ensemble.ipynb                                      |          | 482023.65000 |

## Leaderboard

Public LB: 22/883
Private LB: 25/883

