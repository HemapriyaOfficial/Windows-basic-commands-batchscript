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

![326174173-f874ddb1-ee02-4a98-866c-822976c70384](https://github.com/HemapriyaOfficial/Windows-basic-commands-batchscript/assets/147114275/2afa9455-55b9-43e2-b60f-2d7562adb316)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

## COMMAND AND OUTPUT

![326174203-2ba4c6bb-8c38-4ce0-9527-af157449dc1a](https://github.com/HemapriyaOfficial/Windows-basic-commands-batchscript/assets/147114275/22728022-b244-4f5a-b054-3c9efbadb224)

List the contents of the "MyLab" directory.

## COMMAND AND OUTPUT

![326174235-81982adb-dd79-4df5-bf38-6e577ff4c630](https://github.com/HemapriyaOfficial/Windows-basic-commands-batchscript/assets/147114275/f2fa7f2f-3368-4e06-aba7-fd478579338a)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
![326174264-f6e9c1c3-ec06-4cc1-a394-63bd6f2c25c9](https://github.com/HemapriyaOfficial/Windows-basic-commands-batchscript/assets/147114275/a9895cbf-64a2-4d5a-8d07-7e019beaaf9e)


Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
![326174270-05a6d26d-62b1-47d9-91de-53c37f29ee72](https://github.com/HemapriyaOfficial/Windows-basic-commands-batchscript/assets/147114275/51acd898-4521-43a7-9583-b73c7afaf18e)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```





## OUTPUT



![326174351-937daaff-887f-400b-a7f6-81ed1783397c](https://github.com/HemapriyaOfficial/Windows-basic-commands-batchscript/assets/147114275/a16e3169-4968-4ef2-8bf7-f85afcb57deb)


# RESULT:
The commands/batch files are executed successfully.

