# Chat app 💬 using websockets (Nodejs, Express & Socket.io)

i have develop a chat application using Express, Websockets. Tough you can use plain websockets but i would be using a library called Socket.io - which is wrapper around Websockets, its super easy to use and provies a fallback to xhr requests until the websocket connection is established.

The frontend-ui is based on Flexbox, no external UI libraries are used.

---

## What is Websocket ?

WebSockets are an alternative to HTTP communication in Web Application, they offer full-duplex communication, that is, it is, bi-directional and that means the data can flow in both ways, so it can flow from client to the server and also from server to the client.