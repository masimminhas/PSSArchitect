# PSSArchitect
An Industrial workbench to provide PSS Modelling feature with auto generation of PSS Source Code.
# Istallation Pre-requisite
The best option is to use ObeoDesigner 11.6 which implicitly contains both Sirius 6.0 and Acceleo.In Case you choose Eclipse Modelling Framework or any other version of eclipse, you will need to install Sirius 6.0 and Acceleo Query Framework 7.0.0.2.
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
1. Download PSSArchitectGenerator_1.0.0.zip file
2. Go to ObeoDesigner/Eclipse Modelling Framework and Go to File->Import->Projects from Folder or Archive
3. Provide address of the downloaded zip file and following two files will be imported.
  I. org.eclipse.acceleo.modeule.sample
  II. PSS-CASESTUDY1
# How to Run Already Provided Case Study in ObeoDesigner/Eclipse Modelling Framework
1. We assume that you have followed the above mentioned steps in sequence.
2. Just Open the Serial No. (I) and (II) projects.
3. Right Click on PSS-CASESTUDY1 -> Goto ViewPoint Selection
4. Choose PSSVIEWPOINT.
5.All PSS MODEL Diagrams can be loaded -> Goto Representations.aird -> PSSVIEWPOINT ->PSS MAIN DIAGRAM
6. CLicking on PSS MAIN DIAGRAM will open the main diagram user interface.
7. Double click on any specific icPSS-CASESTUDY1on/box will lead you to your desired DIAGRAM.
# How to Generate PSS Code pertaining to PSS-CASESTUDY1.
1. We assume that you have followed the above-mentioned steps in sequence.
2. Go to RUN CONFIGURATIONS-> Click on ACCELEO APPLICATION
3. You will be presented with four different text boxes. Click on First Browse Button and Select org.eclipse.acceleo.module.sample that you have already loaded.
4. Click on Search Button and select org.eclipse.acceleo.module.sample.main.
5. For Model click on Browse Button and Select 'SOC.pss' by typing soc in search box.
6. For target code generation -> Select PSS-CASESTUDY1.
7. Click on Apply and then Click on Run.
8. All PSS Source Code Files will be generated in PSS Folder in main project of PSS-CASESTUDY1.
9. Right Click on Generated files and open them in Text Editor to view the generated Code.
 
                            Thank you so much.
 
  
 
                            M. Asim Minhas
