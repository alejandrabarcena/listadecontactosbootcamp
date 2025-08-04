# 📒 Lista de Contactos con React & Context API

Aplicación moderna y profesional para la gestión de contactos, desarrollada con **React.js**, **React Router DOM** y **Context API**, que permite realizar operaciones CRUD completas: **Crear**, **Leer**, **Actualizar** y **Eliminar** contactos de manera eficiente, escalable y visualmente clara.

---

## 📘 ¿JavaScript o TypeScript?

El proyecto está implementado principalmente en **JavaScript**, pero fue generado con la plantilla **Vite + React + TypeScript**, lo que incluye archivos de configuración en TypeScript como:

- `vite.config.ts`
- `tsconfig.json`
- `tsconfig.node.json`

Aunque **no se utilizó tipado estricto ni archivos `.tsx`**, el entorno ya está listo para una futura migración a TypeScript si se desea.

> ✅ *Esto no afecta el funcionamiento del proyecto. Es común en entornos modernos scaffolded con Vite.*

---

## ⚙️ Tecnologías utilizadas

- ⚛️ React 18 con Hooks
- 🌐 React Router DOM
- 🧠 Context API para estado global
- 🎨 CSS
- 💡 HTML5
- 🔧 JavaScript
- 🧩 TypeScript *(solo configuración del entorno)*

---

## 🌐 Demo en línea

- 🔗 [Deploy en Netlify](https://listasdecontactosbootcamprj.netlify.app/)
- 🔗 [Deploy en Vercel](https://listadecontactosbootcamp-lskt.vercel.app/)

---

## 📸 Vista previa

![Vista previa 1](https://github.com/PatsyBarcena/listasdecontactosbootcampRJ/blob/main/listadecontactosvistaprevia1.png)
![Vista previa 2](https://github.com/PatsyBarcena/listasdecontactosbootcampRJ/blob/main/listadecontactosvistaprevia2.png)

---

## ✨ Funcionalidades principales

- ✅ **Crear** nuevos contactos
- 🔍 **Leer** la lista de contactos existentes
- ✏️ **Actualizar** información de contacto
- 🗑️ **Eliminar** contactos con confirmación por modal
- 🔄 Comunicación con API externa mediante `fetch`

---

## 🧠 Manejo del estado global con Context API

La lógica del CRUD está centralizada utilizando **Context API**, lo que permite:

- Evitar el prop drilling
- Compartir estado y funciones entre componentes
- Escalar la aplicación de forma ordenada y limpia

---

## 🚀 Cómo ejecutar este proyecto localmente

`
