
**Puedes:**
- 📂 Guardarlo en múltiples ubicaciones (USB, nube, etc.)
- 📧 Enviártelo por email
- 🖨️ Imprimirlo para tenerlo físicamente

---

### 🔐 **Gestión Avanzada de Licencias**

**4 operaciones principales:**

#### 1️⃣ **Verificar Activación**
- Comprueba el estado actual de tu licencia
- Muestra fecha de expiración (si aplica)
- Indica si hay problemas de activación

#### 2️⃣ **Reactivar Windows**
- Intenta activar Windows automáticamente
- Útil cuando Windows se desactiva después de un cambio de hardware
- Usa el comando oficial `slmgr /ato`

#### 3️⃣ **Instalar Nueva Licencia**
- Introduce una nueva Product Key
- Aplica la licencia automáticamente
- Valida el formato antes de aplicar

#### 4️⃣ **Desinstalar Licencia**
- Elimina la licencia actual de forma segura
- Útil antes de vender tu PC
- Requiere confirmación para evitar errores

---

### 🎨 **Interfaz Moderna - Cyber Purple**

Diseñada con los estándares modernos de UI/UX:

- 🌙 **Tema oscuro optimizado** - Reduce fatiga visual
- 💜 **Paleta Cyber Purple** - Gradientes morados y cyan
- ✨ **Animaciones fluidas** - Experiencia premium
- 📊 **Sistema de logs en tiempo real** - Transparencia total
- 🔔 **Alertas elegantes** - Notificaciones con SweetAlert2
- 🖱️ **Botones intuitivos** - Iconos claros y descriptivos

**Componentes visuales:**

| Elemento | Descripción |
|----------|-------------|
| 🎯 Panel de información | Muestra datos del sistema en tiempo real |
| 🔑 Display de Product Key | Encriptado visualmente con blur |
| 📋 Log de actividad | Historial de todas las acciones |
| 🎨 Splash screen | Pantalla de carga animada |
| ⚡ Acciones rápidas | 6 botones principales de gestión |

---

### 🛡️ **Seguridad y Privacidad**

Tu seguridad es prioridad:

- ✅ **Verificación de permisos de administrador** - La app solo funciona con privilegios elevados
- ✅ **Sin telemetría** - No recopilamos ni enviamos datos
- ✅ **Sin conexiones externas** - Solo se conecta a internet para descargar ISOs (opcional)
- ✅ **Código local** - Todo se ejecuta en tu PC
- ✅ **No requiere cuenta** - No necesitas registrarte
- ✅ **Open Source** - (Opcional: si decides hacer público el código)

---

## 🚀 **Descarga e Instalación**

### **📥 Descargar la última versión**

<p align="center">
  <a href="https://github.com/TU_USUARIO/windows-license-manager/releases/latest">
    <img src="https://img.shields.io/badge/⬇️%20Descargar-Windows%20License%20Manager%20v1.0.0-9333ea?style=for-the-badge&logo=windows" alt="Descargar">
  </a>
</p>

**Versión actual:** `v1.0.0` | **Tamaño:** ~150 MB | **Portable:** No requiere instalación

---

### **▶️ Cómo ejecutar**

1. **Descarga** el archivo `WindowsLicenseManager-v1.0.0-Portable.exe`
2. **Guárdalo** en cualquier carpeta de tu PC
3. **Clic derecho** sobre el archivo
4. Selecciona **"Ejecutar como administrador"**
5. Acepta el diálogo de **Control de Cuentas de Usuario (UAC)**
6. ✅ **¡Listo!** La aplicación se abrirá automáticamente

⚠️ **IMPORTANTE:** Si ejecutas sin permisos de administrador, verás una advertencia y la app se cerrará.

---

### **🖥️ Compatibilidad**

| Sistema Operativo | Soporte | Notas |
|-------------------|---------|-------|
| ✅ Windows 11 | Completo | Todas las versiones (21H2, 22H2, 23H2, 24H2) |
| ✅ Windows 10 | Completo | Todas las versiones (1809 a 22H2) |
| ⚠️ Windows 8.1 | Limitado | Funciones básicas |
| ⚠️ Windows 7 | Limitado | Algunas características pueden no funcionar |
| ❌ Windows Server | No soportado | Próximamente en v2.0 |

**Requisitos mínimos:**
- 💻 Procesador: Intel/AMD 64-bit
- 🧠 RAM: 512 MB
- 💾 Espacio: 150 MB
- 🔐 Permisos: Administrador (obligatorio)

---

## 📖 **Guía de Uso Completa**

### **🔑 1. Extraer tu Product Key**

<details>
<summary><strong>👉 Haz clic para ver la guía paso a paso</strong></summary>

#### **Paso 1: Abrir la aplicación**
- Ejecuta como administrador

#### **Paso 2: Clic en "Extraer Key"**
- Botón morado con icono de llave 🔑
- Se encuentra en la parte superior

#### **Paso 3: Esperar la detección**
- La app probará los 3 métodos automáticamente
- Verás logs en tiempo real del proceso

#### **Paso 4: Ver el resultado**
- ✅ **Éxito**: Verás tu Product Key en pantalla
- 📌 Se mostrará el método usado (BIOS/PowerShell/Registry)
- ℹ️ Información adicional sobre la licencia

#### **Posibles resultados:**

| Mensaje | Significado |
|---------|-------------|
| ✅ Key extraída exitosamente | Tu licencia fue encontrada |
| ⚠️ Licencia digital detectada | Está vinculada a tu cuenta de Microsoft |
| ❌ No se pudo extraer | Puede ser OEM sin clave en BIOS |

</details>

---

### **💾 2. Guardar Backup de tu Licencia**

<details>
<summary><strong>👉 Haz clic para ver la guía paso a paso</strong></summary>

#### **Paso 1: Extraer la key primero**
- Necesitas extraer la key antes de guardar

#### **Paso 2: Clic en "Guardar Backup"**
- Botón con icono de disco 💾

#### **Paso 3: Elegir ubicación**
- Se abrirá un diálogo de "Guardar como"
- Nombre sugerido: `Windows_License_2026-01-31.txt`
- Puedes cambiarlo

#### **Paso 4: Guardar**
- Haz clic en "Guardar"
- Verás confirmación en pantalla

#### **Paso 5: Abrir el archivo (opcional)**
- Aparecerá un botón "Abrir archivo"
- Verifica que toda la información esté correcta

**💡 Consejos:**
- Guarda el backup en múltiples lugares (USB, nube)
- No compartas tu Product Key públicamente
- Guárdalo antes de formatear

</details>

---

### **📥 3. Descargar ISO de Windows**

<details>
<summary><strong>👉 Haz clic para ver la guía paso a paso</strong></summary>

#### **Paso 1: Clic en "Descargar ISO"**
- Botón con icono de descarga 📥

#### **Paso 2: Ver información detectada**
- Se abrirá una ventana nueva
- Verás tu versión exacta de Windows
- Build number
- Arquitectura

#### **Paso 3: Elegir método de descarga**

**Opción A: Microsoft Oficial**
- Para descargar la última versión estable
- Abre la página oficial de Microsoft
- Descarga directa

**Opción B: UUP Dump (Recomendado)**
- Para descargar el build EXACTO que tienes
- Perfecto para reinstalar sin problemas
- Búsqueda automática de tu build

**Opción C: Media Creation Tool**
- Para crear USB booteable
- Herramienta oficial de Microsoft

#### **Paso 4: Seguir instrucciones en el navegador**
- Se abrirá la página correspondiente
- Sigue las instrucciones de descarga

**⚠️ IMPORTANTE:**
- Descarga la misma versión que tienes instalada
- Misma arquitectura (64-bit o 32-bit)
- Tu Product Key solo funcionará con la versión correcta

</details>

---

### **✅ 4. Verificar Activación**

<details>
<summary><strong>👉 Haz clic para ver la guía paso a paso</strong></summary>

#### **Paso 1: Clic en "Verificar"**
- Botón con icono de check ✅

#### **Paso 2: Esperar verificación**
- Tarda 5-10 segundos
- Ejecuta `slmgr /xpr`

#### **Paso 3: Ver resultado**
- Aparecerá una ventana con el estado
- Puede mostrar:
  - ✅ "Windows está activado permanentemente"
  - ⏰ "Windows expira el [fecha]"
  - ❌ "Windows no está activado"

</details>

---

### **🔄 5. Reactivar Windows**

<details>
<summary><strong>👉 Haz clic para ver la guía paso a paso</strong></summary>

#### **¿Cuándo usar esta función?**
- Windows se desactivó después de cambiar hardware
- Mensaje de "Windows no está activado"
- Problemas de activación

#### **Paso 1: Clic en "Reactivar"**
- Botón con icono de recarga 🔄

#### **Paso 2: Confirmar acción**
- Aparecerá un diálogo de confirmación
- Haz clic en "Sí, reactivar"

#### **Paso 3: Esperar proceso**
- Puede tardar 30-60 segundos
- Se conectará a los servidores de Microsoft
- Requiere internet

#### **Paso 4: Ver resultado**
- ✅ Éxito: Windows se reactivó
- ❌ Error: Puede requerir activación telefónica

**💡 Si falla:**
- Ve a Configuración → Actualización y seguridad → Activación
- Usa "Solucionar problemas de activación"
- Contacta a soporte de Microsoft

</details>

---

### **📥 6. Instalar Nueva Licencia**

<details>
<summary><strong>👉 Haz clic para ver la guía paso a paso</strong></summary>

#### **¿Cuándo usar esta función?**
- Compraste una nueva Product Key
- Quieres cambiar de edición (Home a Pro)
- Migraste hardware

#### **Paso 1: Clic en "Instalar Nueva"**
- Botón con icono de descarga 📥

#### **Paso 2: Introducir Product Key**
- Aparecerá un campo de texto
- Formato: `XXXXX-XXXXX-XXXXX-XXXXX-XXXXX`
- 5 grupos de 5 caracteres

#### **Paso 3: Validar formato**
- La app verifica que sea válida
- No valida autenticidad (eso lo hace Windows)

#### **Paso 4: Aplicar licencia**
- Haz clic en "Instalar"
- Espera 30-60 segundos

#### **Paso 5: Activar**
- Automáticamente intentará activar
- Si falla, usa "Reactivar"

**⚠️ PRECAUCIÓN:**
- Asegúrate de que la key es auténtica
- No uses keys piratas o crackeadas
- Puede cambiar tu edición de Windows

</details>

---

### **🗑️ 7. Desinstalar Licencia**

<details>
<summary><strong>👉 Haz clic para ver la guía paso a paso</strong></summary>

#### **¿Cuándo usar esta función?**
- Vas a vender tu PC
- Quieres transferir la licencia a otro equipo (Retail)
- Problemas de activación severos

#### **Paso 1: Clic en "Desinstalar"**
- Botón ROJO con icono de papelera 🗑️

#### **Paso 2: Leer advertencia**
- Aparecerá un diálogo de advertencia
- Lee cuidadosamente

#### **Paso 3: Confirmar acción**
- Escribe "DESINSTALAR" (en mayúsculas)
- Haz clic en "Confirmar"

#### **Paso 4: Esperar proceso**
- Tarda 10-20 segundos
- Windows quedará sin licencia

#### **Paso 5: Verificar**
- Windows mostrará marca de agua
- Estado: "Windows no está activado"

**⚠️ ADVERTENCIA:**
- Esta acción desactiva Windows
- Necesitarás reinstalar una licencia después
- Solo licencias Retail son transferibles

</details>

---

## 🐛 **Solución de Problemas**

### **❌ Error: "No se puede extraer la Product Key"**

**Posibles causas:**
1. Licencia digital vinculada a cuenta de Microsoft
2. OEM sin clave embebida en BIOS
3. Licencia KMS corporativa

**Soluciones:**
- Ve a **Configuración → Sistema → Activación**
- Si dice "Windows está activado con una licencia digital", tu clave está en la nube
- Inicia sesión con tu cuenta de Microsoft para recuperarla
- Si es OEM, contacta al fabricante de tu PC

---

### **❌ Error: "Requiere permisos de administrador"**

**Causa:**
- No ejecutaste como administrador

**Solución:**
1. Cierra la aplicación
2. Clic derecho en el `.exe`
3. **"Ejecutar como administrador"**
4. Acepta el diálogo de UAC

---

### **❌ Windows Defender bloquea la descarga**

**Causa:**
- Falso positivo (común en apps nuevas sin firma digital)

**Solución:**
1. En el mensaje de Windows Defender
2. Haz clic en **"Más información"**
3. Haz clic en **"Ejecutar de todas formas"**

**Alternativa:**
- Agrega excepción en Windows Defender
- Configuración → Seguridad de Windows → Protección antivirus
- Administrar configuración → Exclusiones → Agregar exclusión

---

### **❌ Error: "No se puede activar Windows"**

**Posibles causas:**
1. Sin conexión a internet
2. Servidores de Microsoft caídos
3. Key incorrecta o ya usada
4. Cambio drástico de hardware

**Soluciones:**
- Verifica tu conexión a internet
- Espera unas horas y vuelve a intentar
- Usa "Solucionar problemas" en Configuración de Windows
- Contacta a soporte de Microsoft para activación telefónica

---

### **❌ La aplicación no abre**

**Soluciones:**
1. Verifica requisitos del sistema (Windows 10/11 64-bit)
2. Instala **Visual C++ Redistributable**
3. Desactiva temporalmente el antivirus
4. Ejecuta como administrador
5. Descarga de nuevo el `.exe` (puede estar corrupto)

---

### **❌ Error al descargar ISO**

**Causa:**
- Enlaces de Microsoft pueden cambiar

**Solución:**
- Visita manualmente:
  - Windows 11: https://www.microsoft.com/software-download/windows11
  - Windows 10: https://www.microsoft.com/software-download/windows10
- O usa UUP Dump: https://uupdump.net

---

## 💖 **Apoya el Proyecto**

Si **Windows License Manager** te fue útil, considera apoyar el desarrollo:

### **☕ Invítame un café**

<p align="center">
  <a href="https://www.paypal.com/paypalme/TU_PAYPAL">
    <img src="https://img.shields.io/badge/PayPal-Donar-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal">
  </a>
  <a href="https://ko-fi.com/TU_KOFI">
    <img src="https://img.shields.io/badge/Ko--fi-Apoyar-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi">
  </a>
  <a href="https://www.buymeacoffee.com/TU_USUARIO">
    <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donar-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee">
  </a>
</p>

### **🌟 Otras formas de apoyar**

- ⭐ **Dale una estrella** a este repositorio
- 🐛 **Reporta bugs** en [Issues](https://github.com/TU_USUARIO/windows-license-manager/issues)
- 💡 **Sugiere mejoras** en [Discussions](https://github.com/TU_USUARIO/windows-license-manager/discussions)
- 📢 **Comparte** con tus amigos y en redes sociales
- 📝 **Escribe una reseña** en tu blog o YouTube

---

## 👨‍💻 **Sobre el Desarrollador**

<p align="center">
  <img src="https://avatars.githubusercontent.com/TU_USUARIO?s=150" alt="Rodolfo Álvarez" style="border-radius: 50%;">
</p>

### **Rodolfo Álvarez**
**Desarrollador Full Stack | Especialista en Windows & Electron**

Apasionado por crear herramientas que simplifican la vida de los usuarios. Con más de X años de experiencia en desarrollo de software, me especializo en aplicaciones de escritorio multiplataforma y soluciones empresariales.

---

### **📬 Contacto**

<p align="center">
  <a href="mailto:rodolfoalvarezalvarez@gmail.com">
    <img src="https://img.shields.io/badge/Email-rodolfoalvarezalvarez@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

<p align="center">
  <a href="https://github.com/TU_USUARIO">
    <img src="https://img.shields.io/badge/GitHub-@TU__USUARIO-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://linkedin.com/in/TU_LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-Rodolfo%20Álvarez-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://twitter.com/TU_TWITTER">
    <img src="https://img.shields.io/badge/Twitter-@TU__TWITTER-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
</p>

---

### **🚀 Otros Proyectos**

- 📱 **[Proyecto 1]** - Descripción breve
- 🌐 **[Proyecto 2]** - Descripción breve
- 🎮 **[Proyecto 3]** - Descripción breve

---

## 📜 **Licencia**

Este proyecto está bajo la **Licencia MIT** - consulta el archivo [LICENSE](LICENSE) para más detalles.

