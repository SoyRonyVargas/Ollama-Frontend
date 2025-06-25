# Chat Web para DeepSeek-R1 con Ollama

## Descripción

Interfaz web de chat que permite interactuar con el modelo de inteligencia artificial DeepSeek-R1 utilizando Ollama como backend. Ofrece persistencia de conversaciones, formateo avanzado de respuestas y un diseño moderno en tonos azules.

## Características principales

- **Conexión con DeepSeek-R1**: Interacción con el modelo de IA a través de la API de Ollama
- **Persistencia de conversaciones**: Historial guardado automáticamente en localStorage
- **Formateo avanzado**: Soporte para código, encabezados, listas y bloques de cita
- **Diseño moderno**: Interfaz limpia con paleta de colores azules y animaciones
- **Responsive**: Funciona en dispositivos móviles y de escritorio
- **Indicador de escritura**: Visualización animada durante la generación de respuestas

## Requisitos previos

1. Tener [Ollama](https://ollama.com/) instalado y funcionando
2. Descargar el modelo DeepSeek-R1:
```bash
   ollama pull deepseek-r1
```

## Uso

- Abrir el archivo HTML en el navegador
- Escribir mensajes en el área de texto inferior
- Presionar Enter o el botón de enviar (➤)
- Esperar la respuesta del modelo

## Funcionalidades adicionales

- Limpiar chat: Botón 🗑️ para borrar el historial
- Formateo Markdown: Soporte para sintaxis Markdown en respuestas
- Resaltado de sintaxis: Bloques de código con resaltado adecuado
- Área de texto adaptable: Campo de entrada que se expande automáticamente