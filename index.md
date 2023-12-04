
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


















# LAB REPORT 2
## Part 1 
**Failure-Inducing Input (Buggy Program)**
JUnit Test:

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/f9bbaa8e-7109-4633-9b27-52559c718b43)

 Input Array: 
- We start with an 'array: {1, 2, 3, 4}'.

**Calling 'reverseInPlace:'**
- The 'reverseInPlace' method is supposed to reverse the array.
However, due to a bug in the code, it doesn't reverse it correctly.

Bug in 'reverseInPlace':
- The code swaps the elements incorrectly, leading to unexpected results.
For example, it may end up turning '{1, 2, 3, 4} into '4, 3, 3, 4}'.

Assertion:
- The test checks if the modified array is equal to the expected reversed array '{4, 3, 2, 1}'.
Because of the bug, the modified array doesn't match the expectation.

Conclusion:
- The test fails because the reverseInPlace method does not reverse the array as expected. The bug in the code prevents it from working correctly.

Bug:

Code: 

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/8b76f873-ac1e-42db-8a81-43ed6f7c10c6)

Symptom: 

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/565f28bd-9dab-4c47-93f1-e890949200b3)

- The original implementation of the reverseInPlace method had a flaw in the loop condition.
- It incorrectly swapped elements in a way that led to unexpected results.

Fixed code: 

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/dc359284-faf4-4fdb-9066-97074a567e74)

- The fix involves changing the loop condition to iterate only 'halfway through the array' (arr.length / 2).
- Introducing a 'temporary variable' (temp) is crucial for correctly swapping elements from both ends.
- Swapping elements ensures that the array is 'reversed in place.'

The original issue was caused by the loop condition, which incorrectly traversed the entire array and led to incorrect element assignments. The fix addresses this by iterating only up to the midpoint of the array and using a temporary variable to perform proper element swaps. This correction ensures that the array is reversed in place, providing the expected behavior for the reverseInPlace method.


---
# LAB REPORT 4

## Step 4

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/60e3f600-2db5-42e8-8afc-45451ec93aba)

## Step 5

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/6159fbc7-9903-4810-8767-74a7ad1ea7a0)

## Step 6 
![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/0674f517-0e64-4539-ae34-c335d8963420)

 First, I used the Vim command to access `ListExamples.java`. Then, I used the <kbd>J</kbd> key to navigate down to line 44. Next, I pressed the <kbd>L</kbd> key to move to column 1. After that, I used the <kbd>x</kbd> key to delete the '1' at index1. Using the <kbd>i</kbd> key, I inserted '2', changing 'index1' to 'index2'. Finally, I used the <kbd>:wq</kbd> keys to save and exit.

## Step 7

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/19d8c4e6-9802-4d2c-981a-4de73c5f498d)

## Step 8  

![image](https://github.com/Satvikmatta18/cse15l-lab-reports/assets/106504471/9000ff1b-74bd-4ae5-ae62-d87c950ebc00)







