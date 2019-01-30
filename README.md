# Overview

This repo contains various scripts including:

- NMAP to excel converter (GNMAP to XLS).  Currently supports GNMAP format. Takes the output of a Greppable NMAP scan results, filtered on                OPEN ports per IP/Node, and then populates an excel spreadsheet with the findings.  Incorporating Styles Headings and Sheets where required.
- A simple TCP Server and associated TCP Client.

### Installation - nmap2excel.py/nmap2excel.exe

Clone this repository and run as required and as per usage below.

### Usage

    nmap2excel.py -i file -o file -t [output input file contents to terminal]
    nmap2excel.exe -i file -o file -t [outputs input file contents to terminal]
    -i .gnmap format file
    -o filename of your chosen output file (appends .xls)
    -t terminal output

### Installation - SimpleServer.py

Clone this repository and run as required and as per usage below.

### Usage

    SimpleServer.py <host> <port>
    host - chosen server IP address
    port - chosen listening port

### Installation - SimpleClient.py 

Clone this repository and run as required and as per usage below.
    
### Usage

    SimpleClient.py <host> <port>
    host - server IP address to connect to
    port - server port to connect to
   
