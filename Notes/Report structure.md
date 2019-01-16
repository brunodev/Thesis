# Report structure

## Problem definition
Leave out nbns and llmnr in the problem background??

## Introduction
* Introduction
* Pentesting windows domains
    * Read team, internal pentest etc.
    * How do we start? Machine on network or similar
    * Goals
    * How its usually done
    * Report, Timeline
    * Other hurdles
* Report structure
### Exploitation of Active Directory Domains

## Credential gathering
### Spoofing
#### NBNS/NetBIOS
#### LLMNR
### Credential acquiring
#### Types of Credentials, LM, NT, NTLM, NetNTLMv1, NetNTLMv2
#### SMB
#### HTTP

## Reconnaissance / Targets
### LDAP enumeration
#### Users
#### Hosts
#### BloodHound

## Attack methods
* Explain why we can't use NetNTLMv2 hashes for anything yet
    * Crack the password - Bruteforce

### Pass-the-hash
* How does it work?
    * NTLM Authentication
    * NT used to create NetNTLMv2 hashes

### Impacket WMIExec
### Mimikatz

## Implementation

### Technologies
* VueJS
* SignalR
* ASP.NET Core

### Considerations
* Modular
    * Common interface
    * Adding new modules easy
    * Types of modules
* Ease of use
* Storage
    * Efficiency, have to sync all nodes
    * I/O considerations
        * Saving is long, still need to access/modify data
    * Scaling
    * Testing

### Final product
* Structure diagrams
* Workflow diagrams

## Discussion

