# case-e – Standalone eCRF Application

**Overview:**  
**case-e** is the packaged, standalone version of the eCRF system. It contains the eCRF application bundled with all necessary components (such as a web server and database) so that users can run the system out-of-the-box without installing any additional software or configuring environments. The case-e package is ideal for researchers and clinicians who want to try or use eCRF quickly. Everything is self-contained in this distribution, simplifying the deployment process.

---

## Source code
Source code be found here: [eCRF](https://github.com/venkateshhs/eCRF)

---

## Download the Latest Build (choose your OS)

> **Recommended:** Download from **GitHub Releases**.

- **macOS:**  
  **Download:** https://github.com/venkateshhs/case-e/releases/latest/download/eCRF-mac.tar.gz

- **Windows:**  
  **Download:** https://github.com/venkateshhs/case-e/releases/latest/download/eCRF-win.zip

> **Alternative (less preferred):** You can still download the repository ZIP via the green **“Code” -> “Download ZIP”** button, then extract. Releases are smaller and faster.

**Command-line download examples (optional)**

**macOS**
```bash
curl -L -o eCRF-mac.tar.gz https://github.com/venkateshhs/case-e/releases/latest/download/eCRF-mac.tar.gz
tar -xzf eCRF-mac.tar.gz
```

**Windows (PowerShell)**
```powershell
iwr https://github.com/venkateshhs/case-e/releases/latest/download/eCRF-win.zip -OutFile eCRF-win.zip
Expand-Archive .\eCRF-win.zip -DestinationPath .\eCRF
```

---

## How to Run the Standalone Application

Using the case-e standalone application is straightforward and does not require any technical setup.

### macOS
1. **Download & Extract** `eCRF-mac.tar.gz` (see link above), then double-click it in Finder **or** run:
   ```bash
   tar -xzf eCRF-mac.tar.gz
   ```
2. **Locate the Executable:** In the extracted `eCRF` folder, find **`eCRF-bin`**.
3. **First-Run on macOS**  
   If macOS shows **“Apple could not verify ‘eCRF-bin’ is free of malware”**:
   - Open **System Settings -> Privacy & Security**.
   - In the **Security** section, you’ll see a note that *“`eCRF-bin` was blocked from use”*. Click **Open Anyway**.
   - When prompted, click **Open**.  
   *(Alternative: Control-click `eCRF-bin` -> **Open** -> **Open**.)*  
   This is a one-time approval for this app.
4. **Launch eCRF:** Double-click `eCRF-bin`. A small terminal/console may appear while the server starts. A browser window will typically open to the login page.  
  

### Windows
1. **Download & Extract** `eCRF-win.zip` (see link above) and **Extract All…** into a folder such as `.\eCRF`.
2. **Locate the Executable:** Inside `eCRF`, run **`eCRF-bin`** (it may appear as **`eCRF.exe`**).
3. **First-Run on Windows**  
   If you see *“Windows protected your PC”*:
   - Click **More info** -> **Run anyway**.
4. **Launch eCRF:** On launch, a console appears and your default browser will open to the login page.  


### Use the Application
Once the application is running, you will see the eCRF login interface in your browser window. You can now log in and begin using eCRF.

No additional installation steps are required - you do **not** need to set up a separate database, web server, or any programming environment. The case-e package includes an embedded database to store data and a web server to run the application logic, all bundled together for your convenience.

---

## Default Login Credentials and Security

When running the standalone version for the first time, log in with the default administrator account:

- **Username:** `admin`  
- **Password:** `Admin123!`

After logging in successfully, **immediately navigate to the User Management section to change the default password.** The default credentials are provided for first-time access, but keeping them unchanged poses a security risk (anyone who knows the software’s default password could log in). In the User Management interface, select the `admin` user and update the password to a strong, unique password of your choice.

---


**Conclusion:**  
The **eCRF system** provides a comprehensive solution for electronic data capture in clinical trials, and **case-e** makes it easy to deploy and use this system without technical barriers. By following this documentation, you can get started with designing eCRFs, managing users, and collecting high-quality data for your clinical studies.
