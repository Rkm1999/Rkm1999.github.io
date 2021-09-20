---
title:  "How I study for my CCNA
"
excerpt: What meterials I used to study CCNA

toc: true
toc_sticky: true
 
date: 2021-08-19
last_modified_at: 2020-08-29
---


# Study guide

When I started study with CCNA, First study meterial I used was [CCNA 200-301 Official Cert Guide](https://www.ciscopress.com/store/ccna-200-301-official-cert-guide-library-premium-edition-9780136755494). I used that because I dind't know anything about it so thinking

>Official guide should teach you everything you need. Let's go with it.

Well.... that was not good idea. First few topics were okay. But when I got into VLAN, I didn't know what to do. It showed me a theory, but I didn't understand those commands. It says used this command but why that? why not that one. So, I decided to look for another study guide. 


## CBTnuggets

I searched up and found out [CBTnuggets](https://www.cbtnuggets.com/home) have one of popular study guide <del>Also found out official guide isn't that useful</del>. It give you 1 week trail so I tried it and it was awesome. It give you videos to study so you can do on your on pace and shows how many hours left so you can track how far you went. 


### Study environment

So I carried on with it and while going threw, it showed me 2 way to set up environment for study. One way was using virtual machine to build virtual lab such as [GNS3](https://www.gns3.com) or [CISCO VIRL](https://learningnetworkstore.cisco.com/cisco-modeling-labs-personal/cisco-cml-personal). Another way was using actual enterprise equipment and build lab with it. 


#### Physical lab

I chose to go with physical lab because I like handling actual physical device and I was thinking to implement those equipment to my network and play with it .Of course I'm not buying brand new equipment. Those thing start from few thousands dollars to tens of thousands dollars. But ones that are retiring from enterprise are dirty cheap compare to brand new. And it is enough to study for certification.  


##### My equipment

For the equipment, you will be fine with 1 router and 1 switch. you will get to use all of commands but you will be lack of ospf, vtp, cdp, lldp, ect. So my recommandetion is get 3 router and 3 switch. I'm going to implement it my network so I'm going to need least 1 router capable of 1 Gigabit. I looked on craigslist and found one 2960-S, two 3750-X, two 2811 and one 2801. I know that 2811 and 2801 does not handle Gigabit NAT, but it was closest thing I could get so I went with it. And bought some dump switch to create private WAN and server rack to keep it safe.


## ExSim-Max

So I got study guide and equipment ready. I'm ready to pass test, right? Actualy, no. I book for first test and I got score 772 but passing score was 825. I knew most of topic and know how to set it up, but questions were not what I thought it would be. What I thought was more right if you know it show how you do it. It was used to be right that, but they changed to did you memorize it. They even had a question asking which tab do you go to set this in GUI. What a dumb question, **YOU JUST NEED TO GO ANOTHER TAB IF IT DOESN'T HAVE IT**. They changed to that way because 