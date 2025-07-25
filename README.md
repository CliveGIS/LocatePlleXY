# LocateParcelTool

**LocateParcelTool** is a QGIS plugin that helps users locate parcels by either geographic coordinates (X/Y in Lambert projection) or cadastral identifiers (Nature, Number, Index).

This tool is designed to facilitate fieldwork and data verification for professionals, especially in Morocco (Lambert Nord Zone 1 - EPSG:26191).

---

## 🔍 Features

- Locate any position using X and Y coordinates in Lambert (EPSG:26191).
- Locate parcels using cadastral reference:
  - Nature
  - Number
  - Index
- Highlights all matching parcels with red markers.
- Zooms and selects all parcels found.
- Supports any selected vector layer with matching fields.
- Simple and intuitive interface for daily use.

---

## 🗺️ Use Case

This plugin is especially useful for:
- Cadastral technicians and field agents
- Land registry operators
- Any GIS professional dealing with Moroccan parcel data

---

## 🛠️ Requirements

- QGIS 3.10 or higher
- Python 3
- The target layer must contain at least three fields: `nature`, `numero`, and `indice`.

---

## 🚀 How to Use

1. Open the plugin from the QGIS toolbar.
2. Choose your working vector layer (e.g. Parcelles).
3. Choose between:
   - Coordinate mode: Enter X and Y values.
   - Cadastral mode: Enter Nature, Number, Index.
4. Click "Locate".
5. The map will center and show red markers on results.

---

## 🔒 License

This plugin is licensed under the **GNU General Public License v2+**.

---

## 👤 Author

**Saad Fetah**  
GIS Specialist (Morocco)  
📧 simo.clive@gmail.com

---

## 🌍 Language

The plugin interface is available in French.

---

## 🧩 Plugin Repository

To install this plugin manually, copy the folder to your QGIS plugin directory.

To submit it to the official QGIS Plugin Repository, follow instructions here:  
[https://plugins.qgis.org/](https://plugins.qgis.org/)
