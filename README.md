## Project 
### WeRateDogs Wrangle and Analyze Data

## Project Context
wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. 

## Data Sources
- Enhanced Twitter Archive \
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets

- Additional Data via the Twitter API \
Additional data that can be gathered by anyone from Twitter's API.

- Image Predictions File \
A table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images) after running all images from WeRateDogs Twitter Archive in neural network.

## Key Points

Key points to keep in mind when data wrangling for this project:

- You only want original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.

- Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.

- Cleaning includes merging individual pieces of data according to the rules of tidy data.

- The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.

- You do not need to gather the tweets beyond August 1st, 2017. You can, but note that you won't be able to gather the image predictions for these tweets since you don't have access to the algorithm used.

# How To Run

1. Create Virtual Environment using virtualenv and activate it

    ``
    virtualenv venv 
    ``
    then
    ``
    .\venv\Scripts\activate
    ``

2. Install Required Packages Numpy & Pandas

    ``pip  install numpy pandas matplotlib requests jupyter``

3. Run jupyter then run the notebook `` wrangle_act.ipynb ``

    ``jupyter notebook``

4. the Required Reports ``wrangle_report.pdf`` and ``act_report.pdf`` could be found in reports directory.

5. plots used in reports are in plots directory.
