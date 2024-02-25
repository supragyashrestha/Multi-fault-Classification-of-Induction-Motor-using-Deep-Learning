# Multi-fault-Classification-of-Induction-Motor-using-Machine-Learning

Problem -

In several manufacturing processes, induction motors are essential components. Therefore, it is becoming increasingly important to track induction motors online. The primary
problem in this role is the lack of an appropriate theoretical model to characterize a defective motor with multiple forms of faults, such as winding faults. This leads to unintended
faults in various motor components. In their early stages, these defects are normally left ignored and conclude with disastrous system failure.


Solution -

The process flow begins with pre-processing the data and designing the appropriate model architecture. This is followed by the model's training and testing over the data to get the final predictions. These predictions are then further checked and analyzed to better the existing model.


Brief Results-

Basic neural networks gave accuracy much less than CNN and LSTM.
* For the Basic neural network, the f1-score is low for labels 0-6 indicating that the model is not performing better in predicting those values.
* So in comparison to a simple NN, CNN performs much better as the given data is large(4498000 rows X 10 columns).
* LSTM is a type of RNN that helps in processing this sequential data and thus performs even better.

For further information read this - https://github.com/supragyashrestha/Multi-fault-Classification-of-Induction-Motor-using-Deep-Learning/blob/master/Final-BTP-report-INT9.pdf
