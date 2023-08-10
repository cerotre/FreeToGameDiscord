# 🎮 FreeToGameDiscord: Notificador de Juegos Gratuitos para Discord

## 📄 Descripción

FreeToGameDiscord es una herramienta que te permite estar al tanto de los juegos gratuitos disponibles en la plataforma PC a través de notificaciones en tu servidor de Discord. A diferencia de un programa que se ejecuta automáticamente cuando se actualiza la API, FreeToGameDiscord te permite controlar cuándo obtener y enviar las notificaciones. Cada vez que ejecutes el script, comenzará desde el primer juego y enviará notificaciones hasta el último.


## ⭐ Características

- Utiliza la API de FreeToGame para obtener la lista de juegos gratuitos disponibles en PC.
- Crea mensajes en formato de "embed" para notificar sobre los juegos en Discord.
- Reintentos automáticos en caso de error al enviar una notificación a Discord.
- Control de velocidad para respetar las restricciones de la API de Discord.
- Muestra la fecha y hora de envío en el pie del mensaje "embed".

## 💻 Uso

1. Ejecuta el script proporcionando la URL del webhook de Discord cuando se solicite.
2. El script obtendrá la lista de juegos gratuitos utilizando la API de FreeToGame y enviará notificaciones a través del webhook.

## 📋 Requisitos

- Python 3.x
- Bibliotecas: `requests`

## 🚀 Instrucciones de Ejecución

1. Clona este repositorio en tu máquina local.
2. Abre una terminal y navega hasta la carpeta del proyecto.
3. Instala las bibliotecas necesarias si aún no lo has hecho: `pip install requests`
4. Ejecuta el script: `python free_to_game.py`
