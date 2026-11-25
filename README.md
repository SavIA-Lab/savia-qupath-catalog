# Catálogo SavIA para QuPath

Este catálogo permite instalar SavIA 0.2.0 desde el gestor de extensiones de QuPath 0.7.0.

## Publicar el catálogo

1. Publica la release `v0.2.0` en el repositorio público `qupath-extension-savia` y adjunta `qupath-extension-savia-0.2.0.jar`.
2. Sustituye `TU-ORGANIZACION` en `homepage` y `main_url` de `catalog.json` por la cuenta u organización que aloja la extensión. Ajusta las URLs si el repositorio, la etiqueta de la release o el JAR tienen otro nombre.
3. Comprueba que `main_url` descarga el JAR de instalación y publica estos dos archivos en la raíz de un repositorio público independiente llamado `qupath-catalog-savia`.

## Instalar SavIA

1. Abre **Extensiones → Administrar extensiones → Administrar catálogos de extensiones** en QuPath.
2. Pulsa **Agregar** e introduce la URL del repositorio del catálogo, por ejemplo `https://github.com/TU-ORGANIZACION/qupath-catalog-savia`.
3. En el gestor de extensiones, pulsa **+** junto a **SavIA — Exportación YOLO**.

[Documentación de catálogos de QuPath](https://qupath.github.io/extension-catalog-model/)
