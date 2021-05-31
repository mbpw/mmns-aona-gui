# MMNS AoNA GUI

GUI (ArcGIS add-in) for navigational algorithm

## 1. Requirements

- ArcGIS Desktop (tested on 10.8.1)
- Python 2.7 with ArcPy extension (installed with ArcGIS)

## 2. ESRI addin assistant

You can create plugin template by using `/tools/addin_assistant/bin/addin_assistant.exe` application. Follow these
instructions:
https://desktop.arcgis.com/en/arcmap/latest/analyze/python-addins/creating-an-add-in-project.htm

## 3. Modifications

After creating the add-in you need to modify its files (inside `/Install/` directory).

## 4. Installation

To install the final add-in in your ArcGIS environment do following steps:

1) Run the terminal/console inside the directory containing Python 2.7 with ArcPy extension (e.g. `C:\Python27`),
2) Type `python <path_to_this_project>/plugin/makeaddin.py` and press enter,
3) Run the newly created `.esriaddin` file by double-click and press **"Install Add-in"**).

More here: https://desktop.arcgis.com/en/arcmap/latest/analyze/python-addins/testing-an-add-in.htm

&copy; 2021 MMNS sem. 2 team