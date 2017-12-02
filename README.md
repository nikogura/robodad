# Robodad  *Automated Toddler Monitoring*

This is the server side component for a tool I wrote when my twin daughters were about 2.

I ran this off a Raspberry Pi connected to an infared webcam in the nursery.

On the system I ran https://github.com/Motion-Project/motion and masked it so that it was only monitoring the floor in front of the toddler beds.

They could rock out all they wanted in bed, but when they set foot on the floor, it would trigger a recording of Dad's voice saying sternly "**Get in bed!**".

## Implementation

There's an HTTPD instance on the Pi running a little Perl CGI that touched a file to arm/disarm and trigger sounds on command.

I just rediscoverd this code.  It's ancient and crude, but hilarious.

## Results

It worked pretty well... for a while.

I would keep a live window open from my basement office to watch at nap time.  If I'd thought to record the video output, my children would have been an internet sensation.

My girls occupy opposite ends of just about any spectrum you'd like to consider.

Aria, who inherited her father's issues with authority, just flat out refused to comply.  One day I saw her get out of bed, look the camera square in the lens, lift her chin, and pointedly shake her head 'no' as she stomped towards the door.

Lana on the other hand, loves to please, and is rather excitable.  She'd be bopping around the bed until she reached critical velocity and tried to escape, and when the recording was triggerd, she'd leap a foot in the air and scurry back into bed.

One day I found her exploring the boundaries of the motion sensor by dangling her stuffed animal over the side.  First one leg, then two legs.  The little hacker was totally looking for loopholes.  *sigh*

I used to joke that the world was in trouble, because my girls would look like their mother, but act like me.

Well, I was half right.  Lana is the one I warned everyone about.  Aria looks like me *and* acts like me.  Sorry world.  I didn't mean to do this to you.

Eventually Robodad was retired.  My wife could never remember to turn it off before going into the nursery.  She used to joke that I wrote it to order *her* into bed as well as the kids.  If only that worked....

It was fun for a while, and still makes a great story.

