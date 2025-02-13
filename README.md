# ERP Simulator API

Este proyecto utiliza `json-server` para simular una API. A continuación, se detallan los pasos para inicializar la API utilizando el archivo `db.json`.

## Requisitos

- Node.js instalado en tu máquina.

## Instalación

1. Clona el repositorio:

    ```bash
    git clone https://github.com/tu-usuario/ERP_simulator.git
    cd ERP_simulator
    ```

2. Instala `json-server` globalmente:

    ```bash
    npm install -g json-server
    ```

## Inicialización
1. Inicia el servidor `json-server` utilizando el archivo `db.json`:

    ```bash
    json-server --watch db.json
    ```

3. La API estará disponible en `http://localhost:3000`.

