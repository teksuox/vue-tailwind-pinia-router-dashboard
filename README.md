# Vue 3 Project

Este es un proyecto básico de Vue 3 que utiliza Vue Router, Pinia y Tailwind CSS.

## Estructura del Proyecto

```
vue-project
├── public
│   └── avatar.png
│   └── logo
├── src
│   ├── assets
│   │   └── main.css
│   ├── components
│   │   └── Estructura_Web
│   │       └── Dashboard
│   │       └── Footer
│   │       └── Header
│   │       └── Panel_Derecho
│   │       └── Panel_Izquierdo
│   │       └── SidebarLink
│   ├── router
│   │   └── index.js
│   ├── stores
│   │   └── ui.js
│   ├── views
│   │   ├── home
│   │   └── login
|   |   └── perfil
│   ├── App.vue
│   └── main.js
├── package.json
├── pnpm-lock.yaml
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js
```

## Requisitos

Asegúrate de tener instalado:
- **Node.js** (v24.8.0 o superior)
- **pnpm** (v11.0.0 o superior) - [Instalar pnpm](https://pnpm.io/installation)

## Instalación

1. Clona el repositorio o descarga el proyecto.
2. Navega al directorio del proyecto.
3. Instala pnpm globalmente (si aún no lo has hecho):

```bash
npm install -g pnpm
```

4. Ejecuta el siguiente comando para instalar las dependencias:

```bash
pnpm install
```

> **Nota**: Este proyecto utiliza **pnpm** en lugar de npm para una mejor seguridad, rendimiento y gestión de dependencias. pnpm proporciona:
> - 🔒 Mayor seguridad con caché aislada e integridad verificada
> - ⚡ Instalación más rápida mediante deduplicación
> - 💾 Menor uso de espacio en disco
> - 🛡️ Mejor protección contra ataques de dependency confusion

## Ejecución

Para iniciar la aplicación en modo de desarrollo, ejecuta:

```bash
pnpm run dev
```

La aplicación estará disponible en `http://localhost:5173/`

## Construcción

Para construir la aplicación para producción, ejecuta:

```bash
pnpm run build
```

Los archivos de construcción se generarán en el directorio `dist`.

## Auditoría de Seguridad

Para verificar que no hay vulnerabilidades conocidas, ejecuta:

```bash
pnpm audit
```

## Tecnologías Utilizadas

- Vue 3
- Vue Router
- Pinia
- Tailwind CSS
- Vite
- pnpm (Package Manager)

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o un pull request.
