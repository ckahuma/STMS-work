# STMS-GROUP-G-1
This is a string task manager system created in C programming language (to implement socket programming). It contains a client program which is used by the user to interface with commands that are serviced by the socket server program. The client provides options on how the server can manipulate a string and a prompt for the user to enter their strings. The server on the other hand contains programming logic to manipulate strings sent to it and return results to the client program. The server also has the ability to handle multiple clients and schedule the jobs of these clients by placing them in a busy_list and where it assigns priorities to the jobs based on predefined conditions and writes to another file ready_list in the order of the priority numbers. It later reads one job at  time from ready_list while processing it and sends the result to the respective client. 
On the other side of the coin, we have a web-based platform that contains acess to the database in which information about currently processing jobs is kept.Here the web-admin keeps track of the number of waiting_jobs, ready_jobs and is able to see the success and failure rate of the jobs.

# Key features include



  i). How to encrypt and decrypt strings
  ii). Reversing a string
  iii). Doubling a string
  iv). Replacing characters at specified positions of a string
  v). Deleting characters at specified position of a string
  vi). Handling multple clients in socket programming
  vii). Connecting C and PHP and the database
  viii). Performing crone jobs in ubuntu
