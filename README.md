# Event-Resources

## Capture the Flag (CTF)
With our promotion of the upcoming redpwnCTF 2021, we have put together a collection of CTF resources. The point of this repository is not to give you the best guide of everything CTF related, but to simply point you in the right direction so you have all the tools you need to tackle any challenge and have links to some of the best learning resources so you are not wasting your time. Likewise, in most cases during a CTF you will need to do your own research and googling to help you find a solution. Part of what makes a good CTF player is how well they can research the problem (since no one can be an expert at everything) and adapt the information online to be used in the context of the problem they are trying to solve.

Competing in CTFs is not only a personally rewarding experience, but will also help you immensely in your future studies and career if, and only if, you **apply yourself**. 

### Tools (set these up before you try learning)
* Python 3 - Used for scripting e.g., automating web or pwn attacks using pwntools
* pwntools - A Python library that simplifies the process of writing pwn or web exploits. Installation details found at https://docs.pwntools.com/en/stable/install.html.
* Kali Linux - A Linux distribution designed for pentesting. Download the ISO at https://www.kali.org/downloads/ and install it using VMWare. Don't forget the Murdoch gives all students access to VMWare Pro Workstation. There are plenty of guides online detailing how to install Kali Linux using VMWare, so I won't go into detail here.
  * Comes preinstalled with many useful tools that you will use regularly in CTFs including (I will leave it up to you to research these):
    * Burpsuite
    * base64
    * Wireshark
    * binwalk
    * sqlmap
    * volatility
    * edb debugger
    * ollydbg
    * and more

* Docker - Used to setup your own instances of challenges locally. Find more details about how it is used at https://www.youtube.com/watch?v=cPGZMt4cJ0I
* https://github.com/apsdehal/awesome-ctf/blob/master/README.md - **has a more complete list of tools for each category of challenge**

### Learning Resources
CTF challenges are typically broken down into the following categories:
  * Pwn - Binary exploitation - pretty much figuring out how to get an executable file to execute some sort of code that you want (e.g., buffer overflows, ROPchains etc.)
  * Reversing - reverse engineering an executable file
  * Web - web-based attacks .e.g, SQLi, XSS, etc.
  * Cryptography
  * Forensics - typically involve looking through packet captures, memory dumps, or reverse engineering some form of malware
  * Misc - miscellaneous challenges that don't fit into any category specifically
The following sections will list the links to some of the most useful learning resources we have personally used, or otherwise have heard to be very useful for each of the respective CTF categories. Where possible, try to get your hands on the challenge files and follow along to the writeups.

#### Pwn
* https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN - LiveOverflow playlist of binary exploitaiton/reversing
* https://trailofbits.github.io/ctf/exploits/binary1.html - basic binary exploitation guide
* https://ropemporium.com/ - ropchain exercises (many guides and walkthroughs available online e.g., https://www.youtube.com/watch?v=oBZy0bGNezo&list=PLHUKi1UlEgOKAVRdiMlpX6hgayiY6dTwu)
* https://www.youtube.com/watch?v=6DRuT1JBmBE&t=1491s - writeups for HackTheBox Cyber Apocalypse 2021 Pwn challenges
* https://www.youtube.com/watch?v=yH8kzOkA_vw&list=PL1H1sBF1VAKVg451vJ-rx0y_ZuQMHPamH - John Hammond's binary exploitation playlist

#### Reversing
* https://malwareunicorn.org/workshops/re101.html - Intro to reversing (explains basics of program, assembly and stacks)
* https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN - LiveOverflow playlist of binary exploitaiton/reversing
* https://www.youtube.com/watch?v=z4lgNNaCH3s - writeups for HackTheBox Cyber Apocalypse 2021 Reversing challenges
* https://github.com/N4NU/Reversing-Challenges-List - list of reversing challenges from various past CTFs

#### Web
* https://pentesterlab.com/exercises/web_for_pentester/course
* https://pentesterlab.com/exercises/web_for_pentester_II/course
* https://portswigger.net/web-security - learn basic web attacks
* https://www.youtube.com/watch?v=vqR4i730soY&t=954s - writeups for HackTheBox Cyber Apocalypse 2021 Web challenges
* https://www.youtube.com/watch?v=S2mQBXcW3P0&list=PL1H1sBF1VAKX9Mz0UVU2eR7EdGmtb5XJK - John Hammond's web playlist

#### Cryptography
* https://cryptopals.com/ - guide on all things crypto with exercises
* https://cryptohack.org/ - crypto learning platform
* https://www.youtube.com/watch?v=Wku6uEOAGIc&t=1023s - writeups for HackTheBox Cyber Apocalypse 2021 Crypto challenges
* https://www.youtube.com/watch?v=p__QZIxjHMk&list=PL1H1sBF1VAKU05UWhDDwl38CV4CIk7RLJ - John Hammond's playlist for cryptography challenges

#### Forensics
* https://www.youtube.com/watch?v=f0PEr6I27To&t=1251s - writeups for HackTheBox Cyber Apocalypse 2021 Forensics challenges
* https://www.youtube.com/watch?v=iQxLsURS1Mo&list=PL1H1sBF1VAKVPNh6Q8k1fpU97vhJc_c45 - John Hammond's forensics playlist
* https://www.youtube.com/watch?v=I-HQJPoTZSc&list=PL1H1sBF1VAKV6rTEh76pxQKgeFwme5gsT - John Hammond's steganography playlist

#### General Learning / Learning Platforms
* PicoCTF - https://picoctf.org/resources
* HackTheBox (challenges section) - https://www.hackthebox.eu/
* OverTheWire - https://overthewire.org/wargames/

### Where to Start if You Are Completely New to CTFs
1. Create an account on PicoCTF and work through a few challenges from each category to get a general idea of how a CTF operates
2. Move on to learning category specific skills found under the **Learning Resources** section. Choose any categories that you are interested in and focus on a few categories, rather than trying to learn them all in-depth at once.
3. Practice past CTF challenges and watch/read walkthroughs if you are really stuck. See:
  * redpwnCTF 2020 past challenges - https://github.com/redpwn/redpwnctf-2020-challenges (setup locally with Docker)
  * redpwnCTF 2020 writeups https://ctftime.org/event/995/tasks/ (also probably some videos on YouTube)
  * https://github.com/DownUnderCTF/Challenges_2020_public - DownUnderCTF 2020 challenges and writeups
  * Past HackTheBox Cyber Apocalypse 2021 challenges - ask around in their discord to see if someone has a repository of downloadable challenges from the event https://discord.gg/hackthebox . There are plenty of writeups for this CTF online if you search on Google.
  * https://github.com/mitre-cyber-academy/2018-ctf-game - Dockerfiles and writeups for the 2018 Mitre CTF
  * https://www.cyberchallenge.com.au/2018/index.html - Downloadable challenges and solutions from the 2018 CySCA CTF

### Further Questions
If you have any further questions regarding how to go about these CTFs, feel free to message me as I am also in the MITS discord. If you want to contact me directly, my username is jc#5897, otherwise just pop a message into the cybernet-general chat and I am sure that either myself, or one of the many other people in the Discord familiar with CTFs will be able to help.

Happy hacking and good luck :)



## Coding Hackathon
