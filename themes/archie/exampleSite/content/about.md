+++
date = 2020-06-16T23:00:00Z
tags = []
title = "About"

+++
Everything starts with the phase one. The year is 2028. Deployment of process initiated. Ideas are forming.


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

