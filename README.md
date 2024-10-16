# HHA504_assignment_dbs

## MySQL

### Azure
![azure-db-settings](https://github.com/user-attachments/assets/a8357c88-d1f9-4772-8d87-b5ceb81ad341)
![azure-db-deployed](https://github.com/user-attachments/assets/7b30554b-8ebb-4170-85ea-447e58dea277)
![azure-db-details](https://github.com/user-attachments/assets/f7604761-34e3-4f9b-8cd7-8e19cf8f6c1f)

- I navigated to the Azure portal and searched for MySQL flexible servers. When setting the basic configurations, I made sure it was under the correct subscription and resource group. I gave it a server name and entered the server admin login information. For location, I had to choose south central US because when I chose the east US and west US options, the deployment always failed. Next, I selected the checkbox to add firewall rule. For the remaining basic settings, I left them as their default options. Notably, for the compute + storage configurations, they were automatically applied because there were no sections to change the options. Then, it took some time for the database to successfully deploy.
  
### GCP
![gcp-db-settings](https://github.com/user-attachments/assets/1641edfd-fab5-431f-9256-997f0b307296)
![gcp-db-settings](https://github.com/user-attachments/assets/fd23f1b7-3819-4ded-afee-ccf99e1e04be)
![gcp-db-settings](https://github.com/user-attachments/assets/27bd4513-0e5b-4bcd-bf3b-87bd19df8a96)
![gcp-db-settings](https://github.com/user-attachments/assets/acbc0afb-b5cf-4434-a2e6-a64eb745401f)
![gcp-db-settings](https://github.com/user-attachments/assets/a163ac84-8d4f-4d56-9769-d4c38b878717)
![gcp-db-settings](https://github.com/user-attachments/assets/26d3d903-38e3-468a-a8e9-511a5d096e4e)
![gcp-db-deployed](https://github.com/user-attachments/assets/b0c6186b-8f4e-4420-a443-9dade44ac6c6)
![gcp-db-details](https://github.com/user-attachments/assets/9d4d05aa-4127-4bbc-95be-1163ff7b466b)

- I navigated to GCP and searched for SQL to select the MySQL server. I pressed create instance and started by choosing enterprise instead of enterprise plus, which allowed me to choose sandbox as the edition preset. Next, I chose the latest database version and changed zonal availability to single zone. For machine configuration, I changed the machine shape to shared core and chose the lowest compute + storage option. I left the storage type as the default option of SSD and chose 10GB as the capacity because it was the lowest option. Under data protection, I unselected the checkbox labeled “enable deletion protection” to make sure I would be able to delete the instance after completing the assignment. For the remaining sections and fields (connections, data protection, maintenance, flags, query insights, and labels), I did not change any of the default options. Notably, throughout setting the configurations, I tried choosing the most basic options which slowly brought down the total cost to $0.01 per hour. Then, it took some time for the database to successfully deploy.

- *Note: When comparing the set-up experiences in Azure and GCP, Azure did not let me choose the individual configurations for compute + storage and was applied by default. While GCP allowed me to select each compute + storage setting in detail and lower the total cost.

## BigQuery

### GCP
