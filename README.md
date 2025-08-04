# builder-orbit-den

# Blog Automatizado de Programación

🤖 **Sistema completamente automatizado** que genera artículos de programación y ebooks usando IA.

## 🚀 Características

- **3 artículos diarios** generados automáticamente con Gemini AI
- **Ebooks bisemanales** listos para vender en Hotmart
- **SEO automático** con sitemap y meta tags
- **Feed estilo Facebook** para mostrar artículos
- **Completamente responsivo** (mobile + desktop)
- **Cero mantenimiento** - Todo funciona solo

## 🛠️ Tecnologías

- **Frontend**: React 18 + TypeScript + Tailwind CSS
- **Backend**: Express.js + Node.js
- **IA**: Google Gemini API (gratuita)
- **Automatización**: GitHub Actions
- **Deployment**: Netlify/Vercel compatible

## ⚡ Configuración Rápida

### 1. Configurar API de Gemini (Gratis)

```bash
# 1. Ve a https://makersuite.google.com/app/apikey
# 2. Crea una API Key
# 3. En GitHub: Settings > Secrets > Actions
# 4. Agrega: GEMINI_API_KEY = tu_api_key
```

### 2. Habilitar GitHub Actions

```bash
# Settings > Actions > General
# ✅ Read and write permissions
```

### 3. Personalizar dominio

```bash
# Editar dominio en .github/workflows/update-sitemap.yml
```

## 📅 Automatización

| Acción       | Frecuencia           | Descripción                 |
| ------------ | -------------------- | --------------------------- |
| 📝 Artículos | Diario 10:00 AM UTC  | 3 artículos de programación |
| 📚 Ebooks    | Bisemanal (Domingos) | PDF listo para Hotmart      |
| 🗺️ Sitemap   | Automático           | SEO optimizado              |

## 🎯 Estructura

```
├── client/                 # Frontend React
│   ├── pages/             # Páginas (Index, ArticleDetail)
│   ├── services/          # ArticleService para carga
│   └── components/        # UI components
├── .github/workflows/     # GitHub Actions
│   ├── generate-articles.yml
│   ├── generate-ebook.yml
│   └── update-sitemap.yml
├── public/articles/       # Artículos generados
├── ebooks/               # Ebooks (privados)
└── templates/            # Plantillas HTML
```

## 📊 Funcionalidades

### Blog Feed

- ✅ Feed tipo Facebook
- ✅ Filtros por categoría (Frontend, Backend, DevOps)
- ✅ Búsqueda en tiempo real
- ✅ Artículos destacados
- ✅ Responsive design

### Artículos

- ✅ Generación automática con IA
- ✅ Contenido único y detallado
- ✅ Ejemplos de código funcionales
- ✅ SEO completo (meta tags, structured data)
- ✅ 35+ temas de programación

### Ebooks

- ✅ Compilación automática de artículos
- ✅ Diseño profesional para ventas
- ✅ Portada y metadatos automáticos
- ✅ PDF optimizado para Hotmart
- ✅ Precio sugerido incluido

## 🚀 Desarrollo

```bash
# Instalar dependencias
npm install

# Desarrollo local
npm run dev

# Build producción
npm run build

# Iniciar servidor
npm start
```

## 📈 Monetización

Los ebooks se generan automáticamente con:

- 📖 Formato PDF profesional
- 💰 Precio sugerido ($47 USD típico)
- 🎨 Portada atractiva
- 📄 80+ páginas de contenido
- 🏷️ Metadatos para Hotmart

## 🔧 Personalización

### Cambiar temas de artículos

Edita `programmingTopics` en `.github/workflows/generate-articles.yml`

### Modificar prompt de IA

Personaliza las instrucciones en el GitHub Action

### Ajustar frecuencias

Cambia los cron jobs en los workflows

## 📚 Documentación

- [Sistema Automatizado](SISTEMA-AUTOMATIZADO.md) - Guía completa
- [Setup Instructions](SETUP.md) - Configuración paso a paso

## 🎉 Resultado

**Un blog que se actualiza solo** con contenido de calidad y productos digitales listos para vender.

¡Perfecto para bloggers, desarrolladores y emprendedores digitales! 🚀

---

## 📄 Licencia

MIT License - Libre para uso comercial

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Contacto

GitHub: [@lksarmiento67](https://github.com/lksarmiento67)

---

⭐ **¡No olvides dar una estrella si te gusta el proyecto!** ⭐
