# Azure-IoT-Hub-Project-with-Stream-Analytics-Streaming-Data-Azure-Data-Engineering-Project

![image](https://github.com/user-attachments/assets/8e92e35f-0f0d-4b80-953c-451672fd3989)

![image](https://github.com/user-attachments/assets/68dbecf0-c3b5-4598-a812-44417321a5e6)

![image](https://github.com/user-attachments/assets/27ca4cf7-0224-459e-8e75-c6b1f86c6b21)

![image](https://github.com/user-attachments/assets/1d6e56d3-ccd4-491c-9a05-d0767621f061)


Simulator Link: https://azure-samples.github.io/raspberry-pi-web-simulator/

Working:

1.In the portal go to IoT hub, create new (i.e,no need to change any setting)

2.click on Device-add device-give any device name-save

3.inside the device created, we can see primary connection string,copy that

![image](https://github.com/user-attachments/assets/0cde20aa-07a1-4dc8-86ea-8b54e3df7884)

4.In the online simulator,copy the primary connection string in 15th line of code

5.In the portal go to Stream-Analytics JOBS,click on create and give basic details,in the storage tab click on add storage account and then create.

6.input - IoT hub -can change input alias name- no changes required in other columns.

![image](https://github.com/user-attachments/assets/84a386ee-95cc-4c9c-9ea8-78cffa2d2cb8)

7.create a storage account and give container name.

8.output - Blob storage -can change output alias name- give storage account name and container name

9.can give minimum rows(like 10) and maximum time(like 1 minute)

![image](https://github.com/user-attachments/assets/b6ac6d2f-d2ba-47bc-b1ce-333ca1ed3114)

10.click query-input -write query-save

wE CAN EVEN USE wINDOWING FUNCTIONS

![image](https://github.com/user-attachments/assets/5ca7dbbe-5b0c-47d7-94b8-c06be576dd03)

![image](https://github.com/user-attachments/assets/c684571c-8faf-4c3a-9bce-592f616ac2d5)


11. In stream analytics job,overview- start then when it shows running then 
    Run the Raspberry Pi Azure IoT Online Simulator

12.in query-input -Refresh -we can see data generated

![image](https://github.com/user-attachments/assets/51b196bd-4a2d-42bf-973a-2589e01d29be)

13.in the test results we can see output as expected.

![image](https://github.com/user-attachments/assets/0c9812e4-2331-459a-a29c-46c1fe96d444)

14.check the storage account,container -refresh and check where we can see a file gets generated

15. After completing make sure to stop job.



























