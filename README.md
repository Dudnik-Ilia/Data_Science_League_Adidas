# Data Science League in Adidas
As a part of a team from Friedrich-Alexander-Universität, we participated in the Data Science League hackathon which was organized by Adidas, where we took **4th** place. 

Adidas provided the following task: predict measurements for foot's last that would minimize customer's (in e-commerce) return probabilities of a product. 

## Scorer function 
Trains the **xgboost** regressor to predict the return rate (mean between too_large and too_small) and finetune it with a randomized search. 
You can load the model using the _my_pipeline.joblib_ file without training from the beginning.

## Deap genetic search
Sets up a genetic search using **deap** for the best last measurements for each _tuple(sport, sex)_ using the model we trained before.
You can call the _Score_ class that will predict the mean return rate given _tuple(sport, sex)_ and last's 6 measurements.

## Team Members

-  [Ilia Dudnik](https://www.linkedin.com/in/ilia-dudnik/)
-  [Dmitrii Maksimov](https://www.linkedin.com/in/maksimov-dmitry/)
-  [Isa Bagirov](https://www.linkedin.com/in/isabagirov/)
-  [Aman Qureshi](https://www.linkedin.com/in/aman-qureshi/)
-  [Hana Ibrahim](https://www.linkedin.com/in/hana-h-ibrahim/)
