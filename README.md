# My Blog Project

Este es un proyecto de blog utilizando FastAPI para el backend y React para el frontend.

## Configuración del Backend

1. Navega al directorio `backend`:
    ```bash
    cd backend
    ```

2. Crea y activa un entorno virtual:
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

3. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

4. Ejecuta el servidor:
    ```bash
    uvicorn app.main:app --reload
    ```

## Configuración del Frontend

1. Navega al directorio `frontend`:
    ```bash
    cd frontend
    ```

2. Instala las dependencias:
    ```bash
    npm install
    ```

3. Ejecuta la aplicación:
    ```bash
    npm run dev
    ```

## Despliegue

Instrucciones para desplegar la aplicación en [Heroku](https://www.heroku.com/), [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/) o [Azure](https://azure.microsoft.com/).
