---
title: "Inexpensive Digital Signage with the Raspberry Pi"
date: 2013-04-08 09:47:38
categories: [Projects]
permalink: /2013/04/08/pi-signage/
layout: post
---
I recently purchased a <a title="Raspberry Pi" href="http://www.raspberrypi.org/" target="_blank">Raspberry Pi</a> after hearing about its potential over the past few months from <a title="Joe Gullo Raspberry Pi Project" href="http://www.surfrock66.com/raspberry-pi-shadowbox-case/" target="_blank">friends</a> and <a title="Lifehacker Raspberry Pi page" href="http://lifehacker.com/raspberry-pi/">tech media</a>.  The Raspberry Pi is a small, inexpensive (<a title="Buy a Raspberry Pi" href="http://www.newark.com/jsp/search/productdetail.jsp?sku=43W5302&COM=raspi-group" target="_blank">currently $35</a>) computer that's designed to be fiddled with.  In fact, it was designed so that parents could afford to give one to their child to learn about computer programming and technology engineering. You see, the device doesn't come with any operating system, you have to install one from any number of sources; a <a title="Linux" href="https://en.wikipedia.org/wiki/Linux" target="_blank">Linux distribution</a>, a home-brewed OS, or you can use the command line to give the device instructions.  Since I'm not a programmer, I went with the "easy" route of finding a pre-built operating system to install.

http://www.youtube.com/watch?feature=player_embedded&v=X9KqdTzvdNA

After looking around on the web for a simple first-project I stumbled upon <a title="Screenly" href="http://www.screenlyapp.com/" target="_blank">Screenly</a>, which is a program for the Pi that is used to manage a monitor/tv as a digital sign. This sparked my interest as I thought it might be fun to give it a shot and write a review of the project for my colleagues in the Higher Ed field, who are always looking for digital signage solutions on a shoestring budget.
<h2>Project kit list</h2>
1. Raspberry Pi & power cable
2. <a title="SD Cards on Newegg.com" href="http://www.newegg.com/Product/ProductList.aspx?Submit=ENE&N=100007962%20600082443%20600006200&IsNodeId=1&Description=SD&name=Secure%20Digital%20High-Capacity%20%28SDHC%29&Order=BESTMATCH" target="_blank">SD Card</a>
3. Monitor/TV
4. Computer and internet connection
5. Ethernet cable
6. USB Keyboard
<h2>Process</h2>
Once I accumulated all of the materials I followed the instructions on the Screenly site to download and install the operating system onto the SD Card, which serves as the hard drive of the Pi.  This part of the project required the most dedication as I needed learn a little about flashing a SD Card.  Because the Raspberry Pi is open source in philosophy, most of its users and documentation is oriented to those who operate in the Linux world.  Since I use Windows I had to find a few small programs that would allow me to unzip the Screenly software and then flash it onto the SD Card.

Once I had the software on the SD Card I plugged it into the Pi and hooked up all of the inputs/outputs (HDMI, ethernet, keyboard, and power).  Once the power was on the Pi started to boot up on my TV and after just about 2 minutes it made it into the start-up screen of Screenly which provides the URL to control the assets that will be displayed on the TV. There is a bit of command line interaction that has to be done, but it was pretty straightforward with the instructions.

Once up-and-running it was simply a matter of using the online interface to control the screen. For about $50, a screen, and 2 hours of computer time I had my very own digital sign.
<h2>Uses</h2>
I can imagine many uses for this simple setup on a college campus.  Menu boards for eateries, directional signage for conferences or meetings, advertising for events, looped video playback of news or sports highlights, and obviously branding. In my college days as the director of <a title="Union Board Films" href="http://www.imu.indiana.edu/board/films.shtml" target="_blank">films for the  Union Board</a> at Indiana University, I would have used it to play looped trailers for upcoming films.

The version of the software that I used was free and open source, however it did have a limit of one screen.  The makers of Screenly are working on a multi-screen management version that is due out soon. There is another software project our there for digital signage called <a title="Concerto" href="http://www.concerto-signage.org/overview" target="_blank">Concerto</a> that seems promising as well.
