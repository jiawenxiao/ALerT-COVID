 
The code is used to build four models to predict the future cumulative CCPM (Confirmed Cases per Million) for the target countries.
-----------------------------------  

    
### The tutorial includeds data, code, model and result.
   
  
### 1、The folder of data includes source countries and target countries(which is a sample data).
    The data has been reprocessed, and every country is a file with confirmed cases per million.
          
### 2、The folder of model includes pre-trianed source model for model B ,model C and model D.  
     As the model does not use the transfer learning techniques, there is no source model for model A.

### 3、 The codes includeds four files, where each file is corresspond to the model A, model B ,model C and model D .
    In every code file, we write the process of building the source model and predicting the CCPM for the target countries .Moreover,the model D also makes a simulation experiment about keeping lockdown measures or lifting lockdown measures. 


### 4、 The folder of result includeds the result of mape metrics for target countries, which is summarized in the result.xls file. In addtion,the prediction result for the target countries about the effect on lockdown measures is included in result_predict.xls.  
    The result is also listed in the form of table and boxplot figure in our paper.
