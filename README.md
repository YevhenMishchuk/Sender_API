webex branch

Install java on ubuntu
    sudo apt install default-jdk

Start Sender_api.jar
    java -jar Sender_api.jar

List of operating procedure

1. Register on Webex for Developers https://developer.webex.com/
2. Create on account on Webex Teams https://teams.webex.com/signin
3. Create room on the Webex Teams and adding your team

4. Create file on the python for give you list of rooms
    For this step you need token from "Webex for Developers" 
5. Create file on the python for give you list of e-mails
    For this step you need token from "Webex for Developers" and name of your room
6. Create file on the python for send messages. 
    For this step you need: 1) token from "Webex for Developers"; 2) name of your room; 3) message 

Use java

For use GUI on java you must have next files:
-Get_list_of_email.py
-Get_room.py
-Send_mess.py

File for use python to run this app are in the branch - senpy
On python this app run just in console mode


