# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

<img width="516" height="85" alt="Screenshot 2026-05-18 114027" src="https://github.com/user-attachments/assets/8e341fe5-29ee-40f0-b4c4-955e2b62b0b5" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="508" height="72" alt="Screenshot 2026-05-18 114037" src="https://github.com/user-attachments/assets/77aa5c54-d803-4ef3-8f78-2bcc1972d6d9" />



Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="508" height="287" alt="Screenshot 2026-05-18 114051" src="https://github.com/user-attachments/assets/c2bd9466-fe8c-4db9-a0f8-352a8d65f2e2" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="505" height="120" alt="Screenshot 2026-05-18 114100" src="https://github.com/user-attachments/assets/858f26c5-cf70-4d7d-b99b-0595733d20e7" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="443" height="110" alt="Screenshot 2026-05-18 114117" src="https://github.com/user-attachments/assets/a98ebe83-0296-408e-a5dd-009900c0b996" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="437" height="222" alt="Screenshot 2026-05-18 114126" src="https://github.com/user-attachments/assets/09070bde-3ae8-4f0a-8f5b-dc5edf188bcb" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="437" height="222" alt="Screenshot 2026-05-18 114126" src="https://github.com/user-attachments/assets/e09557c2-a763-4058-a8ff-3d216ca3daea" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="267" height="532" alt="Screenshot 2026-05-18 114205" src="https://github.com/user-attachments/assets/511aeb70-88f4-4305-9637-de3e4d951b77" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="347" height="118" alt="Screenshot 2026-05-18 114247" src="https://github.com/user-attachments/assets/be156ba5-ce49-4575-a261-a58ccc3404a5" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="467" height="98" alt="image" src="https://github.com/user-attachments/assets/1a3c5bc2-fb0f-400e-8936-a8374425c277" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="342" height="205" alt="Screenshot 2026-05-18 114256" src="https://github.com/user-attachments/assets/0cb8a868-bad5-4f11-b9e0-cecd9da50ce7" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="346" height="118" alt="Screenshot 2026-05-18 114317" src="https://github.com/user-attachments/assets/a064d6fd-e1f8-4a83-adcd-0b2e7698e4ed" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="341" height="160" alt="Screenshot 2026-05-18 114327" src="https://github.com/user-attachments/assets/52de2bc1-d62f-454d-9cd8-8ee9b081ee41" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="280" height="271" alt="Screenshot 2026-05-18 114217" src="https://github.com/user-attachments/assets/92724bdf-1d84-4ed8-b591-6ac963cbd1b8" />


# RESULT:
The commands/batch files are executed successfully.

