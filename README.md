## case-e – Standalone eCRF Application

**Overview:**  
**case-e** is the packaged, standalone version of the eCRF system. It contains the eCRF application bundled with all necessary components (such as a web server and database) so that users can run the system out-of-the-box without installing any additional software or configuring environments. The case-e package is ideal for researchers and clinicians who want to try or use eCRF quickly. Everything is self-contained in this distribution, simplifying the deployment process.

### How to Run the Standalone Application  
Using the case-e standalone application is straightforward and does not require any technical setup:

1. **Download case-e:** Download the case-e package from the link: https://github.com/venkateshhs/case-e (Click on Button "<> Code" and click on "Download ZIP"). Once downloaded, extract the contents.  
2. **Locate the Executable:** Inside the extracted case-e directory, find the folder named **`eCRF`**. In this folder, there will be an executable file called **`eCRF-bin`** .  
3. **Launch eCRF:** Double-click the `eCRF-bin` executable. This action will start the eCRF application. You might see a terminal screen or a console window indicating that the server is starting up. In some distributions, a browser window or application window will open automatically to the eCRF login page once startup is complete. If it doesn’t open automatically, open your web browser and navigate to the address:  or a similar address) as indicated in the documentation.  
4. **Use the Application:** Once the application is running, you will see the eCRF login interface in your browser window. You can now log in and begin using eCRF.

No additional installation steps are required – you do **not** need to set up a separate database, web server, or any programming environment. The case-e package includes an embedded database to store data and a web server to run the application logic, all bundled together for your convenience.

### Default Login Credentials and Security  
When running the standalone version for the first time, log in with the default administrator account:

- **Username:** `admin`  
- **Password:** `Admin123!`  

After logging in successfully, **immediately navigate to the User Management section to change the default password.** The default credentials are provided for first-time access, but keeping them unchanged poses a security risk (anyone who knows the software’s default password could log in). In the User Management interface, select the `admin` user and update the password to a strong, unique password of your choice. It’s also advised to update the admin email or other recovery settings if applicable, and add additional user accounts for other team members rather than sharing the admin login.

**Conclusion:**  
The **eCRF system** provides a comprehensive solution for electronic data capture in clinical trials, and **case-e** makes it easy to deploy and use this system without technical barriers. By following this documentation, you can get started with designing eCRFs, managing users, and collecting high-quality data for your clinical studies.




