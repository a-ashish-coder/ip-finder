# Find IP Address

import socket

def get_ip_address():
    hostname = socket.gethostname()
    ip_address = socket.gethostbyname(hostname)
    return ip_address

if __name__ == "__main__":
    print("Your IP Address is:", get_ip_address())
