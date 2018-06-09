# himinds-iot-project-cloud-secure-websocket-server


We are using the self-signed certificates we created [here](https://github.com/HiMinds/himinds-iot-project-general-self-signed-certificate). You need to copy them into the same folder as server.js.

Please note the row 

```javascript
process.env.NODE_TLS_REJECT_UNAUTHORIZED = "0";
```
We need this to turn off the validation of the self-signed certificate.

Installing the server:

```
npm install
```

Running the server:

```
node server
```

Example

```
19:48 $ node server
received: hello from client
```
