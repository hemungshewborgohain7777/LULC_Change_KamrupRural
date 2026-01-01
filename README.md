# 🌍 LULC Change Detection and Time-Series Analysis of Kamrup (2010–2025)

---

## 1️⃣ Project Overview / Problem Statement
Land Use and Land Cover (LULC) changes are a direct indicator of human–environment interaction. In Kamrup district, rapid population growth, agricultural expansion, urbanization, and river dynamics of the Brahmaputra have significantly altered land cover patterns over time.

This project analyzes **spatio-temporal LULC changes in Kamrup (Rural)** from **2010 to 2025** using supervised classification and change detection techniques. A **change detection matrix** was generated to quantify transitions between land cover classes, providing insights into landscape transformation and environmental impact.

---

## 2️⃣ Objective
The main objectives of this study are:
- To classify LULC for **2010, 2015, 2020, and 2025**
- To quantify **area (km²) and percentage change** of each LULC class
- To analyze **class-to-class transitions** using a change detection matrix
- To identify dominant land cover conversion trends over time
- To demonstrate practical application of **GIS and remote sensing techniques** for change analysis

---

## 3️⃣ Study Area
**Kamrup District (Rural), Assam, India**

- Located along the Brahmaputra River floodplain
- Characterized by agriculture-dominated landscapes, forests, wetlands, and settlements
- Highly dynamic due to river migration, sandbar formation, and human activities

📍 *The study area extent and LULC distribution are shown in the time-series maps and the change detection matrix.*

---

## 4️⃣ Data Sources

### Satellite Data
- **Landsat Series**
  - Landsat 5 / Landsat 7 (2010)
  - Landsat 7 / Landsat 8 (2015)
  - Landsat 8 (2020)
  - Landsat 9 (2025)
- Source: USGS via **USGS Earth Explorer**  
  🔗 [earthexplorer.usgs.gov.com](https://earthexplorer.usgs.gov/)

### Ancillary Data
- Administrative boundary of Kamrup district  
  🔗 https://gadm.org/

---

## 5️⃣ Tools & Methods

### Tools Used
- **USGS Earth Explorer (USGS)** – Image processing and supervised classification
- **ArcGIS** – Post-classification analysis, area calculation, change detection matrix, and cartographic layout

### Methodology
- Selected cloud-free Landsat imagery for **2010, 2015, 2020, and 2025**
- Performed **supervised classification** for the following LULC classes:
  - Agriculture
  - Dense Forest
  - Grasslands
  - Sandbars
  - Settlement
  - Waterbody
- Calculated class-wise **area (km²) and percentage**
- Conducted **post-classification comparison** to detect LULC changes
- Generated a **change detection matrix** to quantify transitions between classes
- Created time-series maps and class-wise change maps for visualization

---

## 6️⃣ Key Outputs (Map Images)
- ✅ LULC classified maps for **2010, 2015, 2020, and 2025**
- ✅ **Time-series LULC comparison map**
- ✅ **Change Detection Matrix (2010–2025)**
- ✅ Class-wise change maps (JPEG format) showing transitions in:
  - Agriculture
  - Dense Forest
  - Grasslands
  - Sandbars
  - Settlement
  - Waterbody
- ✅ Area and percentage statistics embedded in maps

---

## 7️⃣ Results & Interpretation
- Agricultural land shows a **net increase**, indicating expansion into forest and grassland areas
- Dense forest area exhibits a **gradual decline**, suggesting deforestation and land conversion
- Settlement area has increased steadily, reflecting population growth and infrastructure development
- Sandbars and waterbodies show **dynamic fluctuations**, influenced by Brahmaputra river morphology
- The change detection matrix highlights **agriculture and settlement** as dominant transition destinations

---

## 8️⃣ What I Learned
- End-to-end implementation of **LULC classification and change detection**
- Use of **post-classification comparison** for temporal analysis
- Construction and interpretation of **change detection matrices**
- Handling long-term satellite time-series data
- Presenting complex spatial change using clear GIS cartography

---

## 9️⃣ Future Improvements
- Accuracy assessment using **confusion matrix and kappa coefficient**
- Use of higher-resolution data (**Sentinel-2**)
- Integration of **machine learning classifiers** (RF, SVM)
- Incorporation of socio-economic drivers of land use change
- Predictive LULC modeling using **CA-Markov or ANN models**

---
## 🗺️ Maps Included in This Repository

### 1️⃣ LULC Time-Series Analysis Map
**File:** `LULC Kamrup Time-Series.jpg`

- Shows LULC distribution for **2010, 2015, 2020, and 2025**
- Land cover classes:
  - Agriculture
  - Dense Forest
  - Grasslands
  - Sandbars
  - Settlement
  - Waterbody
- Includes **area statistics (km² and %)** and bar charts for each year

---

### 2️⃣ Change Detection Matrix
**File:** `Change Detection Matrix.jpg`

- Displays class-to-class transitions between **2010 and 2025**
- Identifies dominant conversions such as:
  - Agriculture → Settlement
  - Dense Forest → Agriculture
  - Grasslands → Settlement
- Helps quantify land transformation patterns over time

---

### 3️⃣ Class-wise Change Maps
These maps show **individual land cover changes** over the study period:

- `Agriculture.jpg` – Agricultural land change
- `Dense Forest.jpg` – Forest cover change
- `Grasslands.jpg` – Grassland change
- `Sandbars.jpg` – Riverine sandbar dynamics
- `Settlement.jpg` – Urban / rural settlement expansion
- `Waterbody.jpg` – Changes in water bodies

Each map highlights **spatial gain and loss patterns** of the respective class.

---
