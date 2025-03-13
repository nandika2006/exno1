# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
            import pandas as pd
![image](https://github.com/user-attachments/assets/4b11c3a2-22de-4ac3-b83c-5fe605a144ed)


            #READ CSV FILE HERE
![image](https://github.com/user-attachments/assets/fb1c0664-2867-470d-94ef-b3762c5a2edd)

            #DISPLAY THE INFORMATION ABOUT CSV AND RUN THE BASIC DATA ANALYSIS FUNCTIONS
![image](https://github.com/user-attachments/assets/b87a3314-237a-48d3-8f49-219de7a50a1b)

            #CHECK OUT NULL VALUES IN DATA SET USING FUNCTION
![image](https://github.com/user-attachments/assets/b68d7b98-9a8d-4e6b-8498-dba17fc1296d)
![image](https://github.com/user-attachments/assets/c2284e59-a819-4a75-9699-eb614ea49b4a)

            #DISPLAY THE SUM ON NULL VALUES IN EACH ROWS
![image](https://github.com/user-attachments/assets/384aaa0d-b53d-43ed-8e24-c39d177b0217)


            #DROP NULL VALUES
![image](https://github.com/user-attachments/assets/410fb370-b349-4c67-86c7-48ca926b8a44)

            #FILL NULL VALUES WITH CONSTANT VALUE "O"
![image](https://github.com/user-attachments/assets/2cfe3362-748f-4777-9031-f0aa005f5a75)


            #FILL NULL VALUES WITH ffill or bfill METHOD
![image](https://github.com/user-attachments/assets/f96f0de3-c7f3-40ee-862e-a2f62fa3f133)

            #CALCULATE MEAN VALUE OF A COLUMN AND FILL IT WITH NULL VALUES
![image](https://github.com/user-attachments/assets/317aafea-4c91-4482-8b36-3d331ca0c388)

            #DROP NULL VALUES
![image](https://github.com/user-attachments/assets/6a29d8a6-1473-4dd8-a1ba-b77cb03b6cdf)

            import pandas as pd
            import seaborn as sns
            age=[1,3,28,27,25,92,30,39,40,50,26,24,29,94]
            af=pd.DataFrame(age)
            af
            
            #USE BOXPLOT FUNCTION HERE TO DETECT OUTLIER
![image](https://github.com/user-attachments/assets/1c9eac28-af29-46aa-83c2-71e69eb47ef4)

            #PERFORM IQR METHOD AND DETECT OUTLIER VALUES
![image](https://github.com/user-attachments/assets/0168fbaf-b8a8-45dc-be7b-793bf66e15d9)
![image](https://github.com/user-attachments/assets/5d7d9e10-41ec-4ea3-b79a-edf9b174ea69)

            #REMOVE OUTLIERS
![image](https://github.com/user-attachments/assets/b0fa99e5-d926-4dcd-ad42-f61e60f4d56e)
![image](https://github.com/user-attachments/assets/9973a3f7-4530-4dc3-87b3-cb3afb6e1022)
![image](https://github.com/user-attachments/assets/c1ae6801-c2a2-41a7-bfd2-34eb58156f87)

            #USE BOXPLOT FUNCTION HERE TO CHECK OUTLIER IS REMOVED
![image](https://github.com/user-attachments/assets/dc9d7e7f-c192-4de6-afdd-89cb4cfd1d55)


            from scipy import stats #STATS METHOD IS USED TO IMPLEMENT Z SCORE METHOD
            data=[1,12,15,18,21,24,27,30,33,36,39,42,45,48,51,54,57,60,63,66,69,72,75,78,81,84,87,90,93,96,99,158]
            df=pd.DataFrame(data)
            #USE BOXPLOT FUNCTION HERE TO DETECT OUTLIER
![image](https://github.com/user-attachments/assets/c4168ef6-7bc9-4598-b665-50554f50e12f)

            #PERFORM Z SCORE METHOD AND DETECT OUTLIER VALUES
![image](https://github.com/user-attachments/assets/4824a2dc-3780-4483-8306-82566ef30481)

            #REMOVE OUTLIERS
            #USE BOXPLOT FUNCTION HERE TO CHECK OUTLIER IS REMOVED
![image](https://github.com/user-attachments/assets/949379fa-e57a-4298-b263-49515e1dea93)

     










     










# Result
          <<include your Result here>>
