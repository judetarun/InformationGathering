# InformationGathering
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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1915" height="1051" alt="Screenshot 2026-01-30 214825" src="https://github.com/user-attachments/assets/b5918d7f-812a-49a1-bfbe-279dc506da03" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output
<img width="1920" height="1080" alt="ping" src="https://github.com/user-attachments/assets/3cdd1ca0-faee-4379-94ee-1adc8d345f3f" />




## Finding Hosting Company
get further detail by using ip2location.com website.
## output
<img width="1919" height="1079" alt="Screenshot 2026-01-30 215540" src="https://github.com/user-attachments/assets/71325a28-d4ef-4b61-a238-55cff3ed37a9" />




## History of the website:
## output
https://web.archive.org/
<img width="1919" height="1081" alt="Screenshot 2026-01-30 220134" src="https://github.com/user-attachments/assets/2b62f8b1-f498-48bd-85c8-49d82acb6df3" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="1920" height="1080" alt="nc" src="https://github.com/user-attachments/assets/abb3b80b-fde6-4846-8296-fbc0cdfc0ec7" />



## nmap:
## output
<img width="1920" height="1080" alt="nmap" src="https://github.com/user-attachments/assets/95152074-cfb0-4e6e-8979-13b8ef197783" />




## Whatweb
### output
<img width="1920" height="1080" alt="whatweb" src="https://github.com/user-attachments/assets/00dab1f5-cbe2-4854-8d16-6092a05db173" />



## httprint
## output
<img width="1920" height="1080" alt="httprint" src="https://github.com/user-attachments/assets/cbd8cfa6-4a13-4b52-a0d5-2ebb039e4094" />





# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="1920" height="1080" alt="tracerouteT" src="https://github.com/user-attachments/assets/1d5544cc-f971-4908-bc91-964a435e2590" />



## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="1141" height="641" alt="tracerouteu" src="https://github.com/user-attachments/assets/9ecba59b-450e-46d0-af91-7882f2b51b02" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="1920" height="1080" alt="traceroute" src="https://github.com/user-attachments/assets/e671e7ab-a043-4fb6-93e0-b2e75c26303a" />







## RESULT:
The information gathering techniques tools/procedure were  identified successfully
