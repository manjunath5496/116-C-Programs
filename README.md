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

# Question 56

### **Question:**

> ***Write a program to Compare Two Strings.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#include <string.h>
int main()
{
   char a[100], b[100];

   printf("Enter a string\n");
   scanf("%s", a);

   printf("Enter a string\n");
    scanf("%s", b);

   if (strcmp(a,b) == 0) {
      printf("The strings are equal.\n");
   }
   else {
      printf("The strings are not equal.\n");
}
   return 0;
}
```
----------------------------------------

# Question 57

### **Question:**

> ***Write a program to Convert Lowercase to Uppercase.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <ctype.h>
#include <stdio.h>
 
int main()
{
    char ch;
 
    ch = 'g';
    printf("%c in uppercase is represented as  %c", ch, toupper(ch));
 
    return 0;
}
```
----------------------------------------

# Question 58

### **Question:**

> ***Write a program to Convert Uppercase to Lowercase.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <ctype.h>
#include <stdio.h>
 
int main()
{
    char ch;
 
    ch = 'G';
    printf("%c in lowercase is represented as  %c", ch, tolower(ch));
 
    return 0;
}
```
----------------------------------------

# Question 59

### **Question:**

> ***Write a program to find the Average of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
    int num1, num2;
    float avg;

    printf("Enter first number: ");
    scanf("%d",&num1);
    printf("Enter second number: ");
    scanf("%d",&num2);

    avg= (float)(num1+num2)/2;

    printf("Average of %d and %d is: %.2f",num1,num2,avg);

    return 0;
}
```
----------------------------------------

# Question 60

### **Question:**

> ***Write a program to find Quotient and Remainder.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
    int dividend, divisor, quotient, remainder;
    printf("Enter dividend: ");
    scanf("%d", &dividend);
    printf("Enter divisor: ");
    scanf("%d", &divisor);

    quotient = dividend / divisor;

    remainder = dividend % divisor;

    printf("Quotient = %d\n", quotient);
    printf("Remainder = %d", remainder);
    return 0;
}
```
----------------------------------------
# Question 61

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<math.h>
int main()
{
int a, b;
a=2;
b = pow((a), 2);
printf("The square of a = %d", b);
return 0;
}
```
----------------------------------------

# Question 62

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i, avg, sum = 0;
int num [5] = {16, 18, 20, 25, 36};
for(i=0; i<5; i++)
sum = sum + num [i];
avg = sum/5;
printf("Sum of the Elements in the array = %d", sum);
printf("Average of the elements in the array= %d", avg);
return 0;
}
```
----------------------------------------

# Question 63

### **Question:**

> ***Write a program to find the greatest of two numbers using pointers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int x, y, *p, *q;
printf("Enter any integer:");
scanf("%d", &x);
printf("Enter any integer:");
scanf("%d", &y);
p = &x;
q = &y;
if(*p>*q)
{
printf("x is greater than y");
}
if(*q>*p)
{
printf("y is greater than x");
}
return 0;
}
```
----------------------------------------

# Question 64

### **Question:**

> ***Write a program to print the address of x and the value assigned to x.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
int x, *p;
x = 1;
p = &x;
printf("The address of the variable x =%d", p);
printf("The value of the variable x =%d", *p);
return 0;
} 
```
----------------------------------------

# Question 65

### **Question:**

> ***Write a program to print the first 10 numbers starting from one together with their squares and cubes.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i;
for( i=1; i<=10; i++)
printf("Number=%d its square=%d its cube=%d\n", i , i*i, i*i*i);
return 0;
} 
```
----------------------------------------

# Question 66

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char M;
printf("Enter any character:");
scanf("%c", &M);
printf("ch=%c", M);
return 0;
} 
```
----------------------------------------


# Question 67

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i, product = 1;
for( i=1; i<=10; i++)
product = product * i;
printf("The product of the first 10 digits =%d", product);
return 0;
}
```
----------------------------------------

# Question 68

### **Question:**

> ***Write a program to check the equivalence of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int x, y;
printf("Enter any number:");
scanf ("%d", &x);
printf("Enter any number:");
scanf ("%d", &y);
if(x-y==0)
{
printf("The two numbers are equivalent");
}
else
{
printf("The two numbers are not equivalent");
}
return 0;
}
```
----------------------------------------

# Question 69

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char a;
for( a='A'; a<='Z'; a++)
printf("%c\n", a);
return 0;
}
```
----------------------------------------

# Question 70

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b, c, d, e, f;
a = 10;
b=12;
c=a+1;
d=b+1;
e=a-1;
f=b-1;
printf("The incremented value of a =%d", c);
printf("The incremented value of b =%d", d);
printf("The decremented value of a =%d", e);
printf("The decremented value of b =%d", f);
return 0;
}
```
----------------------------------------

# Question 71

### **Question:**

> ***Write a program to print the output:</br>
Einstein [0] = E</br>
Einstein [1] = I</br>
Einstein [2] = N</br>
Einstein [3] = S</br>
Einstein [4] = T</br>
Einstein [5] = E</br>
Einstein [6] = I</br>
Einstein [7] = N</br>***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i;
char name [8] = {' E' , ' I', ' N', ' S', ' T ', ' E', ' I', ' N'};
for(i=0; i<8; i++)
printf("\n Element [%d] = %c", i, name[i]);
return 0;
}
```
----------------------------------------

# Question 72

### **Question:**

> ***Write a program to find square of a number using functions.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int square();
int main()
{
int answer;
answer = square();
printf("Square of the given number=%d", answer);
return(0);
}
int square()
{
int x;
printf("Enter any integer:");
scanf("%d", &x);
return x*x;
}
```
----------------------------------------

# Question 73

### **Question:**

> ***Write a program To print "hello world" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i;
for (i =1; i<=10; i ++)
printf("hello world \n");
return 0;
}
```
----------------------------------------


# Question 74

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i =1;
do
{
printf("%d\n", i++);
} while (i<=5);
return 0;
}
```
----------------------------------------

# Question 75

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
char i;
char body [4] = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++)
printf("\n body[%c] = %c", body[i] , body[i]);
return 0;
}
```
----------------------------------------

# Question 76

### **Question:**

> ***Write a program to check whether a character is an alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#include <ctype.h>
int main()
{
int a =2;
if(isalpha(a))
{
printf("The character a is an alphabet");
}
else
{
printf("The character a is not an alphabet");
}
return 0;
}
```
----------------------------------------


# Question 77

### **Question:**

> ***Write a program to calculate the discounted price and the total price after discount</br>
Given:</br>
If purchase value is greater than 1000, 10% discount</br>
If purchase value is greater than 5000, 20% discount</br>
If purchase value is greater than 10000, 30% discount.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
double PV;
printf("Enter purchased value:");
scanf("%lf", &PV);
if(PV>1000)
{
printf("\n Discount=%lf", PV* 0.1);
printf("\n Total=%lf", PV - PV* 0.1);
}
else if(PV>5000)
{
printf("\n Discount =%lf", PV* 0.2);
printf("\n Total=%lf", PV - PV* 0.1);
}
else
{
printf("\n Discount=%lf", PV* 0.3);
printf("\n Total=%lf", PV - PV* 0.1);
}
return 0;
}
```
----------------------------------------

# Question 78

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i = 1;
while (i<=10)
{
printf("%d\n", i++);
}
return 0;
}
```
----------------------------------------

# Question 79

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int age;
printf("Enter age:");
scanf("%d", &age);
if(age>=60)
{
printf("senior citizen");
}
else
{
printf("not a senior citizen");
}
return 0;
}
```
----------------------------------------


# Question 80

### **Question:**

> ***Write a program to find the size of data types.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
    printf("Size of char: %ld byte\n",sizeof(char));
    printf("Size of int: %ld bytes\n",sizeof(int));
    printf("Size of float: %ld bytes\n",sizeof(float));
    printf("Size of double: %ld bytes", sizeof(double));
    return 0;
}
```
----------------------------------------

# Question 81

### **Question:**

> ***Write a program to check whether a triangle is valid (given sides of triangle).***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>  
   
int main() {  
    int side1, side2, side3;  
   
    printf("Enter Length of Three Sides of a Triangle\n");  
    scanf("%d %d %d", &side1, &side2, &side3);     
   
    if((side1 + side2 > side3)&&(side2 + side3 > side1) &&(side3 + side1 > side2)) {  
        printf("It is a Valid Triangle\n");  
    } else {  
        printf("It is an invalid Triangle");  
    }  
   
    return 0;  
}
```
----------------------------------------

# Question 82

### **Question:**

> ***Write a program to check whether a triangle is valid (given angles of triangle).***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
 
int main()
{
	int angle1, angle2, angle3, sum;
 
  	printf("\n Enter Three Angles of a Triangle : ");
  	scanf("%d%d%d", &angle1, &angle2, &angle3);
  	
  	sum = angle1 + angle2 + angle3;
  	
  	if(sum == 180)
  	{
  		printf("\n This is a Valid Triangle");
 	}
	else
	{
		printf("\n This is an Invalid Triangle");
	}  
 	return 0;
 }
```
----------------------------------------

# Question 83

### **Question:**

> ***Write a program to print your name, date of birth and email address.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h> 
 int main()  
  {
     printf("Name   : Albert Einstein\n"); 
     printf("DOB    : 14 March 1879\n"); 
     printf("Email : einstein@physics.com\n"); 
     return(0); 
  }
```
----------------------------------------

# Question 84

### **Question:**

> ***Write a program to convert specified days into years, weeks and days.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h> 
int main()
{
    int days, years, weeks;

  printf("Enter number of days\n");  
    scanf("%d", &days); 

    years = days/365; 
    weeks = (days % 365)/7;
    days = days- ((years*365) + (weeks*7));

    printf("Years: %d\n", years);
    printf("Weeks: %d\n", weeks);
    printf("Days: %d \n", days);

    return 0;
}
```
----------------------------------------


# Question 85

### **Question:**

> ***Write a program to Check the password until it is correct.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
	int pass, a;	

	while (a!=0)
	{
	printf("\nInput the password: ");
	scanf("%d",&pass);	
	
	if (pass==1988)
	{
		printf("Correct password");
		a=0;
    }
    else
    {
       printf("Wrong password, try again");       
	}
	printf("\n");
   }
	return 0;
} 
```
----------------------------------------


# Question 86

### **Question:**

> ***Write a program to Read an integer and find all its divisor.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
	int x, i;
	printf("\nEnter a number : ");
	scanf("%d", &x);
	printf("All the divisor of %d are: ", x);
	for(i = 1; i <= x; i++) {
		if((x%i) == 0){
			printf("\n%d", i);
			printf("\n");
		}
	}
	
	return 0;
}
```
----------------------------------------

# Question 87

### **Question:**

> ***Write a program to shift given data by two bits to the left.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b;
printf("Enter a integer : ");
scanf("%d",&a);
printf("\nInteger value = %d ",a);
a<<=2;
b=a;
printf("\nThe left shifted data is = %d ",b);
return 0;
}
```
----------------------------------------


# Question 88

### **Question:**

> ***Write a program to Find Absolute Value of a Number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>  
#include<stdlib.h>  
  
int main()  
{  
    int num;  
  
    printf("Enter a positive or negative number\n");  
    scanf("%d", &num);  
  
    printf("Absolute Value of |%d| is %d\n", num, abs(num));  
  
    return 0;  
}  
```
----------------------------------------

# Question 89

### **Question:**

> ***Write a program to accept the height of a person in centimeter and categorize the person according to their height.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   float height;
 
    printf("Enter the height of the person (in cm) :");
    scanf("%f", &height);
    if (height < 150.0) {
        printf("The person is Dwarf. \n");
    }
    else if ((height >= 150.0) && (height < 165.0)) {
        printf("The person is  average heighted. \n");
    }
    else if ((height >= 165.0) && (height <= 195.0)) {
        printf("The person is taller. \n");
    }
    else
    {
        printf("Abnormal height.\n");
    }
        return 0;
}

```
----------------------------------------

# Question 90

### **Question:**

> ***Write a program to compute the area of the various geometrical shape.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main()
{
   int choice,r,l,w,b,h;
      float area;
      printf("Enter 1 for area of circle\n");
      printf("Enter 2 for area of rectangle\n");
      printf("Enter 3 for area of triangle\n");
      printf("Enter your choice : ");
      scanf("%d",&choice);
      
      switch(choice)
      {
           case 1:
                 printf("Enter the radius of the circle : ");
                 scanf("%d",&r);
                 area=3.14*r*r;
                 break;
            case 2:
                  printf("Enter the length and width of the rectangle : ");
                  scanf("%d%d",&l,&w);
                  area=l*w;
                  break;
            case 3:
                  printf("Enter the base and height of the triangle :");
                  scanf("%d%d",&b,&h);
                  area=0.5*b*h;
                  break;
          }
          printf("The area is : %f\n",area);
        return 0;
}

```
----------------------------------------


# Question 91

### **Question:**

> ***Write a program to Find Length of String Using Library Function.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<string.h>
 
int main() {
   char str[100];
   int len;
   printf("\nEnter the String : ");
   scanf("%s", str);
   len = strlen(str);
   printf("\nLength of Given String : %d", len);
   return(0);
}  
```
----------------------------------------

# Question 92

### **Question:**

> ***Write a program to illustrate the bitwise operators.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>

int main() {
    int a, b;
     a=125; 
     b=35;
     a=a>>1;
   printf("After right-shifting by 1, a=%d\n", a);
     b=b<<2;
   printf("After left-shifting by 2, b=%d\n", b);
   return(0);
}

```
----------------------------------------

# Question 93

### **Question:**

> ***Write a program to illustrate the ternary operation.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>

/* 

c will be assigned the value of a
if a is less than b. 
Otherwise, it will be assigned the value of b

*/

int main() {
    int a = 10, b = 20, c;

    c = (a < b) ? a : b;

    printf("%d", c);
   return(0);
}
```
----------------------------------------


# Question 94

### **Question:**

> ***Write a program to accept a character from the keyboard and print "yes" if it is equal to y. Otherwise print "No".***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>

int main() {
char ch;
printf ("Enter a character \n");
ch = getchar ();
if (ch == 'y' || ch == 'Y')
printf ("yes\n");
else
printf ("No\n");
   return(0);
}
```
----------------------------------------

# Question 95

### **Question:**

> ***Write a program to Demonstrate goto Statement.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
   int sum=0;
   for(int i = 0; i<=10; i++){
	sum = sum+i;
	if(i==4){
	   goto addition;
	}
   }

   addition:
   printf("%d", sum);

   return 0;
}

```
----------------------------------------

# Question 96

### **Question:**

> ***Write a program to Demonstrate Infinite Loop.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>

int main() {
int i = 10;
for( ; ;) {
printf("%d\n",i);
}
    return 0;
}
```
----------------------------------------


# Question 97

### **Question:**

> ***Write a program to Demonstrate Macro Substitution.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#define A 15
int main()
{
  int x;
  x=A;
  printf("%d",x);
   return 0;
}

```
----------------------------------------

# Question 98

### **Question:**

> ***Write a program to Check Whether a Number is Even or Odd.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
    int num;
    printf("Enter a number : ");
    scanf("%d", &num);
    if(num % 2 == 0)
        printf("%d is even.", num);
    else
        printf("%d is odd.", num);
    
    return 0;
}

```
----------------------------------------

# Question 99

### **Question:**

> ***Write a program to multiply given number by 4 using bitwise operators.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
    long number, tempnum;
    printf("Enter an integer \n");
    scanf("%ld", &number);
    tempnum = number;
    number = number << 2;
    printf("%ld x 4 = %ld\n", tempnum, number);
    return 0;
}
```
----------------------------------------


# Question 100

### **Question:**

> ***Write a program to check whether a number is power of 2 or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main() {
    int num;

   printf("Enter a number : ");
   scanf("%d", &num);

   if((num != 0) && ((num &(num - 1)) == 0)) {
      printf("\n%d is a power of 2", num);
}
   else {
      printf("\n%d is not a power of 2\n", num);
   }

 return 0;
   
}

```
----------------------------------------




















