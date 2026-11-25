# MiRegistro — Generación de APK y Play Store

## Opción 1: Android Studio
1. Descomprime este ZIP y ábrelo en **Android Studio**.
2. Espera a que Gradle sincronice.
3. Ve a **Build > Build Bundle(s) / APK(s) > Build APK(s)** (o **Generate Signed Bundle / APK** para Play Store).

## Opción 2: GitHub Actions (sin instalar Android Studio)
1. Sube estos archivos a un repositorio de GitHub (incluyendo `.github/workflows/build-apk.yml`).
2. Ve a **Actions > Build MiRegistro APK > Run workflow**.
3. Descarga el artefacto `MiRegistro-debug-apk` con tu archivo `app-debug.apk`.
