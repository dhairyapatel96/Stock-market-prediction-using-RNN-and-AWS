# Stock-market-prediction-using-RNN-and-AWS
1.create AWS account.
2.create an IM role.
3.create sagemaker instance. note: Do not change any default settings. select previously created IM role for that. wait few minutes for "active" status on sagemaker instance. 

4.open Jupyter notenook from that instance.
5.This directory contains all files needed to run and benchmark to predict stocks. Just upload the entire directory on SageMaker.

6.Run the SageMakerNotebbok.ipynb file. file path: Code<inputdata<SageMakerNotebbok.ipynb
7.Read comments in the code if any error occurs. Comments most probably solve the errors.
8.If you are done with all, get back to amazon sagemaker instance and stop the instance from action tab. Note: by not doing this, instance won't turn off automatically and AWS keep charging you the money in USD.

9.remove the instance if you don't want to do anything in this project. Note: by not doing this, instance have the project load and AWS keep charging you the money in USD for that too.

Note: Amazon sagemaker service is not a free tier. You have to get ready to pay some USD for the usage.

Note: some files are same when you're working on sagemaker or AWS. There is no copyright issue for that. 
