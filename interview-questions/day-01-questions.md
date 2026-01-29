# Interview Questions – Day 01

1. What is Java and how is it different from C?

Answer:
Java is a high-level, object-oriented programming language designed to be platform-independent.
C is a procedural, low-level language that is platform-dependent.

Key differences:
Java runs on JVM (Write Once, Run Anywhere)                |   C code runs directly on hardware
Java has automatic memory management (Garbage Collection)  |   C uses manual memory management

2. What is JVM?

Answer:
JVM (Java Virtual Machine) is a runtime environment that executes Java bytecode.
It allows Java programs to run on any operating system as long as a JVM is available.

👉 JVM is the reason Java is platform-independent.

3. What are primitive data types in Java?

Answer:
Primitive data types are basic data types that store simple values.

Java has 8 primitive data types:

byte
short
int
long
float
double
char
boolean

They are not objects and store values directly in memory.

4. How do you compile and run a Java program?

Answer:

Write code in a .java file

Compile using:
javac FileName.java

Run using:
java FileName

Compilation creates bytecode (.class file) which is executed by JVM.

5. What is a data structure?

Answer:
A data structure is a way of organizing and storing data so it can be accessed and modified efficiently.

Examples:
Array
Stack
Queue
Linked List

6. Is a data structure a program? Explain.

Answer:
No, a data structure is not a program.
It is a concept or method used inside programs to manage data efficiently.
Programs use data structures, but data structures alone do not perform tasks.

7. Why are data structures important?

Answer:
Data structures are important because they:
Improve performance
Optimize memory usage
Make programs scalable
Help handle large amounts of data efficiently
Without data structures, complex software cannot work efficiently.

8. What is a computer network?

Answer:
A computer network is a collection of devices (nodes) connected together to share data and resources.

Examples:
Internet
Local Area Network (LAN)
Mobile networks

9. What are nodes and protocols?

Answer:

Nodes: Devices connected to a network (computers, servers, routers, phones)
Protocols: Rules that define how data is transmitted between nodes

Examples of protocols:
HTTP
TCP/IP
FTP

10. Why is the OSI model used?

Answer:
The OSI model is used to standardize networking communication and make troubleshooting easier.
 It divides networking into 7 layers, so: 
 Problems can be identified layer-by-layer
 Different vendors can build compatible systems
 Learning and debugging networks becomes simpler

11. What is the OSI Model? Explain all 7 layers.

Answer:
The OSI (Open Systems Interconnection) model is a 7-layer reference model used to understand how data moves from one computer to another over a network.
It is mainly used to:
Understand networking clearly
Troubleshoot problems easily
Standardize communication between different vendors

OSI Model – 7 Layers (Top to Bottom)
7️⃣ Application Layer
Closest to the user
Provides network services to applications

Examples:
HTTP
FTP
SMTP
DNS
👉 If a website doesn’t load, the issue may be here.

6️⃣ Presentation Layer
Handles formatting, encryption, and compression
Converts data into readable format

Examples:
Encryption (SSL/TLS)
Encoding (ASCII, UTF-8)
👉 Ensures data is understandable.

5️⃣ Session Layer
Manages sessions between two systems
Opens, maintains, and closes connections
👉 Controls who talks and for how long.

4️⃣ Transport Layer
Responsible for end-to-end communication
Ensures data is delivered reliably or fast

Protocols:
TCP (reliable)
UDP (fast, unreliable)
👉 If packets are lost or slow, issue is here.

3️⃣ Network Layer
Handles routing and logical addressing
Decides the best path for data

Examples:
IP addresses
Routers
👉 If data can’t reach another network, problem is here.

2️⃣ Data Link Layer
Handles physical addressing (MAC)
Error detection within same network

Examples:
MAC address
Switches
👉 Works inside a LAN.

1️⃣ Physical Layer
Transmits raw bits (0s and 1s)
Deals with cables, signals, voltages

Examples:
Ethernet cables
Fiber optics
Wi-Fi signals
👉 If cable is unplugged, issue is here.
 
