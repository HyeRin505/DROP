# 📱 DROP - Aplicación Android

![Banner](https://via.placeholder.com/1200x400/3d5a80/ffffff?text=DROP+Android+App)

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

## 📸 Demo
<img src="https://via.placeholder.com/200x400/3d5a80/ffffff?text=Home" width="200" alt="Home Screen"> <img src="https://via.placeholder.com/200x400/3d5a80/ffffff?text=Details" width="200" alt="Details Screen"> <img src="https://via.placeholder.com/200x400/3d5a80/ffffff?text=Settings" width="200" alt="Settings Screen">

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
