# Similarities and Differences between OSI model and the TCP/IP model

## 1. Similarities between OSI model and the TCP/IP model

- Both are logical models.
- Both define standards for networking.
- Both provide a framework for creating and implementing networking standards and devices.
- Both divide the network communication process into layers.
- In both models, a single layer defines a particular functionality and sets standards for that functionality only.
- Both models allow a manufacturer to make devices and network components that can coexist and work with the devices and components made by other manufacturers.
- Both models simplify the troubleshooting process by dividing complex functions into simpler components.
- Instead of defining the already defined standards and protocols, both models referenced them. For example, the Ethernet standards were already defined by IEEE before the creation of these models. So instead of defining them again both models used them as IEEE Ethernet standards.

## 2. Differences between OSI model and the TCP/IP model

- The OSI Layer model has seven layers while the TCP/IP model has four layers.
- The OSI Layer model is no longer used while the TCP/IP is still used in computer networking.
- To define the functionalities of upper layers, the OSI model uses three separate layers (Application, Presentation, and Session) while the TCP/IP model uses a single layer (Application).
- Just like the upper layers, the OSI model uses two separate layers (Physical and Data-link) to define the functionalities of the bottom layers while the TCP/IP uses a single layer (Link layer) for the same.
- To define the routing protocols and standards, the OSI model uses the Network layer while the TCP/IP model uses the Internet layer.
- The OSI model is well documented than the TCP/IP model.
- The OSI model explains every standard and protocol in detail while the TCP/IP model provides a summarized version of the same.

### Differences between the original TCP/IP model and the updated TCP/IP model

- The TCP/IP model which we use nowadays is slightly different from the original TCP/IP model. The original TCP/IP model has four layers while the updated TCP/IP model has five layers.

- The original version uses a single layer (Link layer) to define the functionalities and components that are responsible for data transmission. The updated version uses two layers (Data Link and Physical) for the same.

- It defines the functions that are directly related to the data transmission in the Physical layer and defines the functions that are indirectly related to the data transmission in the Data-link layer.

- In the updated version, the name of the Internet layer is changed to the Network layer.

The following figure compares the OSI reference model, the original TCP/IP model, and the updated TCP/IP model.

![osi_tcp.jpg](osi_tcp.jpg)