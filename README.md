# Information

This challenge is a bit more difficult. 

First it is given to you an image. After opening the image I noticed that there could be a password or buch of numbers that could be used.
(3,1,2,5,5)

So, I used the steghide command to see if there was some message to extract from the image. 
steghide extract -sf cat.jpg

But nothing was extracted...

So, in order to look at the details of the image I load the image at the image metadata.

When I opended it I noticed that the licence looked different to the normal, so I reckoned that could be some code.

Finally I used the code in bas64 decoder and it gave me the flag!
