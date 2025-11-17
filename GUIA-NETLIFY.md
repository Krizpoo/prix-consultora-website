# 🚀 GUÍA PARA PUBLICAR EN NETLIFY

## 📋 INSTRUCCIONES PASO A PASO

### **MÉTODO 1: Netlify Drop (MÁS FÁCIL - SIN REGISTRO)**

#### **Paso 1: Descargar archivos**
Descarga TODOS estos archivos y carpetas de tu proyecto:

```
✅ ARCHIVOS NECESARIOS:
├── index.html
├── favicon.svg
├── favicon-source.jpg
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/
    ├── flag-argentina.jpg
    └── flag-spain.jpg

❌ NO NECESITAS:
├── README.md
├── GUIA-NETLIFY.md
└── generate-favicon.html
```

#### **Paso 2: Ir a Netlify Drop**
1. Abre tu navegador
2. Ve a: **https://app.netlify.com/drop**
3. No necesitas crear cuenta

#### **Paso 3: Arrastrar archivos**
1. Selecciona TODOS los archivos necesarios (excepto los marcados con ❌)
2. Arrástralos a la zona que dice **"Drag and drop your site folder here"**
3. O haz click y selecciona la carpeta completa

#### **Paso 4: Esperar deployment**
- Verás una barra de progreso
- Toma 20-60 segundos
- ¡No cierres la ventana!

#### **Paso 5: ¡LISTO!**
Te mostrará algo como:
```
✅ Your site is live!
https://random-name-123456.netlify.app
```

**Ese es tu link público** - Copialo y compartilo 🎉

---

### **MÉTODO 2: Netlify con Cuenta (MÁS CONTROL)**

#### **Ventajas de crear cuenta:**
- ✅ Puedes editar el nombre del sitio
- ✅ Puedes actualizar archivos después
- ✅ Puedes conectar dominio propio
- ✅ Ver estadísticas de visitas
- ✅ Configuraciones avanzadas

#### **Pasos:**

**1. Crear cuenta gratis**
- Ve a: https://app.netlify.com/signup
- Usa tu email o Google/GitHub

**2. Deploy tu sitio**
- Click en **"Add new site"**
- Click en **"Deploy manually"**
- Arrastra todos los archivos
- Espera el deployment

**3. Cambiar nombre del sitio (opcional)**
- Ve a **"Site settings"**
- Click en **"Change site name"**
- Ponele: `prix-consultora` o `prixconsultora`
- Tu URL será: `https://prix-consultora.netlify.app`

---

## 🌐 **CONECTAR DOMINIO PROPIO (CUANDO LO COMPRES)**

### **Paso 1: Comprar dominio**
Recomendados:
- **Namecheap**: https://www.namecheap.com (~€10/año)
- **Google Domains**: https://domains.google (~€12/año)
- **Dondominio** (España): https://www.dondominio.com (~€12/año)

Busca: `prixconsultora.com` o `prixconsultora.es`

### **Paso 2: En Netlify**
1. Ve a tu sitio en Netlify
2. Click en **"Domain settings"**
3. Click en **"Add custom domain"**
4. Escribe tu dominio: `prixconsultora.com`
5. Click en **"Verify"**

### **Paso 3: Configurar DNS**
Netlify te dirá qué hacer. Básicamente:

**En tu proveedor de dominio (Namecheap, etc.):**
1. Ve a DNS settings
2. Agrega estos registros que Netlify te indica
3. Espera 5-60 minutos (propagación DNS)

**Netlify te guía paso a paso** - Es muy fácil.

---

## 🔧 **ACTUALIZAR TU SITIO DESPUÉS**

### **Si usaste Drop (sin cuenta):**
- No puedes actualizar
- Debes hacer un nuevo deploy
- Perderás la URL anterior

### **Si tienes cuenta:**
1. Ve a tu sitio en Netlify
2. Click en **"Deploys"**
3. Arrastra los archivos nuevos
4. ¡Listo! Se actualiza automáticamente
5. La URL sigue siendo la misma

---

## 📊 **DESPUÉS DE PUBLICAR**

### **Comparte tu sitio:**
✅ El link funciona en cualquier dispositivo
✅ Es responsive (móvil, tablet, desktop)
✅ Tiene HTTPS (seguro) automático
✅ Es rápido (CDN global)

### **Próximos pasos recomendados:**

**1. Google Analytics (gratis)**
- Para ver cuántas visitas tenés
- Ve a: https://analytics.google.com
- Crea cuenta y obtén un código
- Lo agrego en el sitio (toma 2 minutos)

**2. Google Search Console (gratis)**
- Para aparecer en búsquedas de Google
- Ve a: https://search.google.com/search-console
- Agrega tu sitio

**3. Configurar formulario de contacto**
- Actualmente simula el envío
- Con FormSpree (gratis) funciona de verdad
- Te llegan emails cuando alguien complete el form

**4. Redes sociales**
- Actualizar links de LinkedIn, Instagram, WhatsApp

---

## ✅ **CHECKLIST ANTES DE PUBLICAR**

Verifica que tengas:
- ✅ Información de contacto correcta
- ✅ Email: prixconsultora@gmail.com
- ✅ Teléfono: +34 674 723 738
- ✅ Dirección: Barcelona
- ✅ Todos los archivos (HTML, CSS, JS, imágenes)
- ✅ Favicon funcional

---

## 🆘 **PROBLEMAS COMUNES**

**"Mi sitio no se ve bien"**
- Asegúrate de subir TODAS las carpetas (css, js, images)
- La estructura debe ser exacta

**"Las imágenes no cargan"**
- Verifica que la carpeta "images" esté incluida
- Los nombres de archivo deben coincidir (case-sensitive)

**"Quiero cambiar algo"**
- Modifica los archivos
- Vuelve a hacer deploy
- (Por eso conviene tener cuenta)

---

## 💡 **CONSEJOS FINALES**

1. **Guarda tu URL de Netlify** en algún lado
2. **Toma screenshot** del deployment exitoso
3. **Prueba el sitio** en móvil antes de compartir
4. **Comparte con orgullo** - ¡Quedó genial! 🎉

---

## 📞 **SOPORTE**

**Si algo no funciona:**
- Netlify tiene excelente documentación: https://docs.netlify.com
- Chat de soporte (en inglés) disponible

---

**¡Tu sitio de Prix Consultora está listo para el mundo! 🚀🇦🇷🇪🇸**