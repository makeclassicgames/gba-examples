# GBA Examples

Ejemplos de desarrollo de Game Boy advance

En este repositorio puedes encontrar ejemplos de desarrollo para la consola Game Boy Advance, usando las herramientas de [devkitpro](https://github.com/devkitPro).

En cada carpeta puedes encontrar un ejemplo relacionado con una funcionalidad o temática.

## Compilar

Para compilar cada ejemplo, se puedes utilizar el fichero makefile que adjunta en cada caso, con el comando:
```bash
make
```

### Docker

Puede usarse una imagen docker que puedes descargar el fichero Dockerfile desde la dirección:

[https://github.com/zerasul/dockerretro/tree/master/gba](https://github.com/zerasul/dockerretro/tree/master/gba).

Para constuir la imagen:

```bash
docker build -t gba-dev .
```

Para compilar ejecutar el siguiente comando:

```bash
docker run --rm -v $pwd:"src/gba" gba-dev #usar %CD% para windows
```
