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
<img width="608" height="97" alt="Screenshot 2026-03-29 210540" src="https://github.com/user-attachments/assets/f6931c96-b192-498e-8004-86ca226d5ea7" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="556" height="55" alt="Screenshot 2026-03-29 210626" src="https://github.com/user-attachments/assets/8c6e8627-614c-482e-ac55-9028c8b8761b" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="672" height="352" alt="Screenshot 2026-03-29 210642" src="https://github.com/user-attachments/assets/3a1ce91b-1c52-425a-b899-b8f0fce82f87" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="681" height="119" alt="Screenshot 2026-03-29 210708" src="https://github.com/user-attachments/assets/575b5988-eb82-4a41-a056-a17cd02d3a7d" />

Copy the file hello.txt into the file hello1.txt


## COMMAND AND OUTPUT
<img width="656" height="64" alt="Screenshot 2026-03-29 210853" src="https://github.com/user-attachments/assets/eda1c2c9-5ef9-46aa-9832-6d9994f6b604" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="527" height="188" alt="Screenshot 2026-03-29 210907" src="https://github.com/user-attachments/assets/bdbce9f3-cef4-467c-870d-8e1e2c571859" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="585" height="243" alt="Screenshot 2026-03-29 221746" src="https://github.com/user-attachments/assets/545883a7-5466-4704-a31d-bb052a655be1" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="581" height="315" alt="Screenshot 2026-03-29 210942" src="https://github.com/user-attachments/assets/a6d8ee6d-01c1-4c8d-98d6-92060a626c3e" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="624" height="203" alt="Screenshot 2026-03-29 211020" src="https://github.com/user-attachments/assets/ab26c9d3-ebeb-4e59-8687-f4df3a6a8bb9" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="472" height="99" alt="Screenshot 2026-03-29 211256" src="https://github.com/user-attachments/assets/cd5c577f-4dbb-4c52-9cdd-f600e9bafdd2" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="547" height="230" alt="Screenshot 2026-03-29 211312" src="https://github.com/user-attachments/assets/61f55b43-3935-47fd-b918-e1a65b291de4" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="472" height="191" alt="Screenshot 2026-03-29 211327" src="https://github.com/user-attachments/assets/a40852b3-f102-45e4-b6a0-e1cc2c99864c" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="417" height="92" alt="Screenshot 2026-03-29 211337" src="https://github.com/user-attachments/assets/ff63fcac-0ba5-4761-8bd5-64657453b5d1" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="423" height="383" alt="Screenshot 2026-03-29 211344" src="https://github.com/user-attachments/assets/f73d6164-fe17-433c-9563-9db3ec52347c" />



# RESULT:
The commands/batch files are executed successfully.

