# TED Talk Recommendation System

![Title Image](https://github.com/yamasjose11/tedtalk-recommendation-system/blob/main/images/tedtalkmainpage.png)

# Motivation and Objective

My motivation for this project is woven in my underlying passion for learning and TED Talks never fail to teach me something new. I want to see if i can replicate what most major major streaming services do and that is see if I can explore and build my very own recommender system. With this as my main focus I will try and stick to building a content based recommender using various tool and methods to achieve just that.

# Content-Base Recommender System

*A **content-based recommender** looks at the characteristics of the users and items to determine what to recommend. For instance, suppose your open a new MovieBinge account and it asks you for your favorite genres. If you say you like Science Fiction and Comedy, it might recommend Galaxy Quest.*
A content-based approach in our case gives recommendations based on the similarity bewteen different TED Talk attributes. Content-based recommenders are very efficient and very easy to interpret, and are usually great recommenders for new users. 

# The Data

My data is comprised of two datasets from data.world(link to lower reference part of page) after joining the datasets I have one dataset that contains over 2,500 offical TED Talk Transcripts up to late 2017. This is where the majority of the text-processing of the data will be conducted to make use of a better translating of a recommender. 

# Recommender System Approach

## TF-IDF Recommender

Using TF-IDF is a basic approach that helps us in creating our recommender system by evaluating the corpus and vectorizing it. This is done by using the *Term Frequency* and mulitplying it by the *Inverse of the Document Frequency*. This allows us to focus on the importance of the words used across each document. 

(EDA on words count and or recommandation of input)

## LDA Recommender

With the LDA approach we are utilizing topic modeling that allows us the discover nominal "topics" that occur in a collection of documents. Latent Dirichlet Allocation (LDA)

(EDA on words count and or recommandation of input)


# Future Development

Going forward I would like to expand on this recommender system by making it a hybrid recommender system by combining my current content based recommender system and a newly built collabarative filtering system. This will help me with exploring user personalization and better targeted recommendations.

# References

Temple, O., 2016. TED Talks- Complete List - dataset by owentemple. [online] Data.world. Available at: <https://data.world/owentemple/ted-talks-complete-list> [Accessed 31 January 2021].
