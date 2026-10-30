# APP reply moviles

Aplicación Android de ejemplo desarrollada con Kotlin y Jetpack Compose para la asignatura Aplicaciones Móviles.

Reply muestra una interfaz de correo electrónico con datos de ejemplo locales y diseños adaptables al tamaño de la pantalla.

## Contenido

- Lista de correos y pantalla de detalle.
- Categorías de buzón.
- Interfaz adaptable para diferentes tamaños de pantalla.
- Estado de interfaz administrado con ViewModel.
- Pruebas instrumentadas de interfaz y restauración de estado en `app/src/androidTest`.

## Abrir el proyecto

1. Clonar este repositorio.
2. Abrir la carpeta raíz del repositorio en Android Studio.
3. Sincronizar el proyecto con Gradle.
4. Seleccionar la configuración `app` y un dispositivo Android para ejecutarlo.

Configuración incluida: Gradle 8.4, Android Gradle Plugin 8.3.1, Kotlin 1.9.20, `compileSdk` y `targetSdk` 34, y `minSdk` 24. Usar JDK 17 para ejecutar Gradle 8.4.

Los archivos locales de Android Studio, el SDK configurado en `local.properties`, las cachés y los archivos de compilación no se incluyen en el repositorio.

## Origen y licencia

Basado en [Reply de Android Basics with Compose](https://github.com/google-developer-training/basic-android-kotlin-compose-training-reply-app).

Se conservan los avisos de copyright del código original y la licencia Apache 2.0 incluida en `LICENSE`.
