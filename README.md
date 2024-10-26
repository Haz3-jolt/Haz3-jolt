# Hello there 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Hari Srinivasan"
        self.role = "Software Developer"
        self.language_spoken = ["en_US", "ta.IN", "hi.IN"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = SoftwareEngineer()
me.say_hi()
```

## 🔧 Technologies & Tools

**Programming Languages:**

![Python](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=6aa6f8)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Objective-C](https://img.shields.io/badge/OBJECTIVE--C-%233A95E3.svg?style=for-the-badge&logo=apple&logoColor=white)



## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=haz3-jolt&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)

```sql
-- Connect to the database
\c university_db;

-- Creating a table for Mini Project details
CREATE TABLE MiniProject (
    project_id SERIAL PRIMARY KEY,
    student_name VARCHAR(100) NOT NULL,
    reg_number INT NOT NULL,
    department VARCHAR(50),
    semester INT,
    course_code VARCHAR(10),
    course_title VARCHAR(100),
    project_title VARCHAR(100),
    supervisor VARCHAR(100),
    submission_date DATE
);

-- Inserting your details into the MiniProject table
INSERT INTO MiniProject (student_name, reg_number, department, semester, course_code, course_title, project_title, supervisor, submission_date) 
VALUES 
('Hari Srinivasan', 2023115022, 'Information Science and Technology', 3, 'IT23303', 'Database Management Systems', 'AUSEC Quiz Hosting Website', 'Prof. Dr. P. Geetha', '2024-10-19');

-- Display the project details
SELECT * FROM MiniProject;
```
