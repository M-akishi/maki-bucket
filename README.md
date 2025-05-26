# 🪣 maki-bucket

Este es un bucket personal para [Scoop](https://scoop.sh), el gestor de paquetes para Windows desde la línea de comandos.

## Aplicaciones disponibles

| Nombre           | Descripción                                                                                  |
|------------------|----------------------------------------------------------------------------------------------|
| animeflv_cli     | Scrapper CLI para buscar y reproducir anime desde AnimeFLV usando MPV.                       |
| rojadirecta_cli  | Scrapper CLI para buscar y reproducir eventos deportivos desde RojaDirecta usando MPV.       |

## Dependencias

mpv

## Instalación

### 1. Instalar Scoop (si no lo tienes)

Abre PowerShell **como administrador** y ejecuta:

```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
