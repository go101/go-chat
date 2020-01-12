(WARNING: The project was created when I just started learning Go.
There might be some race bugs in it.)

A simple chat server for practice using Go channels.

Build:
```
# WebSocket server
go build go101.org/go-chat/pkg/cmd/chat_wsserver

# General TCP server
go build go101.org/go-chat/pkg/cmd/chat_server
```

Run the WebSocket server:

```
./chat_wsserver
```

Then open http://localhost:6636 in a browser to local test.

In chatting, you can change your name by inputting

```
/name your_new_name
```

and change current room by inputting
```
/room new_room
```
