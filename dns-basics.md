# Domain Name System (DNS)

## What is DNS?
Helps communicating with the devices on the internet withount memorizing comple numbers (IP Address).

## Why Is DNS Needed?
Humans remember names, but computer use IP addresses. DNS converts names into IP addresses.

## Domain Heirarchy
Root Domain: "."
Top-Level Domain: Right-hand part of domain name. Two types:
(a) Generic TLD: Tells the purpose of website. E.g., .com (Commerce), .edu (Education)
(b) Country Code TLD: Geographical purposes. E.g., .in (India), .ca (Canada)
Second-Level Domain: Limited to 63 characters (a-z, 0-9, hyphens). Cannot start or end with hyphens.

## DNS Record Types
(a) A Record: Maps domain to IPv4 address.
(b) AAAA Record: Maps domain to IPv6 address.
(c) CNAME Record: Maps to another domain name.
(d) MX Record (email): Tells where should emails for a certain domain go.
(e) TXT Record: Domain info in the form of text is stored. Main function is to list the authorized servers.

## Making a Request
User → Requests domain name  
   ↓  
Recursive DNS Server (ISP - Internet Service Provider)  
   ↓  
Root DNS Server → Redirects to TLD server  
   ↓  
TLD Server → Points to Authoritative server  
   ↓  
Authoritative Server (stores DNS records)  
   ↓  
Returns IP to Recursive DNS  
   ↓  
Recursive DNS returns IP to User  
   ↓  
User connects to Server
