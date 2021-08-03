Webex_m branch

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



Google_m branch

To connect Gmail Api need to do next steps

1. Create gmail account
2. Go to console Google Cloud Platform 
3. Go to APis & Services -> Library -> Gmail Api -> Enable Api
4. Go to APis & Services -> OAuth consent screen -> Registration App
    In field Test users adding your email. Email must be on the platform google
5. Go to APis & Services -> Credentials -> Create Credentials -> OAuth Client IDs
    In the field Application type choose Desktop app
6. Go to APis & Services -> Credentials -> Download OAuth 2.0 Client IDs
    Downloaded file need paste on the folder with your project. 
    In our case this file has name - credentials.json
7. Go to Gmail for Developers -> Gmail Api - https://developers.google.com/gmail/api/quickstart/python
8. Copy code quickstart.py and paste to the folder with your project
    In our case this file has name - gmail_aut.py
9. Create file for send messages to email
    In our case this file hase name - gmail1.py
10. Install the Google client library for Python. Run the following command:
    pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
11. Run file gmail_aut.py - python3 gmail-aut.py
    After run file gmail_aut.py python create .json file for auth when you send messages.
11. Run file gmail1.py
    Need understud that you nust have account gmail with enable Gmail Api. Messages will be sent from this account. 

    In file gmail1.py at 22 lines of code need add your gmail account with enable Gmail Api.
    We will automate this later. 

   


