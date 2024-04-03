## Criptografia con matrices - Univerisdad Autonoma de Queretaro UAQ


### Funcionamiento

Se ha usado un alfabeto de 41 caracteres, 26 letras del abecedario, 10 dígitos numéricos, del 0 al 9, así como los 4 caracteres siguientes: "\.", "\,", "\:", "\?" y el espacio en blanco, en ese orden.

Cada letra está representada por un número (diccionario).


#### Encriptar

```
> python .\EncriptacionMatris.py

Ingrese el numero:
 1 para encriptar
 2 para desencriptar:
 num: 1
Ingrese la dimension de la matriz llave: 3
Ingrese una frase: DESCANSE EN PAZ CREADOR DEL SHONEN AKIRA TORIYAMA

 Llave utilizada:

 [[8, 21, 32], [32, 8, 20], [30, 33, 25]]

 Texto encriptado: '2,QW,Q6O61H6S,JE,KFY515NJUFUGBVRGB?3N1FND62G7CY.43W'

 Finalizo proceso --> encriptar        

```

#### Desencriptar

```
> python .\EncriptacionMatris.py
  ____ _  __               _           _      _   _ _ _ _ 

Ingrese el numero:
 1 para encriptar
 2 para desencriptar:
Respuesta: 2
Ingrese la matriz llave: [[8, 21, 32], [32, 8, 20], [30, 33, 25]]
Ingrese el valor encriptado: 2,QW,Q6O61H6S,JE,KFY515NJUFUGBVRGB?3N1FND62G7CY.43W

 Texto desencriptado: 'DESCANSE EN PAZ CREADOR DEL SHONEN AKIRA TORIYAMA'

 Finalizo proceso  --> desencriptar

```