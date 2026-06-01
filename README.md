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

Remove the directory "my-folder"
>mkdir my-folder
>rmdir my-folder
><img width="697" height="125" alt="os81" src="https://github.com/user-attachments/assets/750f5697-de95-4e2d-8982-5a023c2576a2" />


## COMMAND AND OUTPUT
Create the file Rose.txt
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
^Z
1 file(s) copied
dir Rose.txt
<img width="1006" height="499" alt="os82" src="https://github.com/user-attachments/assets/4ff53411-edd3-488a-bde2-75abdc1640b6" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
echo “hello world” > hello.txt
type hello.txt
<img width="773" height="139" alt="os83" src="https://github.com/user-attachments/assets/929de114-4e77-428f-bb23-85812aafcdba" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
copy hello.txt hello1.txt
<img width="663" height="103" alt="os84" src="https://github.com/user-attachments/assets/50485e8c-bd92-4618-85f5-f4161ad61eea" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
del hello1.txt

<img width="555" height="79" alt="os85" src="https://github.com/user-attachments/assets/4733d3c5-66bd-4c00-98bf-c0ad86edc2ec" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
dir hello1.txt
<img width="610" height="183" alt="os86" src="https://github.com/user-attachments/assets/1b09f9bc-888a-402b-a4d2-178747043f86" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
assoc | more
<img width="357" height="525" alt="os87" src="https://github.com/user-attachments/assets/79e3d6d1-c287-4032-b9a8-8a4a1a0c3d00" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
fc hello.txt Rose.txt
<img width="726" height="263" alt="os88" src="https://github.com/user-attachments/assets/68b85b76-41e9-4cfa-8f38-971a13945952" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="763" height="190" alt="os89" src="https://github.com/user-attachments/assets/ff2bff0b-e762-472a-a655-10318fce8c8e" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="1115" height="386" alt="os810" src="https://github.com/user-attachments/assets/a0a1c1b3-7d25-4e10-9ffe-10ba276e6512" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="1107" height="300" alt="os811" src="https://github.com/user-attachments/assets/a8040a21-d9fd-4621-98ed-4beaee7ffc5a" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="751" height="190" alt="os812" src="https://github.com/user-attachments/assets/d7629c38-4143-4493-8203-d29494d0c084" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="1064" height="612" alt="os813" src="https://github.com/user-attachments/assets/f2a0ab1d-81d0-4264-9234-ceaed6c24bd5" />


# RESULT:
The commands/batch files are executed successfully.

