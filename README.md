<h1 align="center" id="title">port scan python script</h1>

<p id="description">This Python script is a simple port scanner. It takes two inputs from the user: the target host and the port range. The code then loops over the port range and attempts to connect to each port. If the connection is successful, the code prints a message indicating that the port is open.

The code first imports the socket library. This library provides the functions and classes needed to create and use sockets.

The next step is to print a header for the user interface. This header includes the name of the script and the author's website.

The next step is to get the target host and port range from the user. The input() function is used to get input from the user.

The next step is to print a status message showing the target host and port range. This message is used to inform the user of the ports that are being scanned.

The next step is to loop over the port range. For each port, the code attempts to connect to the target host and port. The socket.socket() function is used to create a new socket object. The socket.connect_ex() function is used to attempt to connect to the target host and port. The 0.1 second timeout value is used to indicate that the connection attempt should not take longer than 0.1 seconds.

If the connection attempt is successful, the code prints a message indicating that the port is open. The socket.close() function is used to close the socket connection.

If the connection attempt is not successful, the code prints a message indicating that the port is closed.

The final step is to print a status message indicating that the scan is complete.</p>

<h2>🛡️ License:</h2>

This project is licensed under the MIT
