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

Desde la raíz del repositorio:

```bash
python3 -m http.server 8000
```

Abre en el navegador:

- `http://127.0.0.1:8000/GymUPM/home.html`
- `http://127.0.0.1:8000/GymUPM/registro_socio.html`

## Hosting recomendado

Sí, este proyecto se puede hostear como web estática.

### Opción 1: GitHub Pages (recomendada)

1. Ve a `Settings -> Pages`.
2. En `Build and deployment`, selecciona `Deploy from a branch`.
3. Elige la rama `master` (o `main`) y carpeta `/ (root)`.
4. Guarda y espera el despliegue.

Con la estructura actual, la URL de la app será:

- `https://<usuario>.github.io/<repo>/GymUPM/home.html`

### Opción 2: Netlify/Vercel (estático)

- Publica el directorio `GymUPM/` como carpeta de salida.
- No requiere build.

## Requisitos

- Navegador web moderno.
- (Opcional para local) Python 3 para servir archivos estáticos.
- (Opcional para editar como app UWP) Visual Studio con soporte UWP/JavaScript.

## Mejoras sugeridas

- Añadir `index.html` en raíz para redirigir automáticamente a `GymUPM/home.html`.
- Validación de formularios y almacenamiento real (API/backend).
- Separar CSS inline de las páginas en archivos dedicados.
- Corregir detalles HTML menores (por ejemplo, `meta charset` en `registro_socio.html`).

