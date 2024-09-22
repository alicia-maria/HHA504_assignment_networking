# Networking in Azure and GCP - IP and Domain Management 
### *Creating a Virtual Private Cloud (VPC)*
  **Azure**
  ![Screenshot_22-9-2024_1060_portal azure com](https://github.com/user-attachments/assets/5f8d1010-ecd0-4120-895f-b4048a7ac5fa)
  ![Screenshot_22-9-2024_10658_portal azure com](https://github.com/user-attachments/assets/a288a317-ac50-4082-a9f9-b762ea5b72e5)
![Screenshot_22-9-2024_10125_portal azure com](https://github.com/user-attachments/assets/8ff51284-6de1-4955-899b-f68fefe68c60)

**GCP** 

![Screenshot_22-9-2024_101823_console cloud google com](https://github.com/user-attachments/assets/a1e7c8b8-8895-4bf5-a3a9-48ee82f70bb6)


### VPN and Tunneling Steps 
**Azure**
1. create the virtual network
2. create a gateway subnet
   - Define Address Range
3. Then save
4. Create a resource virtual network gateway
5. Create
6. Then Configure local gateway network by clicking create
7. Then we are going to establish VPN conenction by nativaging to VNG we created in step 4
8. Then click on Setting , Connections , and + add
9. The click OK

**GCP**
1. Set vnet and then we are going to create a cloud router
2. click network , hybrid connectivity , cloud router
3. then create router
4. After we are going to connect VPN to VPC by navigating to the gateway
5. Then clicking tunnel section
6. creating tunnel
7. After tunneling we are going to configure
8. click VPC network , then routes
9. create route
10. add destination
11. set the hop to VPN tunnel
