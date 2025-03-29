# 📱 DROP - Aplicación Android

![Header Image](https://via.placeholder.com/800x200?text=DROP+App+Banner) <!-- Reemplaza con tu imagen -->

Aplicación móvil desarrollada en Android Studio que implementa:
- ✔️ Jetpack Compose para UI moderna
- ✔️ Navigation Component para flujo de pantallas
- ✔️ ViewModel + LiveData para gestión de estado
- ✔️ Temas personalizables con cambio dinámico de colores

## 📸 Capturas de Pantalla
| Inicio | Detalles | Configuración |
|--------|----------|--------------|
| ![Home](https://via.placeholder.com/150) | ![Details](https://via.placeholder.com/150) | ![Settings](https://via.placeholder.com/150) |

## 🛠 Tecnologías Utilizadas
- **Lenguaje**: Kotlin 100%
- **Arquitectura**: MVVM (Model-View-ViewModel)
- **Componentes**:
  - `Compose` (Pantalla de Detalles)
  - `Fragments` (Pantallas tradicionales)
  - `SharedPreferences` (Persistencia de configuraciones)
- **Dependencias Principales**:
  ```gradle
  implementation("androidx.navigation:navigation-compose:2.7.6")
  implementation("androidx.compose.material3:material3:1.1.2")
  implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:2.6.2")
