# 📄 PDF Toolkit Web App

A modern, full-stack web application that allows users to perform common PDF operations like splitting, merging, and compressing files — all through a clean and responsive user interface.

## ✨ Features

- 🔀 **Split PDF** – Break a large PDF into individual pages or a selected range.
- ➕ **Merge PDFs** – Combine multiple PDFs into one file in a specific order.
- 🗜️ **Compress PDF** – Reduce file size while maintaining quality.

- 🔐 **Password Protection** – Add or remove passwords on PDF files. *(optional)*
- 🖋️ **Watermark** – Add custom watermarks to pages. *(optional)*
- 🖼️ **PDF to Image** – Convert PDF pages to PNG or JPEG. *(optional)*
- 🧾 **Preview Pages** – Preview uploaded PDFs before performing actions.
- 📥 **Drag and Drop Uploads** – Simple file upload with progress indicator.

---

## 🚀 Live Demo
Coming soon...

---

## 🛠️ Tech Stack

### Frontend:
- React + Tailwind CSS
- File upload with progress
- Responsive UI for desktop/mobile

### Backend:
- Python (Flask / FastAPI) or Node.js (Express)
- PDF processing with `PyMuPDF`, `PyPDF2`, `pdf-lib` *(based on language)*
- File handling and cleanup with secure temporary storage

---

## 📂 Project Structure

```plaintext
pdf-toolkit/
├── client/                 # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       └── App.jsx
├── server/                 # Flask or Node.js backend
│   ├── routes/
│   ├── pdf_utils/
│   └── app.py or index.js
├── README.md
└── package.json / requirements.txt

