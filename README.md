# Netflix-Movie-Recommendation-System
Built and implemented Netflix Movie Recommendation System (Collaborative Based Recommendation) in Python, XGBoost, KNN, SVD
<h2> 1.1 Problem Description </h2>
<p>
Netflix is all about connecting people to the movies they love. To help customers find those movies, they developed world-class movie recommendation system: CinematchSM. Its job is to predict whether someone will enjoy a movie based on how much they liked or disliked other movies. Netflix use those predictions to make personal movie recommendations based on each customer’s unique tastes. And while <b>Cinematch</b> is doing pretty well, it can always be made better.
</p>
<p> Credits: https://www.netflixprize.com/rules.html </p>
<h2> 1.2 Problem Statement </h2>
<p>
Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. (Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.) 
</p>
<h2> 1.3 Sources </h2>
<ul>
<li> https://www.netflixprize.com/rules.html</li>
<li> https://www.kaggle.com/netflix-inc/netflix-prize-data</li>
<li> Netflix blog: https://medium.com/netflix-techblog/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429 (very nice blog)</li>
<li>surprise library: http://surpriselib.com/ (we use many models from this library)</li>
<li>surprise library doc: http://surprise.readthedocs.io/en/stable/getting_started.html (we use many models from this library)</li>
<li>installing surprise: https://github.com/NicolasHug/Surprise#installation </li>
<li> Research paper: http://courses.ischool.berkeley.edu/i290-dm/s11/SECURE/a1-koren.pdf (most of our work was inspired by this paper)</li>
<li> SVD Decomposition : https://www.youtube.com/watch?v=P5mlg91as1c </li>
</ul>
<h2>1.4 Real world/Business Objectives and constraints  </h2>
<h4> Objectives </h4>
<p>
1. Predict the rating that a user would give to a movie that he ahs not yet rated. <br>
2. Minimize the difference between predicted and actual rating (RMSE and MAPE) 
</p>
<h4> Constraints </h4> 
<p>
1. Some form of interpretability.
</p>
