# Login
# CodeAlpha_LoginSystem_Task

# Simple C++ Login & Registration System  

## 📌 Overview  
This is a **console-based login and registration system** written in **C++**.  
It allows users to register with a unique username and password, securely stores hashed passwords in separate files, and provides a login system with validation.  

## ✨ Features  
- Register a new account with **username** and **password**  
- Prevents **duplicate usernames** (validation included)  
- Password must be **at least 5 characters** long  
- Passwords are stored in **hashed form** for basic security  
- Each user’s credentials are stored in a **separate file (`<username>.txt`)**  
- Login system validates username and password  
- User-friendly menus with clear **success and error messages**  
- Session menu with options to **Log out** or **Exit**  

## 🛠️ Technologies Used  
- C++  
- `<fstream>` for file handling  
- `<functional>` for password hashing  
- `<conio.h>` for hidden password input (`_getch()`)  
- `<windows.h>` for delays (`Sleep`) and clearing screen  

## 🚀 How It Works  
1. **Registration**  
   - Enter a username → checked for duplicates.  
   - Enter a password → must be at least 5 characters.  
   - Password is hashed and saved in `<username>.txt`.  
   - Username is appended to `Users.txt`.  

2. **Login**  
   - Enter your username & password.  
   - Password is hashed and compared with saved hash.  
   - If correct → **Login Successful**.  
   - Wrong credentials → Retry or Exit options.  

3. **Session Menu**  
   - After login, user can **Log out** (back to main menu) or **Close program**.
   - # Simple C++ Login & Registration System  

## 📌 Overview  
This is a **console-based login and registration system** written in **C++**.  
It allows users to register with a unique username and password, securely stores hashed passwords in separate files, and provides a login system with validation.  

## ✨ Features  
- Register a new account with **username** and **password**  
- Prevents **duplicate usernames** (validation included)  
- Password must be **at least 5 characters** long  
- Passwords are stored in **hashed form** for basic security  
- Each user’s credentials are stored in a **separate file (`<username>.txt`)**  
- Login system validates username and password  
- User-friendly menus with clear **success and error messages**  
- Session menu with options to **Log out** or **Exit**  

## 🛠️ Technologies Used  
- C++  
- `<fstream>` for file handling  
- `<functional>` for password hashing  
- `<conio.h>` for hidden password input (`_getch()`)  
- `<windows.h>` for delays (`Sleep`) and clearing screen  

## 🚀 How It Works  
1. **Registration**  
   - Enter a username → checked for duplicates.  
   - Enter a password → must be at least 5 characters.  
   - Password is hashed and saved in `<username>.txt`.  
   - Username is appended to `Users.txt`.  

2. **Login**  
   - Enter your username & password.  
   - Password is hashed and compared with saved hash.  
   - If correct → **Login Successful**.  
   - Wrong credentials → Retry or Exit options.  

3. **Session Menu**  
   - After login, user can **Log out** (back to main menu) or **Close program**.  

## 📂 File Structure  
project/
│── Users.txt # Stores all registered usernames
│── <username>.txt # Each file stores the hashed password of a user
│── main.cpp # Source code

## 👩‍💻 Author  
- **Aila kanwal**  
- Project for **[CodeAlpha Internship]**  

---
💡 *This is a basic console-level system and not for production use.*


---
💡 *This is a basic console-level system and not for production use.*
