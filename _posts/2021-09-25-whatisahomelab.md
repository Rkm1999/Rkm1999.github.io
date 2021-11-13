---
title:  "What is a HomeLab"
excerpt: Introducing purpose a homelab

toc: true
toc_sticky: true
 
date: 2021-09-25
last_modified_at: 2020-11-09
---


# What is a HomeLab

While I study for CCNA, I got to point where I needed a lab. Either physical or virtual. There is advantage and disadvantage to both physical and virtual lab. 


## Virtual Lab

Virtual Lab is a simulator that allow to have interactive learning without a physical device. Their are few popular tools allow you to build a virtual lab. For example [GNS3](https://gns3.com) and [Cisco Virl](https://learningnetworkstore.cisco.com/cisco-modeling-labs-personal/cisco-cml-personal) is most popular tools in industry. 

### Pros

Pros to have a virtual lab is you can save cost. With a physical lab you need to buy all of devices to build a lab and it can go out of budget very quickly. And with virtual lab, you can expand it as much as you want until your PC can handle it.

### Cons

Cons of having a virtual lab is their could be a bug that only appear on virtual lab. And it is hard to configure it first time. And lack of hand on experience could lead you to problem when you need to do something hands on. Finally, copyright problem. if you will use [Cisco Virl](https://learningnetworkstore.cisco.com/cisco-modeling-labs-personal/cisco-cml-personal), it is Cisco's officail virtual lab, so you are free from copyright problem. But, if you will use [GNS3](https://gns3.com), then you probably have trouble with copyright. And it is not officaily supported by Cisco, so you will have to find all roms to build virtual lab.


## Physical Lab

Now, let talk about physical lab. Physical lab is lab built with actual enterprise equipment. If you are wealthy enough, you could buy latest brand new equipment. But nomally, most of us aren't wealthy enough and vandors usually don't sell it to individual. So normally, we buy second hand enterprise equipment from ebay or craigslist. They are usually near EOL or passed EOL but they are very cheap considering brand new price. Usually, second hand switches cost around 50-120 CAD and routers cost around 90-170 CAD. They are passed EOL, but it is upto date for CCNA study.

### Pros

So, what are the pros to use physical lab over virtual lab. First, hands on experience. Yes you can do most of stuff on virtual lab. But it doesn't mean you can do everything. With physical lab, you can do actual cabling to set it up, know what port is where and what that switch is will help you when you get into industry. Another benefit is you can implement your lab into your home network. With virtual lab, when you finish with a lab objective, you just turn it off when your done. But when you have your homelab implemented to home network, you can do real world hands on experience. You don't know what will happen to it and playing around with it will help you understanding how network works.

### Cons

Now, cons of having physical lab. If you try to build physical lab, it will cost alot more than virtual lab. With CCNA, it is idle to have 3 switches and 3 routers. Normally, switches cost around 50-120 CAD and routers cost around 90-170 CAD. That means if you want to setup idle lab, it will cost you around 420 CAD to 870 CAD. And that is only cost for network equipment. You will need ethernet cables, server rack, power outlet, ect. So total cost will be around 500 CAD to 1000 CAD. And enterprise equipment are not meant to run in home environment, so it will consume alot of power, generate heat, and it is very loud.


## Conclusion

So, conclusion. Do you need a homelab? If you want to improve your self with hands on skills, definitely yes. What lab should you choose? Well.. it depends on your budget. If you are tight on budget, than you better go with virtual lab. If you have enough, than you can go with physical lab if you want. I went with physical lab because I wanted to have real world experience with homelab implemented to my network and I like to do something with hands on experience. In future article, I will post what equipment I used, what design I used and how I built one. Thank you for reading and I hope it was informative for you