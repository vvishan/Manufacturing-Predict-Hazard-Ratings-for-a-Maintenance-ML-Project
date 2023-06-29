## Predict Hazard Ratings for a Maintenance Project - ML project

All the money in the world can not make up for a loss of life. Better safe than sorry is the motto of
all engineering and construction practices which routinely deal with dangerous situations.
However many times , extent of caution is just not enough and leads to very hard learnt lessons
in employee safety .
Instead of relying on something going wrong and then taking preventive measure ; organisations
are coming up with ways of assessing the extent of danger to life for a new project before even
the first hammer strikes .
Given to you is a masked dataset which contains various properties of tasks taken up in heavy
equipments maintenance by a manual crew. Each of these tasks have been given a hazard score
which is eventually used in deciding levels of safety checks and caution while planning for the
maintenance process.

#### Data Files
Train Dataset = Hazard_train.csv
Test Dataset = Hazard_test_share.csv

#### Formal Problem Statement
Variable names are masked and there is no formal data dictionary provided by the client .
Your task here is to build a predictive model for predicting hazard score given other information
related to maintenance tasks. You need to build your model on the train dataset. Test dataset
does not have a response column; you need to predict those values and submit it in a csv
format.
target column = Hazard
