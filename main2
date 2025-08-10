# 기상청(기준: KMA) 기반 날씨 사이트 — 깃허브 레포 버전

아래는 바로 깃허브에 올려 사용할 수 있도록 구성한 프로젝트입니다. 백엔드와 프론트엔드가 한 레포에 있으며, 로컬 실행 및 배포가 용이하도록 `package.json`과 폴더 구조를 구성했습니다.

---

## 폴더 구조

```
my-kma-weather/
├── backend/
│   ├── server.js
│   ├── package.json
│   └── .env.example
├── frontend/
│   ├── src/App.jsx
│   ├── package.json
│   └── vite.config.js
├── README.md
└── LICENSE
```

---

## backend/server.js

```js
// (기존 server.js 코드 그대로)
```

---

## frontend/src/App.jsx

```jsx
// (기존 App.jsx 코드 그대로)
```

---

## backend/package.json

```json
{
  "name": "kma-weather-backend",
  "version": "1.0.0",
  "main": "server.js",
  "type": "module",
  "scripts": {
    "start": "node server.js"
  },
  "dependencies": {
    "dotenv": "^16.3.1",
    "express": "^4.19.2",
    "node-fetch": "^3.3.2"
  }
}
```

---

## frontend/package.json

```json
{
  "name": "kma-weather-frontend",
  "private": true,
  "version": "1.0.0",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "@vitejs/plugin-react": "^4.0.0",
    "vite": "^4.4.0"
  }
}
```

---

## .env.example

```
SERVICE_KEY=발급받은_서비스키
PORT=3000
```

---

## README.md (깃허브 설명)

````markdown
# KMA Weather App

기상청(Open API) 기반 날씨 조회 웹 애플리케이션.

## 실행 방법

```bash
# 백엔드
cd backend
cp .env.example .env
npm install
npm start

# 프론트엔드
cd ../frontend
npm install
npm run dev
````

## 배포

* 백엔드: Vercel / Render / Railway
* 프론트엔드: Vercel / Netlify / Github Pages

```

---

이제 이 내용을 깃허브 새 저장소에 업로드하면 바로 사용할 수 있습니다. `backend`와 `frontend`를 각각 실행하거나, Heroku/Vercel에서 monorepo 형태로 배포할 수 있습니다.

```
