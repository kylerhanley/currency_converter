# 361 Project- Currency Converter

## Microservice

### A. Requesting Data

To request data from the microservice, you have to enter the below code into the program. 
```
s.send(client_message.encode())
```
This will send a message to the server. The server is waiting to recieve messages. 

### B. Recieving Data

The server will recieve the message from the client. If the message is "Generate Name", the server will generate a random
first and last name. The server will then send the name back to the client. For the client to recieve the name, you have 
to enter the following code into the program 
```
name = s.recv(1024).decode()
```
Then you will be able to utilize the ramdomly generated name in the program. 

### C. UML Diagram 
![361UML](https://github.com/kylerhanley/currency_converter/assets/122304552/a1f4be0b-c175-4e28-a087-ac5586668ed4)
