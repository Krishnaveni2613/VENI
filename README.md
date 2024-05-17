 
 
FIRST QUESTION 
# WRITE A BLOG ON DIFFERENCE BETWEEN HTTP 1.1 VS HTTP 2?
ANSWER 
     HTTP 1.1 and HTTP 2 differ significantly in performance and effeciency.
     1. MULTIPLEXING:
                HTTP/2/ allows multiple request and responses to be sent simultanously over a single connections, reducing latency,while HTTP/1.1 processes one request per connection.Causeing head-of-line blocking.
    2. HEADER COMPRESSION:
                HTTP/2 uses HPACK for header compression, reducing over header compression,reducing over head abd improving speed.HTTP/1.1 sends headers and plain text,leading to larger,repetitive data.        
    3. BINARY PROTOCOL:
                HTTP/2 uses a binary protocol, which is more efficient to parse compared to the text-based protocol of HTTP/1.1
    4.SERVER PUSH:
                HTTP/2 can proactively send resources to a client before it requests them.improving load items.HTTP/1.lacks this capability.
     5.STREAM PRIORITIZATION:
                 HTTP/2 allows clients to prioritize streams, improving resource allocation and loading efficiency.HTTP/1.1 process requests sequentially without prioritization.


SECOND QUESTION
WRITE A BLOG ABOUT OBJECTS AND ITS INTERNAL REPRESENTATION IN JAVA SCRIPT?
OBJECTS IN JAVA SCRIPT:
              An object is defined using curly braces {} with key value pairs seperated by commas. 
                  INTERNAL REPRESENTATION:
PROPERTIES AND METHODS:
          Internally each objects is a collection of properties and methods. each property has a key and value.
PROTOTYPE CHAIN:
          Objects in javascript have an internal link to another object called the prototype. thid forms a chain known as the prototype chain,allowing properties and methods to be inherited from other objects. The base of this chain is typically object.prototype.
HIDDEN CLASS:
          Java script engines, like v8,optmize objects using hidden classws or shapes.these are internal representations that allow the engine to effeciently manage property access and
          method calls by categorizing objects with similar structures.

PROPERTY ATTRIBUTES:
         Each property in an object has attributes that define its characteristics:
         VALUE:The actual data stored in the property.
         WRITABLE:I ndicates if the property can be changed.
         ENUMBERABLE:Determines if the property shows up in for....in loops and object.keys().
         CONFIGURABLE:Specifics if the property can be deleted or if its attributes can be modified.

THIRD QUESTION:
READ ABOUT IP ADDRESSS, PORT,HTTP METHODS, MAC ADDRESS:
         IP ADDRESS:
             An IP Adress is an essential component for networking enabling device to local data and communicate with each other.
             An IP ADRESS (internet protocol) is a unique string of numbers seperated by periods (IPV4)or colons (IPV6) that identifies each computer using the Internet protocol to communicate over a network.
     PORT:
            A fundamental components in networking,facilitating communication between device over the internet or networks.
            It used to manage multiple communication seassions simultaneously. Each port is associated with a specific process or service. Port helpndistinguish different types of traffic.

            #WELL KNOWN PORTS:
            #REGISTERED PORT:
            #DYNAMIC/PRIVATE PORT:
HTTP METHOD:
           HTTP methods are verbs used in HTTP request to indicate the desired action to be performed on a resource.
           1. GET: Retrives data from a server without modifying it.used for fetching web pages and data.
           2.POST:
           Sends data to a server to create or update a resource. commonly used for from submissions.
           3.PUT: Replaces all current representations of a target resource with the upload content.
           4.DELETE:Removes a specified resource with the provided data,unlike put which replaces the entire resources.
           These methods help define the operations for web interactions, ensuring clarity and consistency in web communication.

           MAC ADDRESS:
                  A mac address (MEDIA ACCESS CONTROL)is a unique identifier assigned to the network interface and (NIC)of a device.It is a 48-bit address typically represented in hexadecimal format,such as 00:1A:2B:3C:4D:5E. MAC adress are used for communication with in a local network and ensure that data packets reach the correct hardware.Unlike IP adresses:mac adresses do not change and are hardcoded into the device by the manufacture.They play a crucial role in network.Management security and diagnostics.

              
                   
