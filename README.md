# RampasMEZAApp

![Android](https://img.shields.io/badge/Platform-Android-green)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-blue)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-Private-red)

> 📱 Aplicación móvil empresarial para la gestión de **inventario y ventas**, desarrollada con tecnologías modernas de Android.

---

## Descripción

**RampasMEZAApp** es una aplicación Android diseñada para optimizar el control de inventario y el registro de ventas dentro de un entorno empresarial.

El sistema permite a los usuarios gestionar productos, controlar stock y registrar transacciones de forma eficiente, segura y centralizada.
---

## Arquitectura

El proyecto está construido bajo el patrón:

```bash
MVVM (Model - View - ViewModel)
```

### 📂 Organización modular

```bash
app/
├── data/                # Modelos de datos
├── ui/
│   ├── auth/            # Autenticación
│   ├── inventario/      # Inventario
│   ├── ventas/          # Ventas
│   ├── navigation/      # Navegación
│   └── theme/           # Estilos
```

---

## Tech Stack

| Tecnología          | Uso                 |
| ------------------- | ------------------- |
| Kotlin              | Lenguaje principal  |
| Jetpack Compose     | UI moderna          |
| ViewModel           | Manejo de estado    |
| Navigation Compose  | Navegación          |
| Firebase            | Backend / servicios |
| EmailJS             | Envío de correos    |
| Gradle (Kotlin DSL) | Build system        |

---

## Instalación

### Desarrollo

```bash
git clone <URL_DEL_REPOSITORIO>
```

1. Abrir en Android Studio
2. Sincronizar dependencias
3. Ejecutar en emulador o dispositivo

---

### Instalación (Empresa)

1. Generar APK:

```bash
Build > Build APK(s)
```

2. Instalar en dispositivo autorizado
3. Habilitar fuentes desconocidas

---

## 🔌 Integraciones

* ☁️ **Firebase**
* 📧 **EmailJS**

---

## 🧪 Testing

```bash
test/           # Unit tests
androidTest/    # Instrumented tests
```

---

## 🔄 Mantenimiento

* Versionado de APKs
* Actualizaciones manuales
* Respaldo de información
* Monitoreo de servicios

---

## 📄 Licencia

```
Uso privado - Proyecto empresarial
```

---

## 👨‍💻 Autor

Desarrollado como proyecto enfocado a soluciones empresariales con tecnologías móviles modernas.

---

## Contribuciones

Actualmente este proyecto es **privado**, por lo que no se aceptan contribuciones externas.

---
