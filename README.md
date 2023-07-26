# Midori128-64 #

## Setup:
1. Clone the repo, or download all the files.
2. Open terminal and run **python3 main.py**
3. Enter message to be encrypted.

The decrypted text may contain trailing zeros, as it was used for padding during encryption.
The Key is generated at random. The main uses 128-bit version for the demo.

# UDP based Client-Server with Midori-64 message encryption
1. Open two terminals T_client and T_server.
2. Inside T_server execue App/server.py
3. Inside T_client execute App/client.py and enter message to sent.

*Note: The server is hosted at localhost:8080 by default you can change it by changing **localport** in server.py and **server_address** in client.py.*
