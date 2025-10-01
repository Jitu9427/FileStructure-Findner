# File Structure Finder

A Flask-based web application that fetches and visualizes the directory structure of any public GitHub repository.  
You can also download the repository structure as a Word document.

---

## Features
- Input a GitHub repository URL and branch name
- Display the repository structure in a tree view format
- Download the structure as a Word (`.docx`) file
- Dockerized for easy deployment

---

## Requirements
- Python 3.11+
- Flask
- Requests
- python-docx

---

## Installation

```bash
git clone https://github.com/your-username/file-structure-finder.git
cd file-structure-finder
pip install -r requirements.txt
```

## Usage

```bash
python app.py
```

Open your browser at:

http://localhost:5000


## Docker setup

Build Docker Image

```bash
docker build -t filestructure-finder .
```

Run Docker Container

```bash
docker run -d -p 5000:5000 filestructure-finder
```

Open in browser:

```bash
http://localhost:5000
```
