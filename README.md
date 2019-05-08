# RIAN
Recurrent Imitation Analyst Network - automated tip generation using linguistic features


This project aims to automate tip generation across multiple industries and topic domains by leveraging human classified training data.  Data is collected from BuzzSumo, and features are engineered from the data (including article titles, authors, domains hosting the page) as it is collected via the API.  

Stage 1:  Collect news content related to a variety of brands/companies across industries.

Brands in collection for initial study:
Alcon
Cargill
Maverick Management
All-State
Delta
Bank of America
Walmart
NBC/Universal
Sony Pictures
Live Nation / Ticketmaster 
Warner
Paramount
Hulu
Uber
Tesla
Netflix
CAA
Activision
Whole Foods
Papa Johns
Chipotle
Wells Fargo
United HealthCare
Pepsi
AEG
Marriott
Gamestop
Bird
Lyft
Southwest
Visa
AT&T
Pixar
LA Lakers
Anheuser Busch

Stage 2:  Human classification of articles from this corpus.  Articles will be manually assigned "tip/no tip" grading from human analysts on the CS / Threat Intel team to produce a human curated training data set on the basis of whether or not a particular article would merit a tip.

Stage 3: Linguistic features will be identified from the article titles (key words, n-grams), as well as other features already present in the data set.  

Stage 4: Train TensorFlow/NN/RandomForest model to classify articles on the basis of how much a given article "looks like" it should be a tip.
