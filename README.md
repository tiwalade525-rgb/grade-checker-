        # grade-checker_single_file.py

def get_score():
    score = int(input("Enter your score: "))
    return score

def calculate_grade(score):
    if score >= 70:
        return "A"
    elif score >= 60:
        return "B"
    elif score >= 50:
        return "C"
    elif score >= 45:
        return "D"
    else:
        return "F"

def display_grade(score, grade):
    print(f"Score: {score}")
    print(f"Grade: {grade}")

def main():
    score = get_score()
    grade = calculate_grade(score)
    display_grade(score, grade)

 main()
⸻

👉 1. input_module.py


