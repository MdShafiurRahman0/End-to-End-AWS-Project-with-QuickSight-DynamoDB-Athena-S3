# End-to-End-AWS-Project-with-QuickSight-DynamoDB-Athena-S3

Build an End-to-End AWS Project with QuickSight, DynamoDB, Athena, S3, Hands-on Tutorial &amp; Documentation


# Arcitecture Overview

![capture_250315_145326](https://github.com/user-attachments/assets/f2a09d9d-c677-4ba5-a369-2329946af50f)


# Step 1 : Select the Region and Open AWS Quicksight 

![capture_250315_114618](https://github.com/user-attachments/assets/c7989f4e-aed7-4033-9f77-be97fea8d4d6)


![capture_250315_114639](https://github.com/user-attachments/assets/53702fa4-fe86-42de-8f20-0b2d8259dad5)


![capture_250315_114658](https://github.com/user-attachments/assets/228463a0-8b27-4bc0-9f21-28a60f34b820)


![capture_250315_114714](https://github.com/user-attachments/assets/1ab27863-61c8-4929-81e8-23ce12acc7f3)


![capture_250315_114726](https://github.com/user-attachments/assets/ee40ef9c-705b-4134-a6dd-9053f8174741)


# Note : Unselect this for avoiding bills

![capture_250315_114744](https://github.com/user-attachments/assets/31057b43-9835-4d57-822d-9feaa19aeb3b)


# Create 


![capture_250315_114826](https://github.com/user-attachments/assets/c178ec70-b060-4e8a-85cd-3ea7b0e56e0d)


![capture_250315_114957](https://github.com/user-attachments/assets/a10623eb-1294-4493-a442-545e69e9893a)


# Step 2 : In the 1st Stage what we will build

![capture_250315_115653](https://github.com/user-attachments/assets/62c39159-1696-4252-8ab1-3ff59cacf2c1)


# Go to DynamoDB

![capture_250315_115857](https://github.com/user-attachments/assets/ce193044-8096-43a3-bc28-286b95d49ebe)



# Give Table Name & Partition Key & Sort Key as given below

![capture_250315_120215](https://github.com/user-attachments/assets/738ce3d0-3d2b-4739-88ee-515cd30a1e13)


# See the Tables 

![capture_250315_120248](https://github.com/user-attachments/assets/4a22f814-04d4-4942-a160-26958267f010)



# Select Table and Click 

![capture_250315_120350](https://github.com/user-attachments/assets/57fa57c6-5166-4a0c-a8ea-646966634359)



# Click Create Item

![capture_250315_120425](https://github.com/user-attachments/assets/121a5399-f22b-4ed4-9263-695cf1834cba)

# Go to My Github Link :    

# Open this file :  

![capture_250315_120746](https://github.com/user-attachments/assets/4270d7ae-9d4f-4e26-bdad-6a57c38fb698)


# Copy the 1st 

![capture_250315_120823](https://github.com/user-attachments/assets/65522bf6-6c6b-48b3-9553-857183ed965a)

# Paste it in the JSON view 

![capture_250315_120859](https://github.com/user-attachments/assets/26ccbf08-6d0d-491a-b8ea-791463fb3f72)



# Save 

![capture_250315_120957](https://github.com/user-attachments/assets/235bdbe3-5557-4590-8740-38f22becce68)


# Trying to applying Shortcut : 


![capture_250315_121107](https://github.com/user-attachments/assets/e9ff2499-2060-4de8-a638-567a5de473bb)


![capture_250315_122513](https://github.com/user-attachments/assets/8f18e32a-419b-4f29-9718-37066211996d)


# But we Can't : 

![capture_250315_150830](https://github.com/user-attachments/assets/bddd8294-5c64-40b4-a250-c697e45b16bd)



# Repeat the same process and Create the Items in Tabels iin JSON format : 

![capture_250315_123220](https://github.com/user-attachments/assets/83cf5d76-e0b8-450d-ba45-eceba7011856)


# We have successfully Created DynamoDB for our project : 


![capture_250315_123245](https://github.com/user-attachments/assets/3230cef7-8037-42dc-bdcb-386fed108d58)


# if you see the arcitecture : 

![capture_250315_123411](https://github.com/user-attachments/assets/3c607150-9f43-41d2-9fc5-288631351263)


# we cant fetch the data from DynamoDB 

![capture_250315_123411](https://github.com/user-attachments/assets/fdf3923a-73ed-4b13-92cf-aaef7b394138)


# we need a connecter for fetching the data from DynamoDB 

![capture_250315_123420](https://github.com/user-attachments/assets/9361875a-7f4f-423e-868a-4fc8786ccc96)

# While we are setting the Lambda Connecter there is AWS Glue is auto set behind sence

![capture_250315_123457](https://github.com/user-attachments/assets/ce6a832e-bf24-4afc-8351-38982def7683)

# Open Athena in new tab 

# Choose 

![capture_250315_153117](https://github.com/user-attachments/assets/e3fa5f0e-d0ec-450c-8c53-de43dac78e1d)

# Choose Data Source 

![capture_250315_124008](https://github.com/user-attachments/assets/5b72e8c4-d361-40ec-9300-6526b9b6225f)


# Enter Data source Name : 


![capture_250315_124437](https://github.com/user-attachments/assets/f1bed1fc-fdd9-4706-bfa4-d476616c298c)

# Remeber to write the Name : 

![capture_250315_124444](https://github.com/user-attachments/assets/4def2d08-4908-4044-8c5d-20b74d32ddb2)


# Now we have to set up S3 for our project : 


![capture_250315_124750](https://github.com/user-attachments/assets/f4cbb455-e999-4f33-9119-88504f5c14f4)



# Create the Bucket : 

![capture_250315_124840](https://github.com/user-attachments/assets/c3b6338b-a97c-4ddd-b2c9-7aaebb210d1e)


![capture_250315_125032](https://github.com/user-attachments/assets/b4bf9c16-048d-45e7-8d86-3551157f541b)


# Now in go back to Athena and Browse s3

![capture_250315_125055](https://github.com/user-attachments/assets/ab9f258d-8f37-4b73-861a-c12c8dee25ab)


![capture_250315_125106](https://github.com/user-attachments/assets/c50f4ace-0a6c-4219-bec7-0ddda9616f6a)


# Give the name Spill Loaction Name : 

![capture_250315_125118](https://github.com/user-attachments/assets/c9f73109-1197-4578-b6c9-4f6120b07174)


# Review and Create :  

![capture_250315_125152](https://github.com/user-attachments/assets/206233f1-b52c-4df9-a274-79e010bd1472)


![capture_250315_125340](https://github.com/user-attachments/assets/65bf18cd-b4e3-4bd0-9c69-28f4bb80b5e9)


# Now go to the Athena Query Editor : 


![capture_250315_130344](https://github.com/user-attachments/assets/3e64203d-b05b-45f9-919f-dff9f3525892)





![capture_250315_130421](https://github.com/user-attachments/assets/35d1107f-053d-4eb9-9d2d-bf57b7e7935c)





















