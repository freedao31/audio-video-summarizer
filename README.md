# Audio-video-summarizer
Audio Summarizer es una aplicación que permite convertir audio a texto y resumir el texto utilizando técnicas de inteligencia artificial. La aplicación es útil para aquellos que necesitan procesar grandes cantidades de audio y extraer información relevante de manera rápida y eficiente.

# Requisitos
```
pip install -r requirements.txt
```

## Si deseas correr whisper localmente
### pytorch-gpu
Entra aqui para poder generar el comando que te permita instalar el pytorch correspondiente a tu maquina y ambiente: 
https://pytorch.org/get-started/locally/

### cuda
De no disponer de cuda, Krish Naik dispone de un buenisimo tutorial de como instalarlo
https://www.youtube.com/watch?v=StH5YNrY0mE

# Ejemplo
### Video subido
<img src="Resources/team-meetting.jpg" alt="team meeting" width="400" height="300">
Fuente:https://www.youtube.com/watch?v=k8K6wQLxooU&t=538s

### Resultado
<img src="Resources/team-meetting-result.jpg" alt="Result team meeting" width="800" height="600">

# Como utilizar la app
Para convertir el audio a texto y resumir los resultados, sigue los siguientes pasos:

1. Abre una terminal y ejecuta la aplicación utilizando el siguiente comando:
```
flask run
```

2. En la terminal podras ver la url del servidor web donde se esta ejecutando la aplicacion, por ejemplo: http://127.0.0.1:5000 Pega la url en el navegador


3. Darle click en "Choose file" y escoge el archivo de audio o video que deseas resumir

4. En la terminal podras ver como realiza el proceso, al terminar podras ver en la app y la terminal el resultado

# Contribucion
Si deseas contribuir a Audio Summarizer, por favor envía un pull request con tus cambios. Asegúrate de que tus cambios sean coherentes con la visión de la aplicación y que hayas incluido pruebas adecuadas. También puedes sugerir nuevas características abriendo un issue en el repositorio.
