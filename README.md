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



# Question 7

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


# Question 8

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


# Question 9

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

# Question 10

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

# Question 11

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


# Question 12

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

# Question 13

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

# Question 14

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

# Question 15

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

# Question 16

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

# Question 17

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


# Question 18

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

# Question 19

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

# Question 20

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


# Question 21

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

# Question 22

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
    
    feet = (meter*3.2808);
    
    printf("\n\n %f meter in feet = %f  \n",meter,feet);

    return 0;
}


```
----------------------------------------


# Question 23

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
    
    meter = (feet/3.2808);
    
    printf("\n\n %f Feet in Meter = %f  \n",feet,meter);

    return 0;
}


```
----------------------------------------


# Question 24

### **Question:**

> ***Write a program to Convert Feet to Centimeters.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
 float cm;
  float feet;
  

	printf("\n\n Enter Length in Feet  : ");
	scanf("%f", &feet);
    
    cm = 30.48 * feet;
    
    printf("\n\n %f Feet in Meter = %f  \n",feet,cm);

    return 0;
}

```
----------------------------------------

# Question 25

### **Question:**

> ***Write a program to Convert Feet to millimeters.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
 float mm;
  float feet;

	printf("\n\n Enter Length in Feet  : ");
	scanf("%f", &feet);
    
    mm = (feet * 304.8);
    
    printf("\n\n %f Feet in Millimeter = %f  \n",feet,mm);


    return 0;
}

```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to Convert Kilometer to Miles.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
 float km;
  float miles;
  

	printf("\n\n Enter Length in Kilometer  : ");
	scanf("%f", &km);
    
    miles = (0.621371*km);
    
    printf("\n\n %f Kilometer in Millimeter = %f  \n",km,miles);


    return 0;
}

```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program to Convert Yard to Foot.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
  float yard;
  float foot;
  

	printf("\n\n Enter Length in Yard  : ");
	scanf("%f", &yard);
    
    foot = (3*yard);
    
    printf("\n\n %f Yard in Foot = %f  \n",yard,foot);


    return 0;
}


```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program to Convert Inch to Cm.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   
  float inch;
  float cm;


	printf("\n\n Enter Length in inch  : ");
	scanf("%f", &inch);
    
    cm = (2.54*inch);
    
    printf("\n\n %f inch in cm = %f  \n",inch,cm);


    return 0;
}


```
----------------------------------------

# Question 29

### **Question:**

> ***Write a program to convert bytes to kilobytes.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

	int bytes;

	double kilobytes;

	printf("Enter number of bytes: ");

	scanf("%d",&bytes);

	kilobytes=bytes/1024.00;

	printf("Kilobytes: %.2lf",kilobytes);

	return 0;


}
```
----------------------------------------

# Question 30

### **Question:**

> ***Write a program to convert MB to KB.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

double megabytes , kilobytes;

printf("Please enter the amount of megabytes to convert.\n");

scanf("%lf",&megabytes);

kilobytes = megabytes * 1024;

printf("There are %lf kilobytes in %lf megabytes.\n",kilobytes,megabytes);

return 0;

}
```
----------------------------------------


# Question 31

### **Question:**

> ***Write a program to convert GB to MB.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

double gb, mb;
  
    printf("\n\n Enter Length in Gigabyte  : ");
	scanf("%lf", &gb);
    
    mb = gb*1024;
    
    printf("\n\n %lf GB  =  %lf MB  \n",gb,mb);


return 0;

}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to convert KB to MB.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>

int main()

{

double kb, mb;
  

	printf("\n\n Enter Length in Kilobyte  : ");
	scanf("%lf", &kb);
    
    mb = (kb/1024);
    
    printf("\n\n %lf KB  =  %lf MB  \n",kb,mb);



return 0;

}
```
----------------------------------------

# Question 33

### **Question:**

> ***Write a program to Convert Kilogram to Pounds.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

 float kg,lbs;
  

    printf("\n\n Enter Weight in Kilogram  : ");
	scanf("%f", &kg);
    
    lbs = kg*2.20462;
    
    printf("\n\n %f Kg  =  %f Pounds \n",kg,lbs );


return 0;

}
```
----------------------------------------

# Question 34

### **Question:**

> ***Write a program to Convert Kilogram to Ounce.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

 float kg,ounce;
  


    printf("\n\n Enter Weight in Kilogram  : ");
	scanf("%f", &kg);
    
    ounce = kg*35.274;
    
    printf("\n\n %f Kg  =  %f Ounce \n",kg,ounce );


return 0;

}
```
----------------------------------------

# Question 35

### **Question:**

> ***Write a program to Convert Pounds to Grams.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

 float pound,gram;
  


    printf("\n\n Enter Weight in Pounds  : ");
	scanf("%f", &pound);
    
    gram = pound*453.592;
    
    printf("\n\n %f Pound  =  %f Grams \n",pound,gram );


return 0;

}
```
----------------------------------------


# Question 36

### **Question:**

> ***Write a program to Calculate total marks and Percentage.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

  int algebra,geometry,arithmetic;
  int sum;
  float percentage;
  

    
    printf("\n\n Enter Marks Scored in Algebra  : ");
    scanf("%d", &algebra);
     
    printf("\n\n Enter Marks Scored in Geometry  : ");
    scanf("%d", &geometry);
    
    printf("\n\n Enter Marks Scored in Arithmetic  : ");
    scanf("%d", &arithmetic);
    
   

    sum = algebra+geometry+arithmetic;
    
    percentage =  (sum*100)/300;
    
    printf("\n\n Total marks scored  = %d /300", sum );
    
     printf("\n\n Percentage Scored  = %f", percentage );


return 0;

}
```
----------------------------------------


# Question 37

### **Question:**

> ***Write a program to Calculate Discount Amount and Discounted Price.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

   float price;
   float discountpercentage;
   float discountamount;
   float discountedprice;
  

    printf("\n\n Enter Price of Item  : ");
    scanf("%f", &price);
    
   
    printf("\n\n Enter Discount Percentage on Item  : ");
    scanf("%f", &discountpercentage);
    
    
    discountamount = (discountpercentage*price)/100;
    
    discountedprice = (price-discountamount);
  
    
    printf("\n\nDiscount amount : %f \n\n",  discountamount);
    printf("Discounted price : %f \n\n",  discountedprice);
  
return 0;

}
```
----------------------------------------


# Question 38

### **Question:**

> ***Write a program to Swap two numbers using a Temporary variable.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

  double first, second, temp;

    printf("\n\n Enter first number :   ");
    scanf("%lf", &first);
    
   
    printf("\n\n Enter second number : ");
    scanf("%lf", &second);
    
     printf("\n\n Before Swapping => first number : %lf    second number : %lf ",  first, second);
     

   temp = first;
   first = second;
   second = temp;
   
    printf("\n\n After Swapping => first number : %lf    second number : %lf ",  first, second);
  
  return 0;

}
```
----------------------------------------


# Question 39

### **Question:**

> ***Write a program to Swap two numbers without using a Temporary variable.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()

{

double first, second;


    printf("\n\n Enter first number : ");
    scanf("%lf", &first);
    
   
    printf("\n\n Enter second number : ");
    scanf("%lf", &second);
    
     printf("\n\n Before Swapping => first number : %lf    second number : %lf ",  first,second);
     
   first = first + second;
   second = first - second;
   first = first - second;
   
    printf("\n\n After Swapping => first number : %lf    second number : %lf ",  first,second);
  

  return 0;

}
```
----------------------------------------


# Question 40

### **Question:**

> ***Write a program to Reverse Digits of a Number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
 
int main(){
    int number, reverse = 0;
    printf("Enter any number \n");
    scanf("%d", &number);
    while(number != 0){
        reverse = (reverse * 10) + number % 10;
        number = number/10;
    }    
    printf("Reversed number : %d\n", reverse);
     
    return 0;
}
```
----------------------------------------


# Question 41

### **Question:**

> ***Write a program to Calculate sum of Digits of Entered Number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
   int n, m, sum = 0;

   printf("Enter a number\n");
   scanf("%d", &n);

   m = n;

   while (m != 0)
   {
  
      sum = sum + m % 10;
      m = m / 10;
   }

   printf("Sum of digits of %d = %d\n", n, sum);

   return 0;
}
```
----------------------------------------

# Question 42

### **Question:**

> ***Write a program to calculate the largest of 3 numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
  
int main()
{
    int A, B, C;
  
    printf("Enter the numbers A, B and C: ");
    scanf("%d %d %d", &A, &B, &C);
  
    if (A >= B && A >= C)
        printf("%d is the largest number.", A);
  
    if (B >= A && B >= C)
        printf("%d is the largest number.", B);
  
    if (C >= A && C >= B)
        printf("%d is the largest number.", C);
  
    return 0;
}
```
----------------------------------------


# Question 43

### **Question:**

> ***Write a program to Check Entered character is a Vowel or Consonant.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
  
int main()
{
   char ch;
  

    printf("\n\n Enter a character : ");
    scanf("%c", &ch);


   if(ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u' ||
      ch == 'A' || ch == 'E' || ch == 'I' || ch == 'O' || ch == 'U' ) {
          
         printf("\n\n %c is a Vowel!! ",ch);
  
  }
   else {
       
         printf("\n\n %c is a Consonant!! ",ch);
   }
   
   
 
    return 0;
}
```
----------------------------------------



# Question 44

### **Question:**

> ***Write a program to Check Entered Number is a Leap Year or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
  
int main()
{
   
   int year;
  

    printf("\n\n Enter a Number : ");
    scanf("%d", &year);


   if ((year % 400 == 0) || ( ( year % 100 != 0) && (year % 4 == 0 ))) {
       
       printf("\n\n %d is a leap year!",year);
   }
   else {
       
       printf("\n\n %d is not a leap year!!",year);
   }
   
  
 
    return 0;
}
```
----------------------------------------


# Question 45

### **Question:**

> ***Write a program to find factorial of a number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
 
int main()
{
    int num,i;
    long int fact;
  
    printf("Enter an integer number: ");
    scanf("%d",&num);
  
    /*product of numbers from num to 1*/
    fact=1;
    for(i=num; i>=1; i--)
        fact=fact*i;
         
    printf("\nFactorial of %d is = %ld",num,fact);
      
    return 0;
}
```
----------------------------------------


# Question 46

### **Question:**

> ***Write a program to Display day of week using switch case.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
 
int main()
{
    int day;

    printf("\n\n Enter Day (1 to 7) : ");
    scanf("%d", &day);

    
  switch(day)  {

     case 1:
    printf("\n\n The 1st day of week is : Sunday");
     break;
     
      case 2:
    printf("\n\n The 2nd day of week is : Monday");
     break;
     
      case 3:
    printf("\n\n The 3rd day of week is : Tuesday");
     break;
     
      case 4:
    printf("\n\n The 4th day of week is : Wednesday");
     break; 
     
     case 5:
    printf("\n\n The 5th day of week is : Thursday");
     break;
     
      case 6:
    printf("\n\n The 6th day of week is : Friday");
     break;
     
      case 7:
    printf("\n\n The 7th day of week is : Saturday");
     break;
     
   default:
    printf("Invalid input!!! ..... ");

}
      
    return 0;
}
```
----------------------------------------


# Question 47

### **Question:**

> ***Write a program to Check Entered number is positive or negative.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
 
int main()
{
    int number;

    printf("\n\n Enter a number : ");
    scanf("%d", &number);

    if(number > 0) {
      printf("\n\n Entered number %d is a positive number ",number);  
        
    }
    else if(number < 0) {
         printf("\n\n Entered number %d is a negative number ",number);  
        
    }
    
    else {
    
         printf("\n\n Entered number %d is neither positive nor negative ",number);
    }

    return 0;
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to Check Entered Character is Upper Case or Lower Case.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main(){
    
  char ch; 
    printf("Enter the alphabet : ");
 
    scanf("%c",&ch);
 
   if(ch>=65 && ch<=90)
 
      printf("upper case");
 
    else if(ch>=97 && ch<=122)
 
 
    printf("lower case");
 
     
    else
     printf("Invalid input");
  
    return 0;
}
```
----------------------------------------


# Question 49

### **Question:**

> ***Write a program to Print Number of Days in a Month.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main(){
    
  int a[12]={31,28,31,30,31,30,31,31,30,31,30,31},m; 
    printf("Enter the month: ");
 
    scanf("%d",&m);
    if(m>12 || m<1)
    {
    	
    
     printf("Invalid input");
    }
    else if(m==2)
    {
    	printf("Number of days in month 2 is either 29 or 28");
    }
    else
    
    	printf("Number of days in month %d is %d",m,a[m-1]);
    return 0;
}
```
----------------------------------------

# Question 50

### **Question:**

> ***Write a program to calculate the length of string.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#include <string.h>
  
int main()
{
    char Str[1000];
    int i;
  
    printf("Enter the String: ");
    scanf("%s", Str);
  
    for (i = 0; Str[i] != '\0'; ++i);
  
    printf("Length of '%s' is %d",Str, i);
  
    return 0;
}
```
----------------------------------------

# Question 51

### **Question:**

> ***Write a program to Concatenate Two Strings.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#include <string.h>
int main()
{
  char a[1000], b[1000];

  printf("Enter the first string\n");
  scanf("%s", a);

  printf("Enter the second string\n");
  scanf("%s", b);

  strcat(a, b);

  printf("String obtained on concatenation: %s\n", a);

  return 0;
}
```
----------------------------------------

# Question 52

### **Question:**

> ***Write a program to Find Maximum Between Two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
  int a,b;
	printf("Enter two numbers:\n");
	scanf("%d%d",&a,&b);
	if(a>b)
	printf("%d is a maximum number\n",a);
	else
	printf("%d is a maximum number\n",b);
  return 0;
}
```
----------------------------------------


# Question 53

### **Question:**

> ***Write a program to check whether the entered number is a prime number or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
    int num, i, count=0;
    printf("Enter a number: ");
    scanf("%d", &num);
    for(i=2; i<num; i++)
    {
        if(num%i == 0)
        {
            count++;
            break;
        }
    }
    if(count==0) {
        printf("\n %d is a prime number", num);
    }
    else {
        printf("\n %d is not a prime number", num);
    }
        
    return 0;
}
```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to Get Input from User.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
    int num;
    printf("Enter the Number: ");
    scanf("%d", &num);
    printf("\nYou've entered: %d", num);
    return 0;
}
```
----------------------------------------

# Question 55

### **Question:**

> ***Write a program to Print ASCII Value of entered Alphabet.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<conio.h>
int main()
{
    char ch;
    int i;
    printf("Enter a Alphabet: ");
    scanf("%c", &ch);
    i = ch;
    printf("\nASCII Value of %c = %d", ch, i);
    return 0;
}
```
----------------------------------------





























