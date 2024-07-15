# Proyecto de Lectura y Análisis de Facturas en PDF

## Descripción

Este proyecto tiene como objetivo automatizar la extracción de información de facturas en formato PDF, almacenar los datos extraídos en una base de datos SQLite y generar gráficos que representen visualmente los saldos mensuales y las cuotas a vencer. Utiliza la biblioteca `pdfplumber` para la extracción de texto de los PDFs y `matplotlib` para la generación de gráficos.

## Requisitos

Para ejecutar este proyecto, necesitarás tener instaladas las siguientes bibliotecas de Python:

- `pdfplumber`
- `re` (incluida en la biblioteca estándar de Python)
- `decimal` (incluida en la biblioteca estándar de Python)
- `sqlite3` (incluida en la biblioteca estándar de Python)
- `os` (incluida en la biblioteca estándar de Python)
- `matplotlib`
- `datetime` (incluida en la biblioteca estándar de Python)

Puedes instalar las bibliotecas adicionales usando pip:

```bash
pip install pdfplumber matplotlib
