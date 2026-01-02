# 📚 Proyecto 14. Análisis SQL — Plataforma de Libros

## 📌 Descripción del proyecto
El presente repositorio presenta el análisis de datos con SQL sobre una base de datos de una plataforma digital de libros.  

El objetivo es identificar patrones de consumo, popularidad y calidad percibida de libros, autores y editoriales para apoyar la creación de una propuesta de valor para un nuevo producto digital.

---

## 🎯 Objetivo del análisis
Analizar:
- Libros y autores mejor calificados
- Editoriales con mayor volumen de publicaciones relevantes
- Comportamiento de usuarios activos (calificaciones y reseñas)
- Tendencias que ayuden a la toma de decisiones de negocio

---

## 🗂️ Estructura de los datos
Tablas analizadas:
- `books` — información de libros
- `authors` — autores y autoras
- `publishers` — editoriales
- `ratings` — calificaciones de usuarios
- `reviews` — reseñas textuales

Las tablas se relacionan principalmente mediante `book_id`, `author_id` y `publisher_id`.

---

## 📊 Análisis realizados
- Libros publicados después del año 2000  
- Número de reseñas y calificación promedio por libro  
- Editoriales con mayor número de publicaciones (>50 páginas)  
- Autores con mejor calificación promedio (≥50 calificaciones)  
- Análisis de usuarios altamente activos  

---

## 🧠 Hallazgos claves
- La popularidad de un libro no siempre implica mayor satisfacción promedio.
- Autores con alta consistencia en ratings representan activos estratégicos.
- Editoriales con mayor volumen dominan el catálogo, pero no necesariamente la calidad.
- Los usuarios más activos no siempre generan más reseñas textuales.

---

## 📌 Conclusiones
Este proyecto demuestra:
- Dominio de SQL aplicado a bases de datos relacionales
- Capacidad para extraer hallazgos aplicables
- Habilidad para traducir resultados técnicos en conclusiones de negocio**

El análisis puede servir como base para recomendaciones de contenido, curaduría editorial y estrategias de engagement.
e cometer errores. Considera verificar la información importante. Ver preferencias de cookies.

---

## 🛠️ Tecnologías y habilidades
- SQL (PostgreSQL): `JOIN`, `GROUP BY`, `HAVING`, subconsultas, funciones de agregación  
- Python: Pandas y SQLAlchemy para ejecutar consultas  
- Análisis relacional de bases de datos
- Validación y exploración de datos
- Pensamiento analítico orientado a negocio
