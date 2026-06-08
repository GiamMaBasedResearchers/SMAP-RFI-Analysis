NASA SMAP-RFI-Analysis

Thanks especially to the NASA SMAP Group that allows us these analyzes with publicly available data!

https://salinity.oceansciences.org/smap-radiometer.htm

Obviously, there will be several fixes to be made, and the code isn't clean, and you will find entities that appear to be false positives but are not always false positives. I consider the exercise very interesting for various levels of understanding, knowledge and technicalities.

As always, you can use the plain HTML locally 👋👋👋

To preview GitHub HTML files, use these services by pasting the links:

https://raw.githack.com/ (Tested / working)

Fast Link:

https://raw.githack.com/GiamMaBasedResearchers/SMAP-RFI-Analysis/main/SMAP%20NASA%20RFI%20Analysis.html

Thanks to:

https://github.com/neoascetic/rawgithack

You can also use W3Schools Tryit Editor:

https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45dad4b8-601d-4c70-a5e1-92bc6fa5454d" />


A client-side web application designed to visualize and analyze Radio Frequency Interference (RFI) data from NASA's Soil Moisture Active Passive (SMAP) satellite mission. This tool enables researchers to detect temporal changes in interference patterns, identifying zones where RFI has appeared ("Turned ON") or disappeared ("Turned OFF") over time.

SMAP Analysis Tool

Features

Monthly Comparison: Compare two specific months to identify localized changes in RFI patterns.
Year-to-Year Comparison: Analyze seasonal trends by comparing two full years side-by-side in a comprehensive grid view.

Automated Difference Maps:

Green Zones: Indicates new or increased interference (Zones Turned ON).
Red Zones: Indicates reduced or disappeared interference (Zones Turned OFF).

Geographic Context: Automatic overlay of country borders for precise geolocation.

Interactive Tools:

Zoom in/out functionality for detailed inspection.
Direct download of analyzed maps (Original, ON, OFF) for reports.
Lightweight Architecture: Runs entirely in the browser using HTML5 Canvas and JavaScript. No backend server installation required.

Getting Started

No installation is needed. This tool is designed as a single, self-contained HTML file.

Download the index.html file from this repository.
Open the file in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge).
Ensure you have an active internet connection to fetch the SMAP imagery data.

Usage
1. Monthly Comparison

    Select "Monthly Comparison" from the top navigation.
    Choose a Start Month and a Comparison Month.
    Click "Analyze Difference".
    The tool will display the original maps for both months, followed by the generated maps highlighting interference changes.


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/45dad4b8-601d-4c70-a5e1-92bc6fa5454d" />
   

3. Year-to-Year Comparison

    Select "Year-to-Year Comparison" from the top navigation.
    Enter Year A and Year B (e.g., 2015 vs 2016).
    Click "Generate Annual Grid".
    The tool will generate a table displaying:
        Original maps for Year A.
        Original maps for Year B.
        Difference maps (ON/OFF) for every month of the year.


<img width="1897" height="901" alt="image" src="https://github.com/user-attachments/assets/2b763780-3ec4-4416-993e-6582cce85a6a" />

NEW VERSION V2

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9f49a148-00df-4ed0-b05a-a5c1d19464f8" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/32400a8f-e352-4e34-a5d4-fc45dc661078" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/990fc4cf-af12-48e1-8cb6-12d3be3d83be" />


Fast Link:

https://raw.githack.com/GiamMaBasedResearchers/SMAP-RFI-Analysis/main/SMAP%20NASA%20RFI%20Analysis%20v2.html

What's New in v2.0

NASA-Themed Interface: A complete visual redesign inspired by NASA mission controls. The interface now features a dark space aesthetic, glassmorphism effects, and high-contrast colors optimized for data analysis.

"Zones Fixed" Analysis: Added a new visualization layer (Yellow) that identifies interference sources present in both compared timeframes, allowing researchers to pinpoint "Fixed" or persistent RFI noise.

Advanced Animation Engine: Introduced a powerful animation suite that goes beyond simple loops.

Playlists: Users can now create custom queues by adding multiple time clips (Start Date -> End Date) with independent visualization modes for each clip.

Composite View: A new playback mode that displays the "Current Frame" and "Previous Frame" side-by-side, allowing for immediate visual correlation of changes.

Smart Frame Processing: Implemented automatic cropping logic to exclude map legends, scales, and dates from the pixel analysis. This improves the accuracy of border projection and prevents processing artifacts on the image edges.


Data Source

This tool utilizes publicly available data provided by the NASA SMAP mission:

https://salinity.oceansciences.org/smap-radiometer.htm

Data Provider: NASA Aquarius/SAC-D & SMAP Missions
Imagery: SMAP Radiometer RFI Percent Maps.


Technical Details

Core Logic: Image processing is performed locally using the HTML5 Canvas API. Pixel intensity values are compared between two timeframes to generate difference maps.
Projection: The tool assumes an Equirectangular (Plate Carrée) projection for map overlay and alignment.
Compatibility: Compatible with all major browsers supporting ES6+ and Canvas API.


⚠️ Disclaimer

Disclaimer: The code is for educational, training, analysis, & security purposes, & is intended for understanding & knowledge. The authors assume no liability for the misuse of this tool or the data it visualizes. Always ensure you have permission to access and visualize telemetry data.



Credits

This code provide from: "GiamMa-based researchers SDR R&D IoT" | @GiammaIoT2
License

This project is provided for research and educational purposes.
