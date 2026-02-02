# Cloud-and-infrastructure-as-a-service-with-Digital-Ocean

## 2 - Setup Server on DigitalOcean


**📖 Summary**

Worked on Lab 2 - **Setup Server on DigitalOcean**, focusing on **deploying and configuring a virtual server (Droplet)** for Java application deployment built with gradle.
Tasks included creating SSH keys for secure access, configuring firewall rules, updating server packages,creating a linux user of the remote server with sude privillages and installing Java. This setup prepares the server for use in a scalable DevOps pipeline.


**🛠️ Tools and technologies Used**


**DigitalOcean Droplet:** ✨ Cloud virtual server for hosting and deploying applications.


**SSH:** ⚙️ Secure Shell protocol for encrypted server access.


**UFW Firewall:** 🔥 Configured to allow only trusted IPs on port 22 (SSH).


**OpenJDK 17:** ☕ Installed to provide Java runtime environment for server-side apps.


**Linux:** An operating system kernel that acts as an interface between hardware and user-space applications.



**🎯 Skills Gained**



**SSH Key Management:** 💡 Learned how to generate and use public/private keys for secure server authentication.


**Firewall Configuration:** 🔍 Set up rules to restrict access, enhancing server security.


**Server Provisioning:** 🚀 Updated and configured a Linux server to prepare for application deployment.


**⚠️ Challenges Faced**

**SSH Authentication Errors:** 🛠️ Resolved by ensuring correct public key was added to Droplet during setup.


**Firewall Blocking Access:** 🔄 Adjusted UFW rules to allow only specific IPs, balancing security and connectivity.


**💡 Why It Matters**

This lab builds foundational skills for cloud server provisioning and security hardening—critical for any DevOps role. By preparing a secure and updated server environment, we establish a reliable platform for running Java-based applications and integrating into CI/CD pipelines. 🌐🚀








## 3 - Deploy and run application artifact on Droplet


**📖 Summary**

Worked on Labs 3 & 4, focusing on **deploying a Java application artifact to a DigitalOcean Droplet and creating a secure Linux user.**
Tasks included building the Java project, securely transferring the JAR artifact to the server, running the application, verifying its operation, and setting up a non-root user with sudo privileges and SSH key access.
This setup ensures secure, organized deployments and follows DevOps best practices by using least-privilege access and service isolation on the cloud server.


**🛠️ Tools Used**



**Gradle:** ✨ Built the Java application artifact (.jar file).


**SCP (Secure Copy):** ⚙️ Transferred the artifact securely to the remote DigitalOcean server.


**Java Runtime:** 🚀 Executed the deployed Java application on the Droplet.


**Linux Command Line Tools:** 🖥️ Used for user management, SSH key setup, and server monitoring.


**DigitalOcean Firewall:** 🔥 Configured to allow incoming traffic on the application port (7071).




**🎯 Skills Gained**



**Artifact Deployment:** 💡 Learned to build, transfer, and run Java artifacts on remote cloud servers.


**Server Security Management:** 🔍 Created and configured a non-root Linux user with sudo privileges and SSH key authentication.


**Process and Network Monitoring:** 🚀 Used ps and netstat to verify the application is running and listening on the correct port.




**⚠️ Challenges Faced**



**Permission Issues:** 🛠️ Resolved by configuring proper SSH folder and file permissions for the new user.


**Firewall Access Configuration:** 🔄 Ensured the correct port (7071) was open in the DigitalOcean firewall for external access.




**💡 Why It Matters**

This lab reinforces secure and efficient deployment practices in a cloud environment, demonstrating how to run application artifacts safely and manage server users according to security best practices.
Mastering these tasks is essential for maintaining operational security and reliable application delivery in DevOps workflows. 🚀🔐