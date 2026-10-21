# Ralag Mods

Repositorio público para alojar mods de Minecraft usando GitHub Pages como URL base para AutoModpack.

## Estructura recomendada

```text
config/
├── create-adapted/
│   └── external-assets/
│       └── create-1.21.1-6.0.10.jar
├── ad-astra-adapted/
│   └── external-assets/
│       └── ad-astra-1.21.1.jar
```

## URL base de GitHub Pages

```text
https://Ralag.github.io/ralag-eter-mods/
```

## Ejemplo de archivos descargables

```text
https://Ralag.github.io/ralag-eter-mods/config/create-adapted/external-assets/create-1.21.1-6.0.10.jar
https://Ralag.github.io/ralag-eter-mods/config/ad-astra-adapted/external-assets/ad-astra-1.21.1.jar
```

## Configuración en AutoModpack

```properties
external-url = "https://Ralag.github.io/ralag-eter-mods/"
```

## Pasos

1. Subir cada archivo `.jar` a la carpeta correcta en el repositorio.
2. Activar GitHub Pages en `Settings > Pages`.
3. Usar la URL base del sitio publicado.
4. Ejecutar:

```bash
/automodpack generate
```

## Nota importante

Si deseas consumir los recursos desde AutoModpack, no uses enlaces de GitHub Releases ni URLs de descarga de CurseForge directamente. La estructura de carpetas del repositorio es la que AutoModpack necesita para resolver rutas 1:1.

Cuando tengas los mods reales, renombra los archivos exactos al nombre final del `.jar` que vayas a distribuir.
