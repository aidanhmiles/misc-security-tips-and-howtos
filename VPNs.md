
# About:

A VPN is a means of protecting the transfer of data between computers, and of anonymizing your activity on the Internet. The technical details of how they work are beyond the scope of this document, but there are plenty of places to read up on it. 
(
    [Wiki](https://en.wikipedia.org/wiki/Virtual_private_network),
    [Lifehacker](http://lifehacker.com/5940565/why-you-should-start-using-a-vpn-and-how-to-choose-the-best-one-for-your-needs),
    [Cisco](http://www.cisco.com/c/en/us/about/press/internet-protocol-journal/back-issues/table-contents-18/what-is-a-vpn.html)
    [Network World](http://www.networkworld.com/article/2168144/malware-cybercrime/can-your-ip-address-give-away-your-identity-to-hackers--stalkers-and-cybercrooks-.html)
)

The gist of it is that when you use a VPN, your computer connects to a server somewhere else via the Internet (which is a public network), and after your computer and that machine have exchanged some secret messages, your Internet traffic is all routed through that machine, and wrapped up in a bundle of encyrption that is indecipherable by anyone that's not you or that machine (which is to say, the data is completely private).

VPNs are so useful that savvy authoritarian governments have started trying to ban them ([UAE](http://www.scmagazineuk.com/uae-bans-vpns/article/512832/), [China](http://www.scmagazineuk.com/uae-bans-vpns/article/512832/)).

The benefits of a VPN are at least twofold:

1) Data that is sent over a VPN connection cannot be read or tampered with, which means that no one can intercept messages (passwords, credit card info) that you type into webpages and send over the wire. Additionally, firewalls (corporate firewalls, China's Great Firewall) are unable to snoop on your internet traffic and censor what you access.

2) Your activity on the Internet is anonymized. Websites see requests coming from the IP address of the VPN provider's server, not your computer's IP, which prevents external tracking of your browsing activity. An IP address can be used as a way of identifying you, and while not everyone cares about that, it's nice to have. Additionally, you can sometimes get around country-based restrictions on digital content (watching live streaming video that's only available in the UK) if your VPN service has servers in a range of countries.

#### Caveats

Streaming video sites might not let you watch their content using a VPN. Netflix completely disallows it. This just means you have to turn off your VPN temporarily to use these services.

Occasionally, websites that are savvy enough might think you're a robot, and either stop you from accessing the site, or requiring you do one of those CAPTCHA tests where you have to identify which pictures contain a thing.

Please don't actually get arrested in the UAE.

## Private Internet Access

I recommend PIA to everyone. It's a highly rated service that's amazingly inexpensive, they keep no logs, they have lots of servers all over the world, and it's **blissfully easy** to use. Keeping no logs means that your activity (your searches, what websites you access, passwords) on their servers is not recorded.

If you're really about your privacy, you can also pay anonymously with not just Bitcoin, but any major brand giftcard (which in turn can be purchased with cash).

### Setup

1) [Start at their website](https://www.privateinternetaccess.com/pages/buy-vpn/), and select the yearly plan ($3.33 / year). 

2) Checkout, and download the app for your platform. Downloading the software is free on all platforms; you're paying for a subscription to the service.

3) Check your email. You'll have received your username and temporary password in one of them, and download links to their apps in another.

4) Use your new account credentials and login. You'll be prompted to choose a new password. Make it a good one.

5) You'll now be able to log into PIA's desktop application and mobile apps. Generally you won't need to do any fancy configuration, but in the event you do, their support is very helpful. To use the app, find the button that says "Connect" and hit it. You'll have different server options to choose from, but it can pick one for you as well.

## Vyper

Faster (they claim; could be true but I have not verified this), and more expensive. I used their service while in China and it has continued to grow. They offer software for a wider variety of devices, including wireless routers.

# Roll your own (sort of)

If you're not afraid of the command-line, you can deploy your own VPN, hosted on your own cloud computing account (AWS, Digital Ocean, et al). Or have me do it!

https://github.com/jlund/streisand

## More Reading



