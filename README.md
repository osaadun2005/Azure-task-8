# Azure-task-8
Security Configuration , Backup, Disaster Recovery, And Expected Outcome.



1. **Task Overview**

   - Security Configuration
   - Backup And Recovery
   - Owner: Intern/ Osa Adun
   - Instructor: Gabriel Mekuleyi
   - Start Date: November 23, 2025
   - Status: Completed




2. **Perequisite**

  - Microsoft Azure Platform
  - Azure subscription
  - Azure CLI installed (az)
  - Virtual Network Configuration
  - Virtual Machine Configuration




3. **Steps to Deploy**

  - Step 1: Login to Azure

   <img width="1280" height="590" alt="image" src="https://github.com/user-attachments/assets/bb63ac91-3ba3-4d91-968f-85ee87a0ee0a" />

  
  
  - Step 2: Create Resource Group 

     <img width="1008" height="569" alt="image" src="https://github.com/user-attachments/assets/6ec4ab00-af95-4b08-add3-efceb11a8e3f" />


  - Step 3: Display Of Created Resources

    <img width="986" height="535" alt="image" src="https://github.com/user-attachments/assets/aacf63c2-852e-44ef-a0b6-e9b1b35d53f0" />
    

  - Step 4: Configure Network Security Group (NSG)

       -  FrontendNSG

    <img width="963" height="497" alt="image" src="https://github.com/user-attachments/assets/91fcb704-1047-4394-a51f-b764f3cef501" />

       - Inbound Security Rule : 3000

    <img width="922" height="411" alt="image" src="https://github.com/user-attachments/assets/ef80ffc3-c8a9-48e5-863a-c43de8fd7513" />

    <img width="1080" height="974" alt="image" src="https://github.com/user-attachments/assets/ee7bb741-4964-4998-9d1a-20c7971bd91f" />

    <img width="969" height="502" alt="image" src="https://github.com/user-attachments/assets/fb91a8de-54fa-47fc-8c16-ad8937618d65" />

       - BackendNSG

    <img width="994" height="512" alt="image" src="https://github.com/user-attachments/assets/b41d7fc7-ffde-4c08-bbb9-47aed5cc87e8" />

       - Inbound Security Rule : 80

    <img width="1008" height="493" alt="image" src="https://github.com/user-attachments/assets/b0a5b150-66d9-4def-862b-000ed005babd" />

    <img width="1080" height="882" alt="image" src="https://github.com/user-attachments/assets/aa465c94-58ab-4eeb-86da-cf5fe41552dc" />

    <img width="952" height="435" alt="image" src="https://github.com/user-attachments/assets/e85777be-4127-4d0e-8a73-66b8c81f4142" />




         
  - Step 5: Deploy Microsoft Defender for  Cloud (Workload Protections

    <img width="1008" height="537" alt="image" src="https://github.com/user-attachments/assets/972d490c-5ae8-411a-847e-61deefff8a11" />


    <img width="974" height="416" alt="image" src="https://github.com/user-attachments/assets/782abe42-1ee8-4aa7-846c-ac0d06d14a93" />


     <img width="975" height="590" alt="image" src="https://github.com/user-attachments/assets/a841319a-03c8-4ecb-adc2-1efe4f165d0b" />



  
  - Step 6:  Enable Just-In-Time (JT) VM Access

    <img width="974" height="416" alt="image" src="https://github.com/user-attachments/assets/d1684db6-b171-461a-b269-82538cb9d7d5" />

    <img width="1008" height="671" alt="image" src="https://github.com/user-attachments/assets/c95f7f57-1373-477b-ac58-c7afac83a3bd" />



  - Step 7:  Deploy Azure Bastion For Secure RDP/SSH

    <img width="943" height="446" alt="image" src="https://github.com/user-attachments/assets/4fb20990-9077-423c-ad19-aeab2e5a1830" />

    <img width="984" height="486" alt="image" src="https://github.com/user-attachments/assets/579382a2-0153-4573-a98c-7d7da2486eef" />

    <img width="947" height="439" alt="image" src="https://github.com/user-attachments/assets/47f7621d-4db2-4113-8d5b-49cc90727fa6" />



  - Step 8: Create A Recovery Service Vault

    <img width="982" height="547" alt="image" src="https://github.com/user-attachments/assets/7769717f-a40c-49d3-b828-255ceb11aaba" />

        - Basic 

    <img width="992" height="516" alt="image" src="https://github.com/user-attachments/assets/688971b8-abb1-4db4-994f-757f416297bb" />

       - Redundancy : Local Rredundancy

   <img width="976" height="522" alt="image" src="https://github.com/user-attachments/assets/d10257d2-7903-4953-bba2-f51e83948bf9" />


      - Networking
       
 <img width="926" height="494" alt="image" src="https://github.com/user-attachments/assets/ff885cd4-8b56-45e3-9b48-5481e1a41b07" />

      - Review + Create

<img width="1008" height="496" alt="image" src="https://github.com/user-attachments/assets/e1e92659-6aa3-4c2a-96e2-060e5bafc8d7" />

<img width="929" height="465" alt="image" src="https://github.com/user-attachments/assets/d6762424-fd81-4cad-8c76-d18064b2cdbb" />

<img width="976" height="543" alt="image" src="https://github.com/user-attachments/assets/cd1c8736-84c4-4764-9f75-71ff7df37773" />


  - Step 10 : Enable Backup For Selected VM"s

<img width="967" height="443" alt="image" src="https://github.com/user-attachments/assets/d20b1ee1-419e-4d91-a180-fef8e3f763c1" />

<img width="976" height="477" alt="image" src="https://github.com/user-attachments/assets/006d7605-63b4-482c-8047-5366d6a8b6f1" />



  - Step 11 : Configure Backup Frequency And Retention

<img width="980" height="471" alt="image" src="https://github.com/user-attachments/assets/058f2ef9-887d-49b6-b287-ecc856232f92" />


<img width="993" height="500" alt="image" src="https://github.com/user-attachments/assets/ca9e4fbc-1e48-45de-a310-9e5a592c500f" />

  - Step 12 : Setup Azure Site Recovery For Failover (Optional)

    <img width="1080" height="597" alt="image" src="https://github.com/user-attachments/assets/6ebbe051-6f31-44cf-b179-62da52262319" />


    <img width="971" height="457" alt="image" src="https://github.com/user-attachments/assets/b2895419-68d2-4838-b711-08db76766cb9" />

    <img width="980" height="454" alt="image" src="https://github.com/user-attachments/assets/cb1c81f6-5d0f-423a-8411-a8c9db82a80a" />





4. **Conclusion**

   - Resilient And Secure VM Infrastructure
  
   - Logical Balanced And Highly Available Environment
  
   - Hardened Security Postured And Backup Reliability
  
   - Real World Experiences With Azure Infrastructure Design







5. **Resources**

   - Instructor: Gabriel Mekuleyi
  
   - Azure Portal
  
   - Microsoft Learn
  
   - GitHub Repository
  
   - Copilot













