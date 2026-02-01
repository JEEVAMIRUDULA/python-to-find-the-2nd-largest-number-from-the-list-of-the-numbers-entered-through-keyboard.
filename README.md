# python-to-find-the-2nd-largest-number-from-the-list-of-the-numbers-entered-through-keyboard.
a=[]
n=int(input("Enter number of elements:"))
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
    a.sort()
    print("Second largest element is:",a[n-2])

note: else:
        print("Not enough elements to find second largest.")
To be given to get output without error

Output: 
Enter number of elements:8
Enter element:5

