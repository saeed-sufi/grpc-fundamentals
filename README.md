# grpc-fundamentals
- There are four communication scenarios that grpc supports:
    - **Simple RPC**: A simple call from client to a server and that server responds back.
    - **Server-side Streaming**: The server keeps a connection open to a client and will send more than one message back to that client through that open connection.
    - **Client-side Streaming**: The client sends a series of messages up to the server and gets a final response back once the final message has been sent. 
    - **Bidirectional Streaming**: This is where we can have asynchronous communication where the client can continue send messages to the server and vice versa. They're not necessarilly dependent on each other. 
