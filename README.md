# CMEMS vs. In‑situ Temperature Validation – Silba Island

Interactive HTML figures validating Copernicus Marine Environment Monitoring Service (CMEMS) sea surface temperature data against *in‑situ* logger measurements in the coastal waters of Silba Island (Adriatic Sea).

These visualizations supplement a Master's thesis that quantitatively assesses the reliability of modelled temperature data for ecological monitoring in the Adriatic.

## 📊 Contents – Validation Workflow

| File | Description |
|------|-------------|
| `index.html` | Overview page linking all validation plots |
| `comparison_copernicus_logger_interactive.html` | **Core validation plot** – direct comparison of CMEMS satellite data with in‑situ logger measurements |
| `logger_daily_all_depths_interactive.html` | Ground‑truth daily temperature averages from in‑situ loggers |
| `logger_raw_all_depths_interactive.html` | Raw, unprocessed logger data used as the reference for validation |
| `temp_2015_2024_by_depth_interactive.html` | Broader spatial context – CMEMS temperature trends for the entire Adriatic Sea (2015–2024) |
| `temp_silba_2015_2024_by_depth_interactive.html` | Local CMEMS temperature trends for the Silba polygon (extracted for direct comparison with loggers) |

## 🔍 Validation Results

The comparison of in‑situ measurements with CMEMS data shows strong agreement, with a **mean deviation of only 0.212 °C**, confirming the reliability of modelled data for monitoring temperature patterns in the study area. Marine heatwave analysis between 2015–2024 revealed multiple thermal anomalies, with the most intense events occurring during summer months.

## 🌐 Interactive Preview

👉 You can view and interact with all plots live here:  
**[ https://vidaivankovic.github.io/cmems-in-situ-temperature-validation-silba/)**  


## 🚀 How to use locally

1. Download and extract the ZIP archive.
2. Double‑click `index.html` to open it in your browser.
3. All plots are fully interactive – hover, zoom, and explore the validation results.

## 📍 Data sources

- **CMEMS Copernicus** – Modelled sea surface temperature data  
- **In‑situ loggers** – Field measurements (10‑month monitoring at multiple depths)  
- **QGIS** – Polygon extraction for the Silba island area

## 📌 Citation

If you use these visualizations, please cite the accompanying Master's thesis:

> Ivanković, V. (2026). *Mass mortality as an indicator of ecological stress: an assessment of the population status of the coral Cladocora caespitosa in the coastal waters of Silba Island*.  (Master's thesis, Sveučilište u Zagrebu, Prirodoslovno-matematički fakultet, Biološki odsjek).
