# FirstStack - Junior IT Profile Generator

Ayuda a juniors sin experiencia laboral a crear perfiles profesionales de IT utilizando IA para transformar proyectos personales en experiencia profesional más atractiva para recruiters y ATS.

---

## 🚀 Demo Online

https://delightful-island-05c932f10.7.azurestaticapps.net

---

## ✨ Características

- 📝 Generador de perfiles IT con IA
- 💼 Reescritura de proyectos como experiencia profesional
- 🎯 Headlines optimizados para LinkedIn
- 📄 Generación de cover letters
- 🔑 Keywords ATS-friendly
- ☁️ Desplegado en Azure Static Web Apps
- 🔄 CI/CD automático con GitHub Actions

---

## 🛠️ Tech Stack

- **Frontend:** HTML / CSS / JavaScript Vanilla
- **AI API:** Groq API
- **Deployment:** Azure Static Web Apps
- **CI/CD:** GitHub Actions

---

## ⚠️ Importante - API Key

Este proyecto NO incluye una API key real de Groq por motivos de seguridad.

Actualmente la aplicación funciona usando la API key directamente en el frontend (`index.html`).

Sé que esto no es una buena práctica para producción, pero he decidido mantener esta versión simple para fines educativos, portfolio y demostración técnica.

En una futura versión, la API será securizada utilizando:

- Azure Functions
- Variables de entorno
- Azure Key Vault
- Arquitectura serverless

---

# 🔑 Cómo usar el proyecto

## 1. Clonar el repositorio

```bash
git clone https://github.com/juanjo96e/firststack.git
cd firststack
```

---

## 2. Crear una API Key gratuita de Groq

Ir a:

https://console.groq.com

- Crear cuenta gratuita
- Generar una API key

La key tendrá un formato similar a:

```plaintext
gsk_xxxxxxxxxxxxxxxxx
```

---

## 3. Añadir tu API Key en el código

Abrir:

```plaintext
index.html
```

Buscar:

```
'Authorization': 'Bearer YOUR_GROQ_API_KEY'
```

y reemplazarlo por:

```
'Authorization': 'Bearer gsk_tu_api_key'
```

---

## 4. Ejecutar la aplicación

Puedes abrir directamente:

```plaintext
index.html
```

o usar una extensión como:

- VSCode Live Server

---

## ☁️ Deployment

La aplicación está desplegada usando:

- Azure Static Web Apps
- GitHub Actions

Cada push al repositorio genera automáticamente un nuevo deployment.

---

## 📁 Estructura del proyecto

```plaintext
firststack/
│
├── index.html
├── README.md
└── .github/
```

---

## 🔒 Seguridad

Actualmente:
- La API key se inserta manualmente en el frontend
- El repositorio NO contiene secrets reales
- No hay backend todavía

Próxima mejora planificada:
- Azure Functions como proxy API
- Variables de entorno
- Secret management
- Arquitectura cloud más segura

---

## 🧠 Objetivo del proyecto

Este proyecto fue creado para:

- practicar integración con APIs AI
- aprender despliegues cloud
- trabajar CI/CD
- mejorar conocimientos de frontend
- construir un proyecto real para portfolio

---

## 📌 Roadmap

- [ ] Azure Functions
- [ ] Secret management
- [ ] Exportación PDF
- [ ] Autenticación
- [ ] Persistencia de perfiles
- [ ] Mejoras UI/UX

---

## 👨‍💻 Autor

Juan José  
Infraestructura | Cloud | DevOps | AI Projects

---



MIT
