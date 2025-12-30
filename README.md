# Image to PDF Converter

A super clean, modern desktop app to turn your photos into PDFs. Drag & drop (or browse), preview with thumbnails, and export with perfect colors/orientation. Built for Linux/Debian but works everywhere!

## Features
- **Modern dark UI** with CustomTkinter (looks native!)
- **Image previews** with correct colors (no more weird rotations)
- **File size display** and individual remove buttons
- **Progress bar** during conversion
- **Handles EXIF orientation** automatically
- **High-quality PDF** output (150 DPI)
- **Super lightweight** - no bloat!

## Quick Start

1. **Clone & install**
```bash

git clone https://github.com/VasilisKokotakis/PDF-Converter.git
cd image-to-pdf-converter
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate  # Windows
pip install -r requirements.txt
```

2. **Run it**
```bash
python modern_image_to_pdf.py
```

3. **Use it**
- Click **"Browse Files"**
- Select your images (JPG, PNG, WebP, etc.)
- Thumbnails appear with file sizes
- Click **"Convert to PDF"**
- Save your perfect PDF!

## Tech Stack
- **Python 3.12+**
- [CustomTkinter](https://customtkinter.tomschimansky.com/) - Modern UI
- [Pillow](https://pillow.readthedocs.io/) - Image processing
- **Zero dependencies** beyond these two!

## requirements.txt
```
customtkinter
pillow
```

## Pro Tips
- **Phone photos?** EXIF rotation fixed automatically!
- **Large batches?** Progress bar shows real-time status
- **Make executable:** `pip install pyinstaller && pyinstaller --onefile modern_image_to_pdf.py`
- **Works offline** - 100% local processing

## Contributing
Found a bug? Have a feature idea? Open an issue or PR!

```
1. Fork the repo
2. Create your feature branch (`git checkout -b my-cool-feature`)
3. Commit changes (`git commit -m "Add cool feature"`)
4. Push (`git push origin my-cool-feature`)
5. Open Pull Request!
```

***
---

> *Perfect for receipts, screenshots, drone photos, or any image batch you need as PDF!* 🚀

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/42513711/73187880-0713-42fa-b4c4-a8312c572ab9/image.jpg)
