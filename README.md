# MFOS Noise Toaster


> ##### Forked from *[Tom Obvious][(https://github.com/Tom-Obvious/MFOS-NoiseToaster)]*

## Status

WIP - working out flaws from Tom's design choices

## Motivation

My first eletronics project, like, at all.
This repository is for the documentation of the changes im currently making to the Rev 6.1 of Tom's design, to better fit with at hand materials and more modern/cheaper components.
Components like the 2N5457 or the LM386N-4 arent exactly easy to find or cheap to buy, moving foward id like to do a circuit analysis of Ray's original circuit to determine if i can swap some pieces out for more common components that arent going out of production anytime soon 

## How to use this repository

This repository contains all the files necessary for building the Noise Toaster, including the synth's PCB.  
If you intend to create your own PCB, simply compress all the files located in the 'PCB/Gerber Files' directory into a .zip file and upload it to the PCB manufacturer of your choice.   
In the directories 'classic design' are all files to build the case of the Noise Toaster.    
For the front panels, I also created PCB designs, which you can upload to a manifacturer. Furthermore, there are CAD files and technical drawings (yet to come!) in the folders.   
The 'src' folder contains additional files which might be helpful.

## Project Structure
.  
│  
└── MFOS-NoiseToaster/  
&ensp;&ensp;&ensp;&ensp;│  
&ensp;&ensp;&ensp;&ensp;├── __'src/'__ &rarr; additional files and images that might be helpful for your own build   
&ensp;&ensp;&ensp;&ensp;├── __'classic design/'__ &rarr; all files to build the classic Noise Toaster case   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;├── __'CAD/'__  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── '.FCstd' &rarr; FreeCAD files for the build    
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── __'front panel/'__  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;└── KiCAD files for front panel PCB &rarr; .zip this Geber files for the manufacturer   
&ensp;&ensp;&ensp;&ensp;├── __'PCB/'__   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── __'Gerber Files/'__ &rarr; .zip this directory for upload to the manufacturer  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── *.gbr   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'Noise Toaster PCB.kicad_pcb'  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── ... &rarr; all files for the circuit diagram    
&ensp;&ensp;&ensp;&ensp;├── __'Bill of Material/'__   
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'BoM checklist.md'  
&ensp;&ensp;&ensp;&ensp;│&ensp;&ensp;&ensp;&ensp;└── 'interactive BoM.html'    
&ensp;&ensp;&ensp;&ensp;├── README.md  
&ensp;&ensp;&ensp;&ensp;└── TODO.md  
&ensp;&ensp;&ensp;&ensp;└── licence.md &rarr; CC-BY-NC-SA  

## Usefull links and resources

* [Music From Outer Space](http://musicfromouterspace.com/)
* [MFOS - Noise Toaster - Documentation](http://musicfromouterspace.com/index.php?MAINTAB=SYNTHDIY&PROJARG=NOISETOASTER/NOISETOASTER.php&VPW=1493&VPH=725)
* [Ray Wilson - YouTube Channel](https://www.youtube.com/@Musicfromouterspace)
* [MFOS Noise Toaster Presentation - Video by Ray Wilson](https://www.youtube.com/watch?v=smFKx6gfOd0)
* [Noise Toaster in action - Video by Ray Wilson](https://www.youtube.com/watch?v=qHlyuIe3wuU)
* [Make: Analog Synthesizers by Ray Wilson](https://learning.oreilly.com/library/view/make-analog-synthesizers/9781449356200/)

---
![CC-BY-NC-SA](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

