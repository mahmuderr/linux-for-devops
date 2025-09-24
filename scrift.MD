Linux Task 03: Interactive User Input Script
📋 Task Overview
This task demonstrates creating an interactive bash script that prompts users for input and displays the collected information.

🎯 Objectives
Create an interactive bash script that accepts user input
Use the read command to collect user data
Display formatted output using collected variables
📁 Files Created
script.sh
An interactive bash script that:

Prompts user to enter their email address
Prompts user to enter their password
Displays the collected information back to the user
🚀 Script Implementation
#!/bin/bash

# this script will take unput from user to enter their email and password and then print the output

read -p "enter your email :" email

read -p "enter your password:" password

echo "Your email is: $email"
echo "Your password is: $password"
📸 Execution Screenshot
Script Execution

🔧 Usage Instructions
Make the script executable:

chmod +x script.sh
Run the script:

./script.sh
