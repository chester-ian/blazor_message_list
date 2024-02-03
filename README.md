# blazor_message_list
sample blazor application that displays a list of message and the ability to add more messages on top of the list. This application is just using a plain text file to store messages

INSTALLATION INSTRUCTIONS:
1) To be able to run the program, the host/local machine should have .Net SDK installed.
2) To check, run "dotnet --version" to check if the machine has already or successfully been installed of .Net (I have used .Net SDK 8 in creating the project )
3) Download or clone the Github Repository
4) Open a terminal and navigate to the directory of the repository. Run "dotnet watch" or "dotnet run" , a web server will run and start a browser tab that goes to http://localhost:5107/
5) Test the message list program, and try adding a message.
6) Try stopping the server by "Ctrl-C" and running it again by "dotnet watch/run". Check if the changes were persistent.
7) The program is just storing the list in a text file found in /webroot/message_list.txt for coding and demo simplicity but it is suggested to be stored in a DB or MQs in production for stability and integrity.
