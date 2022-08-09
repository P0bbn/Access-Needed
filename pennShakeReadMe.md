# Penn-Shake
A simple shell program to simulate a 3-Way TCP Handshake between a Client and a Server.

# Installation and Usage
1. Download the repo.
2. From within the project directory, compile the program using the `make` command. This program was designed to compile using **clang**, not **GCC**.
3. You will need to open two shells from within the same session.
4. In **Shell 1**, execute the following command to start the **tcpserver**: `./async-tcpserver <port number>`. `<port-number>` is usually `8080`. Example: `./async-tcpserver 8080`.
5. In **Shell 2**, execute the following code to initiate the 3-way handshake procedure: `./tcp.sh <ip-address> <port-number> <number of handshake routines to perform>`. `<ip-address>` is usually `127.0.0.1` and the port number must be the same as that which was used when executing the command in **Shell 1**. Example: `./tcp.sh 127.0.0.1 8080 4`.

## Expected Output from Above Commands:
Numbers are randomly generated, so yours may be different.
  - **Shell 1**
  - HELLO 285
  - HELLO 287
  - HELLO 16872
  - HELLO 16874
  - HELLO 235
  - HELLO 237
  - HELLO 36
  - HELLO 38
  - **Shell 2**
  - HELLO 286
  - HELLO 16873
  - HELLO 236
  - HELLO 37
