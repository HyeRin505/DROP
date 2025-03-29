# 📱 DROP - Aplicación Android

Link de descarga: https://drive.google.com/file/d/1ijA0eyh-UqNVTC8v3c2ncwIa4b0EEzfM/view?usp=drive_link

NOTA: DESCARGAR EL ARCHIVO, DESCOMPRIMIRLO Y PASAR LA CARPETA A DONDE SE ALMACENAN LOS PROYECTOS EN ANDROID STUDIO

Aplicación móvil que muestra una implementación híbrida de Jetpack Compose y componentes tradicionales de Android.

## 🚀 Características Principales
- ✅ Pantalla de inicio con **Fragments** tradicionales
- ✅ Pantalla de detalles con **Jetpack Compose**
- ✅ Cambio dinámico de tema con **SharedPreferences**
- ✅ Navegación con **Navigation Component**
- ✅ Arquitectura **MVVM** con ViewModel

## 🛠 Tecnologías
<p align="left">
    <img src="https://img.shields.io/badge/Kotlin-1.9.20-purple?logo=kotlin" alt="Kotlin">
    <img src="https://img.shields.io/badge/Android%20Studio-Flamingo-orange?logo=android-studio" alt="Android Studio">
    <img src="https://img.shields.io/badge/Compose-1.5.4-blue?logo=jetpack-compose" alt="Jetpack Compose">
    <img src="https://img.shields.io/badge/Min%20SDK-24-green?logo=android" alt="Min SDK">
</p>

## 📸 Capturas


## 📁 Estructura del Proyecto
```bash
DROP/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/drop/
│   │   │   │   ├── ui/
│   │   │   │   │   ├── home/       # Fragment + XML
│   │   │   │   │   ├── details/    # Pantalla Compose
│   │   │   │   │   └── settings/   # Preferencias
│   │   │   │   └── theme/          # Temas y estilos
│   │   │   ├── res/                # Recursos
│   │   │   └── AndroidManifest.xml
│   └── build.gradle.kts            # Dependencias del módulo
├── gradle/
└── build.gradle.kts                # Configuración global
