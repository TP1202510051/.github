# 🎨 Abstractify

<div align="center">

**Interfaces potenciadas por IA · Tiempo real · Colaboración**

[![Frontend](https://img.shields.io/badge/React_19-61dafb?style=flat&logo=react)](https://github.com/TP1202510051/front-end)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat&logo=typescript)](https://www.typescriptlang.org/)

</div>

## 🌟 Visión

Crear experiencias de chat, diseño y código potenciadas por IA, con renderización en tiempo real, persistencia y colaboración multiusuario.

## 📦 Repositorios

- **Frontend**: [`TP1202510051/front-end`](https://github.com/TP1202510051/front-end)
- **Backend**: [`TP1202510051/back-end`](https://github.com/TP1202510051/back-end)

## 🏗️ Stack

**Frontend**: React 19 · TypeScript · Vite · Tailwind v4 · Radix/shadcn · Zustand  
**Backend**: REST · WebSocket/STOMP · gRPC · Firebase Auth  
**Deploy**: Firebase Hosting (Frontend) · Docker/K8s (Backend)

## 🚀 Inicio Rápido
```bash
# Frontend
git clone https://github.com/TP1202510051/front-end.git
cd front-end
npm install
npm run dev

# Backend (ver README del repo)
git clone https://github.com/TP1202510051/back-end.git
```

**Variables de entorno**:
- Frontend: `VITE_API_BASE_URL`, `VITE_WS_URL`, `VITE_FIREBASE_*`
- Backend: `DATABASE_URL`, `JWT_SECRET`, `CORS_ORIGINS`

## 🔀 Workflow

**Ramas**: `feature/*`, `fix/*`, `chore/*`  
**Commits**: Conventional Commits (`feat:`, `fix:`, `chore:`, etc.)  
**Entornos**: `main` (prod) · `develop` (staging) · `feature/*` (dev)

## 📋 Pull Requests

- [ ] Lint sin errores
- [ ] Tests pasando
- [ ] Docs actualizados
- [ ] Screenshots (si UI)
- [ ] 1+ reviewer aprobado

**Merge**: Squash & merge

## ✨ Estándares

- **Lint**: ESLint type-aware
- **Format**: Prettier (ancho 100, comillas simples, sin `;`)
- **TS**: Evitar `any`, tipos explícitos
- **Seguridad**: Secretos en env, `npm audit`, 2FA

## 🗺️ Roadmap

- Diseño colaborativo multiusuario
- Strict TypeScript + cobertura tests
- Telemetría y métricas
- Internacionalización

## 💬 Contacto

**Issues**: Reportar en el repo correspondiente  
**Soporte**: Canal Slack/Teams `#abstractify`  
**Owners**: [@TP1202510051](https://github.com/TP1202510051)

---

<div align="center">Hecho con ❤️ por Abstractify</div>
