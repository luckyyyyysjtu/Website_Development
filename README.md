# Web Development
This repository showcases completed web development projects, highlighting proficiency in diverse skills such as HTML, database management, cloud integration, distributed systems, web scraping, and various web models. 

Coding Language: **Java**


## Project Details
**Project1Task1**: Developed a website to compute MD-5 and SHA-256 hashes of user inputs.

![](./image/Project1Task1.png)

**Project1Task2**: Developed a class clicker enabling students to make single-answer choices during class quizzes. Additionally, implemented a result display page that shows the count of each answer selected.

![](./image/Project1Task2.png)
![](./image/Project1Task2Result.png)

**Project1Task3**: Developed a baseball information board that dynamically showcases player statistics and game schedules. Utilized data retrieval techniques, including interfacing with a third-party API and implementing web scraping to aggregate information.

![](./image/Project1Task3.png)
![](./image/Project1Task3Result.png)

**Project2Task0**: This program implements a UDP Echo Client and a UDP Echo Server. The client sends user-entered messages to a UDP Echo Server running on the same machine ("localhost"). The client can send messages to the server, and the server echoes them back.

![](./image/Project2Task0Client.png)
![](./image/Project2Task0Server.png)

**Project2Task1**: This program simulates an Eavesdropper UDP application. It listens on a specified port, intercepts messages from clients, and forwards them to a target server while altering specific content in the messages(changing like in string to dislike). The eavesdropper then captures and echoes the server's responses back to the original client.

![](./image/Project2Task1Client.png)
![](./image/Project2Task1Server.png)
![](./image/Project2Task1Eavesdropper.png)

**Project2Task2**: This program implements a basic UDP Adding Client and UDP Adding Server. The client allows users to enter integer values that are sent to a remote Adding Server. The client receives the server's response, which is typically the result of adding the sent value to a running total on the server. The client can continue to send values until the user enters "halt!" to terminate the client. The server listens on a specified port, receives integer values from clients, adds them to a running total, and returns the updated total to the clients. The server continues to run indefinitely, processing client requests.

![](./image/Project2Task2Client.png)
![](./image/Project2Task2Server.png)

**Project2Task3**: This program implements a basic UDP Remote Variable Client and a basic UDP Remote Variable Server. The client allows users to interact with a remote variable server by performing operations such as addition, subtraction, and retrieval of variable values associated with unique IDs. Users can select operations and provide necessary input values through a menu interface. The server listens on a specified port and handles requests from clients to perform various operations on remote variables identified by unique IDs. Supported operations include addition, subtraction, and retrieval of variable values. The server maintains a collection of variables and their current values using a TreeMap.

![](./image/Project2Task3Client.png)
![](./image/Project2Task3Server.png)

**Project2Task4**: This program implements a basic TCP Remote Variable Client and a basic TCP Remote Variable Server similar to Project2Task3.

![](./image/Project2Task4Client.png)
![](./image/Project2Task4Server.png)

**Project2Task5**: The task adds a identity verification step to Project2Task5. The client application communicates securely with a remote server using the RSA digital signature. It allows the user to perform mathematical operations (addition, subtraction and get) on a remote variable stored on the server, ensuring data integrity and security through digital signatures. The client generates RSA key pairs, signs messages, and sends them to the server for processing. The server validates the signatures and performs the requested operations on the remote variable. The server receives and verifies client requests with digital signatures before processing them. This server listens on a specified port for incoming client requests, verifies the digital signatures on these requests, and processes them if they are valid.

![](./image/Project2Task5Client.png)
![](./image/Project2Task5Server.png)

**Project3Task0**: The program constructs a simple blockchain and provides methods for managing and interacting with the blockchain. Users can add blocks, calculate difficulty, display block contents as JSON, corrupt the chain, repair the chain and check for hash calculation speed.

**Project3Task1**: This task is similar to Project3 Task0. Additionally, it creates a client-server TCP connection. The blockchain is stored on the server side and the client could make requests to do operations on the blockchain.

**Project4**: Designed and built a distributed application consisting of a mobile application, a web service that communicates with a RESTful web service in the cloud, and a dashboard that displays logging and simple analytics about the application. The user log data is stored persistently so that it is available across restarts of the application. MongoDB is used to store log data.
![](./image/Project4Diagram.png)
![](./image/Project4Mobile.png)
![](./image/Project4Dashboard.png)

**Project5Part2**: The program uses Apache Spark to analyze various aspects of the text, including the number of lines, words, distinct words, symbols, distinct symbols, distinct letters, and allows the user to search for specific words within the text.

