# Honeypot
## Honeypots Used
![honeypot-1](https://user-images.githubusercontent.com/52509352/83580904-1b94d100-a4f2-11ea-8c8d-66983e1ff511.png)

![honeypot-2](https://user-images.githubusercontent.com/52509352/83580939-30716480-a4f2-11ea-934d-5f0d65ca9601.png)

![honeypot-3](https://user-images.githubusercontent.com/52509352/83580949-39623600-a4f2-11ea-9775-24d504bd8af8.png)

* As you can see from the screenshots I use several different honeypots:
  * ElasticHoney- It takes requests on the /, /_search, and /_nodes enpoints and returns a JSON response that is identical to a vulnerable ES instance.
  * SnortSensor- Snort has three functions. packet sniffer, packet logger, or a full network intrusion and prevention system.
  * Dionaea- It's intention is to trap malware exploiting vulnerabilities exposed by services offered to a network, the ultimate goal is gaining a copy of the malware.


## Issues Encountered
* Fortunatley I did not run into very many issues, but the small issues i did run into were:
 * When logging onto the MHN Admin make sure that you type the external address of the mhn-admin into the address bar to get to the login page of MHN Admin. Type in the username and password that were setup in Milestone 2, for the Superuser email and password.
## Data Collected
![HoneypotAttacks](https://user-images.githubusercontent.com/52509352/83580964-5991f500-a4f2-11ea-8960-fa8b90e562af.png)

![HoneypotSensors](https://user-images.githubusercontent.com/52509352/83580976-63b3f380-a4f2-11ea-8099-d5d925b09e7d.png)

* There were a total of 1,611 attacks that hit all three of my honey pots.

