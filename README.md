# IfcRelSpaceBoundary test files
## Folders
* [IfcRelSpaceBoundary](https://ifc43-docs.standards.buildingsmart.org/IFC/RELEASE/IFC4x3/HTML/lexical/IfcRelSpaceBoundary.htm)
* [IfcRelSpaceBoundary1stLevel](https://ifc43-docs.standards.buildingsmart.org/IFC/RELEASE/IFC4x3/HTML/lexical/IfcRelSpaceBoundary1stLevel.htm)
* [IfcRelSpaceBoundary2ndLevel](https://ifc43-docs.standards.buildingsmart.org/IFC/RELEASE/IFC4x3/HTML/lexical/IfcRelSpaceBoundary2ndLevel.htm)

Note : 
In `IFC2X3` 1st level and 2nd level boundaries do not have a specific class. 
They are defined in their `Name` attribute. See [IFC4 documentation](https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/link/ifcrelspaceboundary.htm).
In this case files are still stored in `IfcRelSpaceBoundary2ndLevel` folder.

## Files pattern
Files are stored using following pattern:
{Name}\_{AuthoringSoftwareAbreviation}\_{IFC_schema}.{FileFormat}

### AuthoringSoftwareAbreviation:
* BB : BlenderBIM Add-on (IfcOpenShell)
* NV : Nova
* AC24 : ArchiCAD 24
* R23 : Revit 2023

### IFC_schema:
* IFC2x3
* IFC4
* IFC4.3

### File format:
* ifc
* ifcxml
* ifczip

Note: prefer using ifczip for large files and files which will not evolve.

### Example
DemoBEM_BB_IFC4.ifczip
