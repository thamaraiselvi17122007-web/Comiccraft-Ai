# ComicCraft - AI Comic Story Creator

ComicCraft is an AI-powered comic story creator.

It uses:

- FastAPI
- Jinja2
- Google Gemini
- Stable Diffusion through Diffusers
- Pillow
- FPDF
- HTML
- CSS
- JavaScript

The application generates:

1. A comic outline
2. Detailed narration
3. Character dialogue
4. AI-generated illustrations
5. A comic preview
6. A downloadable PDF


# Project Structure

```text
ComicCraft/
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── config.py
│   ├── schemas.py
│   ├── routes.py
│   │
│   └── services/
│       ├── __init__.py
│       ├── gemini_flash.py
│       ├── gemini_pro.py
│       ├── image_generator.py
│       ├── layout_builder.py
│       └── exporters.py
│
├── templates/
│   ├── index.html
│   ├── comic_preview.html
│   └── export_success.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   ├── panels/
│   └── exports/
│
├── tests/
│   └── test_app.py
│
├── .env.example
├── .gitignore
├── pytest.ini
├── requirements.txt
└── README.md