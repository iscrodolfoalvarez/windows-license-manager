# 🔑 **Windows License Manager**

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-9333ea?style=for-the-badge&logo=windows&logoColor=white" alt="Version">
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Platform">
  <img src="https://img.shields.io/badge/license-MIT-00C853?style=for-the-badge&logo=open-source-initiative&logoColor=white" alt="License">
  <img src="https://img.shields.io/github/downloads/iscrodolfoalvarez/windows-license-manager/total?style=for-the-badge&color=blueviolet" alt="Downloads">
</p>

<p align="center">
  <strong>✨ Herramienta profesional de gestión de licencias de Windows ✨</strong>
</p>

<p align="center">
  Extrae, gestiona y descarga ISOs oficiales de Windows con una interfaz moderna y elegante
</p>

---

## 📸 **Preview**

<p align="center">
  <img src="screenshots/main.png" alt="Interfaz Principal" width="700">
</p>

---

## 🌟 **¿Qué es Windows License Manager?**

**Windows License Manager** es una aplicación de escritorio desarrollada con **Electron** que te permite gestionar de forma profesional las licencias de activación de Windows. Con una interfaz moderna estilo **Cyber Purple**, esta herramienta combina potencia y simplicidad para ofrecerte el control total sobre tu sistema operativo.

### **¿Para qué sirve?**

- 🔓 **Recuperar tu Product Key** si la has perdido
- 💾 **Hacer backup** de tu licencia antes de formatear
- 📥 **Descargar la ISO exacta** de tu versión de Windows
- 🔄 **Reactivar Windows** cuando tengas problemas de activación
- 🔐 **Cambiar de licencia** de forma segura
- 📊 **Ver información detallada** de tu sistema y licencia

---

## ✨ **Características Principales**

### 🔑 **Extracción Inteligente de Product Keys**

La aplicación utiliza **3 métodos avanzados** para extraer tu licencia de Windows:

1. **BIOS/UEFI** - Lee la clave embebida en tu placa madre (OEM)
2. **PowerShell** - Extrae claves usando WMI (Windows Management Instrumentation)
3. **Registry** - Busca en el registro de Windows claves de backup

**Soporta:**
- ✅ Windows 11 (todas las versiones)
- ✅ Windows 10 (todas las versiones)
- ✅ Licencias OEM (pre-instaladas)
- ✅ Licencias Retail (compradas independientemente)
- ✅ Licencias MAK y KMS (corporativas)

**Detecta automáticamente:**
- 🏷️ Si tu licencia es transferible o no
- 📌 El tipo de canal de licencia
- ✅ El estado de activación actual

---

### 🖥️ **Información Detallada del Sistema**

Obtén datos precisos sobre tu instalación de Windows:

- **Sistema Operativo**: Windows 11 Pro, Windows 10 Home, etc.
- **Versión de Marketing**: 22H2, 23H2, 24H2
- **Build Number**: 19045, 22621, 26100, etc.
- **Arquitectura**: 64-bit o 32-bit
- **Nombre del Equipo**: Identificación de tu PC
- **Estado de Licencia**: Activado, No activado, Período de gracia
- **Canal de Licencia**: Retail, OEM, Volume:MAK, Volume:GVLK

---

### 📥 **Descargador de ISOs Oficiales**

Una de las características más útiles: descarga la **ISO exacta** compatible con tu licencia.

**¿Por qué es importante?**
- Si formateas, necesitas la misma versión de Windows
- Tu Product Key solo funciona con la versión exacta (Build + Edición)
- Evitas errores de activación por incompatibilidad

**3 métodos de descarga:**

| Método | Descripción | Velocidad | Recomendado para |
|--------|-------------|-----------|------------------|
| 🏢 **Microsoft Oficial** | Descarga directa desde microsoft.com | ⚡⚡⚡ Rápida | Última versión estable |
| ⚡ **UUP Dump** | Build exacta de tu sistema actual | ⚡⚡ Media | Misma versión que tienes |
| 🛠️ **Media Creation Tool** | Herramienta oficial de Microsoft | ⚡⚡⚡ Rápida | Instalación en USB |

**Detección automática:**
- 🔍 La app detecta tu versión exacta (ej: Windows 11 23H2 Build 22631)
- 📊 Te muestra la arquitectura necesaria (x64)
- ⚠️ Te advierte si descargas una versión incompatible

---

### 💾 **Backup Profesional**

Exporta toda la información de tu licencia en un archivo `.txt` estructurado:

