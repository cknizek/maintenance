---
layout: post
title:  "2021-11-17-Plumbing_Map"
date:   2021-11-17 15:46:09 -0800
categories: jekyll update
---
### Stages
# Phase 1
##### What to do
In each bathroom in Cloyne, the sink, toilet, and shower shall be labeled using the encoding below. If the bathroom has a bath, label that instead. 
* You will accomplish this by installing the Dymo Connect app. 
* You shall create a way to log completed labels. I'd recommend a spreadsheet or a text file. It doesn't need to be fancy. Whatever you decide, you'll need to update it in your crew folder every shift.
* Then, you'll use the Dymo MobileLabeler to consequently print labels as you encounter untagged plumbing component or fixtures. 
* The labels shall be placed in a location such that they adhere permanently. 
* Before you place the label, clean the surface with isopropyl alcohol, and then wipe it with a microfiber cloth until dry. 
* Then, carefully place the label against a location such that the label is; (i) clearly visible; (ii) as flat and/or homogenous as possible; (iii) relatively unexposed to sources of degradation. 
* Once you have placed the label, take a photo of the placed label. Add this photo to your crew folder. Update your log of completed labels.

##### What not to do
An example of (iii) would be if you placed the label inside the sink. An example of violating (ii) would be placing it *on* a drain cover. An example of violating (i) would be placing a label in a location that isn't immediately visible within 5 seconds. Additionally, make sure that the label placement is consistent.


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
BA <-> Bath
~~~
