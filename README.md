# Weather Route Planner

Weather Route Planner is a desktop application designed for VFR pilots and aviation professionals. It provides 7-day weather forecasts, METARs, and TAFs along a planned route using an interactive map interface.

Developed by **John Hodgkiss**  
Support the project: [paypal.me/Jhdgkss](https://paypal.me/Jhdgkss)

---

## Features

- **Interactive Map Interface**  
  Add waypoints to your route by right-clicking on the map.

- **7-Day Forecasts**  
  Retrieve detailed hourly weather data from Metcheck for multiple coordinates.

- **Aviation Weather Reports**  
  Automatically identifies nearby airports and collects up-to-date METAR and TAF data using the CheckWX API.

- **Export to PDF and JSON**  
  Generates structured, well-formatted reports for each location. The JSON file is suitable for further analysis, automation, or import into other systems.

- **Compatible with ChatGPT**  
  The exported JSON file can be uploaded to ChatGPT for natural language analysis. Users can ask questions like:
  - *"Which days are best for VFR flying?"*
  - *"Summarise the worst weather expected this week."*

- **Flyability Score Analysis**  
  Calculates a score based on weather conditions to help determine the most suitable days for flying.

- **Customisable Themes**  
  Multiple visual themes are included for a modern and adaptable user interface.

---

## How to Use

1. **Launch the Application**
   - From source:  
     `python main.py`
   - From compiled `.exe`:  
     Double-click the application file.

2. **Add Waypoints**
   - Right-click on the map to define your intended route.

3. **Fetch Weather Data**
   - Click the **"Fetch Weather Data"** button.
   - The app will generate:
     - `weather_data.json`
     - `weather_report.pdf`
   - Files are saved to the `/export` folder.

4. **Analyse the Data**
   - Open the PDF report for a printable summary.
   - Upload the JSON file to ChatGPT for interactive, AI-driven weather analysis.

---

## System Requirements

- Python 3.9 or later
- Dependencies (install with `pip install -r requirements.txt`):
  - `ttkbootstrap`
  - `tkintermapview`
  - `Pillow`
  - `matplotlib`
  - `requests`
  - `reportlab`
  - `scipy`

---
