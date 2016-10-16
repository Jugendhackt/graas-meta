# GRaaS

This is the Meta-Repository of GRaaS. It is a repository of repositories, what else? A Meta-Repository. GRaaS stands for Geiger radiation  counter as a service. Since the buzzwordbingo in the description of the single repos is not realy helpful to understand the purpose of this repo, this readme should help you getting the idea of it.
##Idea
With GRaaS we bulid a device with a [Geiger-Müller counter](https://en.wikipedia.org/wiki/Geiger_counter), a Raspberry Pi and a GPS module.
The Repository for the firmware can be found [here](https://github.com/Jugendhackt/graas-firmware)

This device is sending json over http to a frontend, wich can be found [here](https://github.com/Jugendhackt/graas-backend). The json contains a timestamp, the current GPS location and the radiation.


On our [Website](https://github.com/Jugendhackt/graas-frontend) you can a leaflet map with a heatmap, displaying the data.
