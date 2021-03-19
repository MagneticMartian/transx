# transx
This is a client side file transfer script. It assumes that the source server is an ftp server and that it requires logging into in order to access the files (no anon user access). It also assumes that there are ssh asymmetric key pair setup on the client and server.

## basic usage
./transx <user> <ip_address> /path/to/files <type_of_files>

When prompted for password enter it.
