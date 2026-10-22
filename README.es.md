# Mental Health Chatbot

[English](README.md) | **Español**

## Funcionalidades principales

1. **Carga del dataset**: El chatbot comienza cargando un dataset que contiene ejemplos de conversaciones sobre salud mental. Este dataset se utiliza para entrenar el modelo de inteligencia artificial del chatbot.

2. **Tokenización**: El chatbot procesa el texto del dataset, dividiéndolo en tokens individuales (por ejemplo, palabras). Este es un paso crucial en el procesamiento del lenguaje natural.

3. **Creación del modelo**: El chatbot utiliza un modelo de red neuronal para entender y responder preguntas. Este modelo se crea y configura durante esta etapa.

4. **Entrenamiento del modelo**: Una vez creado el modelo, se entrena utilizando el dataset. Durante este proceso, el modelo aprende a asociar ciertos patrones de palabras con respuestas específicas.

5. **Guardado del modelo**: Una vez entrenado, el modelo se guarda para su uso futuro. Así no es necesario volver a entrenarlo cada vez que se utiliza el chatbot, lo que ahorra tiempo y recursos computacionales. Además, el modelo guardado puede compartirse y reutilizarse, facilitando la reproducibilidad y la colaboración.

6. **Validación del modelo (opcional)**: La validación utiliza datos de prueba para evaluar el rendimiento del modelo y comprobar que puede realizar predicciones precisas sobre datos nuevos.

7. **Despliegue del chat**: Una vez cargado el modelo, se utiliza para interactuar con el usuario y generar una respuesta adecuada a cada entrada.

### Instalación

#### Prerrequisitos
- Python 3.10.11
- pip

#### Pasos
1. Clona el repositorio:
   ```sh
   git clone https://github.com/Fernandolopez2171/mental-health-chatbot.git
   cd mental-health-chatbot
   ```

2. Instala las dependencias del backend:
   ```sh
   pip install -r requirements.txt
   ```

### Uso

#### Scripts principales
1. Ejecuta el entrenamiento de la IA:
   ```sh
   python training.py
   ```

2. Prueba el chatbot en la consola:
   ```sh
   python chat.py
   ```

#### Opcional
Valida el modelo con datos de prueba:
   ```sh
   python validate.py
   ```

#### Despliegue como API
Para utilizar el chatbot como una API, ejecuta:
   ```sh
   python app.py
   ```

[English version](Readme.en.md)
