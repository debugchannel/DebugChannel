Installation
------------
To install clone the repository and install redis-server using following command in bash:

    sudo apt-get install nodejs redis-server git
    git clone clone https://github.com/debugchannel/DebugChannel.git

Run the server
--------------
Change directory into the the DebugChannel repository and run the server using the bash command:

    cd DebugChannel
    node debugchannel.js


Run the webapp
--------------
The server listens on port 1025, point your favorite browser([chrome](https://www.google.com/intl/en/chrome/browser/)) to 127.0.0.1:1025.
if the server is running on another machine, update the ip address to that of the machine running the server.
