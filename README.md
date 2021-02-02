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

  | Recommendations for *Simon Sinek: How great leaders inspire action* using TF-IDF |
  | --------------------------------------------|
   Seth Godin: How to get your ideas to spread
Scott Dinsmore: How to find work you love
Tony Robbins: Why we do what we do
Ricardo Semler: How to run a company with (almost) no rules
Jeff Hawkins: How brain science will change computing
Michael Norton: How to buy happiness
Yuval Noah Harari: Nationalism vs. globalism: the new political divide
Jessica Jackley: Poverty, money -- and love
Seth Godin: The tribes we lead


## LDA Recommender

With the LDA approach we are utilizing topic modeling that allows us the discover nominal "topics" that occur in a collection of documents. Latent Dirichlet Allocation (LDA)

(EDA on words count and or recommandation of input)

  | Recommendations for *Simon Sinek: How great leaders inspire action* using LDA |
  | --------------------------------------------|
John Maeda: How art, technology and design inform creative leaders
Sylvia Earle: My wish: Protect our oceans
Kandice Sumner: How America's public schools keep kids in poverty
David Deutsch: Chemical scum that dream of distant quasars
Colin Camerer: When you're making a deal, what's going on in your brain?
Mona Chalabi: 3 ways to spot a bad statistic
Marvin Minsky: Health and the human mind
Mathias Jud: Art that lets you talk back to NSA spies
Alain de Botton: Atheism 2.0' 'Hans Rosling: New insights on poverty

# Future Development

Going forward I would like to expand on this recommender system by making it a hybrid recommender system by combining my current content based recommender system and a newly built collabarative filtering system. This will help me with exploring user personalization and better targeted recommendations.

# References

Temple, O., 2016. TED Talks- Complete List - dataset by owentemple. [online] Data.world. Available at: <https://data.world/owentemple/ted-talks-complete-list> [Accessed 31 January 2021].
