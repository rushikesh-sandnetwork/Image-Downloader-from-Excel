
# 📸 Image Downloader – Sand Network

A Streamlit app to extract and download images from Excel files.

---

## ✅ Features

- Upload `.xls` / `.xlsx` files
- Enter base image URL
- Choose folder grouping (e.g., Village)
- Auto-download and ZIP images folder-wise
- Download directly in browser
- Branded with Sand Network logo

---

## 📁 Excel Format

Your Excel must have at least:

- `PHOTOURL` (image filename)
- Any folder column (e.g., `Village`)

Example:

| Village | PHOTOURL                             |
|---------|--------------------------------------|
| Katra   | myimage_projectdata_220_2734_133.jpg |

---

## ⚙️ Requirements

Create `requirements.txt`:

```
streamlit
pandas
requests
openpyxl
xlrd
```

Install:

```bash
pip install -r requirements.txt
```

---

## 🚀 Run the App

```bash
streamlit run image_downloader_app.py
```

App opens in your browser (Chrome preferred).

---

## 🏢 Powered by Sand Network

![Sand Logo](https://sandnetwork.in/wp-content/uploads/2024/02/sand-logo.png)
