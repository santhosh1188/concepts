
# Technical paper: OSI Model

## Introduction: 
The OSI (Open Systems Interconnection) Model is a standard created by ISO to explain how different computer systems communicate with each other over a network. It breaks down the process into seven layers, each with a specific function. Although in practice we use the TCP/IP model more, the OSI model is very useful to understand networking concepts and for troubleshooting.

## Importance of OSI model
* Provides a clear structure for understanding networking concepts  
* Helps in designing and troubleshooting networks  
* Standardizes how different systems communicate  
* Useful for academic learning even though TCP/IP is more commonly used in practice 

## The Seven Layers:
Application Layer (Layer 7)
1. This is the layer we interact with directly.
Examples: web browsers, email, applications using HTTP, FTP, SMTP.

2. Presentation Layer (Layer 6)
Takes care of translation, encryption, and compression.
Example: converting data formats, SSL encryption.

3. Session Layer (Layer 5)
Manages sessions or connections between applications.
Example: logging into a website and maintaining the session.

4. Transport Layer (Layer 4)
Ensures reliable delivery of data using TCP or faster delivery with UDP.
Responsible for segmentation, error checking, and flow control.

5. Network Layer (Layer 3)
Deals with logical addressing (IP addresses) and routing.
Example: routers, IP protocol.

6. Data Link Layer (Layer 2)
Responsible for node-to-node delivery, framing, and error detection.
Uses MAC addresses. Ex: swithces

7. Physical Layer (Layer 1)
The actual transmission of bits (0s and 1s) through cables, signals, and hardware.
Example: Ethernet cables, Wi-Fi signals.

## Data Flow in OSI Model:
When you send data (like sending an email), it starts at the Application Layer and passes down through each layer until it reaches the Physical Layer, where it is sent as signals. On the receiving end, the data travels back up from the Physical Layer to the Application Layer.

## OSI vs TCP/IP:
The OSI model has 7 layers, and TCP/IP has 4 layers.
OSI is a theoretical model that is utilized for study, whereas TCP/IP is used practically in actual networks.

## Advantages:
Easy to understand and learn.
Helps in troubleshooting.
Provides a clear layered framework.

## Conclusion:
The OSI Model is an important concept in computer networking. Even though we use TCP/IP in real life, the OSI model provides a clear way to understand how data travels from one computer to another. It is especially useful for students and professionals while learning and troubleshooting network problems.

## References:
OSI Model: Youtube ( https://www.youtube.com/watch?v=vv4y_uOneC0 )
