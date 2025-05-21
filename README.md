# Group-2-assignment

## 📚 Project Overview

The SCIT TUK Database System allows administrators to:
- Register and manage departments our main department of focus the department of Computing and IT
- Create and assign academic programs under our department above 
- Add courses to programs
- Enroll students into programs and courses
- Track which student is in which program and enrolled in which courses

---

## 🧱 Database Design

### 🎯 Entities:
- **Department**
- **Program**
- **Course**
- **Student**
- **Enrollment** (relationship between students and courses)

### 🧾 Attributes Summary:

| Entity     | Attributes                                  |
|------------|---------------------------------------------|
| Department | id, name                                    |
| Program    | id, name, level (`Diploma`, `Bachelors`), department_id |
| Course     | id, name, program_id                        |
| Student    | id, name, age, gender, program_id           |
| Enrollment | id, student_id, course_id                   |

---

