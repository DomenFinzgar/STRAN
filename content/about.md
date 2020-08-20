+++
date = 2020-06-16T23:00:00Z
tags = []
title = "About"

+++
Internet is flawed. A once noble idea of sharing has become yet another market-driven technology where twitter is called democracy; the behaviour is monitored, we are becoming products to be sold, discussion impossible, forcing opinion necessary to survive. But you can log off. ll2028ee is a way to log deployment of the process without commercial aim until the year 2028 when things end. It is a way to log off. No way to comment, no way to share, no extra links, no social media, no adds. It is currently on github, but if conditions change it will migrate to whatever community that keeps it free to host and maintain. It is not listed anywhere, so if you came here, you came here by mistake.

I work in the field of Forestry and art and always seek people to collaborate with. I work for projects ([Stripburger](https://www.stripburger.org),[ Klopotec](https://www.klopotec.si/), ...) where I feel accepted and where work is meaningful and not a mean of self-promotion. write to: domen.finzgar@outlook.com

previously:

Everything starts with the phase one. The year is 2028. Deployment of the process initiated. Ideas are forming.

```go

\##################

\#RECORD ALL

\###################

library(reaper) # DAW

library(sounddevices) # recorder

library(FR-RX) #accordion

library(inputdevices) #microphones

library(basictoolkit) #draw, draw, draw

setwd('C:/Users/d/Documents/LL2028EE/record')

surrounding<- read.wav("farigaig_et_al.wav", header=F)

map = openmap(c(lat= 60.12,   lon= -135.30),

              c(lat= 37.30,   lon= -119.09),type= "esri", zoom=5)

OSMap <- autoplot(map.latlon, asp=1)  +

  labs(title = "Location of SS provenances", x = "Longitude", y="Latitude")+

  #geom_label(data=bias.dtf, aes(x=LON ,y=LAT, label=ID, fontface=7), hjust=1, vjust=0, size=4) +

  geom_point(data=farigaig, aes(Long,Lat, color=State), size=4, shape=19)

  #scale_fill_gradientn(colours = rainbow(10)) +

 

 plot(OSMap, asp=1)

\##################

\#QCI <-scratch that!

\###################

\##################

\#WASHINGTON

\###################

```