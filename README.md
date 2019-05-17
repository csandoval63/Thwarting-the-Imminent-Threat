# Thwarting-the-Imminent-Threat
Incident Response guideline for Eternal Blue Exploit on the NICE Challenge created in California State University, San Bernardino

## Targeted Systems
- Domain-Controller
- Dev-Web systems

## Attack Vector: EternalBlue
EternalBlue is an exploit that uses TCP ports 139 and 445
- Research them yourself also

## Differences between 1xx and 4xx
-Port 139: TCP port 139 is SMB over NETBIOS. NETBIOS is a transport layer protocol designed to use in windows operating systems over network. TCP 445 is SMB over IP
-Port 445: TCP port 445 is used for SMB and direct TCP/IP MS Networking access without the need for a NetBIOS layer


## Temporary Solution 
Best way is to disable SMB on the firewall.
1. Create new rules to block both ports for inbound and outtbound traffic for precautionary measures to make sure it can't recieve or send communcations going in or out
- Go to the firewall wall settings and clicking on advanced settings

## Ultimate Solution
Windows update or a manual hotfix patch provided by the vendor

## Documentation
-Created by C. Sandoval

-Edited by J. Hyun
