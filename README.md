# 🦜 Endangered Bird Species Analysis in Australia
### Interactive Data Visualization with R & Shiny

This project is an interactive web application designed to analyze sightings of endangered bird species across Australia. The primary focus is on uncovering seasonal migration patterns by combining statistical charting with interactive geospatial mapping.

---

## 🚀 Key Features
* **Seasonal Distribution Analysis (VIS 1):** Visualizes the proportional presence of bird species across the four seasons using a 100% stacked bar chart.
* **Interactive Proportional Map:** Displays geographic sighting locations with circle markers scaled according to the frequency of observations in each area.
* **Dynamic Filtering:** Allows real-time filtering by **Species** and **Season**, enabling users to uncover specific migration stories (e.g., the Swift Parrot migration).
* **Responsive Design:** Features a professional layout including a control panel, data narratives, and a spatial visualization pane.

## 🛠 Tech Stack
* **Language:** R
* **Framework:** [Shiny](https://shiny.rstudio.com/)
* **Data Visualization:**
    * `ggplot2` (Statistical plotting)
    * `leaflet` (Interactive mapping)
* **Data Wrangling:** `dplyr`, `lubridate`
* **UI Customization:** `htmltools`, CSS

## 📂 Project Structure
```text
├── ALA_PE2S12026.csv      # Primary dataset (Atlas of Living Australia)
├── app.R                  # Main Shiny application script
├── README.md              # Project documentation
└── Visualisation_Reflection.pdf    # Design justification and reflection report
