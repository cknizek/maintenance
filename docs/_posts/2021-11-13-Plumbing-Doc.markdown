---
layout: post
title:  "2021-11-13-Plumbing-Doc"
date:   2021-11-17 15:46:09 -0800
categories: jekyll update
---


### Model number encoding
~~~
ABCCDDEEEE
1. <A> is the current wing. A valid value is <W>, <C>, or <E>. See Reference Table A.
2. <B> is the current floor.  A valid value is <0>, <1>, <2>, or <3>.
3. <CC> is the bathroom number. This number is located on the door frame to the bathroom.
3. <DD> is the type of plumbing component or fixture. See Reference Table B.
3. <EEEE> is the serial number of the plumbing fixture. A valid value is any unique integer in the range 0-9999 that is one value higher than the most-recently added serial number. 
   This implies that, given there are 322 serial numbers assigned, this value will be 323. The next plumbing component you tag will have the value 324. And so on and so forth.
>>> Example: W112SH0001 = <W><1><12><SH><0001> 

Reference Table A
W <-> West
C <-> Central
E <-> East

Reference Table B
SI <-> Sink
TO <-> Toilet
SH <-> Shower
~~~
