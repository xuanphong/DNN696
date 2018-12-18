# DS692
# PROJECT TITLE: Deep Learning with TensorFlow: Applied Regression and Neural Network to predict the Health Insurance Cost.
#
#
PROJECT SUMMARY: 
Deep Learning is very subject. In this project, Deep Learning is applied to predict the healthcare insurance price. The technique in Deep Learning is applied TensorFlow. The Methods are Applied Regression and Neural Network. The raw data is downloaded from Kaggle.com [3].
#
#
# I: MILESTONES: 
# 
 •	Overall, collect data and applied some basic analyze to find the relationship between variables in the dataset.  There are three variables are used, “charges”, “age” and “bmi” for this project.
 •	There are two methods are used in this project. It’s Regression and Deep Neural Network.  Regression is applied under the frame work of Generalized Additive Models (GAM).  In GAM, Lamda-Mu-Sigma is a method that applied to calculate and predict the results.
 •	This is a big milestone for this project.  Because TensorFlow is the main step entitle the project. 
#
# II: METHODOLOGIES:
LAMDA-MU-SIGMA method is used to applied for the Regression.  General Additive Models is a frame work for this regression.
DEEP NEURAL NETWORK method is a second methods using to compare. The black-end for running DEEP NEURAL NETWROK is Tensorflow Deep Learning.
#
# III: EXPLORE THE DATA AND CREATE THE MODELS:
Expore the data from the raw dataset, create a graphs
> MFdata=caret::createDataPartition(y=mydata$sex, p=400/600,list=FALSE)
> trainset=mydata[MFdata,]
> testset=mydata[-MFdata,]
> head(trainset)
   age    sex   bmi children smoker    region   charges
1   19 female 27.90        0    yes southwest 16884.924
3   28   male 33.00        3     no southeast  4449.462
5   32   male 28.88        0     no northwest  3866.855
6   31 female 25.74        0     no southeast  3756.622
7   46 female 33.44        1     no southeast  8240.590
10  60 female 25.84        0     no northwest 28923.137


