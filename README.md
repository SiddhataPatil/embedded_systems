# embedded_systems

As we all know, an  Embedded System is a device that is made to carry out a particular output
and just a general purpose task like our PC. Do not confuse Computers and Embedded Systems.

In Embedded Systems, there is a program that you feed to a CPU (microprocessor/ microcontroller)
which than gives us the desired output. This firmware is not for the user to manipulate or change.
An Embedded system may or may not have an Operating System.

For example. Your SmartWatch. Let us say it has a Linux Kernal. On top of it there is a Hardware
Abstraction Layer and on top of it there is Android 4.4 operating system. It needs all this 
layers because it has to carry out a number of more sophisticated tasks. Now consider, a microwave
oven. It has to carry out few simple tasks. Why to complicate it by putting an Operating System on 
it when we can do this simply by writing few lines of code. Just flash this firmware on it and all done!

How to decide, the firmware goes in what. Whether to use a microprocessor or a microcontroller?
Microprocessors are good for performing tasks that need lot of computations, complicated mathematical 
calculations and lot use of graphics.  While microcontrollers are good where you need strong IOs such as
interfacing sensors, motors etc. To make it simple, Microprocessor (x86) are used in your computers
and Microcontroller (ARM Cortex A57) are used in your smart phones.

This gives rise to a term called 'SOC' - System on Chip now we also have something known as 'SIP',
for Wearables. 
A little about me, I am passionate about Wearable Technology. When I was in School,
wearable was the reason I did both my internships in Wearable Technology domain. My first internship
was at Nixie Labs, Nixie is a wearable flying camera and was winner for Make it Wearable challenge 2014
by Intel. My summer inernship was at Olio devices. It is Smart watch company based in San Francisco.
Coming back to SOCs. 
SOCs have CPU, GPU, FPU, DSP, etc. on a single chip. 
Lets talk about cores.. I can talk for ages on this topic

Let us consider you have to buy a new laptop. How do you select a CPU in it.
Quite frankly, half of the customers actually go with their favorite brand (Intel vs AMD).
By the way, just a fun fact: AMD was the first to come up with a 64 bit Microprocessor.
Many of us actually tend to believe, more the clock speed faster is the computer.
Which is not completely true, there are so many other factors that needs to be considered,
such as memory latency, IPC ie Instruction per cycle, Power consumption and many other factors.

Let us talk about Smartphones, you are having one right now not more than 2 feet away. 
As we saw in Laptops world the two big names where Intel and AMD. In smart phone world there is 
one big name and that is ARM. Now ARM does not have a fabrication plant like Intel, so what it does
is, it parteners with compinies like Apple, Samsung, Qualcolm, Hwawei etc. and sell their licences.
There are two main types of licences, one is the core licence (use A53 or A 57 as it is or making one 
core run at a lower frequency than the other) and then there is something known as the architecture 
design licence (where you actually modify the architectures).
This thing gave rise to a term called ' Custom Cores '. In April 2008, Apple acquired PASemi and 
together came up with the first 32-bit custom core called Swift which they introduced in iPhone 5
in September 2012. Exactly a year later, September 2013, Apple came up with their first custom 64-bit 
Microcontroller A7, Cyclone which they introduced in their iPhone 5s. In June 2013, Qualcomm had 
announced Snapdragon 801 which was 32 bit. Then later in April 2013, they released Snapdragon 808 and 810,
which are 64 bit. This was done by using  four cores of Cortex A53 and four cores of cortex A57 
(i.e. using these cores and not actually a custom core). Qualcomm came up with their first 64 bit custom core 
Snapdragon 820 (14nm), called Kryo CPU and released it in November 2015 and its first smart phone was launched in 
Jan 2016 during the CES. Samsung came up with their first custom 64 bit CPU in their famous Exynos SOC (14nm) series
early 2016 and its called the Mongoose. They released it with Samsung Galaxy S7 just last month ie August 2016.
So we were talking about Apple, In 2016, when Qualcomm and Samsung are out with their 1st gen of 64 bit custom cores,
Apple is out with its 4th gen custom core ie A10 (14nm) and launched it in iPhone 7 just two days ago i.e. early
September last week i.e. early September 2016. 

So as we can see, there is so much competition in this domain, literally pushing each other to acheive great goals,
But then there lies a great question, all this hype about 64-bit. For a 32 bit microcontroller it can access upto
2^32 i.e. 4GB, while for a 64-bit microcontroller it can access upto 2^64 i.e. 16 EXA bytes. Trust me thats a lot.
Are you really going to use that much memory on your phone?

-Siddhata Patil

P.S. I am here just stating some fun facts, I am not in favor of any company! I am a core Android user myself ! 
I am just plain excited to be witnessing all this technologies growing every single day right here in the Silicon Valley.
