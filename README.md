# ¿Cuál es la tendencia de Netflix en Latam?
## Proyecto para Netflix LATAM 

Análisis exploratorio y storytelling del catálogo de Netflix en Latinoamérica. 

---

## 📖 Descripción

Este repositorio contiene un Jupyter Notebook que explora y visualiza cómo Netflix ha alimentado su catálogo en Latinoamérica entre 2011 y 2021. A través de filtros por país, tendencias temporales, géneros y palabras clave, descubrimos patrones de estreno, meses pico, países protagonistas. 

El reporte final  se encuentra narrado con temática a la serie de Bridgerton. 

Disponible en: [https://drive.google.com/drive/folders/1nRV31uhFGLT44LePaOL3hz3TAxIPxmJ8?usp=sharing](https://drive.google.com/drive/folders/1nRV31uhFGLT44LePaOL3hz3TAxIPxmJ8?usp=sharing)


---

## 📥 Dataset

* **Fuente**: Shivam Bansal – “Netflix Movies and TV Shows” en Kaggle
  [https://www.kaggle.com/datasets/shivamb/netflix-shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

> **Nota**: Por políticas de Kaggle, el CSV original no está incluido en este repositorio.
> Descárgalo y colócalo en `data/netflix_titles.csv` antes de ejecutar el notebook.

---

## ⚙️ Instalación y dependencias

1. Clona este repositorio:

   ```bash
   git clone https://github.com/CharlyTrejo/Netflix_latam.git
   cd Netflix_latam
   ```
2. Crea un entorno virtual e instala dependencias:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate    # Linux & Mac  
   .venv\Scripts\activate       # Windows  
   pip install -r requirements.txt
   ```

---

## 🚀 Uso

1. Asegúrate de haber descargado `netflix_titles.csv` en la carpeta `data/`.
2. Ejecuta el notebook con Jupyter:

   ```bash
   jupyter notebook notebooks/netflix_latam_analysis.ipynb
   ```
3. Sigue las celdas del notebook para reproducir:

   * Filtrado por países LATAM
   * Tendencias por año y mes
   * Análisis de géneros y palabras clave
   * Mapas de calor y gráficas de barras

---

## 📊 Resultados

En el notebook encontrarás:

* Gráficos de lanzamientos por país, año y mes
* Distribución películas vs. series
* Barplots de géneros más comunes
* Word cloud de términos frecuentes en títulos