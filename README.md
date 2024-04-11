# TFTP-server-client 
implemention of an extended TFTP (Trivial File Transfer Protocol) server and client. the
TFTP server is a file transfer protocol allowing multiple users to upload and download files from the server and
announce when files are added or deleted to the server. The communication between the server and the client(s) will
be performed using a binary communication protocol, which will support the upload, download, and lookup of files.
Please read the entire document before starting.
The implementation of the server will be based on the Thread-Per-Client (TPC) servers taught in class, any time
the server receives a message from a client it can replay back to the client itself.
