# Meltdown
Meltdown POC for reading passwords from Mozilla Firefox
This is only for educational purposes. I am not responsible for any loss or damages from the use of this in any way.



How Meltdown Works:
The vulnerability allows user space stuff to read from the raw memory which could include kernel stuff. They get that info by using the speculative execution.

The way they get the info out is by accessing memory at 4k boundries and then they time which cache line is slow. Then from that they figure out what the byte value was. 



Anyways this respitory remains blank until I feel empty enough inside to push the codez :D.
