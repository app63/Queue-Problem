the subject of this programming assignment is to run a simulation of waiting queues.  we consider, for example, the queues of passengers at a check-in counter of an airline.

-   we have two classes of service:  coach and first class.

-   there is one queue for each class of service

-   there are three coach check-in stations and two first-class stations

-   each class of service is characterized by two parameters:  rate of arrival of passengers, and average length of service (for example:  we have one first-class passenger every three minutes on average, and each first class passenger requires an average of eight minutes of service).

-  The input to the simulation is:  the average rate of arrival and the average rate of service of each class of service, as well as the length of simulation (in minutes) and whether the simulation ends abruptly or when all queues and stations are flushed out.

-  The output of the simulation is any type of metrics you may be interested to collect, such as (for each class of service):  max waiting time, average waiting time, rate of occupancy of service stations, average length of waiting queues, max length of waiting queues, number of passengers served, number of unserved passengers at the end of the simulation (if an abrupt end).  you may, if you like, illustrate the evolution of the queue in real time.

----------------------------------

design hints:

-   you define your own time variable; just use an integer.  DO NOT use the system time nor real-time.

-   define a queue ADT and use it/ instantiate it to implement the waiting queues.

-   make the program as simple as possible.