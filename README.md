# Chatroom #
P2P chatroom with testing

## How To Run ##
In order for the files to work correctly, first run either Chatroom/src/simpleChatroom/ServerStarter or Chatroom/src/GUI/SocketGUI. Enter a port number when prompted and it will generate a new chatroom on your ip. Next any client on the same network (TODO: test if it works off of LAN) can connect to the chatroom by running Chatroom/src/GUI/IPandPort or using telnet (or a similar tool) to connect to the host's IP at the previously specified port number.

## Commands ##
Within the chatroom commands are used with a '/' as a restricted symbol before the command. The commands are as follows:
* /help
  * Gives the help menu
* /nick <nickname>
  * changes the user's name into the nickname
* /tell <message>
  * sends a message to all users within the chatroom
* /send <nickname> <message>
  * sends a message to a user with the specified nickname
* /list
  * lists all the users's nicknames that are currently online
* /disc
  * disconnects from the server
