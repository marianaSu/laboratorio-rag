# Laboratorio: Sistema RAG

Materia: Ingeniería del Conocmiento

Alumno: Mariana Suastegui Blanco

No. Control: 22211215

## Descripción

En este laboratorio se implementó un sistema básico de Retrieval-Augmented Generation (RAG) utilizando Python en Google Colab.

El sistema combina:

- Embeddings
- Base vectorial FAISS
- Recuperación de información
- Modelo de lenguaje (LLM)

El objetivo fue responder preguntas utilizando documentos almacenados en una base de conocimiento.


# Preguntas de reflexión

## 1. ¿Cuál es la diferencia entre un chatbot normal y un sistema RAG?

Un chatbot normal responde utilizando solo el conocimiento con el que fue entrenado previamente. En cambio, un sistema RAG primero busca información relevante en una base de documentos y después usa esa información como contexto para generar la respuesta. Esto permite que las respuestas estén basadas en información más específica.

## 2. ¿Por qué RAG reduce las alucinaciones del modelo?

RAG reduce las alucinaciones porque antes de responder le proporciona al modelo información real obtenida de los documentos. De esta forma, el modelo puede apoyarse en ese contexto para generar la respuesta en lugar de inventarla completamente.

## 3. ¿Qué ventajas tiene usar una base vectorial?

Una base vectorial permite almacenar la información en forma de embeddings y realizar búsquedas por significado. Esto hace posible encontrar documentos relacionados con una pregunta aunque no tengan exactamente las mismas palabras, lo que mejora la calidad de las respuestas del sistema.
