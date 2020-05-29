# Bus-reservation-system
Building a bus reservation system using c++


This repository consists of the code of a bus reservation project for the travel agent to add the list of buses along with details and reserve it for his customers.
This is written in C++ programming language with necessary comments placed to increase the readability of the code. This allows one to add the necessary details that include the information regarding the bus - bus number, driver name, source and destination along with arrival and departure timings. This enables us to keep a track of all the buses available. In addition, one can reserve a bus seat according to vacant seat availability. One can also check for the list of vacant seats in a specific bus. We have specific functions to view the list of all buses and the vacancies available in each one of them. One can also make cancellations using this system. This is a simple implementation of basic coding using the concepts of class and structure.

Pre-requisites: 
Before running the code, the user is required to install C++ IDE (for windows OS) and g++ compiler (for Linux).
In the windows OS, the user can simply open the file with any C++ IDE and give execute the compilation and run it. 
UNIX users are required to first navigate to the directory where this busres.cpp file is stored and then run the following commands in terminal.

g++ [filename.cpp]  -> 
./a.out #unix  -> 
a.exe  #windows


Usage:

  void addnewbus();
 This function is used to add details of a new bus. 

  void set_empty(); 
This function is used to set the seats empty for the newly added bus. 

  void reservation();
This function is used to allot a seat to a passenger. We can reserve a seat under a passenger’s name.

  void avail();
This function is used to check for the available buses.

  void show();
This function is used to view the details of the required buses.

  void cancel();
This function is used cancel a seat which is already reserved.

  void position(int i); 
This function is used to display the list of seats in a bus and classify them as reserved/empty. 

