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

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/af1cc675-ae13-4c47-881b-7827f49c1939)

In the provided code:

**Methods called:**

1. In the `StringHandler` class, the `handleRequest` method is invoked. This occurs when an incoming request is processed by the server. The `handleRequest` method is responsible for handling the HTTP request and generating an appropriate response based on the request parameters.

**Relevant arguments and field values:**

- **Relevant Arguments:** The `handleRequest` method takes a single argument of type `URI` named `url`. This argument represents the Uniform Resource Identifier and is used to extract the query information from the request.

- **Field Values:** The `StringHandler` class contains a private field `messages`, which is a list of strings (`ArrayList<String>`). This list (`messages`) holds the messages sent to the server. Upon receiving a valid request with the "add-message?s=" query, a new message is added to this list.

**Changes in the relevant fields:**

Upon the specific request "/add-message?s=Hello":

- The `messages` field in the `StringHandler` class changes. The new message "Hello" is added to the `messages` list, incrementing its size by one. For example, the initial list might be empty, but after this specific request, it will contain a single element with the value "Hello".

**Note:** The `synchronized` block in the `StringHandler` class ensures that concurrent threads can safely access and modify the `messages` list, preventing potential issues that could arise from multiple threads trying to modify the list simultaneously.

This setup is designed to handle incoming HTTP requests to the server's endpoint `/add-message?s=` by adding a new message to the list and generating a response showing the numbered list of all messages received so far.

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/218e6339-d528-436f-8662-a9fc7d480c70)
![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/ba317fd5-b8d7-445f-bdc1-537a70abd279)
![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/70abe46d-9641-41b7-93ae-2535e7e39522)
![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/1d08a3d5-d97b-4782-a7a9-317cfd008cf1)

In weeks 2 and 3, I learned a multitude of practical command-line functionalities and server-related operations. I gained knowledge in SSH login to a remote server, starting a server via Java compilation and execution. Additionally, I learned to access URLs through curl, understand paths and queries, establish SSH keys for convenient access, utilize commands such as mkdir, scp, and man. Moreover, I acquired the ability to create a string server in Java to concatenate strings based on requests, like adding a new line along with a sequence number and text, displaying the cumulative strings in sequential order.


