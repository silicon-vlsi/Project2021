# Project-2021
This page will host all resources (readings/videos/assgnments/etc) for various projects to train the 2022-23 graduates & trainees in CMOS VLSI Design.

## References/Resources
- [**Hodges**] Hodges, David A., et.al. "*Analysis And Design Of Digital Integrated Circuits, In Deep Submicron Technology*" (Special Indian Edition, 3rd Ed). Tata McGraw-Hill Education, 2005.
- [**Kang**] Leblebici, Y., Chul W. K., and Sung-Mo (Steve) Kang. "*CMOS Digital Integrated Circuits Analysis & Design*". 4th ed. McGraw-Hill Education, 2014
- [**OpenSource EDA**](https://silicon-vlsi.github.io/wiki/wiki-cad.html#open-source-custom-design-flow): Instructions and pre-compiled open source EDA to help you setup all the EDA tools on Virtual Box running Linux LXLE distribution.

## SRAM Project
The goal of this project is to analyze, design, simulate and layout and the entire 6T-based SRAM IP Block in 0.5um SCMOS Technology.

**ASSIGNMENT**
- [10 Jul 2021] : Design a 6T-SRAM Cell for minimum area using the 0.5um SCMOS technology.

**READING AND VISUAL MATERIALS**

- **VIDEOS**:
  - [SI2021-03-CMOS-VLSI Lecture](https://www.youtube.com/watch?v=MkMEq4zO9Pc): Semiconductor Memory basics & 6T-SRAM Cell design.

- **SUGGESTED READINGS**:
  - [Kang] Section **8.2**: Behaviour of Bistable Elements 
  - [Kang] Section **10.1** & [Hodges]-**8.1**: Introduction to Semiconductor Memories
  - [Kang] Section **10.3** & [Hodges]-**8.3**: Static Random Access Memory.
 
- **EXCERCISE PROBLEM**:
  - [Kang] Example **10.1**, Exercise **10.4, 10.5, 10.6**
  - [Hodges] Example **8.2**

## MOSIS Scalable CMOS ([SCMOS]/scn4m_subm)
[SCMOS] is a *lambda-based* scalable design rules that can be interfaced to many CMOS fabrication process available at MOSIS. **NOTE** The scalable design rules does not interface with Fabs now because of lot unique process nuances.

- The Spice model files are located at `<INSTALL-DIR>/eda-technology/scn4m_subm/models/scn4m_cnrs_bsim3v1.lib`
- Typical MOS parameters:
  - **NMOS**: tox=7.6nm, nch=1.7e17/cm^3, Vt0=0.49V, un(mobility)=445 cm^2/Vs
  - **PMOS**: tox=7.6nm, nch=1.7e17/cm^3, Vt0=-0.66V, up(mobility)=151 cm^2/Vs
  - Vdd=5V, Lmin=0.4um, Wmin=0.6um

 
