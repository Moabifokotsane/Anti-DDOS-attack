# Anti-DDOS-attack
**Theoretical Hypothesis**
DOS attacks often take place on domains with firewall and some aren't really strong (depending on which type of DOS attack)
old DOS attacks use SYN & SYNARK attacks to take down domains. New Firewalls can detect and stop these attacks. As of that hackers like security experts they developed a solution to prevention of SYN attacks on domains via firewalls by Using "Botnet" (multi server assistance) to overfill those domain firewalls, this worked until "unlimited bandwidth" was introduced to domains. (if your system is not on unlimited bandwith then you're vulnerable to DDOS attacks).

The latest DOS attacks use "get" functions and requests to attack domains. Python became handy here with this latest attack , what happens is the Code attacks domain with many HTTP get requests which a device uses to establish connection to domain. Firewalls cannot prevent this type of attack because obviously it will mean denying anyone from reaching your domain if your firewall closes all get requests therefore no users for your domain. The latest firewalls can prevent DOS attacks when they detect a distributed get request connection from the same ip address and hence eventually block the individual device and categorizing it as a threat but allowing other devices to connect. This is is the part when PYTHON becomes resourceful. By automatically generating fake IP devices (thousands) to go attack the domain using get request. this happens so fast the firewall wont recognize its an attack but think its just random users all sending get requests at the same time. This will criple the domain when the code is run in a Botnet now making it a distributed denial of service attack any system cannot withstand. 

this is where the cyber world is at in this stage of DDOS attacks hackers are advanced more than security experts at this point. 

**solution**
**HYPOTHESIS**
What if we want to prevent DOS attack off the face of cyber security what can we do? 
1. Build firewalls which use python to mirror domains 
   -Domain Masking or Mirroring can help in cases were ip devices connect to mirror domains which are images of the real domains
   using the same system hackers use to make fake ip devices to send get requests to domains. by making plenty mirror domains so that once the connection    is made the mirror is destroyed and device can now enter main domain.this will allow a limited number of requests before the mirror is destroyed. 
2. IP ADDRESS AUTHENTICATING (cloud container whose main focus is to carry out SYN AKR ) cloud containers are isolated systems running in a single system    (cloud server) with a container running an IP Address AuthN resource then handing it over to AuthZ resource for access to full domain will help in the    event when an attack is made it can be picked up from first sight in the AuthN container which can be acted on without affecting the entire sever.        Containers can work as a better solution to data security. A container can run python in it which can be dedicated to do that one duty. in future this    system can be "captcha for iP addresses". 
3. .........
4. .........
5. .........
6. .........
7. .........
8. .........
