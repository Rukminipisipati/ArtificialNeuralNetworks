# ArtificialNeuralNetworks
# Implemented on the dataset Churn_Modelling.csv whether the customer exits the bank based on few parameters such as CreditScore,Geography,Gender,Age,Tenure,
# Balance,NumOfProducts,HasCreditCard,IsActiveMember and EstimatedSalary.
# Preprocessing is done i.e. Label Encoding and One Hot Encoding is applied on features Gender, Geography respectively.
# Splitting the dataset and Feature Scaling is done on train and test set.
# Neural Network is initialized from keras which is tensorflow where the number of input layers are the number of independent features.
# In this case, 2 hidden layers are taken with 6 each neurons in it where the 'recifier' activation function is used.
# The activation function that is used in the output layer is 'sigmoid' where the probability is also obtained.
# Optimizer that is used is 'adam' which implements Stochastic Gradient Descent, loss function is 'binary_crossentropy' since the end output is either 0 or 1.
# Training the Artificial Neural Network based on epochs i.e. epochs=100 is taken in this usecase.
# Finally, the prediction is made and the accuarcy of the model is found.
 
