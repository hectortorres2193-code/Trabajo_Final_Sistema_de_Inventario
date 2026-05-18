# Sistema de Registro de Ventas y Facturación

## Aviso Legal
Esta sociedad anónima se desliga de cualquier fallo provocado por el uso no especificado 
del producto en los siguientes apartados.

## Para el Usuario

### Primer paso
Al iniciar el producto, crear un registro. Esto generará automáticamente los 3 archivos 
manipulables: `clientes.txt`, `Productos.txt` y `Fechas.txt`.

### Ver archivos
Los pasos siguientes no siguen un orden específico a menos que se mencione.
Para ver los archivos tienes 3 opciones:

1. Seleccionar opción **2** para ver el archivo central
2. Seleccionar una opción para ver uno de los archivos menores
3. Abrir directamente desde las carpetas del sistema

### Actualizar registros
Para actualizar tienes 2 opciones:

1. Editar desde el programa seleccionando la opción de modificar uno de los archivos menores
2. Modificar los archivos directamente desde el Bloc de notas

### Aclaraciones
- Si el cambio no se ve reflejado, usar la opción de **Refrescar**
- Si aún así no se ve reflejado, significa que no se guardó correctamente 
  la modificación en el Bloc de notas

## IMPORTANTE
Cualquier cambio realizado directamente en el archivo **central.txt** 
NO SE CONSERVARA.

## Borrar
cuando se seleciona borra una linea de un archivo menor esta se remplaza para no comprometer la linea central en los archivos de texto se pone la palabra latina de nihil que simifica nada en los precios se convierte a 0 y en las fecha retrocede ala fecha mas antigua que permite el programa 
## errores
si pone un dato no procesable como 32 de febrero el id se vacia y pide que sea rellenado otra vex el codigo espesifica cual fue el tipo de erros
## Modificaciones
si se desea modificar el codigo se recomiendo craer nuvas funciones y no modificar las existentes,no prohibimos tajantemente las modificaciones directas aunque si las desaconsejamos
## estrutura del codigo
todas las funciones del codigo estan en la parte superios despues en el main hay un ciclo que se repetira indefinidamente hasta que se selecione la opcion de salida le sigue una funcion para asegurar que la fecha si exista en nustro calendario se crean los 3 archivos y se pide que los llenen ala par quese crea un 4 donde de junta la informacion unidad por el id comun le sigue una función que permite ler los archivos individuales,otra que destruye y recontruye al archivo central esta funcion se llama refrescar por ultimo hay 2 familias de funciones la de actualiza y la de borra que depende de a funcion de refrescar para su corecto funcionamiento
## Autores
- **Héctor Leonardo Torres** - https://github.com/hectortorres2193-code
- **David Gutiérrez Maciel** - https://github.com/David-Esperantista
