# Platzom

Platzon es un idioma inventado para el [curso
de Fundamentos de JavaScript de Platzi](https://platzi.com/js), el mejor 
lugar de educacion online

## Descripcion del idioma 

- Si la palabra original es un palindromo,
ninguna regla anterior cuenta y se devulve
la misma palabra, intercalando Mayusculas
y minusculas. 

- Si la palabra termina en "ar" se le quitan esos dos caracteres

- Si la palabra inicia con Z se le añade "pe" al final

- Por ultimo, si la palabra traducida tiene 10 o mas letras, se debe partir a la mitad y unir con un guion
del medio.

## Instalacion

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar") //Program
platzom("Zorro") //Zorrope
platzom("Zarpar") //Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") //SoMeTeMoS
```

##Créditos

- [Ada Parra](https://twitter/pao506)