# Milestone1
** Overview
## This project is a basic Policy Management System for an insurance company. The system allows policy managers to manage policyholders, policy products, and payments. The system is implemented in Python, using object-oriented principles.
Policy Management System
Overview
This project is a basic Policy Management System for an insurance company. The system allows policy managers to manage policyholders, policy products, and payments. The system is implemented in Python, using object-oriented principles.

Features
Policyholder Management: Add, suspend, and reactivate policyholders.
Product Management: Create, update, and remove/suspend insurance products.
Payment Management: Handle payment processing, send payment reminders, and manage penalties for late payments.
Classes and Functionality
Policyholder:

register_policyholder(): Registers a new policyholder.
suspend_policyholder(): Suspends a policyholder's account.
reactivate_policyholder(): Reactivates a suspended policyholder.
Product:

create_product(): Creates a new insurance product.
update_product(): Updates an existing product.
remove_product(): Removes or suspends a product from the system.
Payment:

process_payment(): Handles payment for policyholders.
send_payment_reminder(): Sends a reminder for due payments.
apply_penalty(): Applies penalties for late payments.
Files
The project contains the following Python files:

main.py: The entry point of the application, where the program starts.
policyholder.py: Contains the Policyholder class and methods for managing policyholders.
product.py: Contains the Product class and methods for managing insurance products.
payment.py: Contains the Payment class and methods for managing payments.
Installation
Clone the Repository: If the code is hosted on a GitHub repository, clone it to your local machine using:

bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Navigate to the Project Folder: Open a terminal or command prompt and navigate to the folder where the files are located:

bash
Copy code
cd "C:\Users\User\Desktop\Assignment 3 Milestone1"
Ensure Python is Installed: Make sure you have Python installed on your machine. You can check by running:

bash
Copy code
python --version
Run the Program: To run the program, execute the main.py file:

bash
Copy code
python main.py
Usage
Policyholder Demonstration: In the main.py file, you will find a demonstration where two policyholders are created and assigned an insurance product. Their account details will be displayed.

Modify the Code: You can modify the main.py file to add more functionality or test different scenarios such as suspending policyholders, adding new products, or processing payments.

Example
Here is an example of how the system creates a policyholder and processes their details:

python
Copy code
from policyholder import Policyholder

# Create a policyholder
policyholder = Policyholder("John Doe", "PH1001")
print(policyholder.display_details())

# Suspend and reactivate the policyholder
policyholder.suspend_policyholder()
policyholder.reactivate_policyholder()
Requirements
Python 3.x
Troubleshooting
If you encounter a ModuleNotFoundError while trying to run the code, ensure that:

All Python files (main.py, policyholder.py, product.py, payment.py) are in the same directory.
You are running the program from the correct folder.
License
This project is provided for educational purposes and is not intended for commercial use.
