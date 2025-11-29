# 🚀 AlexPSMC Launcher

<p align="center">
  <img src="src/assets/images/icon.png" alt="Light Launcher" width="400" height="400">
</p>

<p align="center">
  <strong>Launcher de Minecraft moderno y potente para los servidores de Light Studio</strong>
</p>

<p align="center">
  <a href="https://github.com/AlexPSMC/AlexPSMCLauncher/releases/latest">
    <img src="https://img.shields.io/github/v/release/miguelkix30/MiguelkiNetworkMCLauncher?style=for-the-badge&logo=github&logoColor=white" alt="Latest Release">
  </a>
  <a href="https://github.com/AlexPSMC/AlexPSMCLauncher/releases">
    <img src="https://img.shields.io/github/downloads/miguelkix30/MiguelkiNetworkMCLauncher/total?style=for-the-badge&logo=github&logoColor=white" alt="Total Downloads">
  </a>
  <a href="https://discord.gg/Pk3UqJUFEX">
    <img src="https://img.shields.io/discord/1300477405957329018?style=for-the-badge&logo=discord&logoColor=white&label=Discord" alt="Discord">
  </a>
</p>

<p align="center">
  <a href="https://nodejs.org">
    <img src="https://img.shields.io/badge/Node.js-18+-green?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
  </a>
  <a href="https://electronjs.org">
    <img src="https://img.shields.io/badge/Electron-36.5+-blue?style=for-the-badge&logo=electron&logoColor=white" alt="Electron">
  </a>
</p>

---

## 📋 Tabla de Contenidos

- [📦 Descargas](#-descargas)
- [🔧 Instalación](#-instalación)
- [🛠️ Desarrollo](#️-desarrollo)
- [📄 Licencia](#-licencia)

---

## 📦 Descargas

### 📥 **Descarga Rápida**

| Sistema Operativo | Descarga Directa | Requisitos |
|:----------------:|:----------------:|:----------:|
| **Windows x64** | [📥 Descargar](https://github.com/AlexPSMC/AlexPSMCLauncher/releases/latest/download/Light-Client-win-x64.exe) | Windows 10+ |
| **macOS Universal** | [📥 Descargar](https://github.com/AlexPSMC/AlexPSMCLauncher/releases/latest/download/Light-Client-mac-universal.zip) | macOS 10.15+ |
| **Linux x64** | [📥 Descargar](https://github.com/AlexPSMC/AlexPSMCLauncher/releases/latest/download/Light-Client-linux-x86_64.AppImage) | Ubuntu 18.04+ |

### 🔄 **Otras Opciones**
- 📋 [**Todas las releases**](https://github.com/AlexPSMC/AlexPSMCLauncher/releases) - Versiones anteriores y beta

---

## 🔧 Instalación

### Windows
1. Descarga el archivo `.exe`
2. Ejecuta como administrador
3. Sigue el asistente de instalación
4. ¡Listo para usar!

### macOS
1. Descarga el archivo `.zip`
2. Extrae el contenido
3. Arrastra la aplicación a `/Applications`
4. Ejecuta la aplicación

### Linux
1. Descarga el archivo `.AppImage`
2. Dale permisos de ejecución: `chmod +x *.AppImage`
3. Ejecuta el archivo: `./Light-Client-linux-x86_64.AppImage`

---

## 🛠️ Desarrollo

### 📋 **Requisitos de Desarrollo**
- **Node.js** 18 o superior
- **npm** o **yarn**
- **Git**

### 🏗️ **Compilación**
```bash
# Clonar el repositorio
git clone https://github.com/AlexPSMC/AlexPSMCLauncher.git
cd AlexPSMCLauncher

# Instalar dependencias
npm install

# Modo desarrollo
npm run dev

# Compilar para producción
npm run build
```

### 🧪 **Scripts Disponibles**
```bash
npm run start      # Ejecutar en modo desarrollo
npm run dev        # Desarrollo con hot-reload
npm run build      # Compilar aplicación
npm run icon       # Generar iconos
```

### 🔧 **Herramientas de Desarrollo**
- **Verificador de Compatibilidad**: `node run-loader-check.js`
- **Configurar Dependencias**: `node setup-loader-checker.js`
- **Diagnósticos**: Incluido en el launcher

---

## 📄 Licencia

Este proyecto está bajo la **Licencia CCANC** (Creative Commons Attribution-NonCommercial).

### 📜 **Condiciones de Uso**
- ✅ **Uso personal** y educativo
- ✅ **Modificación** con atribución
- ✅ **Distribución** con créditos
- ❌ **Uso comercial** sin autorización

### 🤝 **Atribución Requerida**
Si utilizas este código, debes dar crédito a:
- **AlexPSMC** (Autor de este fork)
- **Luuxis** (Autor original de [Selvania Launcher](https://github.com/luuxis/Selvania-Launcher))

---
