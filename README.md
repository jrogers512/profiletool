# Profile Tool
![Profile Icon](icons/profileIcon.png)
The Profile Tool QGIS Plugin plots terrain profiles along interactive pointed or selected polylines.  The resulting profile diagram can be exported to SVG, PNG, DXF (3d polyline), PDF, or SVG formats.

## Getting Started
1. Install the plugin in QGIS under *Plugins* menu then *Manage and Install Plugins* by searching for and installing ***Profile tool***
2. If you do not yet have an elevation layer, add it now.
   - You can optionall install the ***SRTM-Downloader*** plugin which conveniently selects and downloads an elevation raster layer from NASA servers
3. Once your elevation layer is in place, open the Profile tool by selecting *Plugins* menu then *Profile tool* -> *Terrain profile**
4. The ***Profile Tool*** panel should open.  On the right is a box for elevation layers.  Select your elevation layer in the ***Layers*** panel, then select the "Add layer" button in the ***Profile Tool*** panel.
5. Select two or more points on the canvas that you would like to generate an elevation profile for.  Right click to cancel and start over.  

## Tips and Troubleshooting
- When the tool is ready to select points for the polyline, it will have a crosshair cursor.  If it does not, try returning to the tool by selecting *Plugins* menu then *Profile tool* -> *Terrain profile**.

## License & Support
Written in 2008 by Borys Jurgiel, Written in 2012 by Borys Jurgiel, Patrice Verchere
GNU GPL 2 - [Support and Requests](https://github.com/etiennesky/profiletool/issues)

## Requirements
- Qwt5 (python-qwt5-qt4) and/or python-mathplotlib
- QT v4.1 (for saving to PDF) or v4.3 (for saving to SVG)
- A raster or point vector layer with elevation
