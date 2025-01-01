# ChatRoom_OverTheNetwork / An alternative to port forwarding for multiplayer functionalities
This is a chatroom app that utilizes ngrok's free utilities into a chatroom that could be used over the network, without any port forwarding.

# Why?
The concept initially started as a way to implement multiplayer capability into my pygame projects without dealing with port forwarding. This chatroom utilizes ngrok to create a room number, which is passed to the client to establish a connection, which is a common occurence in multiplayer games. This is only a prototype for this concept, but i will work on it further if it get's interest.

# Setup
You need to create a file named "ngrok_token.txt" in the same directory with the server.py file, and put your token right into it without any prefix.
Also run:
pip install -r requirements.txt

# A possible error
The connection assumes that your ngrok url is created with the "eu" prefix, if you are outside of the eu or for any reason the link generated by ngrok has a different format, a modification to the room number functionality might be necessary.
