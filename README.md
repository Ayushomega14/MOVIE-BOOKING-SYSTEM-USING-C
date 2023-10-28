 MOVIE-BOOKING-SYSTEM-USING-C
This C code implements a simple movie ticket booking system with a menu-driven interface. Users can perform various actions related to booking, canceling, and viewing movie reservations. Below is a summary of the key components and functionality of the code:

Header Inclusions: The code includes standard C library headers, such as <stdio.h>, <stdlib.h>, and <string.h>.

Global Variables: Global variables are used to store movie reservations and other data, including a reservation structure array, a count of reservations, and an identifier for each reservation.

Main Function: The main function is the entry point of the program, containing a loop that presents a menu to users. Users can choose from options like changing ticket prices, viewing reservations, booking tickets, canceling reservations, and exiting the system.

Menu and Functions: The program offers a menu-driven interface with functions for each menu option. Notable functions include:

choice1: Displays the main menu and allows users to select an action.
changeprize: Allows administrators to change the ticket price by entering a password.
details: Requires a password and displays details of reservations.
movie: Prompts users to select a movie from the available options.
reservation: Allows users to reserve seats, providing their name, phone number, and desired seat number.
cmovie: Asks users to select a movie for ticket cancellation.
cancel: Lets users cancel a reservation using a booking ID.
Ticket Printing Functions: Separate functions are used to print tickets for different movies. These functions display information about the show, customer, date, time, hall, seat number, and price.

Password Protection: Some functions, like changing ticket prices and viewing reservations, are password-protected to restrict access to authorized users.

Dynamic Memory Allocation: Memory is dynamically allocated for a 2D array called seat to manage seat reservation status.

User Interaction and Loop: The program operates within a loop until the user selects the option to exit (option 5).

Error Handling: Basic error checking is implemented, such as password validation and seat number validity. However, the error handling is minimal.

Clearing the Screen: The code uses the system("cls") command to clear the screen, but its effectiveness may vary depending on the operating system.

Hard-Coded Movie Information: Movie information, such as names, dates, times, halls, and prices, is hard-coded into the program.
