# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/aac93c52-30dd-49f4-9cc9-de830cfde0bf)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/0e31fa1a-6a76-4b92-a433-a79e91efc18f)
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/23c61a41-9026-4b9c-840b-d39fd7507212)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/36fb7ba4-b761-41a0-b6ee-386500374405)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/1e27d270-9a15-439f-9cf3-b70141fbd1b5)
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/9ff396ff-d7d4-402a-a43c-c9bb883baed3)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/d120321c-a47f-402f-8ffe-c02e070ae9b5)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!


## OUTPUT
![image](https://github.com/Priyangarajapandiyan/Windows-basic-commands-batchscript/assets/144872535/68482a85-11be-4d72-b49b-cb91c0e8ef79)



# RESULT:
The commands/batch files are executed successfully.

