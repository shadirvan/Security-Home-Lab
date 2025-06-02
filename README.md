# Security-Home-Lab

## Objective

A Security Detection Lab project 🎯 was created to build a controlled playground 🛡️ for simulating and detecting cyber attacks ⚔️. Its main goal? To ingest and analyze logs 📊 within a powerful SIEM system 🕵️‍♂️, generating realistic test telemetry 📡 that mimics real-world attack scenarios 🌐🔥. This hands-on experience 💻🔍 helps sharpen skills in network security 🛡️, uncover attack patterns 🧩, and master defensive strategies 🛠️ to stay one step ahead of cyber threats! 🚀✨

### Skills Learned
- Install A Linux Operating System
- Using a Hypervisor

### Tools Used

- Debian (As Operating System)
- VMware 

## Steps
1. Download a good Hypervisor. I prefer vmware as it more stable than virtualbox.
   - [Vmware](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion)
2. Choose a Linux Operating system for Installing Splunk: Here i choose debian because it is lighter and comes with less no of packages packages
   - [Debian](https://www.debian.org/distrib/)
   
   ![Screenshot 2025-06-02 at 16-49-29 Debian -- The Universal Operating System](https://github.com/user-attachments/assets/d208347d-4c35-4442-982d-1a223076fc55)
3. Install Debian OS
   - Load the ISO in vmware
   - Follow the steps to install debian
   ![Debian 12 x 64-bit-2025-06-02-17-44-17](https://github.com/user-attachments/assets/03f0936b-1184-4a29-bb93-e0e9fa30872a)
![Debian 12 x 64-bit-2025-06-02-19-18-01](https://github.com/user-attachments/assets/671cf2d4-8711-482c-b6fb-02e45211548c)
4. Download and Install Splunk.
     - Signup to https://splunk.com and download splunk enterprise free trial.
       
       ![Debian 12 x 64-bit-2025-06-02-20-26-40](https://github.com/user-attachments/assets/dfb025a7-4f87-4503-9b35-1fd0983b4f85)
   
      - Download the .deb package.
    - Install the package
      
      ![Debian 12 x 64-bit-2025-06-02-20-32-24](https://github.com/user-attachments/assets/0b719091-c28c-407b-8fcd-32afdfbcb8c1)
5. To run splunk Navigate to `/opt/splunk/bin` directory.
6. Run `sudo ./splunk start`
   
     ![Debian 12 x 64-bit-2025-06-02-20-37-05](https://github.com/user-attachments/assets/fd9961cc-e42e-4a47-a3fb-73b63f74246b)
   
7. Accept Terms and Agreement
   
   ![Debian 12 x 64-bit-2025-06-02-20-38-23](https://github.com/user-attachments/assets/0fe1ce81-9679-4004-aebc-602eb19b0b06)
   
8. Create admin user with a password
    ![Debian 12 x 64-bit-2025-06-02-20-38-39](https://github.com/user-attachments/assets/ab0f2a1c-35d4-4b93-8c0b-47f6d7a95c65).
   
9. Launch the webserver by clicking the Url
    
 ![Debian 12 x 64-bit-2025-06-02-20-38-49](https://github.com/user-attachments/assets/77eae1c2-5e03-42c0-bc65-6e2a29007b1d)
10. Login With the Credentials
    
![Debian 12 x 64-bit-2025-06-02-20-39-03](https://github.com/user-attachments/assets/52cd89cb-c07a-4160-a7a0-232f5303a755).

11. Now You can access the Splunk Dashboard
 ![Debian 12 x 64-bit-2025-06-02-20-39-18](https://github.com/user-attachments/assets/a34e2b1f-5af2-44d0-afd7-3d90020aaf1f)
   
    
   

  

