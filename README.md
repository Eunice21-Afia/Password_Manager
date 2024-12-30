

### **Password Manager**  
**A simple command-line application for secure password management.**  

- **Technologies Used**: Python, Cryptography Library (Fernet encryption).  
- **GitHub Repository**: [password-manager](https://github.com/aaronpaddy/password-manager)  

---

#### **Key Features**  
- **Secure Encryption**: Implements the Fernet symmetric encryption method to ensure password safety.  
- **Password Management**: Add new passwords, securely store them, and view existing ones.  
- **Automatic File Generation**: Automatically generates and manages `key.key` (encryption key) and `passwords.txt` (encrypted passwords).  
- **User-Friendly CLI**: Simple command-line interface for seamless interaction.  

---

#### **Installation and Usage**  
1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/aaronpaddy/password-manager.git  
   cd password-manager  
   ```  

2. **Install Dependencies**:  
   ```bash  
   pip install cryptography  
   ```  

3. **Run the Application**:  
   ```bash  
   python password_manager.py  
   ```  

---

#### **Usage Examples**  
- **Adding Passwords**:  
   - Enter "add" when prompted, provide an account name and password.  
   - Passwords are encrypted and stored in `passwords.txt`.  
- **Viewing Passwords**:  
   - Enter "view" to display decrypted passwords alongside their account names.  

---

#### **Folder Structure**  
- **`key.key`**: Encryption key used for securing passwords.  
- **`passwords.txt`**: File containing encrypted passwords.  

---

#### **Security Notes**  
- Keep the `key.key` file private, as it decrypts all stored passwords.  
- Avoid sharing the `passwords.txt` file, even though it contains encrypted data.  

