# Arduino PIC Programmer
Esta herramienta funciona para programar PIC con un Arduino UNO R3

## Como usar:
1. Carga el sketch "ArduPIC.ino" en el arduino
2. Realiza la conexión del PIC al arduino mediante un protoboard ([Ver Esquema](docs/esquema.md))
3. Ejecuta desde un terminal

     ./ardupic.py -i ARCHIVO_HEX

### Compatibilidad
Ha sido exitosamente utilizado para cargar el HEX de pinguino.cc para los siguientes PIC:

- 18F2550
- 18F4550
