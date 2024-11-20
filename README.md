# MeeshoChallenge

Hi, I am Hriday Desai. I participated in this contest as a solo participant. I have attained 42 rank in the private leaderboard.

# My Approach:
I have separated the five categories of clothing and imputed the missing product attribute values for each of their attributes by developing a CNN based imputer model which I trained on the available data in each attribute and then hence worked with a completely labelled dataset. At the end I trained a ResNet based Cnn model with the number of output_heads same as the number of attributes for that category. 

As a Preprocessing step for some images, I also utilized OpenCV to improve the color quality and highlight certain regions of the image. I feel highlighting the edges inside the dress can help us effectively make out the pattern present on the dress which can be very useful for sarees and kurtis particularly. Color is one area where the model gave low accuracy scores and probably should have been decided by using some different model instead of a simple CNN model.

I enjoyed taking part in this competition. My code is present in these five notebooks which I ran using Kaggle GPUs. Feel free to run them and use them to your advantage. Open to improvements and suggestions from the community.
