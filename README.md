# Electrical-Switch
C program to build Electrical switch in swimming pull lights

#include <stdio.h>
int main() {
	int switchValue;
	printf("Enter switch value (0 = OFF, 1 = ON): ");
    scanf("%d", &switchValue);
    if(switchValue == 0) {
        printf("Swimming pool lights are OFF.\n");
	} else if(switchValue == 1) {
    	printf("Swimming pool lights are ON.\n");
	} else {
        printf("Invalid input! Please enter 0 or 1.\n");
	}
   	return 0;
}

