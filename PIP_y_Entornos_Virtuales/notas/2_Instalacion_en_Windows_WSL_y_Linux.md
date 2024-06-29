# Instalación en Windows (WSL) y Linux

## Fecha
**Fecha de la lección:** 2024-06-29

## Objetivo de la lección
- [x] Instalar Python en Windows.
- [x] Instalar Python en Linux

## Instalación
- Instalación de Python:
```bash
sudo apt update && sudo apt -y upgrade
```
- Verificar la Instalación de Python:
```bash
python3 -V
```
- Instalar el paquete gestor de dependencias en Python:
```bash
sudo apt install -y python3-pip
```
- Verificar la version de la instalación sea correcta:
```bash
pip3 -V
```
- Instalación de dependencias para un entorno profesional:
```bash
sudo apt install -y build-essential libssl-dev libffi-dev python3-dev
```

Los anteriores fueron los pasos para tener Python en un entorno profesional.



## Lecturas recomendadas
- [Platzi: Cursos online profesionales en tecnología](https://platzi.com/clases/2292-terminal/53893-opcional-instalar-wsl-usa-linux-dentro-de-windows/)