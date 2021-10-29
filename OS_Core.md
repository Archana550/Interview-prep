# 0. [Basics of OS](https://www.geeksforgeeks.org/introduction-of-operating-system-set-1/?ref=lbp)
# 1. What is the main purpose of an operating system? Discuss different types? 

The purpose of an operating system is to provide an environment in which a user can execute programs conveniently and efficiently. 

Types of Operating Systems: Some widely used operating systems are as follows- 

### 1. Batch Operating System – 
This type of operating system does not interact with the computer directly. There is an operator which takes similar jobs having the same requirement and group them into batches. It is the responsibility of the operator to sort jobs with similar needs. 


![Screenshot from 2021-10-30 01-02-03](https://user-images.githubusercontent.com/42698268/139492196-39294259-bed7-4ff5-928c-3b24df9909f4.png)


*Advantages of Batch Operating System: 

* It is very difficult to guess or know the time required for any job to complete. Processors of the batch systems know how long the job would be when it is in queue
* Multiple users can share the batch systems
* The idle time for the batch system is very less
* It is easy to manage large work repeatedly in batch systems

*Disadvantages of Batch Operating System:  

* The computer operators should be well known with batch systems
* Batch systems are hard to debug
* It is sometimes costly
* The other jobs will have to wait for an unknown time if any job fails

Examples of Batch based Operating System: Payroll System, Bank Statements, etc. 


### 2. Time-Sharing Operating Systems – 
Each task is given some time to execute so that all the tasks work smoothly. Each user gets the time of CPU as they use a single system. These systems are also known as Multitasking Systems. The task can be from a single user or different users also. The time that each task gets to execute is called quantum. After this time interval is over OS switches over to the next task. 

![Screenshot from 2021-10-30 01-04-00](https://user-images.githubusercontent.com/42698268/139492226-0ced6018-4828-40d8-a7bb-5d2eed924294.png)


*Advantages of Time-Sharing OS:  

* Each task gets an equal opportunity
* Fewer chances of duplication of software
* CPU idle time can be reduced

*Disadvantages of Time-Sharing OS:  

* Reliability problem
* One must have to take care of the security and integrity of user programs and data
* Data communication problem

Examples of Time-Sharing OSs are: Multics, Unix, etc. 


### 3. Distributed Operating System – 
These types of the operating system is a recent advancement in the world of computer technology and are being widely accepted all over the world and, that too, with a great pace. Various autonomous interconnected computers communicate with each other using a shared communication network. Independent systems possess their own memory unit and CPU. These are referred to as loosely coupled systems or distributed systems. These system’s processors differ in size and function. The major benefit of working with these types of the operating system is that it is always possible that one user can access the files or software which are not actually present on his system but some other system connected within this network i.e., remote access is enabled within the devices connected in that network. 


![Screenshot from 2021-10-30 01-08-59](https://user-images.githubusercontent.com/42698268/139492665-cae247d6-a5d7-40a6-8013-e73edebcb464.png)


*Advantages of Distributed Operating System:  

* Failure of one will not affect the other network communication, as all systems are independent from each other
* Electronic mail increases the data exchange speed
* Since resources are being shared, computation is highly fast and durable
* Load on host computer reduces
* These systems are easily scalable as many systems can be easily added to the network
* Delay in data processing reduces


*Disadvantages of Distributed Operating System:  

* Failure of the main network will stop the entire communication
* To establish distributed systems the language which is used are not well defined yet
* These types of systems are not readily available as they are very expensive. Not only that the underlying software is highly complex and not understood well yet

Examples of Distributed Operating System are- LOCUS, etc. 

### 4. Network Operating System – 
These systems run on a server and provide the capability to manage data, users, groups, security, applications, and other networking functions. These types of operating systems allow shared access of files, printers, security, applications, and other networking functions over a small private network. One more important aspect of Network Operating Systems is that all the users are well aware of the underlying configuration, of all other users within the network, their individual connections, etc. and that’s why these computers are popularly known as tightly coupled systems. 

![Screenshot from 2021-10-30 01-10-49](https://user-images.githubusercontent.com/42698268/139492831-d8ede7f4-42d5-4c26-a767-2069b31e4f84.png)


*Advantages of Network Operating System:

* Highly stable centralized servers
* Security concerns are handled through servers
* New technologies and hardware up-gradation are easily integrated into the system
* Server access is possible remotely from different locations and types of systems


*Disadvantages of Network Operating System:  

* Servers are costly
* User has to depend on a central location for most operations
* Maintenance and updates are required regularly


Examples of Network Operating System are: Microsoft Windows Server 2003, Microsoft Windows Server 2008, UNIX, Linux, Mac OS X, Novell NetWare, and BSD, etc. 


### 5. Real-Time Operating System – 
These types of OSs serve real-time systems. The time interval required to process and respond to inputs is very small. This time interval is called response time. 


Real-time systems are used when there are time requirements that are very strict like missile systems, air traffic control systems, robots, etc. 

Two types of Real-Time Operating System which are as follows: 

* Hard Real-Time Systems: 
These OSs are meant for applications where time constraints are very strict and even the shortest possible delay is not acceptable. These systems are built for saving life like automatic parachutes or airbags which are required to be readily available in case of any accident. Virtual memory is rarely found in these systems.

* Soft Real-Time Systems: 
These OSs are for applications where for time-constraint is less strict.

![Screenshot from 2021-10-30 01-13-26](https://user-images.githubusercontent.com/42698268/139493111-6a91d50b-3080-45a8-ba5d-3da1068820a0.png)


Advantages of RTOS:  

* Maximum Consumption: Maximum utilization of devices and system, thus more output from all the resources
* Task Shifting: The time assigned for shifting tasks in these systems are very less. For example, in older systems, it takes about 10 microseconds in shifting one task to another, and in the latest systems, it takes 3 microseconds.
* Focus on Application: Focus on running applications and less importance to applications which are in the queue.
Real-time operating system in the embedded system: Since the size of programs are small, RTOS can also be used in embedded systems like in transport and others.
* Error Free: These types of systems are error-free.
* Memory Allocation: Memory allocation is best managed in these types of systems.


Disadvantages of RTOS:  

* Limited Tasks: Very few tasks run at the same time and their concentration is very less on few applications to avoid errors.
* Use heavy system resources: Sometimes the system resources are not so good and they are expensive as well.
* Complex Algorithms: The algorithms are very complex and difficult for the designer to write on.
* Device driver and interrupt signals: It needs specific device drivers and interrupts signals to respond earliest to interrupts.
* Thread Priority: It is not good to set thread priority as these systems are very less prone to switching tasks.

Examples of Real-Time Operating Systems are: Scientific experiments, medical imaging systems, industrial control systems, weapon systems, robots, air traffic control systems, etc.







