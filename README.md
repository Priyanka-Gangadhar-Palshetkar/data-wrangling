# Data Wrangling

Data wrangling consists of:
- Gathering data 
- Assessing data
- Cleaning data

Final Step is storing, analyzing, and visualizing your wrangled data

### Project Context: 
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The following packages (libraries) need to be installed. You can install these packages via conda or pip.
pandas
NumPy
requests
tweepy
json
seaborn

### Working with Twitter API:

How to Query Twitter Data
In this project, you'll be using Tweepy to query Twitter's API for additional data beyond the data included in the WeRateDogs Twitter archive. This additional data will include retweet count and favorite count.

Some APIs are completely open, while others require authentication. The Twitter API is one that requires users to be authorized to use it. This means that before you can run your API querying code, you need to set up your own Twitter application. Here are the steps to do that on the Twitter site:

- First, if you do not already have one, you need to sign up for a Twitter account.
- Next, to set up a developer account, follow the directions on Twitter’s Developer Portal, in the “How to Apply” section.
- You will be guided through the steps, and asked to describe in your own words what you are building.
- Once you submit your application, you should soon receive an email from Twitter letting you know they have approved your new Twitter developer account. Follow the link in the email from Twitter to a page of directions to get started creating your app.
- If you are asked for an app name, it can be anything appropriate, and if you’re asked for a Website URL, it can be anything in a standard URL format. You can do the same with other requested URLs, or perhaps leave them blank.
- You'll be asked to add how your app will be using the API
- Once that is done, complete the process. You should then be given a Success message, and a new developer page displayed to you where you can manage your app.
- You can then go to the Keys and Tokens tab on this page to find or generate the Consumer API keys, and the Access Token and Access Token Secret that you will need.
