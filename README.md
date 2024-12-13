
## Replacing NetCat
Netcat uses UDP and TCP connections to read or write the data,
pass file back and forth,even open a remote shell.

### Libraries  Used
- argparse
- socket
- shlex
- subprocess
- sys 
- textwrap
- threading

### About 
Provide example usage that program will display when the user invokes it with --help and add six arguments that specify how the program should behave.

handle() method executes the task corresponding to command line argument it receives :execute the command,upload a file,start a shell.

BHP Tool - Black Hat Python Tool ,used for designing the network task.

### Main Functionality

  The tool allows for various networking tasks, including:

  - Command Shell: Providing a command shell interface for executing commands on remote systems.
  -  File Upload: Allowing files to be uploaded to a remote system.
  - Command Execution: Executing specified commands on remote systems.
  - Listening Mode: Listening for incoming connections.
  - Connecting to a Server: Initiating connections to a specified target server.
