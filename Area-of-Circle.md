//This program has been coded by Avinash Shandilya in Code::Blocks IDE.

//Program to find the area of a circle whose radius is given.


#include <stdio.h>

#include <stdlib.h>


int main()

{

    float radius;

    printf("enter the radius of the circle: ");

    scanf("%f", &radius);


    float area,pi;
  
    pi = 3.14;
    
    area = radius * radius * pi;

    printf("area of the circle is %.2f", area);
    
    return 0;
}

