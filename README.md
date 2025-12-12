# Simple Quiz Program

score = 0

print("Welcome to the Quiz!")
print("Answer the following questions:\n")

# Question 1
print("1. What is the capital of India?")
print("a) Mumbai")
print("b) Delhi")
print("c) Chennai")
answer = input("Your answer: ")

if answer.lower() == "b":
    score += 1

# Question 2
print("\n2. Which language is used to write Python programs?")
print("a) English")
print("b) Python")
print("c) Both a and b")
answer = input("Your answer: ")

if answer.lower() == "c":
    score += 1

# Question 3
print("\n3. What is the result of 2 + 3?")
print("a) 4")
print("b) 5")
print("c) 6")
answer = input("Your answer: ")

if answer.lower() == "b":
    score += 1

print("\nQuiz Completed!")
print("Your Score:", score, "/ 3")
