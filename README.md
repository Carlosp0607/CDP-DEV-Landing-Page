# CDP DEV — Landing Page

Portafolio personal de Carlos Daniel Polanco Turizo, Ingeniero de Software. Reúne los proyectos desplegados, el stack y las vías de contacto en una sola página.

**En línea:** [cdp-dev-landing-page.vercel.app](https://cdp-dev-landing-page.vercel.app)

---

## Qué contiene

- Perfil profesional y stack técnico.
- Cinco proyectos, cada uno con enlace al repositorio y a la demo en funcionamiento.
- Descarga directa de la hoja de vida en PDF.
- Contacto: correo, GitHub y LinkedIn.

---

## Proyectos enlazados

| Proyecto | Descripción | Demo |
|---|---|---|
| **LexDoc** | Gestión de casos jurídicos con control de acceso por roles | [lexdoc.onrender.com](https://lexdoc.onrender.com) |
| **ParkSystem** | SaaS multi-tenant para parqueaderos | [parqueadero-app-zbj3.onrender.com](https://parqueadero-app-zbj3.onrender.com) |
| **MediAssist Rural** | Orientación en salud con IA para zonas rurales | [mediassist-rural.vercel.app](https://mediassist-rural.vercel.app) |
| **Sistema de piscina** | Control de acceso y pagos para clubes acuáticos | [piscina-app.vercel.app](https://piscina-app.vercel.app) |
| **TranscriptoHub** | Procesamiento de secuencias de ARN en Python | Proyecto de grado |

---

## Stack

Sitio estático de un solo archivo. Sin framework, sin dependencias, sin paso de build.

| Componente | Tecnología |
|---|---|
| Estructura | HTML5 |
| Estilos | CSS3 embebido |
| Tipografía | IBM Plex Mono |
| Despliegue | Vercel |

La decisión de mantenerlo en un archivo es deliberada: una página de portafolio no necesita build ni dependencias, y así carga de inmediato y no se rompe con el tiempo.

---

## Ejecución local

No requiere instalación. Basta con abrir el archivo:

```bash
git clone https://github.com/Carlosp0607/CDP-DEV-Landing-Page.git
cd CDP-DEV-Landing-Page
```

Abre `index.html` en el navegador, o levanta un servidor si prefieres:

```bash
python -m http.server 8000
```

---

## Estructura

```
index.html               Página completa: estructura, estilos y contenido
CV_Carlos_Polanco.pdf    Hoja de vida enlazada desde el boton de descarga
```

---

## Contacto

- **Correo:** carlosdanielpolanco0@gmail.com
- **GitHub:** [Carlosp0607](https://github.com/Carlosp0607)
- **LinkedIn:** [carlos-daniel-polanco](https://www.linkedin.com/in/carlos-daniel-polanco-930115328)
