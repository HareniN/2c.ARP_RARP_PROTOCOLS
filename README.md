# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP

![Screenshot 2025-03-19 094508](https://github.com/user-attachments/assets/007f8248-9f87-4647-b815-493236a96c31)

## OUPUT - ARP

![Screenshot 2025-03-19 095612](https://github.com/user-attachments/assets/e2710841-aea9-45b6-8f40-b2d51d5cf7ad)

## PROGRAM - RARP
![Screenshot 2025-03-19 100612](https://github.com/user-attachments/assets/44777ed4-e954-46c7-808e-4ae803ade376)

## OUPUT -RARP

![Screenshot 2025-03-19 101148](https://github.com/user-attachments/assets/959e4035-1faf-4081-bfe7-2aa24fba009b)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
