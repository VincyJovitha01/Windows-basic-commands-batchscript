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
```
mkdir %userprofile%\Desktop\MyLab
```

![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/c8a70dc1-96ba-43b6-9a3a-8503840b0dd1)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
%userprofile%\Desktop\MyLab
```
![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/291e219e-6d40-40b2-b12e-749792c0b0d7)
![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/48017ea2-c3fd-4ea9-8488-d61277ae3d6f)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

```
%userprofile%\Desktop\MyLab
```
![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/1d817e44-e22d-48bf-a506-e266f7b10c24)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
```
![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/80e7f597-0db8-495b-b45e-bc5d0cebaa0b)
![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/ce49bb23-236c-4b12-9849-f1e0d382641d)

## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/1d396700-d029-4c85-888a-d50a41b92780)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx
%userprofile%\Desktop\DocBackup echo Backup completed successfully!
```

## OUTPUT
![image](https://github.com/VincyJovitha01/Windows-basic-commands-batchscript/assets/147121113/12f35e92-fa8c-46e1-8ea3-7b14a1a1969e)

# RESULT:
The commands/batch files are executed successfully.

