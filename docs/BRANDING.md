# Application icon

The owner supplied the new silver trophy with a lavender star and blue base.
ImageGen removed the white background, including the openings in the handles.

- Transparent source: `assets/logo-master.png`.
- 256-pixel transparent exports: `assets/app.png` and `assets/logo-transparent.png`.
- Windows icon: `assets/app.ico` with sizes from 16 to 256 pixels.

The README and GitHub profile use the transparent PNG. The application header,
Windows executables and installer use the ICO. Regenerate the exports locally:

```powershell
python tools/build_assets.py
```
