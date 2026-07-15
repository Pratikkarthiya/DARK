# Photo-Resize

A web app for resizing and compressing photos and PDFs for various document formats (DL, NSDL, Parivahan).

## Features

- **DL Photo & Signature Resize** — Sarathi/Parivahan dimensions (420×525 and 256×64)
- **NSDL Photo & Signature Resize** — NSDL Demat dimensions (197×276 and 354×157)
- **PDF Compressor** — Compress PDFs to a target size (minimum 270 KB)
- **Local Processing** — All operations run in your browser; no server uploads

## How to Use

1. Open [Photo resize.html](Photo%20resize.html) or visit the deployed app
2. Upload your photo or signature
3. Download the resized file in the required format

## Deploy to Render

1. **Create a Static Site** on [Render](https://render.com)
2. **Connect this repository** as the source
3. **Set publish directory** to `./`
4. **Deploy** — the app will be live in seconds

### Environment
- Type: Static Site
- Build Command: (leave empty)
- Publish Directory: `./`

## Files

- `index.html` — Entry point (redirects to Photo resize.html)
- `Photo resize.html` — Main application
- `render.yaml` — Render deployment configuration

## License

See [LICENSE](LICENSE) file for details.
