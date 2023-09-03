# Product Recommendation System using Amazon Electronics Dataset 


## Introduction to Recommendation systems

In today's data-rich world, we often struggle to extract relevant information from the overwhelming amount of data available to us. To address this issue and assist users in discovering product information, recommendation systems were developed.

Recommendation systems establish connections between users and items, leveraging these connections to provide suggestions. These systems can address several key challenges:

What recommeder system can solve ?

1. Facilitating accurate product discovery for users.
2. Enhancing user engagement; for instance, Spotify's recommendation system led to a 50% increase in user time spent on the platform.
3. APersonalizing content, as demonstrated by Facebook's recommendation algorithms, which help users discover relevant posts, groups, and friends, resulting in increased user engagement and time spent on the platform.
4. Personalizing content, as evidenced by Netflix, where a significant portion of movie rentals originates from recommendations.

## Learning Outcomes:  
E-commerce platforms such as Amazon and Flipkart employ various recommendation models to offer tailored suggestions to their diverse user base. Presently, Amazon utilizes item-to-item collaborative filtering, a highly scalable approach capable of delivering top-notch real-time recommendations, even for extensive datasets.

#### ● Exploratory Data Analysis 
#### ● Building a recommendation system model using real data 
#### ● Comparing KNN, baseline, co-clustering algorithms and SVD 

## Data Description:  
Link :  https://www.kaggle.com/datasets/saurav9786/amazon-product-reviews

The dataset here is taken from the below website.

Source - Amazon Reviews data (http://jmcauley.ucsd.edu/data/amazon/) The repository has several datasets. For this case study, we are using the Electronics dataset.


### Domain: 
E-commerce

### Attribute Information:
 

● userId : Each user is identified with a unique id 

● productId : Each product is identified with a unique id 

● Rating : Rating of a particular product by the corresponding user 

● timestamp : Time of the rating(ignored for this problem)

## Steps and tasks: 

#### 1. Explore the dataset by renaming columns, plotting histograms, and analyzing data characteristics. 
#### 2. Create a denser subset of the data, retaining users with 50 or more ratings.
#### 3. Randomly split the data into training and test sets using a 70/30 ratio. 
#### 4. Build Popularity Recommender model.  
#### 5. Build Collaborative Filtering model. 
#### 6. Evaluate both models by calculating the Root Mean Square Error (RMSE) on test data predictions. 
#### 7. Generate the top 5 recommendations for each user to suggest new products based on their preferences.  
#### 8. Summarize key insights from the analysis and modeling process.