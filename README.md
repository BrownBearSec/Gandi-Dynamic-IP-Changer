# Gandi-Dynamic-IP-Changer
Changes the DNS record of your Gandi domain to fit your ever changing Dynamic IP, when you dont have a static one.

After coming across the issue of my public IP changing and me also not wanting to buy a £50 router to get a static IP I have made this, I hope it can be of use to anyone else too.

The program must be edited slightly to fit your domain, instructions for this are commented in the code.

If you are running you're website on a Raspberry Pi, like myself, I reccomend putting this file in the /boot directory so that in the case of a powercut the website will be up as soon as possible and there will be less maintenance
