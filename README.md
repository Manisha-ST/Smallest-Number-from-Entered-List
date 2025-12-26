# Smallest-Number-from-Entered-List

n = int(input("Enter the Limit less than 9999999999: "))
small = 9999999999

for i in range(1, n + 1):
    print("Enter", i, end=" ")
    a = int(input("th number: "))
    if a < small:
        small = a

print("Smallest number is:", small)

Output:
Enter the Limit less than 9999999999: 4
Enter 1 th number: 45
Enter 2 th number: 12
Enter 3 th number: 89
Enter 4 th number: 7
Smallest number is: 7
