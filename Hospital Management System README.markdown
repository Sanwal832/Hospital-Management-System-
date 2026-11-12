# Hospital Management System

## BLUF (Bottom Line Up Front)
The **Hospital Management System (HMS)** is a simple, easy-to-use digital tool that replaces messy paper files with an organized computer system. It allows clinic and hospital staff to securely save patient records, manage doctor schedules, book appointments without double-booking, and generate daily reports—all automatically saved to your computer so no information is ever lost.

---

## Dependencies (What You Need)
You do **not** need expensive software, internet access, or complicated database setups. You only need:
1. **A Standard Computer:** Windows, Mac, or Linux.
2. **A C++ Program Runner (Compiler):** Free software like **Dev-C++**, **Code::Blocks**, or **MinGW (g++)** to turn the code into a clickable application.
3. **Built-in System Files:** Everything else is already built into standard C++ (`<iostream>`, `<fstream>`, `<string>`). No extra downloads are required.

---

## Installation (How to Set It Up)
Follow these 4 easy steps to get the system running on your computer:

1. **Save the Project File:** Place the program file (`main.cpp`) into a dedicated folder on your computer (for example, on your Desktop).
2. **Open Your Terminal / Command Prompt:** Open the folder and launch your computer's Command Prompt (Windows) or Terminal (Mac/Linux).
3. **Prepare the Program:** Type the following command and press **Enter** to build the application:
   ```bash
   g++ main.cpp -o HospitalSystem
   ```
   *(Note: If you use Dev-C++ or Code::Blocks, simply open `main.cpp` and press **F11** or click **Compile & Run**).*
4. **Launch the System:**
   * **Windows:** Double-click `HospitalSystem.exe` or type `HospitalSystem.exe` and press **Enter**.
   * **Mac / Linux:** Type `./HospitalSystem` and press **Enter**.

---

## Minimal Working Example (How to Use It)
Once opened, you control the entire system simply by typing numbers on your keyboard. Below is a quick example of registering a new patient:

```text
========================================
       HOSPITAL MANAGEMENT SYSTEM       
========================================
1. Register New Patient
2. Add New Doctor
3. Schedule Appointment
4. View All Patients
5. View All Doctors
6. Exit
========================================
Enter your choice (1-6): 1

--- Register New Patient ---
Enter Patient ID: 101
Enter Full Name: John Doe
Enter Age: 34
Enter Gender: Male

[SUCCESS] Patient saved! (Automatically stored in patients.txt)
```

---

**Project Credits:** University of Kamalia | Team: Muhammad Sher Bahadar, Naheed Akhtar, Ayesha Hassan | Supervised by: Sir Abdul Noman Pasha