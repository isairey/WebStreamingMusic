<p align="center">
  <img width="120" src="https://cdn-icons-png.flaticon.com/512/727/727245.png" />
</p>

<h1 align="center">🎵 Spring Music</h1>

<p align="center">
  <strong>Plataforma moderna de streaming musical desarrollada con Next.js y Firebase</strong>
</p>

<p align="center">
  Disfruta de música en tiempo real, gestiona playlists y accede a una experiencia rápida, escalable y moderna.
</p>

---

<p align="center">
  <a href="https://spring-music-player-n27p.vercel.app">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-Ver%20Aplicación-000?style=for-the-badge" />
  </a>
  <img src="https://img.shields.io/github/stars/isairey/WebStreamingMusic?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/isairey/WebStreamingMusic?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/isairey/WebStreamingMusic?style=for-the-badge" />
</p>

---

## ✨ Características

- 🎧 **Streaming en tiempo real** mediante API de música  
- 🔍 **Búsqueda avanzada** de canciones, artistas y álbumes  
- 🔐 **Autenticación segura** con Firebase (Google / Email)  
- 📂 **Gestión de playlists** (en desarrollo)  
- ⚡ **Alto rendimiento** con renderizado optimizado de Next.js  
- ☁️ **Infraestructura escalable** con Firebase  

---

## 🛠️ Tecnologías utilizadas

#### ⚛️ Frontend
![Next.js](https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

#### 🔥 Backend & Servicios
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Firebase Auth](https://img.shields.io/badge/Auth-Firebase-FFCA28?style=for-the-badge&logo=firebase)

#### 🎵 API de Música
![JioSaavn API](https://img.shields.io/badge/JioSaavn_API-Unofficial-green?style=for-the-badge)

#### 🚀 Deployment
![Vercel](https://img.shields.io/badge/Vercel-000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 📂 Estructura del proyecto

```
spring-music-web/
├── public/ # Recursos estáticos
├── src/
│ ├── components/ # Componentes reutilizables
│ ├── pages/ # Rutas de Next.js
│ ├── styles/ # Estilos globales
│ └── utils/ # Configuración Firebase & API
├── .env.local # Variables de entorno
├── package.json
└── README.md
```

---

## ⚙️ Configuración del entorno

### 1️⃣ Clonar repositorio
```bash
git clone https://github.com/isairey/WebStreamingMusic.git
cd WebStreamingMusic
```
### 2️⃣ Instalar dependencias
```
npm install
```
### 3️⃣ Configurar Firebase
```
Crear proyecto en Firebase
Activar autenticación (Google/Email)
Configurar Firestore
Configurar Storage
```
###
4️⃣ Variables de entorno

Crear archivo .env.local:
```
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
JIO_SAAVAN_API_BASE_URL=your_api
NEXT_PUBLIC_API_URL=your_api_url
```

### 5️⃣ Ejecutar proyecto
```
npm run dev
```
Abrir en navegador:
```
👉 http://localhost:3000
```

---

## 🚀 Despliegue
```
Deploy en Vercel
vercel
```

## 📊 Roadmap

- [ x ] Sistema completo de playlists  
- [ x ] Historial de reproducción  
- [ x ] Recomendaciones inteligentes  
- [ x ] Modo offline  
- [ x ] UI/UX mejorada tipo Spotify  

 ---
 
## 🤝 Contribuidores

<a href="https://github.com/isairey/WebStreamingMusic/graphs/contributors"> <img src="https://contrib.rocks/image?repo=isairey/WebStreamingMusic" /> </a>
👤 Autor

**Isai Reyes**

GitHub: https://github.com/isairey

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT.
