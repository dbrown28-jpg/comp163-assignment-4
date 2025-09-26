# comp163-assignment-4
# Test Case 1 
student_name = "Dion"

current_gpa = 3.5

study_hours = 25

social_points = 50

stress_level = 100
# Test Case 2 
# GPA boost logic
gpa_boost = (study_hours - 20) * 0.01
current_gpa += gpa_boost

# Stress and social adjustments
if study_hours > 30:
    stress_level += 20
    print("You're studying a lot! Stress level increased.")
elif study_hours < 15:
    social_points += 10
    print("You're more social this week!")
else:
    print("Balanced week. Keep it up!")

# Final output
print("\n===Welcome to the game===")
print(f"Your name is {student_name}")
print(f"Your current GPA is {current_gpa:.2f}")
print(f"You study for {study_hours} hours a week")
print(f"Your social points are {social_points}")
print(f"Your stress level is {stress_level}")
