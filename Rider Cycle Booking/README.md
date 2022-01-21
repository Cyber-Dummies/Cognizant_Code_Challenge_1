# Cognizant_Code_Challenge_1

Rider Cycle is a bicycle manufacturing company. The company plans to provide bicycles for rent with 20 rupees per hour as tariff. 
It is a service, primarily to provide a connectivity between riders for travelling inside a specific range or area. 
To utilize this service, customers need to book online. After a successful booking, the customer will receive a message containing the booking 
status and the estimated rent amount. Help the manufacturing company to create a Java application to generate a message after a successful registration.
The estimated rent amount can be calculated by using the time duration of booking (in hours) and rent of bicycle per hour (Rs. 20)
There is a special discount on selected payment cards for Rider Cycle Booking. 
The discount is applicable for the customers who rent a bicycle for 5 hours or more. The discount detail is shown in the table below. 


          Option Card Discount (%)

            1     Visa card    20
            2     Rupay card   15
            3     Master card  nil

Rent for 1 Hour = 20 Rupees

Note:
The name should contain only alphabets. Else display "Invalid Name" and terminate
The time duration must be between 1 and 24 (both inclusive). Else display “Invalid Time Duration” and terminate
The option must be greater than 0 and lesser than or equal to 3. Else display “Try Again” and continue asking the option until the correct option is given.
The output must have exactly two decimal precision.


To get two decimal places, refer the print statement mentioned below:
float piValue=3.1415926535f;
System.out.printf(“%.2f”, piValue);
Please do not use System.exit(0) to terminate the application.


Sample Input 1:
Enter Your Name
John
Enter the time duration
5
List of payment options
1) Visa card
2) Rupay card
3) Master card
Choose an option

2

Sample Output 1:

Dear John your bill amount is 85.00


Sample Input 2:
Enter Your Name
Raja
Enter the time duration
4
List of payment options
1) Visa card
2) Rupay card
3) Master card
Choose an option

5

Try Again

7

Try Again

-1

Try Again

3

Sample Output 2:

Dear Raja your bill amount is 80.00


Sample Input 3:
Enter Your Name
Akash@

Sample Output 3:

Invalid Name


Sample Input 4:
Enter Your Name
John
Enter the time duration
-6

Sample Output 4:

Invalid Time Duration
