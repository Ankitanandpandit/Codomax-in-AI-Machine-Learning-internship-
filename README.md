# Codomax-in-AI-Machine-Learning-internship-
Codomax in AI &amp; Machine Learning internshi
Module 2 Task Completed 

What You'll Do
Apne Python knowledge se ek simple project banao. Examples: Calculator, Guessing Game, Student Grade
Calculator, Expense Tracker, Password Generator.
Recommended Project: Number Guessing Game
User ko 1 se 100 ke beech number guess karna hota hai. Hints milte hain (Too High / Too Low). Maximum 10
attempts.
# Number Guessing Game - Complete Code
import random
def number_guessing_game():
 print("=" * 40)
 print(" Welcome to Number Guessing Game!")
 print("=" * 40)
 secret_number = random.randint(1, 100)
 attempts = 0
 max_attempts = 10
 print(f"I have selected a number between 1 and 100.")
 print(f"You have {max_attempts} attempts to guess it.\n")
 while attempts < max_attempts:
 try:
 guess = int(input(f"Attempt {attempts + 1}: Enter your guess: "))
 attempts += 1
 if guess < secret_number:
 print("Too Low! Try again.\n")
 elif guess > secret_number:
 print("Too High! Try again.\n")
 else:
 print(f"\nCongratulations! You guessed it in {attempts} attempts!")
 print(f"The number was {secret_number}.")
 return
 except ValueError:
 print("Please enter a valid number!\n")
 print(f"\nGame Over! The number was {secret_number}.")
 print("Better luck next time!")
if __name__ == "__main__":
 number_guessing_game()
Other Project Ideas
• Simple Calculator: +, -, *, / operations with menu
• Student Grade Calculator: Marks input → percentage + grade
• Password Generator: Random strong password (letters + digits + symbols)
• Expense Tracker: Daily expenses add karo aur total dikhao
Submission
GitHub Repository Link – Project code + proper README.md (description, how to run, technologies used).