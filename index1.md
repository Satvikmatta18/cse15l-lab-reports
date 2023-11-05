# LAB REPORT 1 

## ```CD``` COMMAND:

------- 1. Using ``` cd ``` with no arguments --------

* Command:``` cd ```

* Working Directory:/home

* Explanation: Running ```cd``` with no arguments does not change the current working directory, so it remains as /home.



--------2. Using ```cd``` with a path to a directory as an argument--------

* Command:``` cd lecture1 ```

* Working Directory: the command was run in the ```/home directory``` after it changed to ```/home/lecture1```. 

* Explanation: This command changes the current working directory to lecture1.  The cd command will return to the home directory without any arguments. For example, if ```cd``` is run in another directory without any argument, it will move back to home. 


-------- 3. Using ```cd``` with a path to a file as an argument (error) --------

* Command: ```cd lecture1/messages/hi.txt ```

* Working Directory: the command was run in the ``` /home/lecture directory ``` then it was changed to ``` /home/lecture1/messages ``` . 

* Explanation: This is an error because cd is used to change directories, not open files. It's not possible to change the working directory to a file.

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/892a1660-ee9b-4f4e-bdd1-785c1206e677)




## ``` lS ``` COMMAND:

-------- 1. Using ```ls``` with no arguments --------

* Command: ```ls```

* Working Directory: /home

* Explanation: This command lists the files and directories in the current working directory /home.


-------- 2. Using ```ls```with a path to a directory as an argument --------

* Command: ```ls``` lecture1

* Working Directory: The command was run in the ```/home``` directory. 

* Explanation: This command lists the files and directories in the specified directory lecture1.


-------- 3. Using ```ls``` with a path to a file as an argument -------- 

* Command: ```ls messages/hi.txt```

* Working Directory: The command was run in the ``` /home ``` directory. 

* Explanation: This command lists the location that the file is in, as it displays lecture1/messages/hi.txt. 

![Image](ls.png)





##``` CAT``` COMMAND:


-------- 1. Using ```cat``` with no arguments (waiting for input) --------

* Command: ```cat```

* Working Directory: ```/home```

* Explanation: This command waits for user input from the keyboard. It does not display any file content until you start typing or provide input. If I print anything it will be printed out again. 


-------- 2. Using ```cat``` with a path to a directory as an argument (error) -------- 

* Command: ```cat Lecture1```

* Working Directory: ```/home```

* Explanation: This is an error because ```cat``` is used to display the contents of files, not directories. You cannot use ```cat``` to display the contents of a directory.


-------- 3. Using ```cat``` with a path to a file as an argument -------- 

* Command: ```cat messages/hi.txt```

* Working Directory: ```/home```

* Explanation: This command displays the contents of the file ```hi.txt```. Hello World! in hindi ```हैलो वर्ल्ड!```is displayed


![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/3fe9b0c0-b68e-410d-8b69-6b85be77fd93)


