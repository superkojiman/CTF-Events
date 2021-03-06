# Defcon Toronto Offline CTF Preparation

**Registration ends November 22, 2016.**
**Save the date!** The CTF takes place on December 3rd, 2016.

DC416 is is happy to announce our second Capture The Flag event. [Capture The Flag](https://en.wikipedia.org/wiki/Capture_the_flag#Computer_security) is a game wherein security professionals and hobbyists compete to solve challenges for which they are rewarded with "flags" that they can submit to earn points for their team. Challenges include:

* [Exploiting vulnerabilities in web applications](https://www.owasp.org/index.php/OWASP_Top_Ten_Cheat_Sheet).
* [Cryptanalysis](http://practicalcryptography.com/cryptanalysis/).
* [Reverse Engineering](https://beginners.re/).
* [Binary Exploitation](https://trailofbits.github.io/ctf/exploits/binary1.html).
* [Steganography](http://steghide.sourceforge.net/).

The team from [VulnHub](https://www.vulnhub.com/) has been working very hard to create high-quality challenges (contained in virtual machine images) exclusively for our event. There are challenges of varying difficulty, ranging from extremely beginner-friendly to more intermediate-advanced challenges. We hope that, no matter your experience, you'll be able to solve some challenges and have a great time.

## Event Venue

The event will be taking place at [Verkspace](http://verk.space), which is [located at 100-32 Britain Street, Toronto, ON M5A 1R6
](https://www.google.ca/maps/place/Verkspace/@43.653916,-79.370617,15z/data=!4m2!3m1!1s0x0:0x2fcf1a874ead22cb?sa=X&ved=0ahUKEwislc3PwqHQAhWq4IMKHdOUAnQQ_BIIdDAP) and begins at **9:30 AM**.

## Registration

**Register soon!** Registration is limited to *ten* participating teams, and we are accepting a waitlist of *five* teams, and registration will be taking place in a first-come, first-served basis.

Teams are allowed to contain up to four members. Because this is an *offline*, remote participation will not be possible.  The registration process is as follows:

1. Finalize your team roster. Your team should ideally contain between three and four people.
2. Decide on a team captain. This person will be responsible for correspondance with DC416 staff.
3. Send an email to ctf@dc416.com containing the following:
   1. Your team name.
   2. The first & last names and aliases (if any) of your team members, as well as each member's email address.
   3. Your team's captain's name and phone number.
   4. T Shirt size for each member based on the following [chart](http://dc416.com/wp-content/uploads/2016/11/sizes.png). i.e. S/M/L/XL

Please note that **any submission not containing all of the information above will be rejected**. You will get an email confirming your registration once our staff reviews and approves.

Registration deadline is **November 22nd**, we will *not* accept new teams after that date.

## Technology

Because this is an "offline" CTF, there are a few steps that are different from other standard CTFs, but we're going to go through everything you need to know.

### Hardware

Because the machines hosting the CTF challenges will be running on a local network, you're going to need a couple of things.

1. An [Ethernet (RJ-45) cable](http://www.bestbuy.ca/en-CA/category/networking-cables/32282a.aspx).
2. An [Ethernet to USB adapter](http://www.bestbuy.ca/Search/SearchResults.aspx?path=ca77b9b4beca91fe414314b86bb581f8en20&query=Ethernet%20adapter) or Ethernet to whatever input your computer supports.
3. You should bring a [flash drive](http://www.bestbuy.ca/Search/SearchResults.aspx?type=product&page=1&sortBy=relevance&sortDir=desc&query=flash+drive) in case any files need to be transferred offline.

Make sure you bring your computer and its charger, too. There will be plenty of power outlets.

### Software

Most of the flags are designed to be possible to be discovered using the tools provided out of the box with [Kali Linux](https://www.kali.org/). You can run Kali on a hypervisor like VMware or Virtualbox, or install it to a flash drive to boot from for the CTF using:

* [Rufus on Windows](https://rufus.akeo.ie/)
* [Unetbootin on Windows, Linux, or macOS](https://unetbootin.github.io/)

Some specific tools you might want to become familiar with:

* [Burp Suite HTTP Intercepting Proxy](https://portswigger.net/burp/) (has a free version)
* [Hopper Disassembler](https://www.hopperapp.com/) (30 minute eval version)
* [WireShark](https://www.wireshark.org/) (is free)

