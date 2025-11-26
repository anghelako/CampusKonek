<h1 align = "center">𐔌 .⋮ CampusKonek .ᐟ ֹ ₊ ꒱</h1>
<h3 align = "center">Find the org for you ✧˖°</h3>

<p align = "center">
<b>CS 211</b> <br/>
<b>Project Members:</b><br/>
Raymond Acuzar <br/>
Lordy Miles J. Ricohermoso <br/>
Myk Angelo D. Tosino <br/>
</p>

---

## ‧₊˚ ┊ Overview  
**CampusKonek** is a console-based Java application designed to help universities manage students and organizations efficiently.  
<br/>
It showcases strong application of **Object-Oriented Programming principles**, including abstraction, inheritance, encapsulation, and polymorphism, combined with proper input handling, modular design, and logically structured menus.

It allows seamless interaction between Admins and Students through login systems and multiple CRUD operations for student and organization management.

---

## ‧₊˚ ┊ Users can:
👨‍🏫 **Admins:**  
- Add, view, update, and delete students  
- Add, view, approve, and delete organizations  
- Manage organization status  

🎓 **Students:**  
- Log in using personal credentials  
- View profile  
- Browse approved organizations  
- Apply for an organization  
- Update personal details  

---

## ‧₊˚ ┊ Project Structure
```
📂 src/
├── Main.java
├── Student.java
├── Admin.java
├── Application.java
├── Database.java
├── InputHelper.java
├── Organization.java
└── User.java
```
- `Main.java` – Entry point; handles main, admin, and student menus  
- `Student.java` – Student data, encapsulated fields, behaviors  
- `Admin.java` – Admin-specific operations and access  
- `Application.java` – Handles student applications to organizations  
- `Database.java` – Stores ArrayLists for students and organizations  
- `InputHelper.java` – Validated input handling  
- `Organization.java` – Org data, approval status, assigned course  
- `User.java` – Parent class for Admin and Student (abstraction)

---

## ‧₊˚ ┊ How to Run the Program
Open your terminal in the `src/` folder and compile using:
```
java CampusKonek/*.java
```


Run the system using:
```
CampusKonek.Main
```

---

## ‧₊˚ ┊ Features  
### 🔐 Authentication
- Fixed **Admin login**
- Personalized **Student login** with unique passwords  

### 👥 Student Management (Admin)
- Add new student  
- View all students  
- Update student name  
- Delete student  
- Exception handling included when adding students  

### 🏫 Organization Management (Admin)
- Add organization  
- View organizations  
- Approve pending organizations  
- Delete organization  
- Dynamic storage using ArrayLists  

### 🎓 Student Operations
- View personal profile  
- Browse approved organizations  
- Apply for an organization  
- Update profile  

### 💡 OOP Concepts Applied
- **Abstraction:** `User` as abstract class with `displayInfo()`  
- **Inheritance:** `Student`, `Admin`, `Organization` inheriting from `User`  
- **Encapsulation:** Private fields in `Student` with getters and setters  
- **Polymorphism:** `displayInfo()` overridden across subclasses  

### 🧰 Additional Features  
- Persistent looping menus for Admin & Student  
- Clean and informative console messages  
- Organized handling of organization approval flow  

---

## ‧₊˚ ┊ Example Output
```
==============================
 UNIVERSITY MANAGEMENT SYSTEM
==============================

1. Login as Student
2. Login as Admin
3. Exit
Choose option: 2

--- ADMIN LOGIN ---
Enter admin password: admin123
Admin login successful!

===== ADMIN MENU =====
1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Add Organization
6. View Organizations
7. Approve Organization
8. Delete Organization
9. Logout
Choose option: 1

--- ADD STUDENT ---
Name: Juan Dela Cruz
Email: juan@gmail.com
Course: BSIT
Hobbies: Programming, Gaming
Create password: juanpass

Student added successfully!


===== ADMIN MENU =====
Choose option: 5

--- ADD ORGANIZATION ---
Organization Name: Tech Innovators Club
Description: For students interested in coding and robotics.
Assigned Course: BSIT

Organization submitted and pending approval.


===== ADMIN MENU =====
Choose option: 2

--- STUDENT LIST ---
ID: S1
Name: Juan Dela Cruz
Email: juan@gmail.com
Course: BSIT
Hobbies: Programming, Gaming
Pending Application: No
-----------------------


===== ADMIN MENU =====
Choose option: 6

--- ORGANIZATION LIST ---
ORG1 - Tech Innovators Club
Course: BSIT
Status: Pending
----------------------------------


===== ADMIN MENU =====
Choose option: 7

--- APPROVE ORGANIZATION ---
Enter Organization ID: ORG1
Organization approved successfully!


===== ADMIN MENU =====
Choose option: 9
Logging out...

==============================
 UNIVERSITY MANAGEMENT SYSTEM
==============================

1. Login as Student
2. Login as Admin
3. Exit
Choose option: 1

--- STUDENT LOGIN ---
Enter your name: Juan Dela Cruz
Enter password: juanpass

Login successful!


===== STUDENT MENU =====
1. View Profile
2. View Available Organizations
3. Apply for Organization
4. Update Profile
5. Logout
Choose option: 1

--- YOUR PROFILE ---
Name: Juan Dela Cruz
Email: juan@gmail.com
Course: BSIT
Hobbies: Programming, Gaming
Pending Application: No


===== STUDENT MENU =====
Choose option: 2

--- AVAILABLE ORGANIZATIONS ---
ORG1 - Tech Innovators Club
Course: BSIT
Status: Approved
----------------------------------


===== STUDENT MENU =====
Choose option: 3

--- APPLY FOR ORGANIZATION ---
Enter Organization ID: ORG1
Application submitted!
You now have a pending application.


===== STUDENT MENU =====
Choose option: 1

--- YOUR PROFILE ---
Name: Juan Dela Cruz
Email: juan@gmail.com
Course: BSIT
Hobbies: Programming, Gaming
Pending Application: YES


===== STUDENT MENU =====
Choose option: 5
Logging out...

==============================
 UNIVERSITY MANAGEMENT SYSTEM
==============================

1. Login as Student
2. Login as Admin
3. Exit
Choose option: 3

Exiting program... Goodbye!
```
---

## ‧₊˚ ┊ Acknowledgment  
Special thanks to everyone who helped make this project possible — instructor Ma'am Fatima Marie Agdon, classmates, and anyone who provided feedback, ideas, or guidance throughout its development.

---

<small>
<b>DISCLAIMER</b><br/>
This project and its contents are provided for academic learning and demonstration purposes only. Students are encouraged to use it as a reference and avoid copying it entirely.
</small>
