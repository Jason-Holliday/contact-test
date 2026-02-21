# Contact Form — React + Vite + Express (Mono)

## Lokal entwickeln

```bash
npm install
cp .env.example .env
# .env befüllen

# Terminal 1 — Backend
npm run dev:server

# Terminal 2 — Frontend
npm run dev:client
```

## Coolify Deployment

**Build Command:**
```
npm install && npm run build
```

**Start Command:**
```
npm start
```

**Base Directory:** `/` (Root leer lassen)

**Environment Variables:**
```
PORT=3000
SMTP_HOST=smtp.ionos.de
SMTP_PORT=587
SMTP_USER=deine@domain.de
SMTP_PASS=dein-passwort
MAIL_TO=empfaenger@domain.de
```
