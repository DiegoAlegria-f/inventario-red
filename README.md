   # inventario-red

   API de inventario de red con FastAPI. Práctica 3, Programación de Redes (UPQ).

   - **Alumno:** Diego Alegria
   - **Matrícula:** 125053449

   ## Instalación

   ```
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
   ```

   ## Ejecución

   ```
   fastapi dev main.py
   ```

   La documentación interactiva queda en http://127.0.0.1:8000/docs

   ## Rutas

   - `GET /` : estado del servicio
   - `GET /dispositivos` : lista el inventario (filtro opcional `?activo=true`)
   - `GET /dispositivos/{nombre}` : busca un equipo por nombre