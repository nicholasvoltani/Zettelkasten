---
layout: post
Date: 2022-01-18
title: Subnetting (IP Networks)
tags: []
comments: true
publish: "true"
---

# What is subnetting?
A subnet mask yields which bits in a network IP are already occupied (called the *routing prefix*) and which are available (which are the *host identifiers*). 

For instance, consider the mask 255.255.255.0. (in IPv4, i.e. 8 bits per "number" separated by dots) (Prints below are from the CyberMentor's worksheet for subnetting.)

![082becf704a73df6a15688f718ff37e2.png](/Attachments/082becf704a73df6a15688f718ff37e2.png)

The number in each subnet mask is the **sum of the powers of the active/occupied bits**: when all (eight) bits are active, the sum evaluates to 255 
$$
\sum\limits_{k=0}^7 2^k = \frac{2^{7+1} - 1}{2 - 1} = 255
$$

The backslash notation indicates **how many bits in total are active/occupied** (in the case above, **/24** means that 24 bits are active). 

The number of **total hosts available** in a subnet is equal to **$2$ to the power of the inactive bits** (since each one can either be on/off), although usually the number is actually this total minus 2 (to account for the **netmask address** as well as the **broadcast address**).

## Example
![397f3983d7b34891a55f97e36c2fba61.png](/Attachments/397f3983d7b34891a55f97e36c2fba61.png)
* The mask is 255.255.255.0: thus, only the last part is mutable, while the others are constant (i.e. all hosts will be of the form 192.168.57.x).
* The **netmask address** defaults to 192.168.57.0, the first available host
* The **broadcast address** defaults to 192.168.57.255, the last available host
* The number of free available hosts is, thus, $2^8 - 2 = 254$ 

# Rule for calculating subnet masks from unoccupied bits
Notice that
$$
255 = \sum\limits_{k=0}^7 2^k = 2^{7+1} - 1 = 2^8 - 2^0
$$
is the sum for $8$ **occupied** bits (i.e. $0$ unoccupied bits).

For $1$ **unoccupied** bit, the sum goes to $2^8 - 1 - 1 = 2^8 - 2^1$. For $2$ unoccupied bits, the sum goes to $2^8 - 1 - 1 - 2 = 2^8 - 2^2$ etc.

Thus, for $0 \leq m \leq 8$ **unoccupied** bits, we have the formula for the corresponding **subnet mask's number** 
$$
2^8 - 2^m
$$ 
Notice that it generalizes even for the case of all ($8$) available bits, for which the respective submask number goes to $0$ (!).

# Exercise
![147fd8c62f63cf4be20cd86489d78bae.png](/Attachments/147fd8c62f63cf4be20cd86489d78bae.png)

| Network IP     |              Subnet              |          Available Hosts | Network     | Broadcast     |     |
| -------------- | :------------------------------: | -----------------------: | ----------- | ------------- | --- |
| 192.168.0.0/22 |  255.255.$(2^8 - 2^{22-16})$.0   | $2^{32-22} - 2 = 1024-2$ | 192.168.0.0 | 192.168.3.255 |     |
| 192.168.1.0/26 | 255.255.255.($(2^8 - 2^{32-26}$) |  $2^{32-26} - 2= 64 - 2$ | 192.168.1.0 | 192.168.1.63  |     |
| 192.168.1.0/27 | 255.255.255.($(2^8 - 2^{32-27}$) | $2^{32-27} - 2 = 32 - 2$ | 192.168.1.0 | 192.168.1.31  |     |
	
