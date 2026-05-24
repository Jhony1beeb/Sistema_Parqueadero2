# 🚗 Sistema de Reservas de Parqueadero

Proyecto universitario desarrollado para la materia de **Ingeniería de Software**.

## ¿Qué es?

Aplicación web para gestionar el parqueadero de una institución. Permite registrar la entrada y salida de vehículos (carros, motos y bicicletas), controlar los espacios disponibles y generar reportes de uso.

## Funcionalidades

- Login seguro con correo y contraseña
- Control de espacios en tiempo real
- Registro de tickets por tipo de vehículo
- Filtros por vehículo y estado
- Reportes diarios, semanales y mensuales
- Zona horaria configurada para Colombia

## Tecnologías usadas

- **Python / Flask** — backend y rutas
- **SQLite** — base de datos
- **HTML + CSS** — interfaz de usuario
- **Werkzeug** — hash de contraseñas

## Cómo correrlo

1. Clona el repositorio
2. Instala las dependencias:
   ```
   pip install flask werkzeug
   ```
3. Corre el servidor:
   ```
   python app.py
   ```
4. Abre el navegador en `http://localhost:5002`

## Credenciales de acceso

| Campo | Valor |
|-------|-------|
| Correo | `admin@hotmail.com` |
| Contraseña | `admin1234` |

## Estructura del proyecto

```
├── app.py              # Lógica principal y rutas
├── database.py         # Configuración de la base de datos
├── templates/
│   ├── index.html      # Login
│   ├── dashboard.html  # Panel principal
│   └── reportes.html   # Reportes
└── static/
    └── css/
        └── style.css   # Estilos
```

## Autores

Proyecto desarrollado como trabajo universitario.
