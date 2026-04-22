# What is a Domain Name?

## Summary
- Har computer ka ek IP address hota hai (e.g. `192.0.2.172`)
- IP addresses yaad karna mushkil hai → isliye **Domain Names** hote hain
- Domain Name = human-readable address for a web server

---

## Structure of a Domain Name

`developer.mozilla.org`

- Read **right to left**
- `.org` → **TLD** (Top Level Domain)
- `mozilla` → **SLD** (Secondary Level Domain)
- `developer` → **Subdomain**

### TLD Types
- `.com`, `.org`, `.net` → generic
- `.us`, `.in`, `.fr` → country specific
- `.gov` → government only
- `.edu` → educational institutions only

---

## Buying a Domain Name

- Domain name **buy nahi hota** — sirf rent hota hai (1 or more years)
- Companies jo domain manage karti hain = **Registrars**
- Available domain check karne ke liye:
    - Registrar ki website pe jaao
    - Ya terminal mein: `whois mozilla.org`

---

## How DNS Request Works

1. Tu `mozilla.org` type karta hai browser mein
2. Browser check karta hai **local DNS cache** mein IP hai ya nahi
3. Agar nahi → **DNS server** se poochta hai
4. DNS server IP address deta hai
5. Browser web server se connect ho jaata hai 

> [!summary] Definition
> DNS (Domain Name System) = domain names ko
> IP addresses mein convert karta hai.