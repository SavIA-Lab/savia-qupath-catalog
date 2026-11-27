# Catálogo SavIA para QuPath

Este catálogo permite instalar SavIA desde el gestor de extensiones de QuPath 0.7.0.

## Actualizar el catálogo

1. Publica la nueva versión en [GitHub Releases](https://github.com/SavIA-Lab/int-software-qupath-extension/releases) y adjunta el JAR de instalación.
2. Agrega la nueva versión a `catalog.json`, conservando las entradas anteriores. Indica la compatibilidad con QuPath y la URL directa del JAR en `main_url`.
3. Comprueba que la URL descarga el JAR antes de subir el cambio del catálogo a GitHub.

## Instalar SavIA

1. Abre **Extensiones → Administrar extensiones → Administrar catálogos de extensiones** en QuPath.
2. Pulsa **Agregar** e introduce la URL del catálogo `https://github.com/SavIA-Lab/savia-qupath-catalog`.
3. En el gestor de extensiones, pulsa **+** junto a **SavIA — Exportación YOLO**.

[Documentación de catálogos de QuPath](https://qupath.github.io/extension-catalog-model/)
