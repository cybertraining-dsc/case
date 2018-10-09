# Raspbery PI 5 Node Cluster Case

Eliyah Zayin<sup>3</sup>, Diego Ansaldo<sup>2</sup>, Gregor von Laszewski<sup>1</sup>

* <sup>1</sup>Indiana University, laszewski@gmail.com 
* <sup>2</sup>The Academy of Science and Entrepreneurship, diegansaldo@gmail.com
* <sup>3</sup>The Academy of Science and Entrepreneurship, eliyahzayin@gmail.com

TODO: move designs form 

https://drive.google.com/drive/folders/1D8YjtOAh8FemuruPYPWuV4zYNxszW_wN

to this github, only keep final design here.

## Abstract

Why doe we need PI clusters ....

Why do we need a case ...

How do we anticipate the case is used ...

Based on these requiremnts we designing a Raspbery PI Case for five PI's qout of laser cut sheets with the goals of keeping the design as simple as possible, using few parts as do minimize production costs, allowing for easy assembly without screws or glue, while making it structurally sound. Furthermore we  allow reproducability throup open sourcing the design.

To accomodate larger clusters in the class setting a Shelf is proposed in which we *place* the miniclusters while attaching it through a power distribution bar and a large network switch to integarte the individual clusters into the larger cluster.


* case for cluster
* iu course
* case easy to assmple no screws, glue
* easy replicatable
* open source
* modifiable
* integrated into box product
* (integrated into shelf)

## Introduction :o: this is an experinec report or a result, but not an introduction

Our first big hurdle in the design process was desiding on an initial design and learning our modeling program well enough to actually build it. First, we brainstormed a fairly simple first design, then we decided to jump in and start modeling. 
Our program of choice, OpenSCAD took a little time to get used to, because of the program first orientation, but we eventually learned enough to build our first prototype. It was very simple compared to the most current versions now, but all things considered was very impressive, and it had many of the elements still central to our current design. We had two major innovations present in our first prototypes, in one of them, the peg and slot system still used today, and the other, the smaller interlocking pieces used to distribute strain in the case. They had none of the refinements of the newer prototypes, but were a very important and large step in the process. These prototypes started what has been the most used and most important process in the design of the case: design, build, test, analyze, repeat. This process allowed us to rapidly design and test, moving the case closer and closer to completion, removing problems and adressing the requirements along the way.

## Requirements

There were a few requirements presented to us at the beginning of the design process: The cluster had to hold at least 5 Raspberry Pi 3 computers as well as a network hub and a power brick, it could not use any glue to stay together, it had to fully incase all parts while having holes for any ports and ventilation, it had to keep all components secure and safe, and the code had to use only variables to define the parts so any change could be easy to adjust to. While there were other components that would be nice to have, these were the main pieces that had to be incorperated. 

## Design

Laser cut parts utilize 3mm cut-to-size acrylic supplied to IU from https://www.tapplastics.com/product/plastics/cut_to_size_plastic. To ensure that the matterial will fit into the laser cutter, acrylic sheets are ordered with dimentions reduced by a quater inch. Acrylic may come cast or extruded. Choosing cast acrylic will give a higher quality in color and engraving but it is also more expensive.

The list of parts not including the custom made laser cut parts is provided in Table 1.

COMMENT: Not sure what else to put here. Should it be a description of the design process, a description of the current design, or none of the above? Thanks for the clarification.

Table 1: Parts list as copied from <https://github.com/cloudmesh-community/book/blob/master/chapters/pi/case.md>

| Price | Description | URL |
| :- | :------- | :- |
$29.99 | Anker 60W 6-Port USB Wall Charger, PowerPort 6 for iPhone 7 / 6s / Plus, iPad Pro / Air 2 / mini, Galaxy S7 / S6 / Edge / Plus, Note 5 / 4, LG, Nexus, HTC and More | [link](https://www.amazon.com/Anker-6-Port-Charger-PowerPort-iPhone/dp/B00P933OJC/ref=pd\_sim\_107\_70?\_encoding=UTF8\&psc=1\&refRID=B1S6V5G0CTJ9NH5G0CRT) |
$8.90 | Cat 6 Ethernet Cable 1 ft White (6 Pack) - Flat Internet Network Cable - Jadaol Cat 6 Computer Cable short - Cat6 Ethernet Patch Lan Cable With | [link](https://www.amazon.com/Cat-Ethernet-Cable-White-Pack/dp/B01IQWGI0O/ref=sr\_1\_1?s=electronics\&ie=UTF8\&qid=1513699717\&sr=1-1\&keywords=Cat+6+Ethernet+Cable+1+ft+White+\%28+6+Pack+\%29+\%E2\%80\%93+Flat+Internet+Network+Cable+\%E2\%80\%93+Jadaol+Cat+6+Computer+Cable+short+-+Cat6+Ethernet+Patch+Lan+Cable+With\%E2\%80\%A6) |
$19.99 $^{(1)}$ | D-link 8-Port Unmanaged Gigabit Switch (GO-SW-8G) | [link](https://www.amazon.com/D-link-8-Port-Unmanaged-Gigabit-GO-SW-8G/dp/B008PC1MSO) |
$10.49 | SanDisk Ultra 32GB microSDHC UHS-I Card with Adapter, Grey/Red, Standard Packaging (SDSQUNC-032G-GN6MA) | [link](https://www.amazon.com/SanDisk-microSDHC-Standard-Packaging-SDSQUNC-032G-GN6MA/dp/B010Q57T02/ref=sr\_1\_10?s=pc\&rps=1\&ie=UTF8\&qid=1498443283\&sr=1-10\&refinements=p\_85:2470955011,p\_n\_feature\_two\_browse-bin:6518304011,p\_n\_feature\_keywords\_two\_browse-bin:5947557011) |
$8.59 | Short USB Cable, OKRAY 10 Pack Colorful Micro USB 2.0 Charging Data Sync Cable Cord for Samsung, Android Phone and Tablet, Nexus, HTC, Nokia, LG, Sony, Many Digital Cameras-0.66ft (7.87 Inch) | [link](https://www.amazon.com/OKRAY-Colorful-Charging-Samsung-Cameras-0-66ft/dp/B00R5GZJR6/ref=sr\_1\_6?s=pc\&ie=UTF8\&qid=1498447476\&sr=1-6\&keywords=micro+usb+cable+1ft) |
$7.69 | 50 Pcs M2 x 20mm + 5mm Hex Hexagonal Threaded Spacer Support | [link](https://www.amazon.com/20mm-Hexagonal-Threaded-Spacer-Support/dp/B00FH8AB8Q/ref=sr\_1\_9?s=industrial\&ie=UTF8\&qid=1513700337\&sr=1-9\&keywords=hex+spacers+m2+20mm) |
$7.99 | Easycargo 15 pcs Raspberry Pi Heatsink Aluminum + Copper + 3M 8810 thermal conductive adhesive tape for cooling cooler Raspberry Pi 3, Pi 2, Pi Model B+ | [link](https://www.amazon.com/Easycargo-Raspberry-Heatsink-Aluminum-conductive/dp/B07217N5LS/ref=sr\_1\_3?s=industrial\&ie=UTF8\&qid=1513700498\&sr=1-3\&keywords=raspberry+pi+3) |
$34.95 | 5 * Raspberry Pi 3 Model B+ Motherboard | [link](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/) |
$6.99 | HDMI Cable, Rankie 2-Pack 6FT Latest Standard HDMI 2.0 HDTV Cable - Supports Ethernet, 3D, 4K and Audio Return (Black) - R1108 | [link](https://www.amazon.com/Cable-Rankie-2-Pack-Latest-Standard/dp/B00Z07XQ4A/ref=sr\_1\_6?s=wireless\&ie=UTF8\&qid=1513782649\&sr=1-6\&keywords=hdmi+cable+6ft) |

(1) items were replaced with similar


## Alternatives

There were a few alternatives we looked into for creating the case before settling on the current solution.

* This program creates basic boxes based on any dimension provided by the user.
    - https://www.festi.info/boxes.py/

## Manufacturing Facilities

Most of our testing and production of cases were conducted at the maker space at Luddy Hall of IU's School of Informatics and Computing Engineering. Luddy Hall has two laser cutters, both from Trotech; the Speedy 360 and the Speedy 400. The 360 has a 813x508mm bed while the 400 has a 1000x610mm bed. For our chosen matterial, acrylic, the machines can cut for matterial thicknesses less than 6mm.

## Converting the Design for Laser Cutting

To produce a phyisical copy of our prototypes, we could not simply use the file in it's SCAD format. To ready the design for laser cutting, we first hav to export the file as a SVG. One this is done, the file can be edited in a graphic design program, such as Adobe Illustrator. Edits reqired to prepare the design include the removal of the interior fill color of the case components and adjustment of the edges for cutting. The laser cutter is preset to cut along red lines with a low thickness. For the prototypes, we used a 0.03 point thickness.

The design must also be correctly scaled to the right size. So far, we have achived the corect scaling by finding a feature within the design and find the correct scale factor by measuring it. We are currently considering the posiblity of using the size of the rectangle the case fits into; this should speed up the process, since the dimentions can be viewed in Illustrator by clicking on the artboard tab on the right vertical tool bar and selecting the artboard setings button. Once the design is appropriatly scaled, the artboard must be scaled up as well.

Once all editing is done, the design can be cut. This can be done by selecting the print option in the graphic design program and clicking on setings, in Illustrator, this can be found in the lower left corner of the main print window. If the laser cutter is not selected as the printer, it will need to be selected. The dimentions in the print setings will also need to be adjusted if they are smaller than the size of the design; in Illustrator, the size can be changed under preferences, which is located directly beneath the printer selection. The setings window can now be closed and the "print" button on the main print window can be selected. This will send the file to the laser cutter as a job.

## Product

Here is the progression of our design, from the first prototype to our most recent model. 

COMMENT: Not sure if I should put anything else in this section

* box with stuff in it

![Prototype 1](images/prototype1.jpg)

**Figure 1:** Prototype 1

![Prototype 2](images/prototype2.jpg)

**Figure 2:** Prototype 2


## Future work

We will continue to work on the current design, but it is nearing completion, and we have a few more related projects for the future:
* 19 inch rack for 40 nodes via bitscope, <https://www.festi.info/boxes.py/Rack19Box>
* Shelf for 5 Pi cases.

COMMENT: Should I add more here?

## Refernces

* Other cases are at <https://github.com/cloudmesh-community/book/blob/master/chapters/pi/case.md>


