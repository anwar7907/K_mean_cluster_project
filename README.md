# K_means_cluster_project
For this project I will use KMeans Clustering to cluster Universities into to two groups, Private and Public.  

# Note:
The data have labels, but I will not use them in the model.

# Columns    
Column Name | Description
------------ | -------------
Private | A factor with levels No and Yes indicating private or public university
Apps | Number of applications received
Accept | Number of applications accepted
Enroll | Number of new students enrolled
Top10perc | Pct. new students from top 10% of H.S. class
Top25perc | Pct. new students from top 25% of H.S. class
F.Undergrad | Number of fulltime undergraduates
P.Undergrad | Number of parttime undergraduates
Outstate | Out-of-state tuition
Room.Board | Room and board costs
Books | Estimated book costs
Personal | Estimated personal spending
PhD | Pct. of faculty with Ph.D.’s
Terminal | Pct. of faculty with terminal degree
S.F.Ratio | Student/faculty ratio
perc.alumni | Pct. alumni who donate
Expend | Instructional expenditure per student
Grad.Rate | Graduation rate

# Problem:  
Whether the university is public or private?

# Goal:
Create a cluster model that will help predict whether the unviersity is priavate or puplic.

# Summary of the solution:
## 1. Data overview:
   1. Data type
   2. Number of columns
   3. Numbers of rows
   4. Data description and statistical summary
## 2. Data Analysis Exploration (EDA)
   1. Scatterplot for graduation rate and room and board costs per each type of unversities
   2. Scatterplot for fulltime undergraduates and Out-of-state tuition per each type of unversities
   3. Histogram for Out-of-state tuition per each type of unversities 
   4. Histogram for graduation rate per each type of unversities 
## 3. Setting up the data for machine learning
   1. Model train
       * K_means clustering model
         * KMeans
## 4. Model predection
## 5. Model evaluations
   * Classification_report
   * Confusion_matrix
