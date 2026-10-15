# CC.MSCA2102FLE.B03.202630.1_al07183971---Modulo02_T04

# Benchmark Multi-Paradigma de Modelos de Inteligencia Artificial

## Descripción del Proyecto
Este proyecto realiza un análisis comparativo de rendimiento (Benchmarking) entre tres paradigmas diferentes de Machine Learning utilizando modelos preentrenados de Hugging Face:
1. **Procesamiento de Lenguaje Natural (NLP):** Clasificación de texto con DistilBERT en el dataset SST-2.
2. **Visión por Computadora:** Clasificación de imágenes utilizando Vision Transformers (ViT).
3. **Modelos Multimodales:** Clasificación Zero-Shot utilizando CLIP.

Evalúa métricas clave de calidad predictiva (Accuracy, Precision, Recall, F1-Score) frente al costo computacional de tiempo (Latencia en milisegundos).

## Entorno de Ejecución
El proyecto se diseñó para ejecutarse utilizando **Python 3.10+** y aceleración por GPU (CUDA) para optimizar los tiempos de inferencia de las redes neuronales deep learning.

### Requisitos de Software
Las dependencias se administran mediante un entorno virtual utilizando `requirements.txt`.

## Pasos de Ejecución

1. **Clonar el repositorio:**
   ```bash
   git clone <https://github.com/alvarocoronaj/CC.MSCA2102FLE.B03.202630.1_al07183971---Modulo02_T04>
   cd mi-proyecto-benchmark
