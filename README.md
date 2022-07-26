# Mapeo de teclas en español para el Corne Keyboard
*Basado en Soundmonster's*


### Características:
- Definición de teclas para Español, en formarto que me acomoda personalmente.
- Indicador de Capas ↑ ↓
- Indicador gráfico para: ⌘ ⇧ ⌥ ⌃

###
Como usarlo:

1. Bajar el Firmware QMK desde su repositorio [qmk/qmk_firmware](https://github.com/qmk/qmk_firmware).
2. Seguir los pasos de configuración de QMK puedes bajar la documentación en [Docs QMK](https://docs.qmk.fm).
2. Crear una carpeta donde guardaremos los archivos de este repositorio, la carpeta deberá estar dentro de la siguiente ruta del código descargado de QMK

> keyboards\crkbd\keymaps

Yo he creado una carpeta llamada `mmaragan`

Para compilar con mi versión de teclado se deben copiar todos los archivos de este repositorio en la carpeta `mmaragan` y compilar con el siguiente comando:

```
qmk compile -kb crkbd -km mmaragan
```

Usando QMK Tookbox, cargan el .hex creado en el microcontrolador.
