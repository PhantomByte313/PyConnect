# PyConnect

PyConnect is a simple Python tool for communication between a server and a client. It supports both sending and receiving messages in real-time. It also allows the server to execute specific commands (like file extraction) on the client's system.

## Features

- **Server Mode**: Start a server to accept connections from clients.
- **Client Mode**: Connect to a server and send/receive messages.
- **File Extraction**: The server can request the client to extract a file from a specified path.
- **Color-Coded Messages**: Sent messages appear in white, while received messages appear in cyan.
- **Interactive Command Execution**: The server can run commands such as file extraction on the client system.

## Installation

Make sure you have Python 3 installed on your system. You can install Python from [here](https://www.python.org/downloads/).

### Dependencies

No external dependencies are required, just Python's standard libraries.

## Usage

### Start the Server

To start the server, use the following command:

```bash
python3 tool.py --start-server <port> -e <path>
