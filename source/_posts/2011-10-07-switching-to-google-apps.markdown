---
layout: post
title: "Switching to Google Apps"
date: 2010-03-21 13:16
comments: true
categories: 
author: Gerald Lovel
---
Using Free, Open-Source Solutions (FOSS) is a basic value for AAltSys. Our AAltSys Server provides an advanced office server design using only FOSS, for example. However, converting an office to FOSS requires changing user applications as well. There are three areas of concern here. The first concern, personal productivity, is handled quite well with Sun/Oracle’s OpenOffice suite. The next issue is collaboration, where Microsoft dominates the market with Exchange and Active Directory. The final frontier for companies is accounting, but I will save that topic for a future post. Today’s topic is collaboration software.

Originally corporate email was restricted to within an organization’s walls, because that was as far as the mainframe reached. Today email, calendars and documents are commonly shared between organizations and across national boundaries. This sort of collaboration cannot work using proprietary software designs and local implementations. Instead, email, calendars, and documents  must be encoded in formats readable by all software. The recognized standards here are IMAP for email, ICAL for calendars, and OpenDoc for documents. Microsoft’s office products fail to provide compatibility with any of these standards.

At AAltSys, we have experimented with numerous FOSS products to provide collaborative applications on our servers. We used Mozilla’s Thunderbird, Evolution email, Yahoo’s Zimbra, and eGroupWare, along with many lesser lights. While all these products proved unsatisfactory, our trials allowed us to understand the requirements for real collaboration. These are:

Cross-system. Products must work with any popular operating system, including Windows, Macintosh OSX, and various Linux releases.
Cross-platform. Products must integrate with desktops, WiFi laptops, netbooks, mobile phones, and thin clients.
Standards-based. Data must be portable between systems using open protocols and standards.
Web accessible. All systems must provide a functional web interface which can be accessed over public networks.
Secure. Access to collaborative systems must be fully secure and encrypted.
Available. Systems must have essentially 100% up-time.
Durable. Data loss is not an option for collaborative information.
These demands are a tall order, and virtually every system we tried failed on numerous points. (Microsoft Exchange fails on almost every one of these demands, and this a premier product from the biggest vendor in the business!) So are we asking too much here? No, and here is why. A small business or office cannot expect to provide 100% availability of web-served data, as this would require outsourced hosting. Any software you can install on your own computers cannot possibly meet the requirements we list. Instead, look elsewhere for a solution.

We have switched to Google Apps to provide our collaborative software. While this is not a FOSS solution, all documents are stored in standards such as IMAP, ICAL, and OpenDoc. Using Google Gears, data can be backed up on local systems and accesssed off-line. Web interfaces work across every system and platform. Google communicates with clients using https security. And while GMail and associated data can be moved to other platforms, now the reverse is also true. Google provides simple tools to import data from proprietary platforms as well, [as is now described on their site](http://googleenterprise.blogspot.com/2010/03/now-its-easy-switch-to-google-apps-from.html).