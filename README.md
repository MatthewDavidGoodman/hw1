# TCP Chat Client/Server — Coursework

Legacy networking assignment implementing a basic multi-client chat system with Python sockets and threads.

## Components

- `chat_server.py` — accepts TCP connections and broadcasts messages between connected clients.
- `client.py` — connects to the server and sends/receives chat messages.

## Usage

```bash
python chat_server.py <IP_ADDRESS> <PORT>
python client.py <IP_ADDRESS> <PORT>
```

Example:

```bash
python chat_server.py 192.168.55.13 8081
python client.py 192.168.55.13 8081
```

## Status

Historical coursework artifact. The server uses legacy Python threading/socket conventions and is not maintained as a production application.
