## SquamaterCreateEntitiesAndAttributesFromDataDictionary

**Squamata** is the largest order of reptiles, comprising lizards, snakes and amphisbaenians (worm lizards), which are collectively known as squamates or scaled reptiles.

**SquamaterCreateEntitiesAndAttributesFromDataDictionary** is a Jupyter Notebook Used to create FGDC XML formatted Detailed Entity and Attribute Section from a data dictionary for insertion into G3 metadata.

Contact Phil Brown, https://www.usgs.gov/staff-profiles/philip-j-brown or visit Phil Brown's git hub "repo", https://github.com/pbrown-usgs?tab=repositories regarding any questions or concerns pertaining to this Jupyter notebook.

**V1.0 -** 
- Import a data dictionary CSV containing entity names, and entity and attribute definitions
- Parse names and definitions from imported data dictionary
- Open data CSV
- Corrrelate values in data dictionary with csv data
- Calculate Min and Max of data channels
- Create Detailed Metadata in FDGDC XML UTF 8 ASCII format for insertion into G3 metadata templates

<center> **Notes for future development** </center>
- It may be useful to perform checks on the metadat template being used before inserting EandA?
- It may be useful to insert the EandA directly into the metadata - version 1 relys on a user cut and paste?
- It may be useful to operate on files stored in sharepoint instead of the users harddrive?

### Instructions
- Create a template in UTF8 ASCII FGDC XML format that contains boilerplate text common to all childeren in a data release.  Be sure this template contains the approriate curly bracket tags, {SquamataTagExample} used to populate the template using this notebook.

#### To execute a function/command select a cell and Hold-Shift + Press-Enter

*"Birthing the tail that feeds it..."* 

![Squamata - birthing the tale that feeds it](https://github.com/pbrown-usgs/SquamataAssemblyAMT/blob/master/SquamataLemniscateOuroboros.png)
