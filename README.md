# FTP_Client

please contact me at u2010151@gmail.com to get help with this project


FTP Client 

Description
The goal of this project is to deepen your ability to write network code. At this point you can open a socket and send and receive simple messages. In this project, you will implement a client for a more complex protocol, that has more features, and uses two sockets rather than one.

Specifically, in this project you will develop a client for the File Transfer Protocol (FTP) protocol. We have setup an FTP server for you to use when developing and debugging your client.

What is FTP
Developed in 1971, the File Transfer Protocol (FTP) is one of the oldest protocols still in common use today. FTP’s development predates TCP/IP, yet the protocol still works fairly well on the modern internet.

FTP is a client-server oriented protocol for uploading, downloading, and managing files. The FTP server’s job is to listen for incoming connections from clients and then respond to their requests. These requests include all common file and directory operations, such as listing the files in a directory, making and deleting directories, uploading files from the client machine to the server, and downloading files from the server to the client machines. FTP clients connect to FTP servers and issue commands to tell the server what to do.

Because the FTP protocol is so old, it has many, many features, some of which are vestigial and no longer make sense on the modern internet (e.g., uploading a file in 36-bit, EBCDIC format directly to a line-feed printer), and others that are so esoteric that they are rarely used and supported. Wikipedia has an extensive article on the FTP protocol, as well as a list of all FTP protocol commands. Fortunately, a FTP client only needs to support a minimum, basic set of commands in order to function. We outline the necessary functionality for the FTP client you will develop below. Our reference implementation is roughly 300 lines of Python3, including self-documentation and extensive error checking.
