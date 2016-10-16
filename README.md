# RemoteAccessor
This desktop app developed in Netbeans environment can execute any command on client computer connected with LAN to the server computer.
This is achieved using ProcessBuilder class in java to start a cmd process in client computer to execute a given command. The connected computers are communucating via socket object.

Developers: 1.Utkarsh Deep
            2.Shubham Sinha
This app needs to be executed in command prompt separately in client and server computers to make a valid connection.
Steps to be followed:
1.Copy the server class files in a separate directory in server computer.
2.Copy the client class files in a separate directory in client computer.
3.Connect the two computers with LAN(wireless or wired cable). You can also connect them to a common wifi network.
4.Note down the ip address(IPv4 address) of the server connection using "ipconfig" command in the command prompt.
5.Now open command prompt in both the computers and set the directory where your class files are kept.
6.Execute "java Server" in server cmd and "java Client1" in client cmd.A new window will appear in both server and client computers.
    HOW TO MAKE A VALID CONNECTION:
    1.Click on "Start Server" button on the server window. 
    2.Enter ip address of server connection that you noted in the above step(step no.4) and HIT ENTER.
    3.Now click on "connect" button.This should automatically change the "connect" button to "connected" in client window and "start server" button to "connected" button in server window. If this change doesn't happen then you must have entered wrong ip address of your server connection. SO, TAKE CARE THAT YOU ENTER THE EXACT IP ADDRESS OR ELSE YOU WONT GET A VALID CONNECTION.
    4.If you can see the above changes, then congratulations!! you have made a valid connection.
    
    HOW TO EXECUTE A COMMAND IN CLIENT COMPUTER:
    1.Enter a command in the server window and hit the enter button(on your keyboard).
    2.Click on the "enter" button on the server window.
    3.Click on the "execute" button on the client window.
    4.To execute another command, return to step 1.
    
