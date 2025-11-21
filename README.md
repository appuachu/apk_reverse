# 📘 README – Reverse Engineering & APK Cracking Demo

## 🎯 Purpose of This Project
This Android application is created **only for educational and cybersecurity training purposes**.  
The goal of this demo is to help students learn:

- 🔍 How Android apps can be reverse-engineered  
- 🔑 How passwords and logic can be exposed using tools  
- 📝 How to edit and modify smali code  
- 🛠️ How to rebuild and sign an APK  
- 🛡️ Why secure coding practices are important  

By completing this practical exercise, students will understand **how attackers analyze and modify Android apps**, allowing them to build **more secure applications** in the future.

---

## 🧪 What the App Does
When the app is opened:

1. It asks the user to enter a **password**.  
2. If the password is **correct**, it shows:  
   **✅ Congratulations**
3. If the password is **incorrect**, it shows:  
   **❌ Invalid Password**

### 🔐 The correct password for this demo:
**`password123@#`**

Students must reverse engineer the APK to:

- ✔ Find the correct password inside the code  
**OR**
- ✔ Modify the smali logic so it **always shows “Congratulations”** (bypass the password check)

---

## 🛠️ Tools You Will Use
| Tool | Purpose |
|------|---------|
| **jadx-gui** | View Java source code & find password logic |
| **apktool** | Decompile & recompile the APK |
| **smali** | Edit low-level Android bytecode |
| **apksigner** | Sign the modified APK so it can be installed |

---

