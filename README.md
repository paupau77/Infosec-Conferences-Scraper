# 🔎 Infosec Conferences Scraper

[![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)](https://www.python.org/)  
[![Playwright](https://img.shields.io/badge/Playwright-Automation-brightgreen?logo=microsoft)](https://playwright.dev/python/)  
[![Excel Export](https://img.shields.io/badge/Export-Excel%20(.xlsx)-orange?logo=microsoft-excel)](https://openpyxl.readthedocs.io/en/stable/)  
[![License](https://img.shields.io/badge/License-MIT-purple)](LICENSE)

## 📌 Descripción
Este proyecto es un **web scraper en Python con Playwright** que extrae de [Infosec-Conferences](https://infosec-conferences.com/) una lista detallada de **eventos de ciberseguridad**.  
Guarda toda la información en un archivo Excel (`.xlsx`), incluyendo una columna con la **descripción detallada de cada evento**.

## ⚡ Funcionalidades
- Navegación automática con **Playwright**  
- Extracción de datos de tablas y descripciones individuales de eventos  
- Exportación en **Excel** con columnas autoajustadas  
- Modo **debug visual** (navegador no headless)

## 📂 Archivos del repo
- `AppScrappingdetallado.py` → Script principal de scraping  
- `infosec_conferences.csv` → Ejemplo de salida con eventos  
- `infosec_conferences_full.xlsx` → Archivo generado con detalle completo  

## 🚀 Uso
1. Clona el repo:
   
   git clone https://github.com/tu-usuario/infosec-conferences-scraper.git
   cd infosec-conferences-scraper

2. Instala dependencias:

pip install playwright openpyxl
playwright install


3. Ejecuta el scraper:

python AppScrappingdetallado.py


4. Obtendrás un archivo Excel con todos los eventos scrapeados.



🛠️ Requisitos

Python 3.10+

Playwright

Openpyxl


📜 Licencia

Mi proyecto se distribuye bajo licencia MIT.
