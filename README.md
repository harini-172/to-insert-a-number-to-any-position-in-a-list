# to-insert-a-number-to-any-position-in-a-list
numbers = [3, 4, 1, 9, 6, 2, 8]
print("Original list:", numbers)

x = int(input("Enter the number to be inserted: "))
y = int(input("Enter the position: "))

numbers.insert(y, x)
print("Updated list:", numbers)
output
Original list: [3, 4, 1, 9, 6, 2, 8]
Updated list: [3, 4, 1, 7, 9, 6, 2, 8]
