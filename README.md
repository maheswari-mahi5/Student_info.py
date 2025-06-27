# Student_info.py
name = input("Enter your name: ")
roll = input("Enter your roll number: ")
branch = input("Enter your branch: ")

# Email generation
email = name.lower() + "@college.com"
#Final output
print("\n🎓 Student Details:")
print("Name     :", name.upper())
print("Roll No  :", roll)
print("Branch   :", branch)
print("Email ID :", email)
