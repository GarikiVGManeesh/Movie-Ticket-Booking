# Movie-Ticket-Booking
Description

This is a simple C program for booking movie tickets. The program allows users to select a movie, choose the number of tickets, make a payment, and confirm or cancel their booking. If canceled, the refund process is initiated.

Features

Select a movie from a list.

Choose the number of tickets.

Calculate total price based on ticket count.

Payment options available (Net Banking, Debit/Credit Card, Phone Pe, Google Pay).

Option to confirm or cancel the booking.

Refund processing for canceled tickets.

How to Run

Compile the C program using GCC:

gcc movie_ticket_booking.c -o movie_ticket_booking

Run the program:

./movie_ticket_booking

Code Structure

ticket_booking(): Handles movie selection.

price_(): Calculates total ticket price.

payment(int p): Processes payment and asks for confirmation.

cancel_ticket(int p): Cancels the ticket and refunds the amount.

Prerequisites

A C compiler (e.g., GCC)

Basic understanding of C programming

Future Enhancements

Add a graphical user interface.

Integrate an actual payment gateway.

Store booking details in a file or database.

Author

GARIKI V G MANEESH



