Hospital Management System (C)

A simple Hospital Management System written in C.
This project allows managing patient records using file handling. It is a console-based application that demonstrates CRUD (Create, Read, Update, Delete) operations for patients.



Features

Add a new patient record

View all patients

Search patient by ID

Delete patient record

File-based storage for persistent data




File Structure

hospital_management.c     # Main C source code hospital.txt              # Data file generated automatically README.md                 # Project description



How to Compile & Run

Compile

gcc hospital_management.c -o hospital  
  
Run  
  
./hospital       # Linux/Mac  
hospital.exe     # Windows  
  
  

  
Usage  
  
1. Add Patient: Enter ID, Name, Age, Gender, Disease.  
  
  
2. View All Patients: Displays all saved patient records.  
  
  
3. Search Patient: Enter ID to search for a patient.  
  
  
4. Delete Patient: Enter ID to remove a patient record.  
  
  
5. Exit: Quit the program.  
  
  
  
  
  
Technology Used  
  
C Programming Language  
  
File Handling (Binary/Text)  
  
Console-based user interface  
  
  
  

  
Future Improvements  
  
Add Doctor management and appointments  
  
Implement billing module  
  
Add login system for admin/staff  
  
Convert to GUI using C graphics, or port to Python/Web  
  
  
  
  
