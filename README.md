# C-Programming-Lab
## Lab task 3
### Making a repository
This repository has been made for my PF Lab Task#3\
This assignment is due on ~~7 PM~~ **8 PM, Thursday**
I was instructed to;
- [x] Create a GitHub account (if not already created).
- [x] Create a new repository with the name C-Programming-Lab.
- [x] Add a README.md file and write a short description about the repository.

Listed above are the ***objectives.***\
*I experimented with Github during the online class, hence my account already has some repositories/ files present.*


LAB 4: TASK 1 #include <stdio.h> int main() { int age; printf("enter your age: "); scanf("%d", &age); if (age>=18) { printf("you are eligible to vote"); } else { printf("you are not eligible to vote"); } } TASK 2 #include <stdio.h> int main() { int num; printf("enter a number: "); scanf("%d", &num); if (num%2==0) { printf("this is an even number"); } else { printf("this is an odd number "); } }

TASK 3 #include <stdio.h> int main() { int a; int b; int c; printf("enter first value: "); scanf("%d",&a); printf("enter second value: "); scanf("%d",&b); printf("enter third value: "); scanf("%d",&c); if (a==b || a==c || c==a) { printf("two or more of the values are equal"); } else if (a>b && a>c) { printf("the first value is the largest"); } else if (b>a && b>c) { printf("the second value is the largest"); } else { printf("the third value is the largest"); } }

TASK 1; #include <stdio.h> int main() { int score; printf("enter your score: "); scanf("%d", &score); if (score>=90) { printf("A"); } else if (score>=80) { printf("B"); }else if (score>=70) { printf("C"); }else if (score>=60) { printf("D"); } else { printf("F"); } } TASK 2; #include <stdio.h> int main() { int color; printf("enter a color (1 for Red, 2 for Yellow, 3 for Green): "); scanf("%d", &color); switch (color) { case 1: printf("Stop"); break; case 2: printf("Ready"); break; case 3: printf("Go");

} } break; default: printf("Invalid input"); TASK 6; #include <stdio.h> int main() { int a,b; char operation; printf("enter the first value: "); scanf("%d",&a); printf("enter the second value: "); scanf("%d",&b); printf("enter an operator: "); scanf(" %c", &operation); switch (operation) { case '+': printf("%d", a+b); break; case '-': printf("%d", a-b); break; case '': printf("%d", ab);;0 break; case '/': printf("%d", a/b); break; default: } printf("Invalid input");

} TASK 7; #include <stdio.h> int main() { int year; printf("enter a year: "); scanf("%d",&year); if(year%400==0) { printf("this is a leap year"); } else if(year%100==0){ printf("this is not a leap year"); } else if (year%4==0){ printf("this is a leap year"); } else{ printf("this is not a leap year"); } }

TASK 8; #include <stdio.h> int main() { int a; printf("enter a number: "); scanf("%d",&a); if(a==0) { printf("this number is neither positive nor negative"); } else if(a>0){ printf("this number is positive"); } else{ printf("this number is negative"); } } TASK 9; #include <stdio.h> int main() { int day; printf("enter a number (1-7): "); scanf("%d",&day); switch(day){ case 1: printf("monday"); break; case 2: printf("tuesday"); break; case 3: printf("wednesday"); break; case 4 : printf("thursday");

} } break; case 5: printf("friday"); break; case 7: printf("saturday"); break; case'7': printf("sunday"); break; default: printf("invalid input"); TASK 10; #include <stdio.h> int main() { int num; int password=1111; printf("enter the password: "); scanf("%d",&num); if (num==password) { printf("access granted"); } else{ printf("access denied"); } }