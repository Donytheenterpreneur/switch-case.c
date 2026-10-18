//switch-case.c
//this is the basic code for switch case in c
#include <stdio.h>

int main() {
    int choice;

    // Prompt user for input
    printf("Select an option (1-3):\n");
    printf("1. Say Hello\n");
    printf("2. Say Goodbye\n");
    printf("3. Print a Welcome Message\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    // Switch case evaluation
    switch (choice) {
        case 1:
            printf("Hello! Have a wonderful day.\n");
            break; // Exits the switch block
            
        case 2:
            printf("Goodbye! See you later.\n");
            break;
            
        case 3:
            printf("Welcome to the C Programming world!\n");
            break;
            
        default:
            // Executed if choice does not match 1, 2, or 3
            printf("Invalid selection! Please enter a number between 1 and 3.\n");
    }

    return 0;
}
