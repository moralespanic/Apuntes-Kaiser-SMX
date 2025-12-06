# Bits / Bytes
## Teoría
Un bit (representado con `**b**`), es la unidad mínima para representar información en el mundo de la informática. Puede ser un `0` o un `1`.

Un byte (representado con `**B**`) equivale a `8 bits`.

> El hecho de que la letra "B" esté en mayúsculas o minúsculas indica si se trata de bits (`b`) o bytes (`B`).

## Ejemplos
### Conversión de Bytes a Bits
#### Ejemplo 1
50 B → ? b  

50 × 8 = 400 b

#### Ejemplo 2
1 024 B → ? b  

1 024 × 8 = 8 192 b

### Ejemplo 3
7 B → ? b  

7 × 8 = 56 b


## Conversión de Bits a Bytes
### Ejemplo 1
800 b → ? B  

800 ÷ 8 = 100 B

### Ejemplo 2
256 b → ? B  

256 ÷ 8 = 32 B

### Ejemplo 3
1 000 b → ? B  

1 000 ÷ 8 = 125 B

# Almacenamiento de archivos

Por definición técnica, esto es lo correcto:

```
Base 2: 1 GiB (gibibyte) = 1024 MiB (mebibyte)

Base 10: 1 GB (gigabyte) = 1000 MB (megabyte)
```

Pero, para ser más "accesible al público", Windows estandarizó lo siguiente:

```
1 GB (gigabyte) = 1024 MB (megabyte)
```

Lo cual no es correcto... Windows representa valores de **base 2** (`1024`) con unidades de **base 10** (`GB, MB, KB...`).

Esto se ha estandarizado tanto, que hoy en día, en el lenguaje coloquial, e incluso profesional, se utiliza esta forma de representar los valores. Aunque no sea correcto.

Pero bueno... como nosotros estamos aquí para seguir las órdenes de los profes, vamos a seguir la *tradición* de Windows, y representar valores de base 2 con unidades de base 10.

## Tabla de definición

| Unidad de almacenamiento de datos |         Tamaño por unidad                |
|:---------------------------------:|:-----------------------------------------|
| Bit (**b**)                       | Un valor único, que puede ser 0 o 1      |
| Byte (**B**)                      | Un conjunto de 8 bits (p.ej. `10010011`) |
| Kilobyte (**KB**)                 | 1024 Bytes                               |
| Megabyte (**MB**)                 | 1024 Kilobytes                           |
| Gigabyte (**GB**)                 | 1024 Megabytes                           |
| Terabyte (**TB**)                 | 1024 Gigabytes                           |
