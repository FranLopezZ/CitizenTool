<div align="center">

# CitizenTool

### Herramienta de automatización para Star Citizen

[![Version](https://img.shields.io/badge/version-1.0.0-89b4fa?style=for-the-badge)](https://github.com/TU_USUARIO/TU_REPO/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-a6e3a1?style=for-the-badge&logo=windows)](https://github.com/TU_USUARIO/TU_REPO/releases)
[![License](https://img.shields.io/badge/licencia-privada-f38ba8?style=for-the-badge)](https://github.com/TU_USUARIO/TU_REPO)

</div>

---

## ¿Qué es CitizenTool?

**CitizenTool** es una utilidad de escritorio para Windows diseñada para automatizar acciones repetitivas en **Star Citizen**. Permite configurar clics automáticos, pulsaciones de teclas y arrastres de objetos, todo con una interfaz limpia y controles globales de teclado.

> ⚠️ Esta herramienta es de **uso privado y restringido**. Se requiere una clave de acceso para utilizarla.

---

## Características

| Función | Descripción |
|---|---|
| 🖱️ **Clic automático** | Haz clic izquierdo de forma repetida en la posición actual del ratón |
| ⌨️ **Pulsación de tecla** | Pulsa automáticamente cualquier tecla a intervalos configurables |
| 🔄 **Arrastre automático** | Mueve objetos del punto A al punto B de forma repetida |
| ⚡ **Tecla de activación** | Inicia y detiene todo con una sola tecla global (configurable) |
| 💾 **Configuración persistente** | Todos los ajustes se guardan automáticamente |
| 🔒 **Sistema de licencias** | Acceso controlado por clave personal |
| 🔄 **Actualizaciones automáticas** | La app avisa cuando hay una versión nueva y se actualiza sola |

---

## Requisitos

- Windows 10 / 11
- Clave de acceso proporcionada por el administrador

> No se necesita instalar nada más. El `.exe` incluye todas las dependencias.

---

## Instalación

1. Descarga la última versión desde [**Releases**](https://github.com/TU_USUARIO/TU_REPO/releases)
2. Ejecuta `CitizenTool.exe` **como Administrador** (necesario para la captura global de teclas)
3. Introduce tu clave de acceso cuando se solicite
4. ¡Listo!

---

## Uso

### Interfaz principal


<img width="609" height="552" alt="image" src="https://github.com/user-attachments/assets/0b27c1e7-ca29-4ff9-b33c-9c41f88527d2" />


### Controles rápidos

| Acción | Cómo |
|---|---|
| Iniciar / Detener | Tecla global (por defecto `F6`) o botones en pantalla |
| Cambiar tecla de activación | Clic sobre la tecla azul en la barra inferior |
| Capturar coordenadas | Botón **Capturar** → mueve el ratón al punto → espera 3s |
| Parada de emergencia | Mueve el ratón a la **esquina superior izquierda** |

### Sección Clic automático

Hace clic izquierdo repetidamente en la posición actual del ratón. Configura el intervalo en **milisegundos** (`ms`) o **segundos** (`seg`).

### Sección Pulsación de tecla

Pulsa automáticamente la tecla asignada. Para cambiarla: haz clic en el campo de tecla y pulsa físicamente la tecla deseada.

### Sección Arrastre automático

Simula coger un objeto del **Punto A** y soltarlo en el **Punto B**:
1. Pulsa **Capturar** junto a Punto A, mueve el ratón al origen y espera 3 segundos
2. Repite para el Punto B
3. Ajusta la **velocidad del movimiento** (menos ms = más rápido) y el **intervalo entre arrastres**

---

## Configuración

Todos los ajustes se guardan automáticamente en:

```
%APPDATA%\Kisko\CitizenTool\opciones.cfg
```

El archivo tiene formato JSON y se restaura al abrir la aplicación.

---

## Actualizaciones

Cuando hay una nueva versión disponible, la app muestra un aviso al arrancar con el changelog. Pulsa **Actualizar ahora** y la aplicación se actualiza y reinicia sola.

También puedes comprobar manualmente pulsando el botón **↻** junto a la versión.

---

## Clave de acceso

Esta herramienta requiere una **clave de acceso personal** para funcionar. Las claves:

- Son individuales y no transferibles
- Se validan online cada vez que abres la app (requiere conexión a internet)
- Pueden ser revocadas en cualquier momento por el administrador

Para solicitar acceso, contacta con el administrador de la organización.

---

## Solución de problemas

**"No se puede conectar al servidor de licencias"**
→ Comprueba tu conexión a internet. La app necesita validar la licencia al arrancar.

**La tecla global no funciona**
→ Ejecuta el `.exe` como Administrador.

**El icono no aparece en el Explorador**
→ Ejecuta `Limpiar_Cache_Iconos.bat` si dispones de él, o mueve el `.exe` a otra carpeta.

**Windows Defender bloquea el archivo**
→ Es normal con ejecutables sin firma comercial. Pulsa *Más información → Ejecutar de todas formas*, o añade una excepción en Defender.

---

<div align="center">

Hecho con ❤️ para la organización · **Citizen Tool by Kisko** · `v1.0.0`

</div>
