## Screenshots of the GCP Storage Process

![alt text](<gcp_img/Screenshot 2024-10-14 at 17.24.26.png>)
![alt text](<gcp_img/Screenshot 2024-10-14 at 17.26.20.png>)
![alt text](<gcp_img/Screenshot 2024-10-14 at 17.28.05.png>)
![alt text](<gcp_img/Screenshot 2024-10-14 at 17.28.18.png>)
![alt text](<gcp_img/Screenshot 2024-10-14 at 17.29.53.png>)
![alt text](<gcp_img/Screenshot 2024-10-14 at 18.53.45.png>)

## Screenshots of the Azure Storage Process

![alt text](<azure_img/Screenshot 2024-10-14 at 19.36.54.png>)
![alt text](<azure_img/Screenshot 2024-10-14 at 19.38.44.png>)
![alt text](<azure_img/Screenshot 2024-10-14 at 21.29.31.png>)

### Storage Management and Security 

- Azure Blob Storage
    - You can use SAS (Shared Accces Signatures), Azure AD for role based access and Stored Access Policies to control them
    - They support Server Side Encryption and Client Side Encryption and you can also restrict access with VNet and firewalls
    - The different storage tiers include Hot, Cool, and Archive to maanage cost based on data access
    - Soft delete, versioning, and immutable storage are available to prevent accidental data loss

- GCP Cloud Storage
    - Utilize IAM roles for granular control
    - Data encryption is done via google managed or customer managed keys
    - Storage tiers include Standard, Nearline, Coldline and Archive
    - Users can enable object versioning, retention policies and object holds for data compliance