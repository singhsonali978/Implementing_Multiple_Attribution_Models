# **Cross-channel marketing spend optimization using deep learning**

## **Developed a Data-pipline using  Amazon AWS** 


 ![Alt Text](https://github.com/singhsonali978/Implementing_Multiple_Attribution_Models/blob/master/Data%20Flow.png)

**Data** -  https://s3-eu-west-1.amazonaws.com/attribution-dataset/criteo_attribution_dataset.zip

# **Steps**
1.  Amazon AWS was used by setting up **EC2 instance** with Ubuntu server-16 setup a Jupyter Notebook. 
2   Data was loaded on the **S3 bucket.**
3.  With web **AWS Glue crawler** connected it to **AWS Athena**.
4.  The output of the Model was saved in the S3 bucket.
5.  The data is connected to the **Apache SuperSet** for visulaization.
 
![Alt Text](https://github.com/singhsonali978/Implementing_Multiple_Attribution_Models/blob/master/superset_visualization.png)

Python notebook will run on **google colab** with changes to data path and saving location.


