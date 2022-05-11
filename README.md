# shabd-2.0
Contains information and files for dataset shabd-2.0


# Creating samples for experiment 2
File 'df.pair.blogYtTw.equals.seed82.1000samples.csv' contains 1000 samples with equal 'actual worldlex_blog_zipf' and 'predicted worldlex_blog_zipf from (youtube_zipf+twitter_zipf)/2.0'. Similarly, there are files with 'actual zipf greater than the predicted zipf' and 'actual zipf less than the predicted zipf '.

Criterion for equality: ((actual_zipf > predicted_zipf - 0.5) and((actual_zipf < predicted_zipf + 0.5))

Criterion for greater: (actual_zipf > predicted_zipf + 0.5)

Criterion for lesser: (actual_zipf < predicted_zipf - 0.5)
