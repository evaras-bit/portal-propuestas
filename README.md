# Portal de Propuestas — Mod Journey

Repositorio de propuestas comerciales de **Mod Journey SPA**.

## 🌐 URL en producción

`https://propuesta.modjourney.cl/{codigo-proyecto}/`

## 📁 Estructura

```
public/
├── rdm343-karin/           # Karin Thomsen — Proyecto RDM343
│   └── index.html
└── (futuras propuestas...)
```

## 🚀 Cómo agregar una nueva propuesta

1. Crear carpeta en `public/` con el código del proyecto:
   ```
   public/sa11-awad/index.html
   ```
2. Commit + push a `main`
3. EasyPanel auto-despliega
4. Compartir con cliente: `https://propuesta.modjourney.cl/sa11-awad/`

## 📋 Propuestas activas

| Cliente | Proyecto | URL |
|---------|----------|-----|
| Karin Thomsen | RDM343 | `/rdm343-karin/` |

## 🛠️ Deploy

EasyPanel auto-despliega cada push a `main` usando el Dockerfile incluido.

- **Imagen base:** `nginx:alpine`
- **Puerto:** `80`
- **Config Nginx:** `nginx.conf` (gzip, cache, headers de seguridad)

## 📝 Tecnología

HTML/CSS/JS vanilla. Sin build step. Cada `index.html` es self-contained.
