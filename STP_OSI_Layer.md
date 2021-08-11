# **OSI LAYERS**

## **` OSI Model:-`**  

<br>

* OSI Stands for **Open Systems Interconnection**. 
* OSI Model was developed by the **ISO (International Organization Standardization)** in `1984`.
* OSI Model is a reference model that describes how the information from software/ browser applications in one computer/ system moves through a physical medium to the software application in another computer.
* OSI Model consists of seven layers, which are given below:-
<br>
    ![](https://cdn.educba.com/academy/wp-content/uploads/2019/07/OSI-Model.png "OSI Layers")

<br>
<br>


1. ### **`Physical Layer :-`**
   ![](https://www.tutorialandexample.com/wp-content/uploads/2020/10/image-202.png "Physical Layer")

    <br>

   * Physical layer is the lowest layer of the OSI Model.
   * It defines electrical and physical specifications for devices.
   * It defines the relationship between a device and a transmission medium, such as an optical cable.
   * It is used to transmit the individual bits from one node to another node.

   <br>

    *  ###  `Some functions of a Physical Layer are given below:-`
        * **Data Transmission:-** 
            > It defines the transmission mode between two devices on the network whether it is half-duplex, full-duplex, or simplex.

        * **Physical Topologies/ Network Topologies :-**
            > Physical Topologies is the Geographical representation of linking devices. There are four types of topology in physical layer [Mesh Topology](https://www.computerhope.com/jargon/m/mesh.htm "Mesh Topology"), [Star Topology](https://www.computerhope.com/jargon/s/startopo.htm "Star Topology"), [Ring Topology](https://www.computerhope.com/jargon/r/ringtopo.htm "Ring Topology") and [Bus Topology](https://www.computerhope.com/jargon/b/bustopol.htm "Bus Topology")

        * **Line Configuration :-**
            > Line configuration defines the way how two or more devices can be connected physically.

        * **Signals Configuration :-**
            > In signals configuration, it determines the type of signals used to transmitting the data/ information.
    
    <br>

    #### `Note :-` For more details [click here](https://www.tutorialspoint.com/data_communication_computer_network/physical_layer_introduction.htm "Physical Layer").
            
    <br>
    <br>

2. ### **`Data Link Layer :-`**
    ![](https://www.includehelp.com/computer-networks/images/data-link-layer-1.jpg "Data Link Layer")

    <br>

    * Data Link Layer is the second-lowest layer of the OSI Model.
    * This layer provides the functional and procedural means to transfer data between network entities and to detect and possibly correct errors that may occur in the physical layer.
    * The responsibility of the data link layer is when a packet arrives in a network then transmits it to the Host using its MAC address.
    * Data link layer is divided into two sub-layers([Logical Link Control](https://www.geeksforgeeks.org/logical-link-control-llc-protocol-data-unit/ "Logical Link Control") and [Media Access Control](https://www.geeksforgeeks.org/introduction-of-mac-address-in-computer-network/ "Media Access Control"))

   <br>

    *  ###  `Some functions of a Data Link Layer are given below :-`
        * **Physical Addressing**   
        * **Farming**
        * **Error Control**
        * **Flow Control**
        * **Access Control**

    <br>

    #### `Note :-` For more details [click here](https://www.javatpoint.com/data-link-layer "Data Link Layer").

    <bt>
    <br>

3. ### **`Network Layer :-`**
    ![](https://static.javatpoint.com/tutorial/computer-network/images/osi-model6.png "Network Layer")

    <br>

    * Network Layer is the third lowest layer of the OSI Model.
    *  The protocols used to route the network traffic are known as Network Layer Protocols.
    * It manages device addressing, tracks the location of devices on the network.
    * It determines the best path to transfer the data from source to destination based on the network speeds.
    
   <br>

    *  ###  `Some functions of a Network Layer are given below :-`
        * **Internetworking**
        * **Logical Addressing**
        * **Routing**
        * **Fragmentation**
    
    <br>

    #### `Note :-` For more details [click here](https://www.javatpoint.com/network-layer "Network Layer").

    <bt>
    <br>

4. ### **`Transport Layer :-`**
    ![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2021/05/OSI-Modeil-normal-image05.jpg "Transport Layer")

    <br>

    * Transport Layer is the fourth layer of the OSI Model.
    * It checks that the messages/ data are transmitted in the order in which they are sent.
    * It also ensures that there is no duplication of data.
    * The layer can be termed as an end-to-end layer as it provides a point-to-point connection between source and destination to deliver the data packages.
    * It is used two protocols layer, [Transmission Control Protocol](https://www.fortinet.com/resources/cyberglossary/tcp-ip "TCP") and [User Datagram Protocol](https://searchnetworking.techtarget.com/definition/UDP-User-Datagram-Protocol "UDP").
    
   <br>

    *  ###  `Some functions of a Transport Layer are given below :-`
        * **Service-Point Addressing**
        * **Segmentation and Reassembly**
        * **Connection Control**
        * **Error Control**
        * **Flow Control**

    <br>

    #### `Note :-` For more details [click here](https://www.javatpoint.com/computer-network-transport-layer "Transport Layer").
            
    <br>
    <br>

5. ### **`Session Layer :-`**
    ![](https://www.tutorialandexample.com/wp-content/uploads/2020/10/image-294.png "Session Layer") 

    <br>

    * The Session Layer is the fifth layer of the OSI Model.
    * It is responsible for the establishment of the connection.
    * It is also maintenance of sessions authentication and also ensures security.
    
   <br>

    *  ###  `Some functions of a Session Layer are given below :-`
        * **Synchronization**
        * **Dialog Controller**
        * **Session Establishment**
        * **Session Maintenance**
        * **Session Termination**

    <br>

    #### `Note :-` For more details [click here](https://www.tutorialspoint.com/The-Session-Layer-of-OSI-Model "Session Layer").
            
    <br>
    <br>

6. ### **`Presentation Layer :-`**
    ![](https://www.includehelp.com/computer-networks/images/presentation-layer.jpg "Presentation Layer")

    <br>

    * The sixth layer of the OSI Model is Presentation Layer.
    * The Presentation Layer acts as a data translator for a network.
    * This layer is also known as Syntax Layer.
    * It is mainly concerned with the syntax and semantics of the data exchanged between two devices.
        
   <br>

    *  ###  `Some functions of a Presentation Layer are given below :-`
        * **Translation**
        * **Compression**
        * **Encryption**


    <br>

    #### `Note :-` For more details [click here](https://www.tutorialspoint.com/The-Presentation-Layer-of-OSI-Model "Presentation Layer").
            
    <br>
    <br>

6. ### **`Application Layer :-`**
    ![](https://www.includehelp.com/computer-networks/images/application-layer.jpg "Application Layer")

    <br>

    * The Application Layer is the seventh layer of the OSI Model.
    * It deals with the issues such as resource allocation, network transparency, etc.
    * This layer provides the network services to the end-users.
        
   <br>

    *  ###  `Some functions of a Application Layer are given below :-`
        * **Mail Services**
        * **File Transfer, Access and Management**
        * **Directory Services**


    <br>

    #### `Note :-` For more details [click here](https://www.javatpoint.com/computer-network-application-layer "Application Layer").
            
    <br>
    <br>

---
---

# **`References :-`**
* [https://www.javatpoint.com/osi-model](https://www.javatpoint.com/osi-model)
* [https://en.wikipedia.org/wiki/OSI_model](https://en.wikipedia.org/wiki/OSI_model)
* [https://www.geeksforgeeks.org/layers-of-osi-model/](https://www.geeksforgeeks.org/layers-of-osi-model/)
* [https://www.youtube.com/watch?v=vv4y_uOneC0&t=564s](https://www.youtube.com/watch?v=vv4y_uOneC0&t=564s)
* [https://www.youtube.com/watch?v=vv4y_uOneC0&t=564s](https://www.youtube.com/watch?v=vv4y_uOneC0&t=564s)
* [https://www.youtube.com/watch?v=cFd1PjKEZM0](https://www.youtube.com/watch?v=cFd1PjKEZM0)