# App FastAPI en la nube 🚀

## Descripción

Aplicación simple desarrollada con FastAPI, desplegada en Render como parte de la preparación de un entorno técnico para soluciones de datos e IA.

## Tecnologías

* Python
* FastAPI
* Docker
* GitHub
* GitHub Actions
* Render

## Endpoints

* `/` → Mensaje principal
* `/saludo/{nombre}` → Saludo personalizado

## Ejecución local

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

## Docker

```bash
docker build -t app .
docker run -p 10000:10000 app
```

## CI/CD

Se configuró GitHub Actions para automatizar la instalación de dependencias en cada push.

## Despliegue

Aplicación desplegada en Render.

## URL

https://proyecto-ia-nube.onrender.com

## Alternativas investigadas

* Vercel: Plataforma enfocada en aplicaciones frontend y    serverless. Es muy fácil de usar y permite despliegues automáticos desde GitHub.

* Railway: Permite desplegar aplicaciones rápidamente con soporte para bases de datos. Es simple y amigable para proyectos pequeños.

* Fly.io: Plataforma que permite desplegar aplicaciones en contenedores cerca de los usuarios, ideal para aplicaciones distribuidas.

![Main]({40A9DD3A-392B-410B-A778-B81173303853}.png)
![Dockerfile]({39040093-255E-4D64-83FC-E16F52940666}.png)
![Requirements]({3AB1343F-33D2-4585-9815-02CDA100E38B}.png)
![Evidencia]({718A7E70-A57D-4F2D-923F-1F472B40B8D0}.png)