# 2D LOCATION OF SIGNALS SOURCE BY POLE-POLAR GEOMETRICY MODELS
## USER’S MANUAL

To develop this work we have built a simulator in MatLab code and used the implemented functions to construct a prototype that processes real data. All code and data used are at anyone’s disposal. We use MatLab releases 2009 and 2014 and problems were not reported

### 1)	First step: unzip the file GeometricModels.rar. Four new folders will be created: PPC&CHC, PLI, TLI&MAI and Experiments.

The geometric models “Pole-Polar Centroid” (PPC) and “Convex-Hull Centroid” (CHC) are in the folder PPC&CHC. The geometric models “Polar Lines Intersections” (PLI) is in the folder PLI and the models “Tangent Lines Intersections” and “Tangent Lines with Minimal Angles” are in the folder TLI&MAI. The folder Experiments contain the code and data for real case experiment and its analysis.

## DATA ENTRY PROCEDURE
The main window of the simulator, for any geometric model, is the data entry interface  

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/ffdc403e-08d2-4ecd-bf82-6c69461f4c77)

The control of the data entry using this interface is done only with the mouse (click-move-click) 

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/aa486e7d-47e0-412a-9347-792f2dc84ffe)

To set a position of a receiver, move the mouse pointer to the desired coordinate and press (first click) any mouse button. A big black point is plotted in this coordinate.
To determine the radial distance (receiver range), move the mouse pointer to the desired coordinate and press (second click) any mouse button. A blue circle line is drawn in this coordinate
Repeat the procedure above for each receiver used by the location system.

## Running PPC and CHC
#### 1)	Set Current Folder in MatLab environment to  D:\...\GeometricModels\PPC&CHC.

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/ee5b63e0-d473-4c53-b7ac-231e622f1e07)


#### 2)	At the prompt of MatLab, in Command Window, typewrite CaseGenerator and press ENTER.

**![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/55990fc1-5bd2-4000-aabc-a59684e18588)**

#### 3)	Typewrite the number of receivers that compose the location system

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/a7f68b5c-53a2-441c-8f3c-09350f86e9d7)


Press ENTER or OK button

#### 4) Select a geometric model PPC, CHC or both.

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/a558762c-264a-4c22-bfcf-4e901c473eae)


Press ENTER or OK button

#### 5)	Perform the data entry procedure (described above) and obtain the graphic results.

## Running PLI

#### 1)	Set Current Folder in MatLab environment to   D:\...\GeometricModels\PLI.

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/266c16ba-4e62-43a2-ab6b-5763964daba8)

#### 2)	At the prompt of MatLab, in Command Window, typewrite CaseGenerator and press ENTER.

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/e6fedb7d-6ed1-4281-b140-7ae57db9ea0d)

#### 3)	Typewrite the number of receivers that compose the location system

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/d4243c9b-0f99-4c2a-be27-8b0500799d77)


Press ENTER or OK button

#### 4)	Perform the data entry procedure (described above) and obtain the graphic results.

## Running TLI and MAI

#### 1)	Set Current Folder in MatLab environment (e.g.   D:\...\GeometricModels\TLI&MAI).

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/9ed3f579-c951-4666-abe0-c3c2a606c822)

#### 2)	At the prompt of MatLab, in Command Window, typewrite CaseGenerator and press ENTER.

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/1ec6842c-1397-4bbe-8964-51614e423d44)

#### 3)	Typewrite the number of receivers that compose the location system

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/6ebec4c5-b965-422b-a395-f322f39a9f41)


Press ENTER or OK button

#### 4)	Select a geometric model TLI, MAI or both.

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/59568884-c201-4b13-8cde-c6d801b84a70)


Press ENTER or OK button


#### 5)	Perform the data entry procedure (described above) and obtain the graphic results.



## Running Real Data Analisys

#### 1)	Set Current Folder in MatLab environment (e.g.   D:\...\GeometricModels\TLI&MAI).

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/1669782f-7d2b-49f1-80d4-b24ec8549419)


#### 2)	At the prompt of MatLab, in Command Window, typewrite ResultAnalisys and press ENTER.

![image](https://github.com/aleksmontanha/geometricsmodels/assets/3112499/245d5a91-c174-4e51-b295-5d5361f65cb2)

Each experimental case is presented in a particular graphic window.

