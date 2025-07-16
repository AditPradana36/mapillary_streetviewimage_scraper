# 🖼️ Mapillary Street-View Image Scraper

A Google Colab-based tool to extract **Mapillary street-level images** using a list of coordinates stored in an Excel file. This scraper is designed for researchers, urban analysts, and geospatial developers who need street imagery for specific locations and years.

![ezgif-70e289bb36849e](https://github.com/user-attachments/assets/ea602da1-64f4-4ba5-a414-6b7545058c2f)

---

## 🎯 Features

- ✅ Scrape the **newest image** per coordinate point
- 📅 Filter images by a **specific year**
- 🔁 Filter images across a **range of years**
- 📁 Save images and metadata (Excel format)
- 🧭 Fully customizable: buffer size, year input, and file paths
- 🎓 Built for **Colab interactivity** with `#@param` input fields
- (soon) Panoramic and Non-panoramic filter
---

## 🧩 Use Cases

- Temporal comparison of urban form  
- Ground-truth validation using street imagery  
- Urban greenery or infrastructure mapping  
- Image-based dataset generation for computer vision  

---

## 📄 Required Excel Format

The input file must be `.xlsx` and contain:

| ID | X | Y  |
|----|---------------|--------------|
| 1  | 106.9023591   | -6.3759857   |
| 2  | 106.8292590   | -6.3672050   |
| ...| ...           | ...          |

Upload manually or load from Google Drive.

---

## 🔧 How to Use

1. 🌐 Open the notebook in [HERE](mapillary_streetviewimage_scraper.ipynb)
2. 🔑 Paste your Mapillary access token from [mapillary.com](mapillary.com)
3. 📥 Upload or link your Excel file
4. 🎯 Choose your method:
   - Newest image
   - Filter by year
   - Filter by year range
5. ▶️ Run the notebook
6. 📂 Images and `.xlsx` metadata will be automatically saved to your specified `{output_dir}` folder

---

## 📦 Dependencies

- `mercantile`
- `mapbox-vector-tile`
- `vt2geojson`
- `pandas`, `openpyxl`
- `requests`

All installable directly from Colab.

---

## 🙋 Author

Mohammad Raditia Pradana | [LinkedIn](https://www.linkedin.com/in/mohammadraditia/) | 2025
