Name:Aditya kumar Company:CODETECH IT SOLUTION ID:CT04DF2936 Domain:C LANGUAGE Duration:11 JUNE 2025 TO 11 JULY 2025  Internship Report: File Handling in C Language(TAsk 1) 1️⃣ Introduction During my internship, I learned and practiced File Handling in C language, which is a crucial concept for storing and managing data permanently. Unlike console-based inputs and outputs, file handling allows us to store data on disk and retrieve it later, making it essential for real-world applications like report generation, user data management, and data analysis.

2️⃣ Objective To understand the concept of file streams in C.

To learn reading, writing, appending data in files.

To implement mini-projects using file handling, such as student data management, log creation, and basic data processing.

3️⃣ What I Learned ✅ How to open files using fopen() in different modes like "r", "w", and "a". ✅ Writing data to a file using fprintf() and fputs(). ✅ Reading data from a file using fscanf(), fgets(), and fgetc(). ✅ The importance of checking for NULL pointers to handle errors in file operations. ✅ Closing the file properly using fclose() to prevent memory leaks. ✅ Using feof() to detect the end of a file during reading operations.

4️⃣ Practical Implementation a. Writing to a File I created a program to write user data (name, age, and grade) into a file:

c Copy Edit FILE *fp = fopen("student.txt", "w"); fprintf(fp, "Name: John\nAge: 20\nGrade: A\n"); fclose(fp); b. Reading from a File I wrote a program to read and display contents from the file:

c Copy Edit FILE *fp = fopen("student.txt", "r"); char ch; while ((ch = fgetc(fp)) != EOF) { putchar(ch); } fclose(fp); 5️⃣ Observations File handling is essential for building real-world applications in C.

Error handling while opening files is crucial for avoiding runtime errors.

Using file handling improves data management and retrieval during program execution.

6️⃣ Challenges Faced Initially faced errors due to incorrect file paths.

Forgetting to close files led to file locking issues during execution.

Understanding the difference between text mode and binary mode.

7️⃣ Conclusion This internship module on File Handling in C helped me strengthen my programming basics and understand how data can be managed efficiently using files in C. I learned to develop simple data management projects using these concepts, which will help in college mini-projects and competitive programming practice.
