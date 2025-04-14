# Netpractice

Netpractice is a network-based project developed as part of the 42 curriculum. This project focuses on practicing network programming techniques in C, handling socket creation, communication protocols, and client-server interactions. The project aims to deepen your understanding of networking concepts while building a fully functional network application.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Additional Information](#additional-information)
- [Authors](#authors)
- [License](#license)

## Introduction

The Netpractice project is designed to challenge your skills in network programming by implementing a client-server model. The goal is to create a robust application that can handle multiple connections, transmit data reliably, and demonstrate real-world networking concepts. This project was developed as part of the training at 42 and adheres to the coding standards set by the school.

## Features

- **Socket Programming:** Establishes client-server connections using TCP/IP.
- **Data Transmission:** Implements reliable data communication and error handling.
- **Multi-Client Support:** Supports multiple clients connecting concurrently to the server.
- **Custom Protocol:** Utilizes a custom protocol for data formatting and transfer.
- **Robust Error Handling:** Provides detailed error messages and graceful degradation for unforeseen network issues.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Kinglo25/Netpractice.git
   cd Netpractice
   ```

2. **Compile the Project:**

   Use the provided Makefile to build the project:

   ```bash
   make
   ```

   This compiles all the source files and generates the necessary executables for both the client and the server.

3. **Clean Up:**

   To remove compiled files and binaries, run:

   ```bash
   make clean
   ```

## Usage

After compilation, you can run both the server and client programs. An example usage is provided below:

1. **Start the Server:**

   ```bash
   ./server [port]
   ```

   Replace `[port]` with the desired port number (e.g., 8080).

2. **Start the Client:**

   In another terminal window, run:

   ```bash
   ./client [server_ip] [port]
   ```

   Replace `[server_ip]` with the server’s IP address and `[port]` with the same port number you used for the server.

3. **Interaction:**

   The client will connect to the server, and you can then test data transmission. Check the terminal outputs for connection and error logs.

## Testing

Testing is crucial for ensuring the reliability of network operations:

- **Unit Tests:** Write tests for each network module to verify socket creation, connection handling, and data transmission.
- **Stress Testing:** Simulate multiple clients connecting simultaneously to evaluate the server’s performance.
- **Error Handling:** Test edge cases such as abrupt disconnections, invalid inputs, and network timeouts.


## Additional Information

- **Documentation:** Detailed comments are provided within the code to explain complex networking concepts.
- **Improvements:** Consider adding SSL/TLS for encrypted communications or extending the custom protocol with new commands.
- **Community:** Feedback and contributions are welcome! Feel free to open issues or pull requests on GitHub.

## Authors

- **Loic M.** ([Kinglo25 on GitHub](https://github.com/Kinglo25))

Special thanks to the 42 community and mentors for their guidance and support throughout this project.
