# ⚽ Liga Manager

**Prototipo web funcional** para gestión de ligas deportivas — sin instalación, sin backend, sin dependencias.

[![Demo](https://img.shields.io/badge/🚀_Demo-GitHub_Pages-00e676?style=for-the-badge)](https://TU-USUARIO.github.io/liga-manager)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![HTML](https://img.shields.io/badge/HTML-5-orange?style=for-the-badge)](https://developer.mozilla.org/es/docs/Web/HTML)

---

## 📸 Pantallas

| Landing | App — Tabla | App — Goleadores |
|---|---|---|
| Página de inicio con planes | Tabla de posiciones en vivo | Rankings con minutos y tipos |

---

## ✨ Features del prototipo

| Feature | Estado |
|---|---|
| 🏠 Landing page con planes Freemium | ✅ Incluido |
| 👥 CRUD de equipos con emojis | ✅ Incluido |
| 📅 Calendario de partidos por jornada | ✅ Incluido |
| 🏆 Tabla de posiciones (auto-calculada) | ✅ Incluido |
| ⚽ Goleadores con penales/autogoles/minutos | ✅ Incluido |
| 📊 Estadísticas y gráficas de rendimiento | ✅ Incluido |
| 📤 Compartir calendario y tabla (texto) | ✅ Incluido |
| 💾 Persistencia en localStorage | ✅ Incluido |
| 🌙 Tema oscuro (dark mode nativo) | ✅ Incluido |
| 📱 Responsive mobile-first | ✅ Incluido |
| 🔔 Notificaciones push | 🔜 v2 (backend) |
| 🔐 Autenticación y roles | 🔜 v2 (backend) |
| 💳 Pagos Freemium reales | 🔜 v2 (backend) |

---

## 🚀 Inicio rápido (3 opciones)

### Opción 1 — Abrir directo (sin nada instalado)
```bash
# Descarga el ZIP desde GitHub y abre index.html en tu navegador
# ¡Listo! No necesitas instalar nada.
```

### Opción 2 — GitHub Pages (recomendado)
```
1. Haz fork de este repositorio
2. Ve a Settings → Pages
3. Source: "Deploy from branch" → main → / (root)
4. Tu app estará en: https://TU-USUARIO.github.io/liga-manager
```

### Opción 3 — Servidor local con Python
```bash
# Clona el repositorio
git clone https://github.com/TU-USUARIO/liga-manager.git
cd liga-manager

# Inicia servidor local (Python 3)
python3 -m http.server 8080

# Abre en el navegador
# → http://localhost:8080
```

### Opción 4 — Servidor local con Node.js (si lo tienes)
```bash
# Instala serve globalmente (una sola vez)
npm install -g serve

# Inicia el servidor
serve .

# Abre en el navegador
# → http://localhost:3000
```

---

## 📁 Estructura del proyecto

```
liga-manager/
├── index.html          ← Landing page + planes Freemium
├── pages/
│   └── app.html        ← Aplicación principal completa
├── README.md
└── LICENSE
```

---

## 🗺️ Roadmap — Próximas versiones

### v2.0 — Backend real (NestJS + PostgreSQL)
- [ ] API REST con NestJS
- [ ] Base de datos PostgreSQL con Prisma
- [ ] Autenticación JWT con roles (Admin, Árbitro, Espectador)
- [ ] Guard de planes (FREE/PRO/ELITE)
- [ ] Deploy en Railway

### v3.0 — App móvil Flutter
- [ ] App iOS + Android con Flutter
- [ ] Notificaciones push (Firebase FCM)
- [ ] Pagos in-app con RevenueCat
- [ ] Marcadores en tiempo real (WebSockets)

---

## 🛠️ Stack tecnológico

**Prototipo actual (v1):**
- HTML5 + CSS3 + JavaScript vanilla
- LocalStorage para persistencia
- Google Fonts (Bebas Neue + DM Sans)
- Sin dependencias externas

**Stack planeado (v2+):**
| Capa | Tecnología |
|---|---|
| App Móvil | Flutter 3.x |
| Frontend Web | Next.js 14 |
| Backend | NestJS + TypeScript |
| Base de Datos | PostgreSQL + Prisma |
| Caché | Redis |
| Push Notifications | Firebase FCM |
| Pagos | Stripe + RevenueCat |
| Deploy | Railway + Vercel |

---

## 🤝 Contribuir

1. Haz fork del repositorio
2. Crea una rama: `git checkout -b feature/mi-feature`
3. Commitea: `git commit -m 'feat: agrego X'`
4. Push: `git push origin feature/mi-feature`
5. Abre un Pull Request

---

## 📄 Licencia

MIT © 2026 — Liga Manager

---

<p align="center">Hecho con ⚽ para comunidades deportivas</p>
