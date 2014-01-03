installation
------------
to install clone the repository and install redis-server using following command in bash:

    git clone clone https://github.com/debugchannel/DebugChannel.git
    sudo apt-get install nodejs redis-server


run the server
--------------
change directory into the the DebugChannel repository and run the server using the bash command:

    cd DebugChannel
    node debugchannel.js


run the webapp
--------------
the server listens on port 1025, point your favorite browser([chrome](https://www.google.com/intl/en/chrome/browser/)) to 127.0.0.1:1025.
if the server is running on another machine, update the ip address to that of the machine running the server.
