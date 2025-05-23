# Network-Protocols(HTTP-FTP-SMTP-etc).
## What are Network Protocols?
Network protocols are rules and conventions that allow devices to communicate over a network. Each protocol defines how data is formatted, transmitted, and processed.

These protocols operate at different layers of the OSI model or TCP/IP model.

![NET](https://pbs.twimg.com/media/FztJhFxacAoNQ9U.jpg)

## HTTP (HyperText Transfer Protocol)
### Used For:
Accessing webpages and web services.

### Port Number:
80 (HTTP)

443 (HTTPS - secure version using SSL/TLS)

### Key Features:
Stateless protocol (each request is independent).

Uses GET, POST, PUT, DELETE methods.

Basis for the World Wide Web.

### Example:
When you type http://example.com, your browser sends an HTTP request to the server to fetch the webpage.

## FTP (File Transfer Protocol)
### Used For:
Transferring files between a client and a server.

### Port Number:
21 (Control)

20 (Data transfer)

### Key Features:
Can upload and download files.

Requires authentication (username and password).

Not secure (data is sent in plaintext).

### Secure Alternative:
SFTP (SSH File Transfer Protocol) – encrypted file transfer over SSH## SMTP (Simple Mail Transfer Protocol)

## SMTP (Simple Mail Transfer Protocol)
### Used For:
Sending email messages between email servers.

### Port Number:
25, 587, 465 (secure)

### Key Features:
Sends email from client to server or server to server.

Doesn’t retrieve or store messages — only sends.

## POP3 (Post Office Protocol v3)
### Used For:
Receiving email (download and remove from server).

### Port Number:
110

995 (secure version)

### Key Features:
Downloads emails to local device and deletes them from the server.

Good for single-device access.

## IMAP (Internet Message Access Protocol)
### Used For:
Accessing and managing email on the server.

### Port Number:
143

993 (secure)

### Key Features:
Emails stay on the server.

Allows multi-device access and folder organization.

Syncs email across all devices.

## DNS (Domain Name System)
### Used For:
Translating domain names into IP addresses.

### Port Number:
53

### Example:
www.google.com → DNS → 142.250.190.132

### Key Features:
Hierarchical system (root, TLD, authoritative servers).

Critical for web browsing.

## DHCP (Dynamic Host Configuration Protocol)
### Used For:
Automatically assigning IP addresses to devices on a network.

### Port Number:
67 (server)

68 (client)

### Key Features:
Reduces manual IP configuration.

Assigns IP, subnet mask, gateway, DNS, etc.

## TCP (Transmission Control Protocol)
### Used For:
Reliable data transmission between devices.

### Key Features:
Connection-oriented (3-way handshake).

Ensures data is delivered in order and without errors.

Used by protocols like HTTP, FTP, SMTP.

## UDP (User Datagram Protocol)
### Used For:
Fast, connectionless transmission (e.g., streaming, gaming, DNS).

### Key Features:
No guarantee of delivery.

Low latency and overhead.

Used by protocols like DNS, VoIP, video streaming.

## HTTPS (HTTP Secure)
### Used For:
Secure communication over the web.

### Port Number:
443

### Key Features:
Encrypts data using SSL/TLS.

Ensures confidentiality, integrity, and authentication.
