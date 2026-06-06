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


<img width="1920" height="1041" alt="image" src="https://github.com/user-attachments/assets/7ac25dc6-84d5-4b0f-ad21-a7d7302ef7f5" />



Data Source

This tool utilizes publicly available data provided by the NASA SMAP mission:

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
