# **Magazine Recommendation Systems**  

## **Project Overview**  
This project explores seven recommendation models to enhance magazine recommendations using the **2018 Amazon Product and Reviews dataset**. Models were built to either **suggest similar magazines** or **predict user ratings**. Some recommendations were compared against Amazon’s actual suggestions for validation.  

## **Models & Results**  
### **Recommendation Models (Suggest Similar Magazines)**  
1. **Collaborative Filtering - Item-Based**  
2. **Collaborative Filtering - User-Based**  
3. **Content-Based Model** 
4. **K-Nearest Neighbors (KNN)**  

### **Rating Prediction Models**  
5. **Non-Negative Matrix Factorization (NMF)** – RMSE: **1.1**  
6. **Singular Value Decomposition (SVD)** – RMSE: **1.13**  
7. **Factorization Machine** – RMSE: **1.009**  

## **Dataset**  
- Extracted **magazine category** from **Amazon 2018 Product & Reviews dataset**  
- Includes user reviews, ratings, and product metadata
- Data Augmentation: Age and Gender data sampled from MovieLens dataset to augment additional user details and built Factorization Machines model


## **Impact**  
Successfully built 7 models and Predicted user rating with RMSE of 1 rank. 
Magazine recommendations matched Amazon website recommendations as highlighted in the presentation.


