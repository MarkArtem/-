class Student:
    def __init__(self, student_id, name, age, grade):
        self.student_id = student_id
        self.name = name
        self.age = age
        self.grade = grade

    def __str__(self):
        return f"ID: {self.student_id}, Имя: {self.name}, Возраст: {self.age}, Класс: {self.grade}"

class Grade:
    def __init__(self):
        self.grades = {}  

    def add_grade(self, student_id, subject, grade):
        if student_id not in self.grades:
            self.grades[student_id] = {}
        self.grades[student_id][subject] = grade

    def get_grades(self, student_id):
        return self.grades.get(student_id, "No grades available")

    def __str__(self):
        return str(self.grades)

class Attendance:
    def __init__(self):
        self.attendance = {}  

    def mark_attendance(self, student_id, date, status):
        if student_id not in self.attendance:
            self.attendance[student_id] = {}
        self.attendance[student_id][date] = status

    def get_attendance(self, student_id):
        return self.attendance.get(student_id, "No attendance records available")

    def __str__(self):
        return str(self.attendance)

students = []
grades = Grade()
attendance = Attendance()

students.append(Student(1, "Алиса", 15, 1))
students.append(Student(2, "Боб", 16, 2))

grades.add_grade(1, "Математика", 5)
grades.add_grade(1, "Английский", 4)
grades.add_grade(2, "Математика", 3)
grades.add_grade(2, "Английский", 4)

attendance.mark_attendance(1, "2024-12-01", "Present")
attendance.mark_attendance(1, "2024-12-02", "Abesent")
attendance.mark_attendance(2, "2024-12-03", "Absent")
attendance.mark_attendance(2, "2024-12-01", "Prsent")

print("Студенты:")
for student in students:
    print(student)

print("Оценки:")
print(grades)

print("Посещаемость:")
print(attendance)
