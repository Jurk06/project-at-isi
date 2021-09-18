
# Analysis of riskiness of the well across the different states of India
# Introduction:  
As we know that world is facing huge crisis of water. There is scarcity of drinkable water. Beside that in India the reliability of water heavily depends upon the wells, ponds etc. This has triggered the crisis. The aim of this project is to analyse the dataset that I received form my Prof. A.B (ISI Kolkata) and analysis of missing features and a solution to impute the missing values and find the riskiness of well i.e. the wells which are more prone to scarcity. Before finding out the riskiness of the well, I have performed data preprocessing , ANOVA is perforfomed , Visualization, Imputataion , Trend Analysis these steps have been performed .

![image](https://user-images.githubusercontent.com/22790745/132808385-86c1c482-387a-466a-a63f-b468ac2a5e88.png)

![Indian Map](https://user-images.githubusercontent.com/22790745/132087350-3e5269f9-fed2-410b-9c9d-ddf38582e5db.png)

# Dataset:
The dataset is of csv format, pandas library helps to read the csv dataset. Beside that we import some bunch of library in order to future work.
![Dataset](https://user-images.githubusercontent.com/22790745/132087281-326390bf-ef10-485c-870e-4483c37f0808.png)


# [ANOVA Analysis](https://www.kaggle.com/jurk06/one-way-anova-analysis) 
It is perfomed in order to get that the significant difference between the independent variables and the featurs. Here I have performed One-way analysis as there is only one independent features we have.

# [Visualization](https://www.kaggle.com/jurk06/indian-map#Well-depth-Analysis) 
The main job here is to plotting the different wells on India map. Since latitute and logitude of all the wells are given in the dataset. I have done the plotting work in th notebook. Bisede that we can see the visualization of the other features as well.

 **Missing Values-**  AS we can see that due to some reason we can see the missing value is in great number. So before analysis we need to impute those misssing values based on the distribution of the 


# [Multiple Imputation](https://rabkumarisinghisikolkata.medium.com/visualization-and-multiple-imputation-734b9e73f2b2)
Here I have mention the technique that will impute the missing value. You can read my blog here in order to understand the whole process behind the imputation and why I have taken this imputation as one of the best before procedding teh modelling .

# [Trend Analysis](https://www.kaggle.com/jurk06/trends-analysis):
Since I have performed the trend analysis as the year is mentioned and as per the year the depth of water table is mentioned. Since I have done the ananlysisn and find out how th eimputatiion works. Though I have mentioned on my blog and also mentiond the conclusion.


#  [Clustering](https://colab.research.google.com/drive/1qAO2AvGzeaz2ozA63z8BkLNZw1-mfiUF?usp=sharing) 
![image](https://user-images.githubusercontent.com/22790745/132794271-830acbb9-bab7-4cb0-9ec1-7ce370396850.png)


After the imputation the main aim is to find the different cluister of the of all well with the given well depth. The cluster can be analysed with defferent range of well depth. The objective is to make sure or identify the well which have the more the depth. 

# [Clustering 2](https://colab.research.google.com/drive/1qAO2AvGzeaz2ozA63z8BkLNZw1-mfiUF?usp=sharing)
THe work is done here . I have divided the work based on the refion or we can say that I have clustered based on the distance. I have performed the hirarchical clustering the divise method . For more about this cluster we can read it from the different book or kaggle.
