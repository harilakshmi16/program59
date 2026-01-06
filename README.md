numbers = [3, 4, 1, 9, 6, 2, 8]
print(numbers)

x = int(input("Enter the number to be inserted: "))
y = int(input("Enter the position: "))

numbers.insert(y, x)
print(numbers)

Output;

[3, 4, 1, 9, 6, 2, 8]
Enter the number to be inserted: 4
Enter the position: 2
[3, 4, 4, 1, 9, 6, 2, 8]

Pgm 78;
numbers = [3, 4, 1, 9, 6, 2, 8]
print(numbers)

x = int(input("Enter the position of the element to be deleted: "))

numbers.pop(x)
print(numbers)

Output;

[3, 4, 1, 9, 6, 2, 8]
Enter the position of the element to be deleted: 4
[3, 4, 1, 9, 2, 8]

