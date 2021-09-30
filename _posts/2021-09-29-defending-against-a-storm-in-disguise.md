---
title: "Defending against a storm in disguise"
date: 2021-09-29T10:00:00-00
share: false
tags:
  - story
header:
  teaser: "/assets/img/defending-thumbnail.png"
---

![thumbnail red and blue](/assets/img/defending-thumbnail.png)

Every once in a while, a security issue comes along that requires urgent attention. At those times, everything comes together in a perfect storm: a large attack surface, ease of exploitation, a lack of a ‘quick fix.’ These are the kinds of vulnerabilities where you can feel your stomach drop while reading the security advisory. The ones where you know you can drop your plans for today. When such a storm starts to arise, network defenders will have to start running to investigate how to prevent, detect and respond against the newly discovered threat.  

Typically, word of such a storm will slowly but surely creep its way through the grapevine. Security aware users are asking if they are protected. Managers want to hear about the progress that is being made to mitigate the risk. Threat Intelligence starts to sip in that a wave of attacks might be coming soon. At this point, defenders are well up to their knees into the nitty gritty details of the attack surface, the traces that can be used for detection and the available indicators of compromise. 

When the pressure starts building, it can be tempting to start checking off boxes quickly. “This measure has been taken, so we are safe now”. “We deployed new detection, so we would see the attack coming from a mile away”. “We found no trace of compromise, our network is clean”. While this temptation is understandable, its dangers are abundantly clear. Celebrate too early and your party might be bluntly interrupted by an attacker that did things differently than you had expected. 

The creativity of attackers continues to surprise and frustrate defenders worldwide. These hackers find new ways to bypass your prevention, they impersonate legitimate activity to the best of their ability, and they delete forensic artifacts to cover their tracks. Especially during the ‘perfect storms’, the attackers have the upper hand. Defenders need help to even the odds.

This is why offensive security is such a big part of defense. Red teamers, ethical hackers, white-hat hackers, whatever name you have for them: you need them. They approach these storms differently. Their eyes are not faced outwards to the threat. They think like the attacker, and their eyes are faced inwards: they focus on getting in, not on keeping others out. They know how they can use this storm to their advantage, and will be keen to get their hands dirty with this newly found piece of weaponry. 

Recently, a severe vulnerability was found that was exploited by malicious actors ‘in the wild’. I was tasked with creating detection for exploitation, and started working right away. In a short period of time I had developed four different ways of detecting the attack. I am quite new in the field of detection engineering, so I proudly presented my work to the senior engineers in the team. Then came a question I should have seen coming: did you ask red team to give it a go? I reached out to one of our ethical hackers, confident that my detection would catch their efforts easily.  

On the attacker’s first try, all alarms went off. I couldn’t help but smile. Only five minutes later, two of my alarms were bypassed. While I wasn’t smiling anymore, I thought to myself “no way they can get past my last two, right?” An hour later, the attacker had slipped through all my defenses unnoticed. While being annoyed by my defeat, I also noticed that these evasive maneuvers had left new traces behind. I had lost the battle, but not the war. While I had fallen pray to the red teamer, I was now in the role of hunter again. This game of back and forth continued, and together we arrived at detection that got the job done. While this practice is commonplace in our detection engineering process, this was a first for me. Let me tell you: the advantages are best observed when you experience them firsthand.

Collaboration between offensive and defensive security specialists is key during perfect storms. A defender might be focused on taking measures quickly before it’s too late. An attacker will ensure that defenders don’t go celebrating too early. Where attackers may know different ways of attacking, defenders know where to look for the fingerprints that are left behind. 

In the eye of the storm, attackers and defenders should combine forces to protect against the real enemy that is sure to come. Combined, they can optimize both the speed and the coverage of defense, and look cool while doing it. Bring your attackers and defenders together now, because the next storm is always coming. 


> I want to read your mind<br>
 To know just what I've got<br>
 in this new thing<br>
 I've found<br>
  \- Bruce Springsteen, Brilliant Disguise
