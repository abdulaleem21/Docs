# Computer networking
---------------
## Definition

The overall scope of how computers communicate with each other.

## Protocol

The rules and standards computers follow to communiacte properly with each other. 

There are several models such as:
- TCP/ IP model
- OSI model

## TCP/ IP FIVE LAYER MODEL
![TCP IP image](https://github.com/abdulaleem21/Docs/blob/main/networking/TCP%20IP%20Model.png)

![TCP IP diagram](https://github.com/abdulaleem21/Docs/blob/main/networking/TCP%20%20IP%20example.png)

### Basics of networking devices

#### Cables
- **Copper**: 
  Binary codes are transmitted as voltage changes across these cables
  Eg: Cat5, Cat5e, Cat6
- **Fibre**: 
  Uses pulses of light to transmit binary code
  Faster, but fragile, and long distance

#### Hubs and switches
Allows many devices to connect with each other unlike cables which suports only end-to-end. 
Fowrards information with a network (LAN)

- **Hub**  
  Sends information to all the devices connected  
  Sometimes causes **Collision domain**  
  Obsolete  
- **Switch**  
  Sends information to only the requesting device  
  Is a part of data link layer (can detect ethernet)  

#### Routers  
A device that knows how to forward data between independent networks.    
A network layer device. Knows IP.    
A home or local network has *Home router* which forwards the data to the ISP which has *Core routers* which are much more complicated and handles more traffic as it interacts with a lot of Home routers.     
Routers share data with each other using **Border Gateway Protocol (BGP)** which lets them learn about the most optimal paths to forward traffic.    

#### Servers and clients

A node refers to the devices which are present in a network.  
A node can be either a server or a client. The terminology depends on it's purpose of existence.   

- **Server**:  
  provides information to the requesting devices
- **Client**:  
  gets information from a server  




