# Calculator-using-c
Calculator using c 

     #include <stdio.h>
    int main()
    {
    float a, b;
    int ch;
    printf("Enter two numbers:");
    scanf("%f%f", &a, &b);
    printf("Enter your choice:\n 1) add \n 2) sub\n 3) mul \n 4) sub\n");
    scanf("%d", &ch);
    switch (ch)
    {
     case 1:
         printf("Your Ans is: %f", a + b);
         break;
     case 2:
         printf("Your Ans is: %f", a + b);
         break;
     case 3:
         printf("Your Ans is: %f", a * b);
         break;
     case 4:
         printf("Your Ans is: %f", a / b);
         break;
 
     default:
         printf("invalid choice");
         break;
         return 0;
    }
}
