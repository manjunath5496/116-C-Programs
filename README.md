# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```
----------------------------------------

# Question 2

### **Question:**

> ***Write a program to Find Sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
   int num1;
	int num2;
	int sum;

    printf("Enter value of 1st number : ");
	scanf("%d", &num1);

	printf("\n\nEnter value of 2nd number : ");
	scanf("%d", &num2);

	sum = num1 + num2;

	printf("\n\n Sum of %d + %d = %d", num1, num2, sum);
	
	return 0;
}
	
	
```
----------------------------------------

# Question 3

### **Question:**

> ***Write a program to Find Difference of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
    int num1;
	int num2;
	int difference;

    printf("Enter value of 1st number : ");
	scanf("%d", &num1);

	printf("\n\nEnter value of 2nd number : ");
	scanf("%d", &num2);

	difference = num1 - num2;

	printf("\n\n Difference of %d - %d = %d", num1, num2, difference);
	
	return 0;
}
	
	
	
```
----------------------------------------

# Question 4

### **Question:**

> ***Write a program to Find Division of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
    int num1;
	int num2;
	int division;

    printf("Enter value of 1st number : ");
	scanf("%d", &num1);

	printf("\n\nEnter value of 2nd number : ");
	scanf("%d", &num2);

	division = num1 / num2;

	printf("\n\n Division of %d / %d = %d", num1, num2, division);
	
	return 0;
}
	
	
```
----------------------------------------


# Question 5

### **Question:**

> ***Write a program to Calculate Area and Circumference of Circle.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
    int radius;
	static float PI = 3.142;
	float area;
	float Circumference;

	printf("Enter the radius of Circle : ");
	scanf("%d", &radius);

	area = PI*radius*radius;

	Circumference = 2*PI*radius;

	printf("\n\nArea of circle with radius %d = %f  \n\n",radius, area);


	printf("Circumference of circle with radius %d = %f  \n\n",radius, Circumference);

        return 0;
}
	
	
```
----------------------------------------









