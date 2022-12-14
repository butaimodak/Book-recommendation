# Book-recommendation
<img src="https://th.bing.com/th/id/R.d044db71757c0ee05e9eace5a935d7b2?rik=J2Y%2fsDdpw4VXtw&riu=http%3a%2f%2fwww.anthonypeguero.com%2fuploads%2f1%2f0%2f6%2f5%2f106530467%2fpublished%2fbooks.jpeg%3f1522450053&ehk=fITV32XzUnWwDEY41pc9K5vcPhQXBVIVD6HmziXXEFM%3d&risl=&pid=ImgRaw&r=0" />

The objective of a recommender system is to model users' historical behaviors in such a way that we can predict what an individual user will most likely enjoy in the future. In short, we would like to create recommendations that are personalized to each user's interest(s).

In the world of recommender systems, we always speak about users and items. Items can be anything a user interacts with, ranging from: 

*   products
*   movies
*   social media posts
*   news articles
*   search results
*   photographic publications
*   restaurants
*   'pinned' articles

and so on. Not so surprisingly, a majority of internet companies we interact with on a daily basis run some sort of recommender system in the background.

These recommender systems try to predict the most relevant item to show us, according to our user-item interactions. These interactions are often categorized as implicit signals (e.g. likes, views, searches, purchases, installations, music listening behavior etc.) and explicit singals (e.g. ratings, reviews). Both types of signals can be used to help us refine how to capture the users' interest, i.e. the user preference. Of course, some signals suggest stronger proxies for user preferences (e.g. purchases, ratings) than others (e.g. views, clicks, time spent looking at an item).
 <img src = "https://user-images.githubusercontent.com/13997178/90336890-0f8fba00-dfdf-11ea-9e32-d6b00988bd10.png" width = "350">
 
 We can collect these user-item interactions to form a user preference vector, i.e. a vector that contains all historical interactions of the user with items that are relevant to our given task.

But how do we then use these user preference vectors to generate personalized recommendations?

Do we need to use all historical interactions? Doesn't the user's taste change over time? What if recommendations reinforce a user's previous choices?
Do we want to recommend complementary, substitute or independent items from what the user has interacted with previously? 
Shall we try instead to show them items that they have not yet been exposed to? 
How do we adjust the ammount of exposure items get when they are already very popular? What to do in cold-start scenarios when a new user or a new item join our platform?

These are just a few of the many considerations that we must consider before designing a recommender system for a downstream use case. There is also not a single answer to these considerations: it really depends on your individual use case. However, the answer will affect not only which models you will use, but also what data you will feed to your model, and how you will set up your objective.


