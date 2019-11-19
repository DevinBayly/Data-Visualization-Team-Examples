# Drop in Offerings

## Maptime: making 3d landscape models

This section covers the potential offerings of a Maptime session. The session will roughly comprise of collection of USGS shaded relief files, processing of the relief image in Blender, and exporting to view on the web. It should be noted that many different initial and final steps can be used with this workflow,  those selected (terrain-party, Don McCurdy's gltf viewer, glitch) have only been selected because of previous experience with these tools. This document is meant primarily as a summary of the offering, and will be extended with details where necessary.

### Finding Relief

[Terrain-Party](https://terrain.party) is an Open Source tool for getting real-world height maps from different locations of the planet. This tool can export a monochrome height map image of a section of the USGS data-set that can be imported into blender

### Blender (Think of a witty section title) 

Blender is an open source 3D modeling tool that is used extensively in hobbyist and production grade projects. To produce a 3d representation of the height map image imported, we make use of the displacement modifier and a simple plane object subdivided to the granularity required by the user. Blender also makes it dead simple to export to many of file formats used for viewing models in other programs and on the web. Choosing the GLTF format, we will then export the mesh landscape and move to the next step.

### Viewing on the Web

Don McCurdy is an active member of many of the WebVR communities, inventor of the Supermedium VR webplatform, and central developer for the GLTF fileformat standard. As such, it is less than surprising that he also has created a wonderful tool for viewing GLTF files known as [gltf-viewer](https://gltf-viewer.donmccurdy.com/). On this page, you can upload the resulting gltf/glb (binary format of gltf) and view the model on the web! 

Glitch is another incredible platform for sharing web programming with a snap of your fingers. Landing on their main site look up an AFrame scene that you can remix (modify and make your own), and then upload the gltf/glb file to the assets folder. Following this you can change the source of the gltf model element and clicking on "Show" button in the top of the window takes you to a live scene in which you may stand upon your landscape and look around.







## Web VR & 3D Modeling 

![](https://drive.google.com/uc?expert=download&id=1gr1N6E1zURNMqfPGNDiqy5QsupdF8SQ9)

**Weaver Science and Engineering Library iSpace / UA Main Library Catalyst Studios **

**Tuesdays 2-4**

  Need help with basic 3D model creation in Blender? Or how to create a Virtual Reality app/experience on the web with A-Frame? Want to put these two things together? Come on in during drop in hours with your questions or  your wild ideas and we will try to bring them to life!

  Devin Bayly is a member of the Research Technologies Data Visualization team here at the University of Arizona. He works with researchers, students, and faculty to tell stories and communicate ideas with visualizations on and off the web.




# Data-Visualization-Team-Examples
This repo will host the examples of data visualizations created by the Research Technologies Data Visualization Consultant team at the University of Arizona.

## 3D


### South West Pots

*See below south west pots in VR*

## VR

### Domoni Crater Mars
Originally built for Dr. Alfred McEwen, Sarah Mattson, and Nilofur Emami of the University of Arizona's Planetary Image Research Lab.  

* Final web VR version [https://lava-step.glitch.me](https://lava-step.glitch.me)
* model files 
  * glb [here](https://drive.google.com/open?id=1fN75AnQdRZNmgPuQZZMYTtzLDAnaOCA6)
  
  
### Spider Room Psychology Experiment
Built originally for Sarah Beth Burger, Department of Psychology, as part of her research into Phobia Psychotherapy in Virtual Reality.  Her dissertation can be found [here](https://repository.arizona.edu/bitstream/handle/10150/222891/azu_etd_12052_sip1_m.pdf?sequence=1&isAllowed=y)

* Final web VR version [http://held-alamosaurus.glitch.me/](http://held-alamosaurus.glitch.me/)
* model files
  * room file [https://drive.google.com/open?id=15q5EBs8lwo5ZNtUOHqi1IlRRJEzb_fEH](https://drive.google.com/open?id=15q5EBs8lwo5ZNtUOHqi1IlRRJEzb_fEH)
  * roof spider [https://drive.google.com/open?id=1A8kyBB-ToSVog5Oi9n4q7SqF_-twUisV](https://drive.google.com/open?id=1A8kyBB-ToSVog5Oi9n4q7SqF_-twUisV)
  * platform spider [jumping spider](https://drive.google.com/open?id=1aWFmB6U2iQQBJcVSqXuU6W4yq3Ga3Ium)

### South West Pots

* Final web VR capable version of scene can be found [here](https://jewel-dingo.glitch.me) on glitch
* To trigger the VR click the icon in the bottom right corner.  Built originally for Arizona State Museum's Dr. Douglass Gann, Center for Desert Archeology, in 2008.

* Data for pots 
  * [SW-Pots unity compiled file](https://drive.google.com/drive/folders/15X2RFoWnB7OCphnI6eU6I5GFCBrPQgx5?usp=sharing)
  * [SW-pots unity assets](https://drive.google.com/open?id=1YRVeARvfWSjvlJXniAM7Ag2USGwxo81T)

# Data Analysis Examples
## Iso-surface Reconstruction
### D. Melanogaster Glial Cell
Data owner is Dr. Lynne Oland, and Ernesto Hernandez of the University of Arizona Department of Neuroscience. Reconstruction and animation done by Christine Deer of UITS Research Technologies Data Visualization Team.  Shared with permission.
* Video ([src](https://drive.google.com/file/d/1nWcNAZb27FrBRhQP7XItD23cr3lMUD9r/view?usp=sharing)) of raw data volume and its reconstruction by Imaris can be found [here](https://youtu.be/mmG_22AdiqI) on youtube

## Quantification
### Spots within a set radius around a surface object. EMPTY
* Video ([src]())

## Tracking
### Adipose Microtubule +end tip associated tracking
Data owner is Dr. Paul Langlais, and Sara Parker of the University of Arizona College of Medicine.  Spot tracking done manually using Imaris by Christine Deer of UITS Research Technologies Data Visualization Team. Shared with permission.  
* Video ([src](https://drive.google.com/file/d/1qpThDGqehlAxy3K0h8kYungXqsaSdxpy/view?usp=sharing)).  Clasp2 +end tip Microtubule associated protein tracking over timecourse after insulin application. Video and links to lab and publication can be found [here](https://youtu.be/fCsVCzbcEZo)
* Lab [website](https://langlaislab.medicine.arizona.edu/)
* Publication using the analysis shown above can be found [here](https://www.ncbi.nlm.nih.gov/pubmed/31018989)

# Modeling Projects
## Video Reconstruction from tracking data
### Eye Tracking Simulation
Data Owner is Dr. Jim Schweigerling and Eddie LaVilla of the University of Arizona Department of Optics.  Blender simulation of eye position by Christine Deer of the UITS Research Technologies Data Visualization Team.  Shared with permission.
* Video ([src](https://drive.google.com/file/d/1v2dpWdCjkt0iwoDJuW7DSlLAFB6_ra6H/view?usp=sharing)) of Blender 2.78 reconstuction of eye tracking data provided by Eddie LaVilla.  The video can be found here [here](https://youtu.be/KBwWLkjP2QE)

## Animated Scientific Methods
### MiniLEO methods EMPTY
* Video ([src]()) of animated methods for the MiniLEO project done at the request of Yadi Wang.  The video can be found here [here]()

# Example Video Loops

This is a short 15 minute video with the examples shown at the Catalyst Studio Soft Opening on 11/2/19.

https://youtu.be/ysR1qcNH_Kk
