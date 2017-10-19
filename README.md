# BOM-Gen

BOM-Gen is [EAGLE](http://www.cadsoftusa.com) ULP script to generate complete BOM (bill of materials) document for EAGLE PCB projects. This script generate BOM document as formatted HTML document.

Usage
-----

1. Copy *bom.ulp* file to EAGLE ULP directory. Normally, in Windows operating systems this directory is located at "C:\Program Files\EAGLE-X.X.X\ulp". Also note that this is an optional step and you can also keep this *bom.ulp* file in any other convenient location in your computer.
2. Run EAGLE and open schematic or board file.
3. If you are in schematic view switch to board view by clicking *File >  Switch to board* menu item.
4. In Board view click *File > Run ULP...* menu item.
5. Select *bom.ulp* file and press "Open" button.
6. When "Save output file" dialog box appears, select location and filename to save .BOM text file.

License
-------

This script is distributed under the terms of [MIT License](http://opensource.org/licenses/MIT). 
Original HTML version by Dilshan R Jayakody, 2015
Plain text version by Alessio Occhiodoro, 2017
Added the feature to group parts with an empty "value" field (like headers, connectors, etc.) using their description.

