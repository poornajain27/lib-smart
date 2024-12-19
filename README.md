#include<stdio.h>
int main()
{
	int book_id, student_id, choice, a, fine;
	char book_details[100];
	
	printf("Proceed by choosing:\n1 Add a Book\n2 Borrow a Book\n3 Return a Book\n4 Get Report\n\nChoice:");
	scanf("%u", &choice);
	printf("\n\n");
	
	switch(choice)
	{
		case 1:
		//Add a book
			printf("Enter the Book id:");
			scanf("%d", &book_id);
			printf("\nEnter the Book Title And Book Author:");
			scanf("%d", &book_details);
			fgets(book_details, sizeof(book_details), stdin);
			printf("Book added successfully.\n");
			break;
			
		case 2:
			//Borrow a book
			printf("Enter Student ID: ");
			scanf("%d",&student_id);
			printf("Enter Book ID: ");
			scanf("%d", &book_id);
			printf("Book borrowed successfully by student %d\n",student_id);
			break;
			
		case 3:
			//Return A Book
			printf("Student Id:");
			scanf("%s",&student_id);
			printf("Book ID:");
			scanf("%d",&book_id);
			printf("Number of Days late (if any, else enter 0):");
			scanf("%d",&a);
	  
			fine = 50*a;
			
			if (a>0)
			{
		
				printf("Book returned successfully with fine Rs.%d.",fine ) ;
				break;
			}
			else 
			{
				printf("Book returned on time");
				break;
			}
	
		case 4:
			//Generate a report
			printf("List of all the books:\n");
			printf("1.Book ID : 102, 'C Programming'\n");
			printf("2.Book ID : 103, 'Importance of Databases'\n");
			printf("3.Book ID : 104, 'History of Operating Sysytems'\n");
			printf("4.Book ID : 105, 'linux os'\n");
			printf("5.Book ID : 106, 'advanced engineering maths'\n");
			printf("6.Book ID : 107, 'environmental studies'\n");
			printf("7.Book ID : 108, 'problem solving'\n");
			printf("8.Book ID : 109, 'let us c'\n");
			printf("9.Book ID : 110, 'engineering physics'\n");
			printf("10.Book ID :111 , 'hk das'\n\n");
			printf("11.Book ID : 112, 'Previous Year Questions-2'\n");
			printf("12.Book ID : 113, 'Importance of Java '\n");
			printf("13.Book ID : 114, 'History of Linux'\n");
			printf("14.Book ID : 115, 'Let us Java'\n");
			printf("15.Book ID : 116, 'advanced engineering maths'\n");
			printf("16.Book ID : 117, 'environmental studies'\n");
			printf("17.Book ID : 118, 'problem solving'\n");
			printf("18.Book ID : 119, 'let us c'\n");
			printf("19.Book ID : 120, 'engineering physics'\n");
			printf("20.Book ID :121 , 'hk das'\n\n");
			printf("List of borrowed books:\n1.\tBook ID : 101, 'Data Structures'\n\tStudent ID : 1203");
			break;
			default: printf("Enter correct choice");
	}
	return 0; 
}
#include<stdio.h>
int main()
{
	int book_id, student_id, choice, a, fine;
	char book_details[100];
	
	printf("Proceed by choosing:\n1 Add a Book\n2 Borrow a Book\n3 Return a Book\n4 Get Report\n\nChoice:");
	scanf("%u", &choice);
	printf("\n\n");
	
	switch(choice)
	{
		case 1:
		//Add a book
			printf("Enter the Book id:");
			scanf("%d", &book_id);
			printf("\nEnter the Book Title And Book Author:");
			scanf("%d", &book_details);
			fgets(book_details, sizeof(book_details), stdin);
			printf("Book added successfully.\n");
			break;
			
		case 2:
			//Borrow a book
			printf("Enter Student ID: ");
			scanf("%d",&student_id);
			printf("Enter Book ID: ");
			scanf("%d", &book_id);
			printf("Book borrowed successfully by student %d\n",student_id);
			break;
			
		case 3:
			//Return A Book
			printf("Student Id:");
			scanf("%s",&student_id);
			printf("Book ID:");
			scanf("%d",&book_id);
			printf("Number of Days late (if any, else enter 0):");
			scanf("%d",&a);
	  
			fine = 50*a;
			
			if (a>0)
			{
		
				printf("Book returned successfully with fine Rs.%d.",fine ) ;
				break;
			}
			else 
			{
				printf("Book returned on time");
				break;
			}
	
		case 4:
			//Generate a report
			printf("List of all the books:\n");
			printf("1.Book ID : 102, 'C Programming'\n");
			printf("2.Book ID : 103, 'Importance of Databases'\n");
			printf("3.Book ID : 104, 'History of Operating Sysytems'\n");
			printf("4.Book ID : 105, 'linux os'\n");
			printf("5.Book ID : 106, 'advanced engineering maths'\n");
			printf("6.Book ID : 107, 'environmental studies'\n");
			printf("7.Book ID : 108, 'problem solving'\n");
			printf("8.Book ID : 109, 'let us c'\n");
			printf("9.Book ID : 110, 'engineering physics'\n");
			printf("10.Book ID :111 , 'hk das'\n\n");
			printf("11.Book ID : 112, 'Previous Year Questions-2'\n");
			printf("12.Book ID : 113, 'Importance of Java '\n");
			printf("13.Book ID : 114, 'History of Linux'\n");
			printf("14.Book ID : 115, 'Let us Java'\n");
			printf("15.Book ID : 116, 'advanced engineering maths'\n");
			printf("16.Book ID : 117, 'environmental studies'\n");
			printf("17.Book ID : 118, 'problem solving'\n");
			printf("18.Book ID : 119, 'let us c'\n");
			printf("19.Book ID : 120, 'engineering physics'\n");
			printf("20.Book ID :121 , 'hk das'\n\n");
			printf("List of borrowed books:\n1.\tBook ID : 101, 'Data Structures'\n\tStudent ID : 1203");
			break;
			default: printf("Enter correct choice");
	}
	return 0; 
}
#include<stdio.h>
int main()
{
	int book_id, student_id, choice, a, fine;
	char book_details[100];
	
	printf("Proceed by choosing:\n1 Add a Book\n2 Borrow a Book\n3 Return a Book\n4 Get Report\n\nChoice:");
	scanf("%u", &choice);
	printf("\n\n");
	
	switch(choice)
	{
		case 1:
		//Add a book
			printf("Enter the Book id:");
			scanf("%d", &book_id);
			printf("\nEnter the Book Title And Book Author:");
			scanf("%d", &book_details);
			fgets(book_details, sizeof(book_details), stdin);
			printf("Book added successfully.\n");
			break;
			
		case 2:
			//Borrow a book
			printf("Enter Student ID: ");
			scanf("%d",&student_id);
			printf("Enter Book ID: ");
			scanf("%d", &book_id);
			printf("Book borrowed successfully by student %d\n",student_id);
			break;
			
		case 3:
			//Return A Book
			printf("Student Id:");
			scanf("%s",&student_id);
			printf("Book ID:");
			scanf("%d",&book_id);
			printf("Number of Days late (if any, else enter 0):");
			scanf("%d",&a);
	  
			fine = 50*a;
			
			if (a>0)
			{
		
				printf("Book returned successfully with fine Rs.%d.",fine ) ;
				break;
			}
			else 
			{
				printf("Book returned on time");
				break;
			}
	
		case 4:
			//Generate a report
			printf("List of all the books:\n");
			printf("1.Book ID : 102, 'C Programming'\n");
			printf("2.Book ID : 103, 'Importance of Databases'\n");
			printf("3.Book ID : 104, 'History of Operating Sysytems'\n");
			printf("4.Book ID : 105, 'linux os'\n");
			printf("5.Book ID : 106, 'advanced engineering maths'\n");
			printf("6.Book ID : 107, 'environmental studies'\n");
			printf("7.Book ID : 108, 'problem solving'\n");
			printf("8.Book ID : 109, 'let us c'\n");
			printf("9.Book ID : 110, 'engineering physics'\n");
			printf("10.Book ID :111 , 'hk das'\n\n");
			printf("11.Book ID : 112, 'Previous Year Questions-2'\n");
			printf("12.Book ID : 113, 'Importance of Java '\n");
			printf("13.Book ID : 114, 'History of Linux'\n");
			printf("14.Book ID : 115, 'Let us Java'\n");
			printf("15.Book ID : 116, 'advanced engineering maths'\n");
			printf("16.Book ID : 117, 'environmental studies'\n");
			printf("17.Book ID : 118, 'problem solving'\n");
			printf("18.Book ID : 119, 'let us c'\n");
			printf("19.Book ID : 120, 'engineering physics'\n");
			printf("20.Book ID :121 , 'hk das'\n\n");
			printf("List of borrowed books:\n1.\tBook ID : 101, 'Data Structures'\n\tStudent ID : 1203");
			break;
			default: printf("Enter correct choice");
	}
	return 0; 
}
#include<stdio.h>
int main()
{
	int book_id, student_id, choice, a, fine;
	char book_details[100];
	
	printf("Proceed by choosing:\n1 Add a Book\n2 Borrow a Book\n3 Return a Book\n4 Get Report\n\nChoice:");
	scanf("%u", &choice);
	printf("\n\n");
	
	switch(choice)
	{
		case 1:
		//Add a book
			printf("Enter the Book id:");
			scanf("%d", &book_id);
			printf("\nEnter the Book Title And Book Author:");
			scanf("%d", &book_details);
			fgets(book_details, sizeof(book_details), stdin);
			printf("Book added successfully.\n");
			break;
			
		case 2:
			//Borrow a book
			printf("Enter Student ID: ");
			scanf("%d",&student_id);
			printf("Enter Book ID: ");
			scanf("%d", &book_id);
			printf("Book borrowed successfully by student %d\n",student_id);
			break;
			
		case 3:
			//Return A Book
			printf("Student Id:");
			scanf("%s",&student_id);
			printf("Book ID:");
			scanf("%d",&book_id);
			printf("Number of Days late (if any, else enter 0):");
			scanf("%d",&a);
	  
			fine = 50*a;
			
			if (a>0)
			{
		
				printf("Book returned successfully with fine Rs.%d.",fine ) ;
				break;
			}
			else 
			{
				printf("Book returned on time");
				break;
			}
	
		case 4:
			//Generate a report
			printf("List of all the books:\n");
			printf("1.Book ID : 102, 'C Programming'\n");
			printf("2.Book ID : 103, 'Importance of Databases'\n");
			printf("3.Book ID : 104, 'History of Operating Sysytems'\n");
			printf("4.Book ID : 105, 'linux os'\n");
			printf("5.Book ID : 106, 'advanced engineering maths'\n");
			printf("6.Book ID : 107, 'environmental studies'\n");
			printf("7.Book ID : 108, 'problem solving'\n");
			printf("8.Book ID : 109, 'let us c'\n");
			printf("9.Book ID : 110, 'engineering physics'\n");
			printf("10.Book ID :111 , 'hk das'\n\n");
			printf("11.Book ID : 112, 'Previous Year Questions-2'\n");
			printf("12.Book ID : 113, 'Importance of Java '\n");
			printf("13.Book ID : 114, 'History of Linux'\n");
			printf("14.Book ID : 115, 'Let us Java'\n");
			printf("15.Book ID : 116, 'advanced engineering maths'\n");
			printf("16.Book ID : 117, 'environmental studies'\n");
			printf("17.Book ID : 118, 'problem solving'\n");
			printf("18.Book ID : 119, 'let us c'\n");
			printf("19.Book ID : 120, 'engineering physics'\n");
			printf("20.Book ID :121 , 'hk das'\n\n");
			printf("List of borrowed books:\n1.\tBook ID : 101, 'Data Structures'\n\tStudent ID : 1203");
			break;
			default: printf("Enter correct choice");
	}
	return 0; 
}
#include<stdio.h>
int main()
{
	int book_id, student_id, choice, a, fine;
	char book_details[100];
	
	printf("Proceed by choosing:\n1 Add a Book\n2 Borrow a Book\n3 Return a Book\n4 Get Report\n\nChoice:");
	scanf("%u", &choice);
	printf("\n\n");
	
	switch(choice)
	{
		case 1:
		//Add a book
			printf("Enter the Book id:");
			scanf("%d", &book_id);
			printf("\nEnter the Book Title And Book Author:");
			scanf("%d", &book_details);
			fgets(book_details, sizeof(book_details), stdin);
			printf("Book added successfully.\n");
			break;
			
		case 2:
			//Borrow a book
			printf("Enter Student ID: ");
			scanf("%d",&student_id);
			printf("Enter Book ID: ");
			scanf("%d", &book_id);
			printf("Book borrowed successfully by student %d\n",student_id);
			break;
			
		case 3:
			//Return A Book
			printf("Student Id:");
			scanf("%s",&student_id);
			printf("Book ID:");
			scanf("%d",&book_id);
			printf("Number of Days late (if any, else enter 0):");
			scanf("%d",&a);
	  
			fine = 50*a;
			
			if (a>0)
			{
		
				printf("Book returned successfully with fine Rs.%d.",fine ) ;
				break;
			}
			else 
			{
				printf("Book returned on time");
				break;
			}
	
		case 4:
			//Generate a report
			printf("List of all the books:\n");
			printf("1.Book ID : 102, 'C Programming'\n");
			printf("2.Book ID : 103, 'Importance of Databases'\n");
			printf("3.Book ID : 104, 'History of Operating Sysytems'\n");
			printf("4.Book ID : 105, 'linux os'\n");
			printf("5.Book ID : 106, 'advanced engineering maths'\n");
			printf("6.Book ID : 107, 'environmental studies'\n");
			printf("7.Book ID : 108, 'problem solving'\n");
			printf("8.Book ID : 109, 'let us c'\n");
			printf("9.Book ID : 110, 'engineering physics'\n");
			printf("10.Book ID :111 , 'hk das'\n\n");
			printf("11.Book ID : 112, 'Previous Year Questions-2'\n");
			printf("12.Book ID : 113, 'Importance of Java '\n");
			printf("13.Book ID : 114, 'History of Linux'\n");
			printf("14.Book ID : 115, 'Let us Java'\n");
			printf("15.Book ID : 116, 'advanced engineering maths'\n");
			printf("16.Book ID : 117, 'environmental studies'\n");
			printf("17.Book ID : 118, 'problem solving'\n");
			printf("18.Book ID : 119, 'let us c'\n");
			printf("19.Book ID : 120, 'engineering physics'\n");
			printf("20.Book ID :121 , 'hk das'\n\n");
			printf("List of borrowed books:\n1.\tBook ID : 101, 'Data Structures'\n\tStudent ID : 1203");
			break;
			default: printf("Enter correct choice");
	}
	return 0; 
}
