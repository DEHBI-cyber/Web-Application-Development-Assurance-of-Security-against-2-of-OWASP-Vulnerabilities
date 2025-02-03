# Web-Application-Development-Assurance-of-Security-against-2-of-OWASP-Vulnerabilities

## 🎯 Objective
The goal of this project is to identify vulnerabilities in a developed application through scanning and implement security measures to address them, based on OWASP recommendations.


### 💪 Skills Learned
- Developing an application using the Django framework.
- Gaining familiarity with the Acunetix tool.
- Researching methods to ensure application security and implementing them.
- Applying security measures to address OWASP vulnerabilities, specifically Broken Authentication and Sensitive Data Exposure.

### 🛠️ Tools Used

- Django Framework: a python framework to create websites.
- Acunetix: a web appliction security testing tool. 
- OWASP Top 10: a standard document that represents the most critical security risks to web applications.

## 📌 Steps
### 1️⃣ Developing a Stock Management Application
▶ This is the homepage of our developed application, designed to serve as the central hub for user navigation.
    
![Rapport_DEHBISiham_MAGATHind pdf-image-001](https://github.com/user-attachments/assets/a2cdbe42-4305-4447-bae9-d9bcbaed1216)

▶ Upon selecting the "List Items" tab, the user is presented with an interface that displays the current list of items.
    
![Rapport_DEHBISiham_MAGATHind pdf-image-003](https://github.com/user-attachments/assets/fa92f9df-aac2-49f9-a81d-d16bc4ee5eea)

▶ If a user wishes to delete an item, he can click the "DELETE" located in the last column of the list.
   
![Rapport_DEHBISiham_MAGATHind pdf-image-002](https://github.com/user-attachments/assets/cf1f0f93-6e5d-4ebf-a067-400a97879727)

▶ The "Add Item" tab provides functionality for users to seamlessly add new items to their inventory or stock.
     
![Rapport_DEHBISiham_MAGATHind pdf-image-004](https://github.com/user-attachments/assets/3073d056-ae2a-48d4-a42b-0f627a47fb2f)

### 2️⃣ Scanning the application using Acunetix
▶ Specify the target system and customize the scan settings to align with the desired objectives.
    
![Rapport_DEHBISiham_MAGATHind pdf-image-005](https://github.com/user-attachments/assets/32b2a37b-50f2-408f-852e-847c4085f9b3)
![Rapport_DEHBISiham_MAGATHind pdf-image-006](https://github.com/user-attachments/assets/fb837ae0-1ff4-4f26-a0ba-d3b4415dcba2)
![Rapport_DEHBISiham_MAGATHind pdf-image-007](https://github.com/user-attachments/assets/42ded028-c135-431f-9fe1-0c23757dabd8)

▶ Access the scan results and get a detailed report summarizing the findings.
   
![Rapport_DEHBISiham_MAGATHind pdf-image-008](https://github.com/user-attachments/assets/84e76945-d3fa-4eb2-82c4-92db5b91091f)
![Rapport_DEHBISiham_MAGATHind pdf-image-009](https://github.com/user-attachments/assets/f8fad867-c4c7-48b1-a364-193bc7aed717)

▶ Generate a comprehensive report highlighting vulnerabilities based on the OWASP Top Ten standards.
    
![Rapport_DEHBISiham_MAGATHind pdf-image-010](https://github.com/user-attachments/assets/374356ae-e453-4733-bbf4-a2e96366c02b)

### 3️⃣ Implementing Security Measures

#### Remediating Broken Authentication

▶ We introduced essential modules to enforce strong password restrictions, configured in the settings.py file. This ensures adherence to best practices for password strength and security.
    
![Rapport_DEHBISiham_MAGATHind pdf-image-011](https://github.com/user-attachments/assets/0ca85c8f-5804-47a6-8466-68bb5299012c)
   
▶ We installed and configured the django-mfa package to enhance authentication security by requiring multiple verification factors.
      
![Rapport_DEHBISiham_MAGATHind pdf-image-012](https://github.com/user-attachments/assets/b4c5ea2d-62cd-4d21-9c7a-d356b80f2b4b)
![Rapport_DEHBISiham_MAGATHind pdf-image-013](https://github.com/user-attachments/assets/e318b01e-4c18-45dc-9aeb-b5b950b6a1ba)
![Rapport_DEHBISiham_MAGATHind pdf-image-014](https://github.com/user-attachments/assets/c6bd2a9f-5f38-49a0-be00-d3b5dbada059)

   
#### Addressing Sensitive Data Exposure
  
▶ We set DEBUG mode to False in the settings.py file to prevent sensitive debug information from being exposed, and we restricted the allowed hosts to the localhost (127.0.0.1).
        
![Rapport_DEHBISiham_MAGATHind pdf-image-023](https://github.com/user-attachments/assets/ed6fbad1-3578-4c11-99e9-202d2a95d658)
   
▶ We also implemented proper exception handling mechanisms to prevent the leakage of exploitable information.
    
![Rapport_DEHBISiham_MAGATHind pdf-image-024](https://github.com/user-attachments/assets/72d8ce49-1d33-4c3b-89ce-7fa5d5756a5f)

## NOTE
This project was completed by me and a friend who also specializes in cybersecurity. That’s why I used 'our' instead of 'me.'
