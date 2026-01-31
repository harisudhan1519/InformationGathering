# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois

<img width="1303" height="943" alt="image" src="https://github.com/user-attachments/assets/2315b827-3276-4d18-b867-edfb26051997" />




### Finding Hosting Company :
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/36254acd-1d04-4835-a540-638565342a9b" />



### History of the website :
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4d03e23f-16ea-4911-a185-62194f7fca85" />


### ping command :
### command:
```ping snapchat.com```

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4cb97893-426e-465b-94d6-4c78b609d402" />


### whois : 
### command: 
```whois snapchat.com```

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f32e3c2d-f575-4c53-b9ef-bb64132982f5" />

### netcat :
### command:
```nc snapchat.com 80```

<img width="488" height="175" alt="Screenshot 2026-01-31 134840" src="https://github.com/user-attachments/assets/a7e8478c-1680-4fc3-9fb4-231bfd0c8ba5" />


### nmap :
### command:
```nmap snapchat.com```


<img width="523" height="190" alt="image" src="https://github.com/user-attachments/assets/8c0f8a24-6f76-4430-85a8-1b251a608089" />

### whatweb :
```
Shows:

Web technologies

Frameworks

CMS
```

### httprint :
```
Shows:

Web server fingerprint
```

### TCP traceroute :

### command:
```traceroute -T snapchat.com```


<img width="540" height="188" alt="image" src="https://github.com/user-attachments/assets/27d62045-f354-469b-b59c-35a7131a73bf" />


### UDP traceroute :

### command:
```traceroute -U snapchat.com```


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
