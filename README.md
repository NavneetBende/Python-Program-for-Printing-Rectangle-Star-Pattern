Printing Rectangle Star Pattern
In this Python Program, we will be discussing about how to write a program to print Rectangle Star Pattern. In this pattern, there are n rows and m numbers of column are present. So, In this Pattern, there are number of stars are different for rows and columns.Then, User have to enter two value, in which one value will be determine as a number of rows and other value will be considered as columns of the pattern. With the help of “for loop”, we will print the Rectangle Star Pattern.

Python Program for Printing Rectangle Star Pattern
Working:
Step 1. Start

Step 2. Take number of rows input from the user and store it in any variable (‘rows’ in this case).

Step 3. Take number of coloum input from the user and store it in any variable (‘cols’ in this case).

Step 4. Run a loop ‘i’ number of times to iterate through all the rows. Starting from i=0 to rows.

Step 5. Run a nested loop inside the main loop for printing stars which is starting from j=0 to cols.

Step 6. Print ‘*’ inside the nested loop to print ‘*’s in all the columns of a row.

Step 7. Move to the next line by printing a new line by using print() function.

Stop 8. Stop

Python Program:
rows = int(input("Enter rows:"))
cols = int(input("Enter Cols:"))

for i in range(0, rows):
    for j in range(0, cols):
        print("*", end="")
    print()
