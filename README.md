# Callbacks

Here I created a custom callback in Keras in tf backend. That can be used in ML training. Using the callback I train the mnist dataset, which is available is in tf, with my custom callback. The acc on val set is more than 93.5%.    

To see the learning rate in cmd type `Get-Content .\log.txt -Wait` (windows) it will show the live progress of training with starting and ending log, along with training and val acc. Check the `log.txt` for details.
