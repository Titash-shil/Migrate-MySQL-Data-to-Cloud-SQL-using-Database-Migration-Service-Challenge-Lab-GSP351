#  Migrate MySQL Data to Cloud SQL using Database Migration Service: Challenge Lab || [GSP351](https://www.cloudskillsboost.google/focuses/20393?parent=catalog) ||

## # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

---
## ⚠️ **Disclaimer:**
#### This script and guide are provided for educational purposes to help you understand the lab process. Please ensure you understand the steps before using any scripts. Before using the script, I encourage you to open and review it to understand each step.The goal is to help you learn how to complete the labs effectively while following Qwiklabs' terms of service and YouTube's community guidelines.
---

- ## Task-1 : **Enable APIs** 
1. **Database Migration API**
2. **Service Networking API**

---
- ## Task-2 : Follow the steps carefully from the Video
---

- ## Task-3 : Run the following commands in `SSH` window to connect to the MySQL interactive console :

1. Open your terminal and execute the following command:  
   ```bash
   mysql -u admin -p
   ```  

2. When prompted for the password, enter:  
   ```bash
   changeme
   ```
---
- ### Update Records in the Database

3. Switch to the `customers_data` database:  
   ```sql
   use customers_data;
   ```  

4. Update the `gender` field for a specific record using the following SQL command:  
   ```sql
   update customers set gender = 'FEMALE' where addressKey = 934;
   ```

---

## Congratulations ..!!🎉  You completed the lab shortly..😃💯

## *Well done..!* 👏

## Thank you for visiting.... :) 🗯️

## [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)

## Join to our community [Digital Dominators](https://chat.whatsapp.com/J0o1beFGCHfJ8ZHGKjcqkd)
