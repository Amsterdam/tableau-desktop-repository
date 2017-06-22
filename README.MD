# Tableau Desktop Repository # 
==============================

City of Amsterdam neighbourhoods, background maps, postal codes and color styles files/settings for use in Tableau Desktop.

### What's it for? ###
----------------------
This repository contains usefull geometry files of the City of Amsterdam for use in Tableau Desktop Public/Personal or Professional.
These are the neighbourhoods based on areas in the period 2011-2015 and the period from 2015 till now.

An example of 2015-now can be downloaded and viewed here: https://public.tableau.com/views/Gebieden2016/Gebieden
It contains an example of the custom geocoding with feature files, to see the used coding/names of the neighbourhoods.

It contains:
1. A custom geocoding file of the City of Amsterdam neighbourhood codes and postal codes:
    - Gemeente (STAD)
    - Stadsdeel (A)
    - Gebieden (DX00)
    - Wijk (A00) 
    - Buurt (A00a)
    - PC6 (1000aa)
    - PC5 (1000a)
    - PC4 (1000)
    - Rayons (AA00)
    - Alternatieve gebieden (AS00)
    - Winkelgebieden (W01)
    - Werkgebieden/Bedrijventerreinen (bb01)
2. Background maps using our TMS services found on https://api.data.amsterdam.nl
3. Standardized color styles which are used at https://ois.amsterdam.nl

### Install Procedure ###
-------------------------
- Download the repository to your desktop
- Unpack the zip file
- Copy and overwrite all files into 'My Tableau Repository' located in My Documents. 

On Windows the directory is located here: 
'C:\Users\<Windows Username>\Documents\My Tableau Repository\'

The provided packaged workbook is saved packaged workbook to tableau public as a version 9.1 to maximize compatibility.

### Exceptions ###
------------------
If you use a virtualized machine where you cannot change the tableau repository:
Download and open the provided packaged workbook to continue working with this file to have the geocoding options available.

### Background ###
------------------
These files are created using our WFS services found on https://api.data.amsterdam.nl.
All neighbourhood layers were joined into one big shapefile.
This shapefile was then converted to a custom geocoding option by using this excelent conversion tool created by Richard Leeke.
He provides support on this page:
https://community.tableau.com/thread/116369

We used this tutorial to made it all work:
http://www.clearlyandsimply.com/clearly_and_simply/2012/03/create-your-own-filled-maps-in-tableau.html 
