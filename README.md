# PSSArchitect
An Industrial workbench to provide PSS Modelling feature with auto generation of PSS Source Code.
# Installation Instructions
1. Download both PSSArchitect_1.0.0 and PSSArchitectGenerator_1.0.0.
2. Open ObeoDesigner/Eclipse Modelling Framework.
3. Go to Help-> Install New Software
4. Click on ADD -> The Add Repository Dialogue box comes up.
5. Click on Archive -> Provide the address of downloaded Archive file (PSSArchitect_1.0.0.zip). Remember choose only PSSArchitect and not PSSArchitectGenerator zip file.
6. Provide a name. For Intance, PSSArchitect.
7. Click On Add Button.
8. PSSArchitect Tool is fetched and loaded by Eclipse. 
9. Follow the remaining steps and complete installation.
# Installation Instructions for PSSArchitectGenerator
a. Download PSSArchitectGenerator_1.0.0.zip file
b. Go to ObeoDesigner/Eclipse Modelling Framework and Go to File->Import->Projects from Folder or Archive
c. Provide address of the downloaded zip file and following two files will be imported.
  I. org.eclipse.acceleo.modeule.sample
  II. PSS-CASESTUDY1
# How to Run Already Provided Case Study in ObeoDesigner/Eclipse Modelling Framework
i. We assume that you have followed the above mentioned steps in sequence.
ii. Just Open the Serial No. (I) and (II) projects.
iii. Right Click on PSS-CASESTUDY1 -> Goto ViewPoint Selection
iv. Choose PSSVIEWPOINT.
v.All PSS MODEL Diagrams can be loaded -> Goto Representations.aird -> PSSVIEWPOINT ->PSS MAIN DIAGRAM
vi. CLicking on PSS MAIN DIAGRAM will open the main diagram user interface.
vii. Double click on any specific icPSS-CASESTUDY1on/box will lead you to your desired DIAGRAM.
# How to Generate PSS Code pertaining to PSS-CASESTUDY1.
 A. We assume that you have followed the above-mentioned steps in sequence.
 B. Go to RUN CONFIGURATIONS-> Click on ACCELEO APPLICATION
 C. You will be presented with four different text boxes. Click on First Browse Button and Select org.eclipse.acceleo.module.sample that you have already loaded.
 D. Click on Search Button and select org.eclipse.acceleo.module.sample.main.
 E. For Model click on Browse Button and Select 'SOC.pss' by typing soc in search box.
 F. For target code generation -> Select PSS-CASESTUDY1.
 G. Click on Apply and then Click on Run.
 H. All PSS Source Code Files will be generated in PSS Folder in main project of PSS-CASESTUDY1.
 I. Right Click on Generated files and open them in Text Editor to view the generated Code.
 Thank you so muck.
 
 regards.
 
 M. Asim Minhas
