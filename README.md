# Backstory:
You are working as a junior developer at "TechCorp," a software development company. Your team is working on a project where you need to organize and process various files related to user data. The files are scattered across different directories, and you've been assigned the task of writing a Python script to gather and organize these files.

# Objective:
Write a Python script using the pathlib module to organize files from different directories into a centralized location based on their file types.

# Tasks:
Create a main_directory variable with the path to the main directory where all the user data files are stored.
Identify three types of files: text files (.txt), image files (.jpg or .png), and document files (.docx or .pdf).
Create three subdirectories named "TextFiles," "ImageFiles," and "DocFiles" inside the main directory.
Traverse through the main directory, identify each file's type, and move it to the appropriate subdirectory.
Print the names of the moved files and the paths to their new locations.

# Requirements:
Understanding of file operations and the pathlib module.

# Test Case:
**please read the following in your IDE to see the correct format!**
Suppose you have the following file structure in the main directory:

/main_directory
    ├── user_data1.txt
    ├── user_data2.jpg
    ├── user_data3.docx
    ├── user_data4.png
    ├── user_data5.txt
    ├── user_data6.pdf
    └── subdirectory
        └── user_data7.txt


After running your script, the file structure should be updated as follows:

/main_directory
    ├── TextFiles
    │   ├── user_data1.txt
    │   ├── user_data5.txt
    │   └── subdirectory
    │       └── user_data7.txt
    ├── ImageFiles
    │   ├── user_data2.jpg
    │   └── user_data4.png
    └── DocFiles
        ├── user_data3.docx
        └── user_data6.pdf
