For this problem, I spent a lot of time learning about how server connections work. I also spent a lot of time figuring out when to send wry messages and implement error-catching in general. These were my two biggest challenges. My high-level approach was to split the code up into several functions - one that sets up the server connection, one that does the binary search for the guessing game, a few different one-line functions to send specific messages to the server, and one to read a "valid" message and send wry messages if needed. My main function parses the arguments received to determine the port, netID, and host address. 