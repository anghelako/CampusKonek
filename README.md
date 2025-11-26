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

---

## ‧₊˚ ┊ How to Run the Program
Open your terminal in the `src/` folder and compile using:


Run the system using:


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


---

## ‧₊˚ ┊ Acknowledgment  
Special thanks to everyone who helped make this project possible — instructor Ma'am Fatima Marie Agdon, classmates, and anyone who provided feedback, ideas, or guidance throughout its development.

---

<small>
<b>DISCLAIMER</b><br/>
This project and its contents are provided for academic learning and demonstration purposes only. Students are encouraged to use it as a reference and avoid copying it entirely.
</small>
