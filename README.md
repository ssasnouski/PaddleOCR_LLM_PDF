# OCR PDF Builder
Simple exemple of building multi-page searchable PDF documents with OCR text layer, optimized file size, and post-OCR correction with LLM

A tool for building multi-page **searchable PDF** documents from images (`.png`)
with an **invisible OCR text layer**, optimized file size, and post-OCR correction with Gemini-2.0-flash.

## Features

- 📄 Build multi-page PDF from PNG images
- 🔍 Invisible OCR text layer (search & copy)
- 🧠 Automatic font size fitting per text line
- 🖼 Image compression (JPEG + downscale)
- ⚖ Uniform page size for text and image pages
- 🚀 GPU acceleration with CUDA (PaddleOCR)
- ✨ OCR error correction using Gemini models
- 📉 Significant PDF size reduction

## Tech Stack

- Python
- PaddleOCR (CUDA)
- PyMuPDF (fitz)
- Pillow
- Gemini (OCR text correction)

## Input

- `*.pdf` / `*.png` — document pages
- `*_res.json` — PaddleOCR OCR results

## Output

- `output.pdf` — optimized searchable PDF

## Use Cases

- Scanned books and documents
- Digital archiving
- OCR processing for PDFs
- Full-text search in scanned documents

## License

MIT
