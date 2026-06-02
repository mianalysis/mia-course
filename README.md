[![Wolfson Bioimaging](./resources/images/Logo_text_UoB_128.png)](https://github.com/mianalysis/mia)

ModularImageAnalysis (MIA): Automation of image analysis workflows
==========================

Materials for "ModularImageAnalysis (MIA): Automation of image analysis workflows" course taught at the [Wolfson Bioimaging Facility](https://www.bristol.ac.uk/wolfson-bioimaging/), University of Bristol.

## Download latest version
[Download course materials (.zip) here](https://github.com/mianalysis/mia-course/releases/download/v1.0.0/mia-course_materials_1.0.0.zip)

## About
ModularImageAnalysis (MIA) is an image analysis workflow automation plugin for ImageJ/Fiji (https://mianalysis.github.io).  MIA allows for complex workflows to be constructed in a code-free manner, with each step in an analysis workflow represented as a single module.  Included modules cover operations such as image processing, object detection, image and object measurements, object-object relationships and visualisation.  Several modules also enable use of popular ImageJ/Fiji plugins such as StarDist, TrackMate and Coloc2.  Workflows constructed in MIA are batch-compatible by default and can be shared via small configuration files, allowing for reproducible analyses.
 
This workshop is suitable for anyone acquiring microscopy data as part of their research. Familiarity with basic image processing concepts will be necessary. These concepts are covered in our [ImageJ/Fiji Level 1 course](https://github.com/wbif-bristol/ImageJ-Fiji-Level-1-course).

## Folder layout
- ["Introduction to MIA.pptx"](./Introduction%20to%20MIA.pptx) is the main PowerPoint presentation.  This is broken down into two halves: the first covers the general principles of MIA, while the second focuses on practical exercises.
- The ["examples"](./examples/) folder contains four distinct exercises, each focusing on a different aspect of using MIA.  All modules within these exercises are annotated with notes, which can be accessed via "View > Show notes panel".  The exercises are:
    - ["Running existing workflows"](./examples/1_Running-existing-workflows/) looks at taking an existing .mia workflow file and running this within MIA.  The activity itself involves segmenting DNA from an AFM (atomic force microscope) image and classifying molecules based on their connectivity.  This can also be used to understand object relationships within MIA.
    - ["Creating new workflows"](./examples/2_Creating-new-workflows/) involves creation of a complete workflow from scratch.  Specifically, this workflow is for segmentation and measurement of nuclei from a 3D fluorescence image stack.
    - ["Object relationships and tracking"](./examples/3_Object-relationships/) focuses on object relationships in the context of object tracking.  The images used here come from the [Cell Image Library (CIL:11813)](https://www.cellimagelibrary.org/images/11813).
    - ["Advanced object handling"](./examples/4_Advanced-object-handling/) uses a TEM (transmission electron microscope) image of [bacteria within a mouse cell](https://commons.wikimedia.org/wiki/File:Orientia_tsutsugamushi.JPG) to introduce manual object segmentation as well as saving and loading objects to file.

## Questions or feedback?
If you've any questions or suggestions, please contact stephen.cross@bristol.ac.uk.