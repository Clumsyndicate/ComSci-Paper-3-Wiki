# Cluster of server
Is a computer program that allows server computers to work together as a computer cluster, to provide failover and increased availability of applications, or parallel calculating power in case of high-performance computing (HPC) cluster.

## Benefits of cluster of server
### 1. Failover systems and servers

It can solve almost all the hardware failures. In anycases when server in the cluster has some problems about mother board, CPU, memory, hard disk or even lose the power source, the failover system will switch all the relative tasks into another server.


2. Focus on the application layer based on the user, application, operation systemand hardware interaction structure.

In an operating system, most user will only use the data and these applications on the hardware. In order to get access to these necessary data, from the graph below, the user needs first access to the application, then the application will help the user to access to the operating system and finally reach the data on the hardware. The problem is that if one part of the whole chain break down, the user can't access to the data. 

It is the same for the server-client model. We only need to replace the hardware by the server. If there is any problems among the application, the operation system and the server, then the server is not able to provide service for us.

However, credit to the cluster of server, we don't need to care about this issure because 

![OPsys](/assets/opsys.png)

3. Reduce the risk of people mistake



## Disadvantages of cluster of server

# API (application programming interface)
The collection of some predefined function. The main function is to enable the programmers to use a group of routine based on simple programs. Therefore, the programmers do not have to access to the source code.

### The role of API in operation system.
Here is the main roles of operation system.

![oprole](/assets/oprole.png)

It is one of the most essential roles for the operation system.

## Examples:
We can open a certain file using the function fopen() in C language. The function fopen()is an example of API design for C so that it can enable the user to use a simple function to finish a serial of operation. 

Without such API function, the user have to search and open the file by himself which is very complex and time consuming. 

We have to 
1. scan the hard disk
2. find the location of the file we want
3. load some data from the file then send to the I/O cash, into the memory
4. Convert the results(0, 1) into letters using ASCLL form or Unicode.
5. display

in order to open a simple file. Therefore, design a proper and useful API is necessary for a new CAD system.

Real life example:

[Firehorn](https://thefirehorn.com/features/cad_integration.html)

[Some simple API function for database](https://datatables.net/examples/api/)

