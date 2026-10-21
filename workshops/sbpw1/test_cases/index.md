<img src="/images/sle-title-bar.png" width="100%">

# SBPW1 Test Cases (2014)

The workshop involves three configurations. Two are required and one
is optional.

- [SEEB-ALR Body of Revolution](seeb-alr/index.md), required
- [69-Degree Delta Wing Body](69-degree-delta-wing-body/index.md), required
- [Lockheed Martin 1021 configuration](lm-1020/index.md), optional

The two required cases have a series of uniformly refined mixed-element and tetrahedral unstructured grids. Each required case also has a point matched structured grid that can be coarsened by utilizing every other point in each computational direction. Only one tetrahedral unstructured grid is provided for the optional case.

A workshop participant submission should consist of ASCII Tecplot files with the file name:

**Lastname_Code_Other_Grid_Model.plt**

**Lastname** : is the surname of the participant  
**Code** : the name of the simulation tool  
**Other** : other identifing information  
(e.g., flux function, limiter, turbulence model)  
**Grid** : grid description including element type and size  
**Model** : model examined (SEEB, Delta, or LM1021)  

There are Tecplot signature extraction macros in a “data-submittal” HTTPS directory for each configuration. See the “data-submittal” HTTPS directory for signature locations and instructions on macro use. These macros assume that the symmetry plane is exactly at y=0. If that is not true, the extraction location may need to be moved by a small amount to be inside of the computational domain.

Each SEEB-ALR calculation should produce one .plt file with two zones, each Delta Wing Body calculation should have one .plt file with ten zones, and each LM 1021 calculation should have five .plt files, each with one zone.

For the required cases with mulitple grids, the participant should choose the largest grid that they can run as well as many of the coarser grids as time permits. Coarser structured grids should be created by utilizing every other point in each computational direction.

If a grid is generated or adapted, The participant is required to upload the grid to the HTTPS server with the data submission. Acceptable grid formats are CGNS, AFLR3, and VGRID. If you need a description of the formats or are not able to produce one of these formats, please contact the workshop committee for assistance.

---

***Return to:*** [Sonic Boom Prediction Working Group Home Page](https://sbpwg.github.io)

---
***Page Curators:*** [Mathias Wintzer](mailto:mathias.wintzer@nasa.gov)  
***Last Updated:*** Dec 21, 2018
