This is the first part of a project I am working on, to try and predict whether a rocket will take off and succeed in its misson, or fail; using logistic regression. As of now, I have collected data, by scraping the "year in spaceflight" articles from wikipedia,  and have cleaned them into usable data.

The steps that remain that I hope to implement in the near future are:
1) Feature engineeering of this data into numbers that can actually be fed to the learning algorithm
2) Train the model on this data to predict rocket launches
3) From the data, it is also evident that the number of successes in spaceflight are far greater than the number of failures (around 8 successes for 2 failures	)(as rocket launches are expensive, and only rockets that have been extensively tested are reused in regular missions.). The model should therefore be trained even more extensively on failures to try and pick up patterns on why the rare failure does end up happening.

As of know this is a data scraping project, but I hope to use this data for the purposes of machine learning soon.
