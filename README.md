task 1 :- 

# Step 1: Create a dictionary of student marks
student_marks = {
    'Alice': 85,
    'Bob': 78,
    'Charlie': 92,
    'Diana': 88
}

# Step 2: Ask the user to input a student's name
student_name = input("Enter the student's name: ")

# Step 3 and 4: Retrieve and display the marks, or print appropriate message
if student_name in student_marks:
    print(f"{student_name}'s marks: {student_marks[student_name]}")
else:
    print("Student not found.")

task 2 :- 

# Step 1: Create a list of numbers from 1 to 10
numbers = list(range(1, 11))

# Step 2: Extract the first five elements
first_five = numbers[:5]

# Step 3: Reverse the extracted elements
reversed_five = first_five[::-1]

# Step 4: Print the lists
print(f"Original list: {numbers}")
print(f"Extracted first five elements: {first_five}")
print(f"Reversed extracted elements: {reversed_five}")
