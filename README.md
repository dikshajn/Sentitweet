# Sentitweet
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sentiment Analysis Readme</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }

        h1 {
            text-align: center;
        }

        p {
            margin-bottom: 15px;
        }

        .code {
            background-color: #f9f9f9;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Sentiment Analysis Readme</h1>
        <p>Sentiment analysis refers to identifying and classifying sentiments expressed in text sources. This project focuses on developing an Automated Machine Learning Sentiment Analysis Model using Twitter data.</p>
        <h2>Getting Started</h2>
        <p>The project requires authentication via the Twitter API. A new application needs to be created to obtain the necessary keys. Additionally, install the required libraries:</p>
        <div class="code">
            <p>pip install tweepy</p>
            <p>pip install textblob</p>
            <p>pip install nltk</p>
        </div>
        <h2>Problem Faced</h2>
        <p>One of the challenges faced is the presence of non-useful characters (noise) along with useful data in the tweets. This project aims to analyze tweet sentiments by developing a machine learning pipeline.</p>
        <h2>Pre-requisites</h2>
        <ul>
            <li>Tweepy - Python library for accessing the Twitter API</li>
            <li>TextBlob - Python library for processing textual data</li>
            <li>NLTK dataset - For better natural language processing</li>
            <li>Keys from Twitter Developer Application Management site:</li>
            <ul>
                <li>Consumer key</li>
                <li>Consumer secret</li>
                <li>Access token</li>
                <li>Access token secret</li>
            </ul>
        </ul>
        <p>The dataset provided consists of 7000 tweets extracted using the Twitter API.</p>
    </div>
</body>

</html>
