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












# Result
          <<include your Result here>>
