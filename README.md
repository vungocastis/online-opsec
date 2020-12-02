# Online Operations Security (OpSec)
Threat models and tools for staying safe, private and informed while Online, used by the average person.

*Until the first draft of this document is finished (sometime before 02/01/2021), it will be updated daily.*

## Introduction
The purpose of this document is to organize useful context (in the form of threat modeling) and tools (most of which are free) for staying safe, private and informed while Online. If a resource mentioned herein does require one to spend money for access, said tool is assuredly both low-cost and high-value.

The need to remain secure when using the Internet is relevant to everyone.

## Threat Models
A threat model is a structured and systematic means by which individuals can identify potential vulnerabilities, understand the implications of each and respond accordingly in order to mitigate damage. The intention behind threat modeling, as mentioned on [Wikipedia](https://en.wikipedia.org/wiki/Threat_model), is to offer an, "*...analysis of what controls or defenses need to be included, given the nature of the system, the probable attacker's profile, the most likely attack vectors, and the assets most desired by an attacker.*" In other words, designing a threat model is the conducting of an organized analysis of one's current situation and possible/foreseeable future dangers therein.

The objective for deploying a threat model is to determing what can go wrong inside a given set of variables; enabling the modeler to gain tactical advantages that might otherwise be missed.

Below you will find a growing number of threat modeling techniques that can be applied to anyone's situation Online.

### STRIDE
STRIDE (originally introduced by Microsoft) is an acronym representing six different types of threats, each tied to a desired/alternative state or property:
* Spoofing / Authenticity
* Tampering / Integrity
* Repudiation / Non-Repudiability
* Information Disclosure / Confidentiality
* Denial Of Service / Availability
* Elevation Of Privilege / Authorization

According to [Wikipedia](https://en.wikipedia.org/wiki/STRIDE_(security)), STRIDE is typically applied when attempting to, "*...find threats to a system. It is used in conjunction with a model of the target system that can be constructed in parallel. This includes a full breakdown of processes, data stores, data flows and trust boundaries.*" The STRIDE model is popular because it is effective, but that relevancy (as mentioned by [Kevin Poniatowski](https://blog.securityinnovation.com/stride)) has been waning.

#### Specific Threats

What follows are the six different threats (as outline above) that the STRIDE model examines in detail.

##### Spoofing
Misrepresenting one's identity, whether that of a person or computer.

##### Tampering
Unauthorized changes made.

##### Repudiation
Leaving no trail or details of illegal or unauthroized activity.

##### Information Disclosure
Gaining access to private and/or secure information without proper authority.

##### Denial Of Service
Preventing intended users from having access to a resource.

##### Elevation Of Privilege
Unauthorized expansion of abilities as a user.

#### Conclusion
The STRIDE threat model is especially useful for personal Online Operations Security.

## Tools
Different tools for staying safe, private and informed while Online.

### Books
* **The Art of Invisibility** - written by Kevin Mitnick, published on September 10th of 2019
* **ComSec** - written by Justin Carroll, published on July 13th of 2018
* **Extreme Privacy** - written by Michael Bazzell, published on May 27th of 2020
* **Going Gray** - written by Matthew Dermody, published on January 22nd of 2020
* **How To Be Your Own Bodyguard** - written by Nick Hughes, published on October 1st of 2011
* **Open Source Intelligence Techniques** - written by Michael Bazzell, published on October 25 on 2019
* **Operator Handbook** - written by Joshua Picolet and published on March 18th of 2020
* **Situational Sense** - written by Matthew Dermody, published on December 10th of 2019
* **Social Engineering** - written by Christopher Handagy, published on July 31st of 2018
* **Surveillance Zone** - written by Ami Toben, published on May 21st of 2017
* **Survive Like a Spy** - written by Jason Hanson, published on September 8th of 2020

### Browser Extensions
* **[Cookie AutoDelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/)** - "*When a tab closes, any cookies not being used are automatically deleted. Whitelist the ones you trust while deleting the rest.*"
* **[Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)** - "*...prevents a lot of requests from reaching networks like Google Hosted Libraries, and serves local files to keep sites from breaking.*"
* **[Google Search Link Fix](https://addons.mozilla.org/en-US/firefox/addon/google-search-link-fix/)** - "*...prevents Google and Yandex search pages from modifying search result links when you click them.*"
* **[HTTPS Everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)** - "*HTTPS Everywhere is a Firefox extension to protect your communications by enabling HTTPS encryption automatically on sites that are known to support it, even when you type URLs or follow links that omit the https: prefix.*"
* **[NoScript Security Suite](https://addons.mozilla.org/en-US/firefox/addon/noscript/)** - "*The best security you can get in a web browser! Allow potentially malicious web content to run only from sites you trust. Protect yourself against XSS other web security exploits.*"
* **[Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)** - "*Automatically learns to block invisible trackers.*"
* **[uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)** - "*Finally, an efficient wide-spectrum content blocker. Easy on CPU and memory.*"
* **[uMatrix](https://addons.mozilla.org/en-US/firefox/addon/umatrix/)** - "*Point & click to forbid/allow any class of requests made by your browser. Use it to block scripts, iframes, ads, facebook, etc.*"

### Browsers
* **[Firefox](https://www.mozilla.org/en-US/firefox/)** - "*...is a free and open-source web browser developed by the Mozilla Foundation and its subsidiary, the Mozilla Corporation. Firefox uses the Gecko layout engine to render web pages, which implements current and anticipated web standards.*" - [Source](https://en.wikipedia.org/wiki/Firefox)
* **[GNU IceCat](https://www.gnu.org/software/gnuzilla/)** - "*GNUzilla is the GNU version of the Mozilla suite, and GNU IceCat is the GNU version of the Firefox browser. Its main advantage is an ethical one: it is entirely free software.*"
* **[Tor](https://www.torproject.org/)** - "*Defend yourself against tracking and surveillance. Circumvent censorship.*"

### Email
* **[ProtonMail](https://protonmail.com/)** - "*...an easy to use secure email service with built-in end-to-end encryption and state of the art security features. Our goal is to build an internet that respects privacy and is secure against cyberattacks.*"

### Firewalls
* **[pfSense](https://www.pfsense.org/)** - "*...is a free network firewall distribution, based on the FreeBSD operating system with a custom kernel and including third party free software packages for additional functionality. pfSense software, with the help of the package system, is able to provide the same functionality or more of common commercial firewalls, without any of the artificial limitations.*"

### Operating Systems
* **[Arch Linux](https://www.archlinux.org/)** - "*...a Linux distribution for computers with x86-64 processors. Arch Linux adheres to five principles: simplicity, modernity, pragmatism, user centrality, and versatility.*" - [Source](https://en.wikipedia.org/wiki/Arch_Linux)
* **[Debian](https://www.debian.org/)** - "*...a Linux distribution composed of free and open-source software, developed by the community-supported Debian Project, which was established by Ian Murdock on August 16, 1993.*" - [Source](https://en.wikipedia.org/wiki/Debian)
* **[Fedora](https://getfedora.org/)** - "*...an innovative, free, and open source platform for hardware, clouds, and containers that enables software developers and community members to build tailored solutions for their users.*"
* **[Kali Linux](https://www.kali.org/)** - "*...a Debian-derived Linux distribution designed for digital forensics and penetration testing. It is maintained and funded by Offensive Security.*" - [Source](https://en.wikipedia.org/wiki/Kali_Linux)
* **[Qubes OS](https://www.qubes-os.org/)** - "*...a free and open-source, security-oriented operating system for single-user desktop computing. Qubes OS leverages Xen-based virtualization to allow for the creation and management of isolated compartments called qubes.*"
* **[Tails](https://tails.boum.org/)** - "*...is a portable operating system that protects against surveillance and censorship.*"
* **[Ubuntu](https://ubuntu.com/)** - "*...a Linux distribution based on Debian and mostly composed of free and open-source software.*" - [Source](https://en.wikipedia.org/wiki/Ubuntu)

### Passwords
* **[Bitwarden](https://bitwarden.com/)** - "*The easiest and safest way for individuals and businesses to store, share, and secure sensitive data on any device[.]*"
* **[KeePassX](https://www.keepassx.org/)** - "*...an application for people with extremly high demands on secure personal data management. It has a light interface, is cross platform and published under the terms of the GNU General Public License.*"

### Search Engines
* **[DuckDuckGo](https://duckduckgo.com/)** - "*DuckDuckGo is an international community of extraordinary individuals, coming together on a mission to set a new standard of trust online.*"

### Social Media And Trend Monitoring
* **[Boardreader](https://boardreader.com/)** - "*Forum search engine[.]*"
* **[Followerwonk](https://followerwonk.com/)** - "*Tools for Twitter Analytics, Bio Search and more[.]*"
* **[Google Alerts](https://www.google.com/alerts)** - "*Monitor the web for interesting new content[.]*"
* **[Google Trends](https://trends.google.com/trends/)** - "*Explore what the world is searching[.]*"
* **[Hootsuite](https://hootsuite.com/)** - "*Easily manage all your social media and get results with Hootsuite.*"
* **[Social Mention](http://socialmention.com/)** - "*Social Mention is a real time search platform[.]*"
*  **[Trendsmap](https://www.trendsmap.com/)** - "*Trendsmap shows you the latest Twitter trending hashtags and topics from anywhere in the world. Click on a word, zoom into your area of interest, and explore.*"
* **[TweetDeck](https://tweetdeck.twitter.com/)** - "*The most powerful Twitter tool for real-time tracking, organizing, and engagement. Reach your audiences and discover the best of Twitter.*"

### VPNs
* **[AirVPN](https://airvpn.org/)** - "*A VPN based on OpenVPN and operated by activists and hacktivists in defence of net neutrality, privacy and against censorship.*"

## Conclusion
There are a good number of reliable tools available to the averge person for staying safe, private and informed while Online. This document brings the best of them to you.

Over the coming weeks, the information and resources found herein will continue to grow; ideally becoming a first class resource for those interested in the serious topic of personal Online OpSec. Many thanks to those who have already suggested improvements to this project.
