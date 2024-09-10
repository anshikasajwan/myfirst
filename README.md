# Myfirst
/*Write a menu-driven program using the switch case statement in 
C to check whether a number is: (i) Even number or Odd number,
 (ii) Two digit positive number or not, (iii) Multiple of 5 or not*/
 #include<stdio.h>
 #include<math.h>
 
 int main() {
 	printf("========PPS ASSIGNMENT========\n");
 	int num1;
 	printf("ENTER ANY TWO DIGIT-NUMBER: ");
 	scanf("%d", &num1);
 	printf("\nCHOOSE: 1)EVEN NUMBER OR ODD NUMBER.\n\n\t2)TWO DIGIT POSITIVE NUMBER OR NOT.\n\n\t3)MULTIPLE OF 5 OR NOT.\n");
    int set;
    printf("\nENTER THE CHOOSEN OPTION(1-3): ");
 	scanf("%d", &set);
 	switch(set) {
 		case 1:  if (num1%2==0) {
 			printf("\nANSWER:%d IS A EVEN NUMBER.", num1);
 		}	else {
		 printf("\nANSWER:%d IS A ODD NUMBER.", num1);
		}	break;
		case 2 : if(num1>=0?printf("\nANSWER:%d is a positive number",num1): printf("\nANSWER:%d is a negative number.",num1));
		break;
		case 3: if (num1%5==0?printf("\nANSWER:%d IS A MULTIPLE OF 5.",num1): printf("\nANSWER:%d IS NOT A MULTIPLE OF 5.",num1));
		break;
		 } 

		 printf("\n========DONE BY:========\n\tANSHIKA\n\tBHUMIKA TEWATIYA\n\tHIMANSHU\n\tKRITIKA");
		 return 0;
		
	 }
