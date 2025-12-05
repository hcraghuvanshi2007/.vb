-----Q1-------------------------------------------------------------------------------------------------------
class Student:    
    def __init__(self): 
        self.name = ""
        self.roll = 0
        self.marks = 0.0
    
    def accept_details(self):
        try:
            self.name = input("Enter student name: ").strip()
            if not self.name:
                raise ValueError("Name cannot be empty")
            
            self.roll = int(input("Enter roll number: "))
            if self.roll <= 0:
                raise ValueError("Roll number must be positive")
            
            self.marks = float(input("Enter marks (0-100): "))
            if not (0 <= self.marks <= 100):
                raise ValueError("Marks must be between 0 and 100")
            
            print("✅ Details accepted successfully!\n")
                
        except ValueError as e:
            print(f"❌ Error: {e}")
            print("Please try again...\n")
            self.accept_details()
    
    def display_details(self):
        grade = self.find_grade()
        print(f"\n{'='*40}")
        print(f"{'STUDENT DETAILS':^40}")
        print(f"{'='*40}")
        print(f"Name:          {self.name}")
        print(f"Roll Number:   {self.roll}")
        print(f"Marks:         {self.marks}")
        print(f"Grade:         {grade}")
        print(f"{'='*40}\n")
    
    def find_grade(self):
        if self.marks >= 90:
            return 'A+'
        elif self.marks >= 80:
            return 'A'
        elif self.marks >= 70:
            return 'B+'
        elif self.marks >= 60:
            return 'B'
        elif self.marks >= 50:
            return 'C'
        elif self.marks >= 40:
            return 'D'
        else:
            return 'F'

if __name__ == "__main__":
    print("\n" + "="*40)
    print("STUDENT MANAGEMENT SYSTEM".center(40))
    print("="*40 + "\n")
    
    
    student = Student()
------Q2------------------------------------------------------------------------------------------------------------------------------------------------------------
def analyze_student_marks(filename):
    marks = []
    try:
        with open(filename, 'r') as file:
            for line in file:
                try:
                    mark = int(line.strip())
                    if 0 <= mark <= 100:  
                        marks.append(mark)
                    else:
                        print(f"Warning: Invalid mark '{line.strip()}' found in file. Skipping.")
                except ValueError:
                    print(f"Warning: Non-integer mark '{line.strip()}' found in file. Skipping.")
    except FileNotFoundError:
        print(f"Error: The file '{filename}' was not found.")
        return
    except Exception as e:
        print(f"An unexpected error occurred while reading the file: {e}")
        return

    if not marks:
        print("No valid marks found in the file to analyze.")
        return

    highest_mark = max(marks)
    average_mark = sum(marks) / len(marks)

    print(f"Highest mark: {highest_mark}")
    print(f"Average mark: {average_mark:.2f}")

analyze_student_marks('marks.txt')


    student.accept_details()
    student.display_details()
