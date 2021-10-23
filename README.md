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
	static float PI = 3.141592;
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


# Question 6

### **Question:**

> ***Write a program to Calculate Area of Rectangle.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    int length;
    int breadth;
	long area;

	printf(" Enter the Length of a Rectangle : ");
	scanf("%d", &length);
    
    
    printf("\n\n Enter the Breadth of a Rectangle : ");
	scanf("%d", &breadth);
    

	area = length*breadth;


	printf("\n\n Area of Rectangle with Length as %d and Breadth as %d  = %ld \n\n",length,breadth,area);


    return 0;
}
	
```
----------------------------------------



# Question 6

### **Question:**

> ***Write a program to Calculate Area of Parallelogram.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    int height;
    int base;
	long area;


	printf(" Enter the height of a Parallelogram : ");
	scanf("%d", &height);
    
    
    printf("\n\n Enter the Base of a Parallelogram : ");
	scanf("%d", &base);
    

	area = height*base;


	printf("\n\n Area of Parallelogram with Height as %d and Base as %d  = %ld \n\n",height,base,area);

    return 0;
}
	
```
----------------------------------------


# Question 7

### **Question:**

> ***Write a program to Calculate Area of Trapezoid.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    int height;
    int base1,base2;
	long area;



	printf(" Enter the Height of a Trapezoid : ");
	scanf("%d", &height);
    
    
    printf("\n\n Enter the Base 1 value : ");
	scanf("%d", &base1);
    
    
    printf("\n\n Enter the Base 2 value : ");
    scanf("%d", &base2);
    
    

	area = (height/2)*(base1+base2);


	printf("\n\n Area of Trapezoid with Height as %d, Base 1 as %d and Base 2 as %d = %ld",height,base1,base2,area);
    return 0;
}
```
----------------------------------------


# Question 8

### **Question:**

> ***Write a program to Calculate Volume of Cube.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    int side;
	long volume;

	printf(" Enter the side of cube : ");
	scanf("%d", &side);
    
    
    
	volume = side*side*side;


	printf("\n\n Volume of Cube with Side as %d = %ld ",side, volume);

    return 0;
}


```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to Calculate Volume of Cylinder.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    const float PI = 3.141592;  
          float radius, height, volume;  
  
    printf("Enter Radius and Height of the Cylinder\n");  
    scanf("%f%f", &radius, &height);  
  
    volume = PI * radius * radius * height;  
  
    printf("Volume of Cylinder is %f\n", volume);

    return 0;
}
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to Calculate Area of an Ellipse.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#define PI 3.141592

int main()
{
    float major, minor, area;

    printf("Enter length of major axis: ");
    scanf("%f", &major);

    printf("Enter length of minor axis: ");
    scanf("%f", &minor);

    area = PI * major * minor;

    printf("Area of an ellipse = %0.4f", area);

    return 0;
}

```
----------------------------------------


# Question 11

### **Question:**

> ***Write a program to Calculate Volume of Pyramid.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#define PI 3.141592

int main()
{
    
    int basearea;
    int height;
    float volume;

	printf("\n\n Enter the Base Area of Pyramid : ");
	scanf("%d", &basearea);
    
    printf("\n\n Enter the Height of Pyramid : ");
	scanf("%d", &height);
    
    
    volume = (1/3)*basearea*height;


	printf("\n\n Volume of Pyramid with Base Area as %d and Height as %d = %f",basearea,height,volume);

    return 0;
}


```
----------------------------------------

# Question 12

### **Question:**

> ***Write a program to Calculate Volume of Cone.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    
    int height;
    int radius;
    float volume;
    float PI = 3.141592;

	printf("\n\n Enter the Radius of Cone : ");
	scanf("%d", &radius);
    
    printf("\n\n Enter the Height of Cone : ");
	scanf("%d", &height);
    
    
    volume = 1/3 * PI*radius*radius*height;


	printf("\n\n Volume of Cone with Radius as %d and Height as %d = %f",radius,height,volume);


    return 0;
}

```
----------------------------------------

# Question 13

### **Question:**

> ***Write a program to Calculate Volume of Sphere.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    
    int radius;
    float volume;
    float PI = 3.141592;

	printf("\n\n Enter the Radius of Sphere : ");
	scanf("%d", &radius);
    
    
    
    volume_of_sphere = (4/3)*(PI*radius*radius*radius);


	printf("\n\n Volume of Sphere with Radius as %d = %f",radius,volume);


    return 0;
}
```
----------------------------------------

# Question 14

### **Question:**

> ***Write a program to Calculate Volume of Ellipsoid.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    
    int r1,r2,r3;
    float volume;
    float PI = 3.141592;

	printf("\n\n Enter the Radius of the ellipsoid of axis 1 : ");
	scanf("%d", &r1);
    
    printf("\n\n Enter the Radius of the ellipsoid of axis 2 : ");
	scanf("%d", &r2);
    
    printf("\n\n Enter the Radius of the ellipsoid of axis 3 : ");
	scanf("%d", &r3);
    
    
    
    volume = (4/3)*(PI*r1*r2*r3);


	printf("\n\n Volume of Ellipsoid with (r1,r2,r3) as (%d,%d,%d) = %f",r1,r2,r3,volume);

    return 0;
}
```
----------------------------------------

# Question 15

### **Question:**

> ***Write a program to Calculate Surface area of Cube.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
  int side;
  long surfacearea;

	printf("\n\n Enter the Side of Cube : ");
	scanf("%d", &side);
    
    
    
    surfacearea = 6*side*side;


	printf("\n\n Surface area of Cude with side as %d = %ld",side,surfacearea);
    return 0;
}

```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program to Calculate Surface area of Sphere.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
  int radius;
  float PI = 3.141592;
  float surfacearea;


	printf("\n\n Enter the Radius of Sphere : ");
	scanf("%d", &radius);
    
    
    
    surfacearea = 4*PI*radius*radius;


	printf("\n\n Surface area of Sphere with radius as %d = %lf",radius,surfacearea);
    return 0;
}

```
----------------------------------------


# Question 17

### **Question:**

> ***Write a program to Generate Multiplication Table.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
  int number;
  int i = 1;

	printf("\n\n Enter number to generate Multiplication Table : ");
	scanf("%d", &number);
    
    printf("\n\nMultiplication Table of %d : \n",number);
    for(i; i <11 ; i++) {
        printf("%d x %d = %d \n\n",number,i, i*number);
    }
   
    return 0;
}


```
----------------------------------------

# Question 18

### **Question:**

> ***Write a program to Compute Simple Interest.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
  int principal;
  int rate;
  int duration;
  float simpleInterest;

	printf("\n\n Enter Principal Amount : ");
	scanf("%d", &principal);
    
    printf("\n\n Enter Rate of Interest : ");
	scanf("%d", &rate);
    
    printf("\n\n Enter Duration : ");
    scanf("%d", &duration);
    
    simpleInterest = (principal*duration*rate)/100;
    
    printf("\n\nSimple Interest :  %lf  \n",simpleInterest);
    return 0;
}



```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to Convert Degree to Fahrenheit.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
   float degree,fahrenheit;

	printf("\n\n Enter Temperature in Degrees  : ");
	scanf("%f", &degree);
    
    fahrenheit = (1.8*degree)+32;
    
    printf("\n\n %f Degree in Fahrenheit = :  %f  \n",degree,fahrenheit);

    return 0;
}


```
----------------------------------------


# Question 20

### **Question:**

> ***Write a program to Convert Fahrenheit to Degree.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
  float degree;
  float fahrenheit;
  

	printf("\n\n Enter Temperature in Fahrenheit  : ");
	scanf("%f", &fahrenheit);
    
    degree = ((fahrenheit-32)*5)/9; 
    
    printf("\n\n %f Fahrenheit in Degree Celsius = %f  \n",fahrenheit,degree);


    return 0;
}


```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to Convert Meters to Feet.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
  float meter;
  float feet;
  

	printf("\n\n Enter Length in Meters  : ");
	scanf("%f", &meter);
    
    feet = (meter*3.26);
    
    printf("\n\n %f meter in feet = %f  \n",meter,feet);

    return 0;
}


```
----------------------------------------


# Question 22

### **Question:**

> ***Write a program to Convert Feet to Meters.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
  float meter;
  float feet;
  
	printf("\n\n Enter Length in Feet  : ");
	scanf("%f", &feet);
    
    meter = (feet/3.26);
    
    printf("\n\n %f Feet in Meter = %f  \n",feet,meter);

    return 0;
}


```
----------------------------------------


