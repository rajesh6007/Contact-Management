# Contact-Management

This is a contact information management system that is created using c++ pragramming language and file system as storage.
CIMS is the main code, if you encounter any error from this code then use CIMS (2) code and run again.

Requirements:

- This code is created based using c as well as C++
- It uses graphics.h library for GUI
- Create Alldata.txt and password.txt in bin folder of Turbo C++
- Alldata.txt stores all the information of users
- password.txt file stores the password for admin authentication
- To change password you can either used change password function in settings of system or manually change the text from password.txt

Features:

- Terminal GUI & CUI
- User and Admin Authentication
- Main and Department wise staff distribution
- File based data storage
- Contact based search
- Data Validation
- Contacts can be created, edited, deleted and searched

# 📇 Contact Information Management System (CIMS)

**Contact Information Management System (CIMS)** — is a project developed in **contact manager** built in **C++** that leverages the **file system** for data storage. It features a visual Command Line Interface (CLI) enhanced with graphical elements created using the `graphics.h` library, providing a unique blend of traditional terminal interaction and graphical user interface. This design offers a compact and efficient way to manage contacts department-wise while demonstrating core C++ programming concepts alongside simple GUI functionality.
This system provides a keyboard-first visual CLI (terminal area + on-screen graphics), secure login, input validation, and full CRUD (create / read / update / delete) for contacts organized by department.

**Keywords:** contact manager, contact-management, C++, graphics.h, CLI, CRUD, student-project

---

![Language](https://img.shields.io/badge/language-C++-blue) ![Project type](https://img.shields.io/badge/project-student--project-orange)

## 📑 Table of Contents

- [About](#about)
- [✨ Features](#-features)
- [🛠️ Technology Stack](#-technology-stack)
- [🚀 How the System Works](#-how-the-system-works)
- [⚡ Quick start — How to run](#-quick-start--how-to-run)
  - [Run with Turbo C++ (recommended for original graphics.h)](#run-with-turbo-c-recommended-for-original-graphicsh)
  - [Run on modern systems (recommended alternatives)](#run-on-modern-systems-recommended-alternatives)
- [📸 Screenshots](#-screenshots)
- [🏆 Learning Outcomes](#-learning-outcomes)
- [👨‍💻 Author](#-author)
- [📝 Note](#-note)

---

## About

CIMS provides a compact, offline contact-management experience focused on learning core C++ concepts: file I/O, validation, simple on-screen graphics (via `graphics.h`), and keyboard-driven UX. It is ideal for students who want an understandable codebase demonstrating GUI-like behavior without web frameworks or databases.

---

## ✨ Features

- ➕ **Full CRUD:** Add, view, edit, and delete contacts.
- 🗂️ **Department-wise organization:** Contacts grouped by department (e.g., Account, Advertisement, Canteen, Developer, Security, Technical).
- 🖥️ **Visual GUI + terminal area:** Minimal on-screen GUI created with `graphics.h` and a separate terminal/navigation area at the bottom.
- ✅ **Input validation:** Prevents invalid or malformed entries at input time.
- 🔐 **User authentication:** Admin login feature based on email and password
- ⌨️ **Keyboard-first navigation:** Operate entirely with keyboard (no mouse).
- ℹ️ **About / Help screens:** Built-in project information and usage hints.

---

## 🛠️ Technology Stack

- **Language:** C++
- **Graphics:** `graphics.h` (Turbo C++ / WinBGIm variants)
- **IDE / Compiler:** Turbo C++ (original) or modern IDEs with `graphics.h` compatibility (see alternatives below)
- **Storage:** File-based (no external DB) — data persisted to local files

---

## 🚀 How the System Works

1. **Login Authentication**

   - The user must log in with correct credentials to access the system.

2. **Navigation**

   - The system uses **keyboard-based navigation**. A separate terminal area at the bottom of the screen is used to guide users while interacting with the GUI.

3. **Managing Contacts**

   - Users can create new contacts, view all contacts, update information, or delete records.
   - All records are managed department-wise for better organization.

4. **Password Management**

   - Includes the option to **change the password** for the user account.

5. **About Section**
   - Provides information about the project, its purpose, and usage instructions.

---

## ⚡ Requiremrnts — Things to consider when running

1. This code is created based using c(for displaying some output) as well as C++

2. It uses graphics.h library for GUI

3. Create Alldata.txt and password.txt in bin folder of Turbo C++

4. Alldata.txt stores all the information of users

5. password.txt file stores the password for admin authentication

6. To change password you can either used change password function in settings of system or manually change the text from password.txt

## 📸 Screenshots

<figure style="text-align:center">
  <img src="Output_images/1.png" alt="Login Screen 1" width="600" />
  <figcaption>Figure 1: Login Screen — user authentication</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/2.png" alt="Login Screen 2" width="600" />
  <figcaption>Figure 2: Alternate Login view</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/3.png" alt="Dashboard" width="800" />
  <figcaption>Figure 3: Dashboard — department counts, table view, and navigation area</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/4.png" alt="New Record" width="700" />
  <figcaption>Figure 4: New Record — enter department</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/5.png" alt="New Record" width="700" />
  <figcaption>Figure 5: New Record — enter contact details</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/6.png" alt="Profile Preview" width="700" />
  <figcaption>Figure 6: Profile preview before saving (Edit / Cancel)</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/9.png" alt="Department View" width="700" />
  <figcaption>Figure 7: Department table — counts and records</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/10.png" alt="Department View" width="700" />
  <figcaption>Figure 8: Account Department table — counts and records</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/11.png" alt="Settings" width="700" />
  <figcaption>Figure 9: Settings — Change Password & About</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/12.png" alt="Settings" width="700" />
  <figcaption>Figure 10: Settings — Change Password</figcaption>
</figure>

<figure style="text-align:center">
  <img src="Output_images/13.png" alt="Settings" width="700" />
  <figcaption>Figure 11: Settings — About</figcaption>
</figure>

> Tip: I hope these images will help you to navigate through the system.

---

## 🏆 Learning Outcomes

- Strengthened core **C++** programming concepts (data structures, file I/O).
- Practiced **input validation** and secure basic authentication patterns.
- Developed a minimal **visual UI** with `graphics.h` and a keyboard-first UX.
- Improved debugging, code organization, and user-flow design.

---

## 👨‍💻 Author

**Author:** rajesh6007
Bachelor in Computer Engineering — 8rd Semester

- LinkedIn: _(https://www.linkedin.com/in/rajesh-hamal-538292359/)_
- Email: _(hamalr551@gmail.com)_

---

## 📝 Note

This project was developed for academic learning purposes. It is a **console + graphics-based system** and may not support modern compilers without additional configuration for `graphics.h`.

Also if you want to know the internal architecture of this system contact me. You can contact me on both email and LinkedIn.
