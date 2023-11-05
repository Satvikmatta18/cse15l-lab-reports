
# LAB REPORT 2
## Part 1


![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/ae278e9c-85c2-4049-b72a-d87b561b944d)


![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/af1cc675-ae13-4c47-881b-7827f49c1939)

In the provided code:

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/b8f3d91b-6cd1-4292-821e-433894b3c447)

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


## Part 2
![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/218e6339-d528-436f-8662-a9fc7d480c70)
![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/ba317fd5-b8d7-445f-bdc1-537a70abd279)
![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/1d08a3d5-d97b-4782-a7a9-317cfd008cf1)

## Part 3
In weeks 2 and 3,  I gained knowledge in `SSH` login to a remote server, starting a server via `Java` compilation and execution. Additionally, I learned to access URLs through `curl`, understand `paths` and `queries`, establish `SSH keys` for convenient access, utilize commands such as `mkdir`, `scp`, and `man`. Moreover, I acquired the ability to create a `string server` in Java to concatenate strings based on requests, like adding a new line along with a sequence number and text, displaying the cumulative strings in sequential order.

