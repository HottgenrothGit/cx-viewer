# CX-Viewer
A 3D **web viewer for IFC** files, developed as part of the **Construct-X** project.

Its goal is to enable the inspection of **Digital Product Passports (DPP)** and **CO2** equivalents for construction/building related products if the data is embedded and linked to an object within the IFC file.

## Supported bSDD

The viewer supports selected parts of the **Construct-X**-related dictionary for IFC.  
Its recommended to use a URL as DPP content in order to link a Digital Product Passport.

For more details see:  
https://search.bsdd.buildingsmart.org/uri/buildingsmart-de/ConX/0.1  
*The bSDD is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)*

## Quickstart

Fast way to use the viewer:
  
1. Clone or download and unzip the project 
    > https://github.com/HottgenrothGit/cx-viewer.git
2. Install yarn globally (if necessary)
    > `npm i -g yarn`
3. Navigate in terminal to the project folder and execute
    > `npm run init repo`
4. Run Build  
    > `npm run build`
5. Start the web app in default Browser
    > `npm run start-open`
6. Click on the **Load** button to select an IFC file
7. Double-click a 3D object to select it. An info box will display available DPP and CO₂ data.

---
### License

MIT License

---

### Acknowledgements

Based on the project [web-ifc-three](https://github.com/ThatOpen/web-ifc-three)

---
