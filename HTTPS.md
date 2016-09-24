
# About

HTTPS refers to HTTP connections (the system of requests and responses between machines, which makes the Internet happen) that are encrypted, and are thus Secure, for the S at the end.

The technical details are beyond this document, but the essence of it is that with the extra encryption, messages that travel between you and example.com are indecipherable and tamper-proof. In practice it's not that simple, but HTTPS is in general a Good Thing. HTTPS ensures that an attacker cannot mess with files that get delivered to your computer – without this protection, they could potentially add malicious code to otherwise harmless websites, and steal any amount of your information. HTTPS also ensures that any outgoing information that you send can only be read by the rightful recipient (e.g. only Facebook can read the password that I send to them).

## HTTPS Everywhere

HTTP is not secure. Partial HTTPS is not secure (any kind of file can be maliciously used). Only 100% HTTPS is secure (and even then, only in certain aspects). To that end, the EFF makes this nifty browser extension called [HTTPS Everywhere](https://www.eff.org/https-everywhere). What it does is it prevents your browser from downloading anything (web pages, images on web pages, really anything) that isn't available by HTTPS. 

As an example of what HTTPS Everywhere does, take Costco.com, which is mostly served over HTTPS. However, some images are not, so I get an incomplete but mostly functional webpage. It is incomplete, but significantly safer for me, the user.

## HTTPS is not everything

HTTPS connections are encrypted using TLS or SSL, which are protocols (rules of communication) that specify how clients (your browser) share secret messages and other info in order to achieve their encryption. TLS is great, and for some reason some people still call it SSL. SSL is the older one, and is broken / known to be vulnerable to attacks of different kinds. Despite this, many websites encrypt connections using the older SSL. This is one reason HTTPS is not everything.

Additionally, neither SSL nor TLS can protect you from e.g. a malicious website that wants to take your money, or one that tries to get you to download malware. They merely protect the connection while your money gets stolen or you download that malware. Your judgment is still a critical part of your own security.


