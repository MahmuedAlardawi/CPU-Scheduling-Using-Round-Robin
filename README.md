# CPU-Scheduling-Using-Round-Robin
King AbdulAziz Universality - Operating Systems (CPCS-361)

This project, developed for the CPCS-361 course at King Abdulaziz University, simulates job and CPU scheduling within an operating system. It uses a dynamic and standard Round Robin algorithm to handle job scheduling based on priority and resource availability.

Made by:
Mahmued Ahmad Alardawi – 2135209 – mmalardawi@stu.kau.edu.sa
Yazeed Alsahafi - 2036556
Submitted on: 10 May 2024
View Full Project, I/O, and Code

Introduction
This project aims to design and implement a program that simulates CPU scheduling. It manages an input stream describing arriving jobs, their requirements, and actions, ensuring jobs are processed based on their priorities and system capabilities.

Key Features
Job Arrivals Management: Manages jobs based on available resources, either rejecting, queuing, or moving them directly to the Ready Queue.
Dynamic and Standard Round Robin Scheduling: Utilizes both dynamic and fixed time quantum approaches to schedule jobs efficiently.
Input Handling: Processes system configuration and job commands from input text, adjusting system settings dynamically.
Technical Requirements
Java Implementation: Both client and server aspects are implemented in Java using sockets for managing TCP connections.
Error Handling: Includes comprehensive error checking to handle various input conditions and system states.
Code Quality: Emphasizes readability and good coding practices, including proper use of comments and consistent code indentation.
Objective
To demonstrate and provide a hands-on experience with CPU scheduling within an operating system, focusing on handling dynamic job arrivals, resource allocation, and scheduling using Round Robin algorithms.

How to Use
Setup and Compilation: Compile the Java source files, including CPU_scheduling.java and other associated classes.
Running the Scheduler: Start the program to initiate the scheduling simulator which listens for incoming job and system configuration commands.
Input Commands: Use the provided input specifications to send job arrivals and system commands.
Review Outputs: Monitor the system's response through console outputs or logs that provide details on job processing and system states.
Explore
Delve into the source code to understand more about:

Job and Queue Management: Explore how jobs are managed across different queues based on their priority and resource requirements.
Scheduling Algorithms: Understand the differences between dynamic and standard Round Robin scheduling.
Performance Metrics: Review how performance metrics such as turnaround time and waiting time are calculated and used to analyze the effectiveness of the scheduling strategies.
