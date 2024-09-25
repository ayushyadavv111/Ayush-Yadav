# Ayush-Yadav


 hastag include<stdio.h>
int main(){
	int n,choice;
	
	printf("Enter an integer in decimal");
	scanf("%d",&n);
	
	printf("\n1. convert %d to octal integer ",n);
	printf("\n2. convert %d to hexadecimal integer ",n);
	
	printf("\n Enter your choice");
	scanf("%d",&choice);
	
	switch(choice){
		case 1:
			printf("\n%d of decimal number system in octal %o",n,n);
			break;
			
			case 2:
			printf("\n%d of decimal number system in hexadecimal %x",n,n);
			break;
			
			default:
				printf("\n Wrong choice");
	}
	
	
	
	return 0;
}
