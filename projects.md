[PROJECTS](./projects.html)  /  [RESEARCH](./research)  /  [MAKING](./making)  /  [TEACHING](./courses.html) / [PUBLICATIONS](./publications.html) /  [CONTACT](./contact.html)  

# P r o j e c t s

 [Geometrid](#geometrid-pavilion)![Geometrid](/2019/Geometrid_Project.jpg) | [Boathouse](#boathouse-at-het-lankheet)![Het Lankheet Boathouse](/2019/Boathouse_Project.jpg) | [Project EGG](#project-egg)![Egg](/2019/Egg_Project.jpg) | [Fort Asperen Dome](#kunstfort-asperen-dome)![Fort Asperen Dome](/2019/Dome_Project.jpg)
  [Column Interoperability](#column-interoperability-etabs-to-revit)![Column](/2019/Col_Interop_Project.jpg) | [MLS Roof Truss](#mls-roof-truss)![MLS Roof Truss](/2019/StadiumTruss_Project.jpg) | [O'Hare International Airport](#o'hare-international-airport)![O'Hare](/2019/ORD_Project.jpg) | [Nijmegen Brug](#nijmegen-brug-analysis)![Nijmegen](/2019/Nijmegen_Brug_Project.jpg)
  [LMNA](#george-lucas-museum-of-narrative-art) ![LMNA](/2019/LMNA_Project.jpg) | [Fukuoka](#fukuoka-international-airport)![Fukuoka](/2019/Fukuoka_Project.jpg) | [Bridge Alignment Tool](#bridge-alignment-tool-processing-to-rhino)![Bridge Alignment](/2019/BridgeAlignment_Project.jpg)  | [Arch. Revit to GSA](#revit-architecture-to-gsa)![Revit to GSA](/2019/Revit_to_GSA_Project.jpg)


-----
### [Geometrid Pavilion](http://core.thorntontomasetti.com/geometrid-pavilion/)
*Physical Prototyping; Concept Development; Fabrication*  

*Collaboration with CORE Studio|Thornton Tomasetti_2015*
Temporary pavilion designed for the 2015 International Association for Shell and Spatial Structures (IASS) Symposium in Amsterdam. The 8m- long suspended kinetic structure “pulses” as the 8 scissor rings spaced along the central truss, expand and contract. Grasshopper was used to study geometric proportions and relationships, Digital Project was used for fabrication modeling, clash detection, and assembly logic, and Processing, Arduino, and Gcode for motion programming and control.

[Article](http://core.thorntontomasetti.com/geometrid-pavilion/)  
[Paper](https://s3.amazonaws.com/corewebsite-media-uploads/CoreStudioWebsite/wp-content/uploads/20150914212851/20150817_IASS_Geometrid-Paper_final_r02.pdf)  
[YouTube](https://www.youtube.com/watch?v=Gt9Fv8wE0YI)  

-----
### Fukuoka International Airport
*Parametric form explorations; Concept Development*  

*HOK 2019*
Conceptual design of a transition wall between the existing airport building and the new addition.  Grasshopper was used to study options for post and beam configurations for the timber screen wall.  A parametric model based on a reciprocal frame structural framing system was built and enabled designers to explore various options with respect to the density of the posts and beams in regions of the screen wall.

------
### MLS Roof Truss
*Parametric form explorations*  

*HOK 2019*
Tasked with the design of the roof structure of the new Major League Soccer stadiun in Miami, the Engineernig team at HOK set out to explore options for the layout and design of space trusses to support the roof.  Grasshopper was used to generate truss centerline curves along the roof surface, defined by the architect.  Various parameters allowed designers to adjust how the centerline curves followed the curvature of the rood surface.  Space truss structures were then built based on these centerline curves and parameters enabled designers to vary the taper of the truss as well as the density of the truss unit modules. 

-----
### Column Interoperability ETABS to Revit
*BIM; Interoperability*  

*HOK 2019*
The intent of this study was to establish a workflow that would enable a user to update the columns in a Revit to reflect changes made in the associated ETABS structural analysis model.  Geometric definition of the columns, as well as section properties of the columns, was extracted from ETABS and recorded in Excel.  Grasshopper was used read this data into a definition which simultaneously used Rhino.Inside to recreate the centerline geometry of the Revit columns in Grasshopper/Rhino.  The definition uses Galapagos, Grasshopper's evolutionary solver, along with some Python modules, to align the Revit and "ETABS" models and compare nearest pairs of columns.

-----
### Bridge Alignment Tool Processing to Rhino
*Parametric form explorations; Interoperability*  

*Research derived from competition 2018*
The objective of this research was to establish a workflow which would enable users to use Processing to communicate the control points of a bridge alignment curve as well as bridge cross-section geometry to Grasshopper.  Once the the control points are placed (in 2D) and a curve representing the alignment is generated in Processing, and the cross section shape and size is determined (using sliders), the geometric data is sent to Grasshopper, where it is used to build a 3D model of concrete box girder bridge.  The intent is to eventually develop a web platform to replace the Processing interface, within which designers could lay out preliminary alignments based on site parameters in a web interface, to generate a basic 3D model which could be further developed in Grasshopper.

-----
### George Lucas Museum of Narrative Art
*BIM; Interoperability*  

*LERA 2017-2018*

The Lucas Museum of Narrative Art will be a 275,000 sq. ft museum building, which will house filmamker George Lucas’ personal collection of artwork, costumes, and artifacts, as well as an education wing, a library, theaters, dining areas, and a rooftop promenade.

A parametric workflow was developed to more easily update the structural Revit model as changes were made to the design.  Scripts were developed in Dynamo to translate structural geometry from Rhino into Revit and to build geometry directly in Revit from point data stored in Excel.  The library of Dynamo scripts also includes tools for generating  a developed elevation of the truss that wraps around the perimeter of the building, as well as tools for placing views on sheets, placing detail components and tags, and querying the model.  A library of adaptive components representing custom built-up structural elements was also generated.

-----
### Nijmegen Brug Analysis
*Grasshopper modeling; Preliminary structural analysis*  

*Independent collaboration 2018*
The objective of this study was to define a prelimary model of an internal structural system for the design of a 3D printed concrete bridge proposed by designer Michiel van der Kley.  Grasshopper was used to rationalize the freeform shape of the bridge into a system of arches and perform a preliminary analysis of the structure.  Parameters including deck width and stringer spacing, arch curvature, spacing of struts, were used to evaluate the structural integrity of various geometric options, using Karamba, the structural analysis add-on for Grasshopper. 


-----
### O'Hare International Airport
*Parametric form explorations; BIM; Interoperability*  

*HOK 2019-2020*
Dynamo was used to link the SAP model to the Revit model.  More specifically, Dynamo scripts were used to translate foundation location, size, and elevation data from SAP into Revit.  Speckle, in combination with Grasshopper, was used to create a dynamic clipping plane tool, which allowed the user to efficiently evaluate foundation elevations across the span of the new passenger terminal.  Dynamo scripts were also used to build model elements as well as extract Revit model data.


------

### Revit Architecture to GSA
*BIM; Interoperability; Structural Ananlysis*  

*HOK 2020*
Given an architectural Revit model, how can we build an associated structural analysis model?  This study sought to extract column centerlines and floor plan areas from an Architectural Revit model to generate a preliminary framing system that could be analyzed in structural analysis software, GSA.

------
### [Kunstfort Asperen Dome](https://www.fortbijasperen.nl/avg.html)
*Parametric form explorations; Structural Analysis*  

*Collaboration with Bureau SLA_2013*
Assisted in the design development of the 12m-diameter timber dome structure which serves as a partial covering for the central core of the landmark fort. Developed concept with BureauSLA and investigated options for discretizing dome.  Performed parametric study of dome configurations.  Built finite element analysis model and performed analysis of total structure and developed details for construction. 

------
### [Project EGG](http://www.michielvanderkley.nl/egg/project-egg/)
*Parametric form explorations; Structural Analysis*  

*Collaboration with Studio Michiel van der Kley_2013*
Performed structural analysis of free-form 3D printed pavilion to determine stability of form. The pavilion  is composed of about 5,000 modules which were 3D printed by volunteers from around the world, and connected on site to build the final form.  The architectural form was discretized into a line element model and analyzed assuming approximate material properties for the 3D printed modules. As a testament to its modular design, the pavilion continues to be disassembled and reconstructed at various venues around the world.

------
### [Boathouse at Het Lankheet](http://dynck.nl)
*Parametric form explorations; Structural Analysis*  

*Collaboration with Dynck_2013*
Performed structural verifcation of the deflection and stability analysis of the timber canopy structure, which was done using the Karamba add-on for Grasshopper. The output generated by Karamba was used, in combination with the evolutionary solver, Galapagos, to optimize the angles of inclination of the canopy’s columns. The parametric model was also used to facilitate fabrication of the boathouse using locally harvested timber. 

------
### [Parametric Truss](/2019/exploration/parametric/index.html)
*Parametric form explorations; p5.js* 

The objective of this study was to begin to translate the parametric truss definition for the MLS stadium roof to a web-based platform that would enable designers to generate various truss configurations and export the geometry for 3D modelling and analysis.

