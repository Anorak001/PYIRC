# PYIRC

# Internet-Relay-Chat-Application
IRC chat application in Python

# Project consists of following files-
1) server_chat.py : Accepts connections from clients(members)

2) client_chat.py : Connects to a server , enters various choice of options provided by server as like join a chatroom or do a personal chat.

3) util_chat : Maintains the implementation of a chatroom , code to provide clients with various options as like join a chat room , leave a chat room , switch a room. It also maintains code to list rooms created along with its members. 

Instructions for running program:

1. Start server. (On linux/unix machine open terminal, reach through cd command till the file location and type the command - python server_chat.py)

2. Start client (from single terminal or different terminal by command - python client_chat.py 127.0.0.1 (ip address for localhost))

3. Program asks for name of member(client). Enter the name (the name entered is nickname ofthe member)

4. Follow the instructions as it provide us with multiple instructions as like-

a) <join> - <join> room1 - creates new room as room1 if room is not present or else joins member to room1

b) <list> - lists all the rooms available along with members

c) <leave> - enables member to leave rooms

d) <personal> - allows members to do a personal chat

e) <switch> - enables user to switch in room to send distinct message

f) <quit> - allows members to disconnect from server.

g) <manual> - provides list of commands using which we can perform operations like join, list in project.

