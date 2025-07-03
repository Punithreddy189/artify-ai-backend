# Artify AI Backend (Flask)

Flask backend for Artify AI that handles image style transfer using Replicate.

## How It Works

- Accepts POST request with `imageUrl` and `style`
- Uses Replicate's Stable Diffusion image-to-image API
- Returns stylized image URL

## Run Locally

```bash
pip install -r requirements.txt
export REPLICATE_API_TOKEN=your_token_here
python app.py
