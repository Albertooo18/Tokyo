# Tokyo

# Proyecto de Reconocimiento de Imágenes y Chatbot con Machine Learning

## Descripción

Este repositorio contiene un proyecto que realiza reconocimiento de imágenes utilizando Python y bibliotecas de Machine Learning para clasificar códigos de barras en archivos CSV. Además, incluye un chatbot que puede acceder a la información de estos archivos CSV y responder preguntas relacionadas con los mismos.

## Características

1. **Reconocimiento de Imágenes**:
   - Utiliza bibliotecas de Python especializadas en Machine Learning y procesamiento de imágenes.
   - Clasificación de códigos de barras a partir de imágenes.
   - Exportación de los datos clasificados a archivos CSV.

2. **Chatbot**:
   - Implementado en Python.
   - Capaz de acceder a los archivos CSV generados.
   - Responde preguntas sobre la información contenida en los CSV.

## Instalación

Para utilizar este proyecto, sigue los siguientes pasos:

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tu_usuario/tu_repositorio.git
    cd tu_repositorio
    ```

2. Crea un entorno virtual:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

3. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

### Reconocimiento de Imágenes

Para ejecutar el script de reconocimiento de imágenes y clasificar los códigos de barras, usa el siguiente comando:

```bash
python image_recognition.py --input /ruta/a/imagenes --output /ruta/a/archivos_csv
```

### Chatbot

Para iniciar el chatbot y hacer preguntas sobre la información en los archivos CSV, usa:

```bash
python app.py
```

## Estructura del Proyecto

```
.
├── chatbot
│   ├── static/           # Archivos estáticos como CSS y JavaScript
│   ├── templates/        # Plantillas HTML
│   ├── app.py            # Ejecuta el Servicio para levantar la página para hablar con el Chatbot
│   └── chatbot.py        # Contiene el código principal para comunicarse con el Chatbot
├── data
│   ├── raw               # Imágenes originales
│   └── processed         # CSV generados
├── src
│   ├── image_recognition # Scripts de reconocimiento de imágenes
│   └── chatbot           # Scripts del chatbot
├── tests                 # Pruebas unitarias
├── requirements.txt      # Dependencias del proyecto
├── README.md             # Documentación del proyecto
└── .gitignore            # Archivos y carpetas a ignorar por git
└── Tokyo                 # venv
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Contacto

Para cualquier consulta, por favor contacta a [cristiannmendoza18@gmail.com](cristiannmendoza18@gmail.com).

---

Este README proporciona una descripción general de cómo instalar, usar y contribuir a este proyecto. Para más detalles, consulta la documentación en el código fuente y los archivos de ejemplo proporcionados.
