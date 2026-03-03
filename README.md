🔄 Remove Duplicates from List in Python

This Python program removes duplicate elements from a list while maintaining the original order.

📌 Features

Takes space-separated input

Removes duplicate values

Maintains original order

Beginner-friendly logic

Interview-focused solution

💻 Technology Used

Python 3

🚀 How It Works

The program takes space-separated numbers as input.

Converts input into a list of integers.

Creates an empty list called unique_numbers.

Iterates through the original list.

Adds element only if it is not already present.

Prints the final list without duplicates.

📝 Code
numbers = list(map(int, input("Enter numbers separated by space: ").split()))

unique_numbers = []

for num in numbers:
    if num not in unique_numbers:
        unique_numbers.append(num)

print("List after removing duplicates:", unique_numbers)
▶️ Example

Input:

1 2 3 2 4 1 5

Output:

List after removing duplicates: [1, 2, 3, 4, 5]

🎯 Learning Concepts

List operations

Looping

Conditional statements

Membership operator (in)

Maintaining order in lists
