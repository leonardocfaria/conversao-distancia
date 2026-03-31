# conversao-distancia

A Flask web app for distance/unit conversion, containerised with Docker.

> Forked from [KubeDev/conversao-distancia](https://github.com/KubeDev/conversao-distancia)

## Tech Stack

- Python
- Flask
- Docker

## Getting Started

### Run with Docker

```bash
docker build -t conversao-distancia .
docker run -p 5000:5000 conversao-distancia
```

### Run locally

```bash
pip install -r requirements.txt
python app.py
```

Then open [http://localhost:5000](http://localhost:5000).
