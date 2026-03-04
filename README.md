# GymUPM

Aplicación web prototipo para un gimnasio (pantalla de acceso y formulario de alta de socios), desarrollada en HTML/CSS/JavaScript y empaquetada originalmente como proyecto JavaScript de Visual Studio (UWP).

## Estado del proyecto

- Tipo: frontend estático (sin backend).
- Funcionalidades actuales:
  - `home.html`: acceso de usuario y navegación a registro.
  - `registro_socio.html`: formulario de alta de socio.
- Persistencia/autenticación real: no implementada (formularios sin conexión a API o base de datos).

## Estructura

```text
.
├── GymUPM.sln
├── README.md
└── GymUPM/
    ├── GymUPM.jsproj
    ├── package.appxmanifest
    ├── home.html
    ├── registro_socio.html
    ├── css/
    │   └── default.css
    ├── js/
    │   └── main.js
    └── images/
```

## Previsualización local

Abre en el navegador:

- `[http://127.0.0.1:8000](https://amayucas.github.io/gymupm-web-portal//GymUPM/home.html)`
- `[http://127.0.0.1:8000](https://amayucas.github.io/gymupm-web-portal//GymUPM/registro_socio.html)`

## Futuras mejoras

- Añadir `index.html` en raíz para redirigir automáticamente a `GymUPM/home.html`.
- Validación de formularios y almacenamiento real (API/backend).
- Separar CSS inline de las páginas en archivos dedicados.
- Corregir detalles HTML menores (por ejemplo, `meta charset` en `registro_socio.html`).

