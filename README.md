# Classify-Song-Genres-from-Audio-Data-with-Decision-Trees

<p><em>These recommendations are so on point! How does this playlist know me so well?</em></p>
<p><img src="https://assets.datacamp.com/production/project_449/img/iphone_music.jpg" alt="Project Image Record" width="600px"></p>
<p>Over the past few years, streaming services with huge catalogs have become the primary means through which most people listen to their favorite music. But at the same time, the sheer amount of music on offer can mean users might be a bit overwhelmed when trying to look for newer music that suits their tastes.</p>
<p>For this reason, streaming services have looked into means of categorizing music to allow for personalized recommendations. One method involves direct analysis of the raw audio information in a given song, scoring the raw data on a variety of metrics. Today, we'll be examining data compiled by a research group known as The Echo Nest. Our goal is to look through this dataset and classify songs as being either 'Hip-Hop' or 'Rock' - all without listening to a single one ourselves. In doing so, we will learn how to clean our data, do some exploratory data visualization, and use feature reduction towards the goal of feeding our data through some simple machine learning algorithms, such as decision trees and logistic regression.</p>
<p>To begin with, let's load the metadata about our tracks alongside the track metrics compiled by The Echo Nest. A song is about more than its title, artist, and number of listens. We have another dataset that has musical features of each track such as <code>danceability</code> and <code>acousticness</code> on a scale from -1 to 1. These exist in two different files, which are in different formats - CSV and JSON. </p>
<br>

# Dependencies
<br> - sklearn.decomposition.PCA
<br> - sklearn.model_selection.train_test_split
<br> - sklearn.tree.DecisionTreeClassifier
<br> - sklearn.preprocessing.StandardScaler
<br> - sklearn.linear_model.LogisticRegression
<br> - from sklearn.metrics.classification_report
<br> - from sklearn.model_selection.KFold
<br> - from sklearn.model_selection.cross_val_score
<br> - Matplotlib
<br> - Numpy
<br> - Pandas


### Please check the <a href='https://github.com/Mohamedsoliman828/Classify-Song-Genres-from-Audio-Data-with-Decision-Trees/blob/main/notebook.ipynb' >Nootebook</a> for detailed description
