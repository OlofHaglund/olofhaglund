---
layout: post
title: "Juice Jacking a Real Threat or Scaremongering?"
description: "Juice Jacking a Real Threat or Scaremongering?"
categories: [Security]
tags: [Security, Mobile]
redirect_from:
  - /2023/06/15/
---

# Juice Jacking a Real Threat or Scaremongering?
The last couple of months' discussions of Juice Jacking is a real threat or not have sprawled up again. Juice Jacking has been discussed a couple of years ago but died off until this year when the FBI went out with a warning to use phone charging booths and USB ports in airports, hotels, and other public spaces. The discussion online in the security community has been if it is a threat to actually be afraid of or not. So far as I have seen people disagree over it so I have decided, a bit late to the party, to give my opinion on this topic. So I brewed some tea, sat down, and philosophized a bit. Discussed a bit with my colleagues and then brewed some more tea. Late to the Juice Jacking party but here we go.

![Glass of juice]({{site.url}}/assets/images/Juice.jpg)

Three things are needed for a juice jacking attack to be performed.
- A vulnerability in the devices being charged.
- A malicious charging station.
- A victim that will use a malicious charge station.

If we start with the first one, an external device should not without permission be able to read or install data on your device. This means an attacker would need access to a valuable zero-day to use. Since some law enforcement pays good money for those vulnerabilities the targets you intend to use the exploit on need to be of more value than selling the exploit.

The second point is that they need a malicious charging station for the victim to connect to. To get any volume out of the exploit the charging station would need to be in places where people are likely to sit and wait, also enough amount of people to use it before anyone notices the exploit and shuts it down. Compared to other types of vulnerabilities that can be performed over the internet, juice jacking doesn't scale very well.

Since it doesn't scale very well another type of victim would instead be high-valued targets such as politicians, journalists, or political activists. A combination of a high values target and threat actor that isn't after money but leverage or state secrets might have the interest and means to pull this off when other attacks haven't worked out. Journalists visiting and covering a larger event like the Olympic Games or the like might also be of interest to a dubious government. But then, why replace charging stations with malicious ones when you just can take a lesson from North Korea and give a USB-powered fan in a gift bag to all journalists. Seems cheaper and easier to pull off.

Now the third point is a victim using a malicious charge station. We are those victims and here is the question that we all want answered. Should we or should we not use a public charge station? I would say for the majority of the people it is probably fine to use them. For people of some kind of status, there might be a small risk to it. But then the protection to this is quite simple and a more agile way of doing it, just use a power bank. If you are out of juice in a power bank, then you can charge that one from the public USB and then charge your phone from the power bank.

Welcome to Olof is philosophizing with some tea and hope you enjoyed it. I want to finish off with a quote that I found funny reading about juice jacking in social media.

> For juice jacking to work there has to exist a zero-day in the phone and should therefore be fixed by Apple and Google.

(The quote was taken from memory and not 100% worded correctly)

Well... Yeah... that's kind of the thing about zero-day. They don't exist until poof there it is and everyone scrambles to hopefully fix it before someone exploits it.
