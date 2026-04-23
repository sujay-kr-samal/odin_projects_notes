# How the Internet Works

>Related : [[Browsing the Web]], [[What is a Domain Name]]
## Internet

- 2 computers + ethernet cable = network
- **Billions of devices** (phones, laptops, servers)
- Connected via cables, WIFI, satellites

> [!summary] Definition
> Internet is a large network of networks

---
## Switches

- 10 computers ko directly connect karo = 45 cables needed .
- Switch = ek special device jo sab computers ko connect karta hai
- Har computer ko sirf 1 cable chahiye (switch se)
- 10 computers + switch = sirf 10 cables 
- Switch ensure karta hai message sirf **target computer** tak jaaye

> [!summary] Definition
> A switch connects multiple computers in a local network
> and delivers messages only to the intended destination.

---
## Routers

- Switch sirf ek network ke andar kaam karta hai
- Router = alag alag networks ko connect karta hai
- Router is like a **post office** 
    - Packet aata hai → address padhta hai → sahi network ko forward karta hai

> [!summary] Definition
> A router is a computer that knows how to forward
> messages between networks.

---
## Modems & ISPs

- Router se network ban jaata hai, but **duniya se connect** kaise hoge?
- Modem = tumhare network ki info ko **telephone infrastructure** ke liye convert karta hai
- ISP (Internet Service Provider) = ek company jiske routers sab connected hain
    - e.g. Jio, Airtel, BSNL

> [!summary] Definition
> Modem converts network data for telephone lines.
> ISP connects your network to the global internet.

---
## IP Addresses & DNS

- Har computer ka ek unique address hota hai = **IP Address**
    - e.g. `192.168.1.1`
- IP address yaad karna mushkil hai humans ke liye
- Isliye **Domain Names** hote hain = human readable alias for IP
    - e.g. `google.com` = `142.250.190.78`
- **DNS** (Domain Name System) = IP aur Domain Name ko map karta hai

> [!summary] Definition
> IP Address = unique identity of a computer on internet.
> DNS = converts domain names to IP addresses.

---
## Internet vs The Web

- Internet aur Web **same nahi hain!**
- **Internet** = infrastructure (cables, routers, modems, ISPs)
- **Web** = ek **service** jo internet ke upar chalta hai
    - Web = websites + browsers (HTTP use karta hai)
- Internet pe aur bhi services hain:
    - SMTP {**simple mail transfer protocol**} (Email)
    - IRC {**internet relay chat**} (chat)
    - FTP {**file transfer protocol**} (file transfer)

> [!summary] Definition
> Internet = infrastructure.
> Web = just one service built on top of the internet.

---
## Intranets & Extranets

- **Intranet** = private network sirf ek organization ke liye
    - e.g. company ka internal portal, shared files, messaging
- **Extranet** = intranet ka part jo **bahar ke logon** ke liye open hota hai
    - e.g. clients, partners ko access dena
- Dono same infrastructure use karte hain jaise internet

> [!summary] Definition
> Intranet = private network for an organization.
> Extranet = semi-private, shared with outside partners.

