#include<stdio.h>

main()

{

int choice=0;

printf("pick an item : \n1. Pizza, Rs.329\n2. Burger, Rs 129\n3. Pasta, Rs 179\n4. French Fries, Rs 99\n5. Sandwich, Rs 149");

scanf("%d",&choice);

switch(choice)

{

case 1:
         
printf("Food item - Pizza, Price - 239");
      
break;

case 2:

printf("Food item - Burger, Price - 129");

break;

case 3:

printf("Food item - Pasta, Price - 179");

break;

case 4:

printf("Food item - French fries, Price - 99");

break;

case 5:

printf("Food item - Sandwich, Price - 149");

break;

default : 
     
printf("Invalid choice");

}

}
