## Overview
The Virtual Café is a client-server application simulating a café environment. Customers can order tea or coffee, check order status, and exit the café.

### Prerequisites
- Java Development Kit (JDK)
- Command-line terminal

### Compilation
First, compile the Java source files:

javac -cp "." Barista.java
javac -cp "." Customer.java

### Running the Server
Start the server by running:

java -cp "." Barista

The server will start and wait for connections from clients.

### Running the Client
In a new terminal window, start a client by running:

java -cp "." Customer

### Interacting with the Café
1. **Enter Your Name:** Start by entering your name when prompted.
2. **Authentication:** The system will provide an authentication code. Enter the code as received.
3. **Place Orders:** You can place orders for tea and coffee using commands like `make 1 tea` or `make 2 coffees`.
4. **Check Order Status:** Type `order status` to check the current status of your order.
5. **Exiting:** Type `exit` to leave the café. If you exit before your order is completed, the server may repurpose your order for other clients.

## Example Commands
- To order tea: `make 1 tea`
- To order coffee: `make 1 coffee`
- To order both: `make 1 tea and 1 coffee`
- To check order status: `order status`
- To exit: `exit`