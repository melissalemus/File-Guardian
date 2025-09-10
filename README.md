# 🛡️ FileGuardian

FileGuardian is a simple **File Integrity Checker and Encryption Tool** built with Python.  
It allows you to:
- Generate and save secure file hashes (SHA-256).  
- Verify file integrity against saved hashes.  
- Encrypt and decrypt files using symmetric encryption (Fernet).  

This tool helps ensure that files have not been tampered with and adds an extra layer of security with encryption.  

---

## ⚙️ Features
-  Generate SHA-256 hash of any file.  
-  Save hashes for later verification.  
-  Verify file integrity (detect tampering).  
-  Encrypt and decrypt files with a key.  
-  Simple menu-driven interface.  

---

##  Requirements (Windows Setup)

Before running, make sure you have installed:

1. **Python 3.10+**  
   - Download from: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)  
   - During installation, check **Add to PATH** (IMPORTANT: It tells your computer where to look for programs when you type a command in the terminal (like python or pip).

2. **Pip (Python package manager)**  
   Comes with Python. Check with:  
   ```bash
   python --version
   pip --version
3. **Requires Python Library**
     Install in terminal:
      ```bash
     pip install cryptography

 ## How To Run the Project (Mainly Windows)     
**1.Generate and save its hash**

-  Choose option 1 in the menu.

-  Enter: example.txt

-  A hash will be saved in hashes.json.

**2.Verify integrity**

-  Choose option 2.

-  Enter: example.txt

-  If the file is unchanged, you’ll see: File integrity is intact!

**3.Encrypt the file**

-  Choose option 3.

-  Enter: example.txt

-  File becomes example.txt.encrypted.

-  Key is saved in secret.key.

**4.Decrypt the file**

-  Choose option 4.

-  Enter: example.txt.encrypted

-  File restores as example.txt.

## Screenshot of what the app currently looks like 

![FileGuardian Screenshot](https://github.com/melissalemus/File-Guardian/raw/main/FileGuardian1.png)



