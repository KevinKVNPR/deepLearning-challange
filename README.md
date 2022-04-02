# deepLearning-challange

Deep Learning: Charity Funding Predictor
We were able to predict from a dataset, containing more than 34,000 organizations that have received funding from Alphabet Soup over the years, whether a campaign would be successful or not using machine learning and neural networks.
•	Data Preprocessing:
o	On the first try, columns EIN and NAME were removed from the dataset the as irrelevant information. These columns were neither targets, nor features. Everything else was considered as features for the model. 

o	The data was split by IS_SUCCESSFUL and the rest of the features. IS_SUCESSFUL was the variable target for the model. 

o	For the Optimizer, column NAME was part of the features. Only EIN was dropped.  

•	Compiling, Training, and Evaluating the Model:
o	We applied a three-layer model. The number of hidden nodes were decided by the number of features. The first model gave out 659 params vs 3480 in the optimized one. 

 
	 
o	On the first try we achieved 73% accuracy, once we optimized the model we were able to achieve 78%
 
 
o	We played around increasing the hidden layers and the numbers of nodes. After several tries, the accuracy would not surpass 75% 
o	Increasing the data by incorporating the column NAME, gave the model more to train with. That is how 78% accuracy was achieved. 
Summary: 
This deep learning model was most effective when provided more data. By leaving in NAME and encoding categorical values, more unique features were added to the model. This gave the model more params to train with.
![image](https://user-images.githubusercontent.com/90887472/161398468-344189ff-838e-413c-a232-76246e3d880a.png)
