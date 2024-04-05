## Restaurant Reservation Chatbot

### Introduction
This Python program implements a Restaurant Reservation Chatbot that allows users to make reservations and check reservation availability.

### Features
- **Make Reservation**: Users can make reservations by providing their name, the number of people, and the desired date and time.
- **Check Availability**: Users can check the availability of reservations for a specific date and time.
- **Exit**: Users can exit the chatbot when they are done.

### How to Use
1. Upon starting the program, users will be greeted with a welcome message and presented with options to make a reservation, check reservation availability, or exit.
2. If the user chooses to make a reservation, they need to enter their name, the number of people, and the desired date and time. If the reservation is successful, a confirmation message will be displayed; otherwise, a notification about the unavailability of the time slot will be shown.
3. If the user chooses to check reservation availability, they need to enter the date and time they are interested in. The program will respond with whether the reservation is available or not. If not available, it will display the details of the existing reservation.
4. To exit the chatbot, the user can choose the exit option.

### Example Usage
```
Welcome to the Restaurant Reservation Chatbot!

What would you like to do?
1. Make a reservation
2. Check reservation availability
3. Exit
Enter your choice (1/2/3): 1
Enter your name: Uma
Enter the number of people: 5
Enter the date and time (YYYY-MM-DD HH:MM): 2024-04-06 19:00
Reservation successful!

What would you like to do?
1. Make a reservation
2. Check reservation availability
3. Exit
Enter your choice (1/2/3): 2
Enter the date and time to check availability (YYYY-MM-DD HH:MM): 2024-04-06 16:00
Reservation available for that time slot.

What would you like to do?
1. Make a reservation
2. Check reservation availability
3. Exit
Enter your choice (1/2/3): 1
Enter your name: viji
Enter the number of people: 2
Enter the date and time (YYYY-MM-DD HH:MM): 2024-04-06 16:00
Reservation successful!

What would you like to do?
1. Make a reservation
2. Check reservation availability
3. Exit
Enter your choice (1/2/3): 2
Enter the date and time to check availability (YYYY-MM-DD HH:MM): 2024-04-06 16:00
Sorry, reservation not available. Reserved by viji for 2 people.

What would you like to do?
1. Make a reservation
2. Check reservation availability
3. Exit
Enter your choice (1/2/3): 3
Exiting. Thank you for using the Restaurant Reservation Chatbot!
```

### Requirements
- Python 3.x
- `datetime` module

### Running the Program
1. Ensure you have Python installed on your system.
2. Copy the provided code into a Python file (e.g., `restaurant_reservation_chatbot.py`).
3. Run the file using a Python interpreter.

### Future Improvements
- Implement a feature to cancel existing reservations.
- Add support for multiple restaurants.
- Enhance user interface with graphical elements.

### Contribution
Contributions to enhance the functionality or usability of this chatbot are welcome. Please feel free to fork this repository and submit pull requests with your improvements.

### License
This program is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
