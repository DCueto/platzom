# README

Platzom es un modulo que traduce palabras a un lenguaje inventado para el Curso de Fundamentos de Javascript de [Platzi](https://platzi.com).


## Descripción del idioma

- Si la palabra termina en "ar", se le quitan esos dos carácteres.
- Si la palabra inicia con Z se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras se debe partir a la mitad y unir con un guión del medio.
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayusculas y minúsculas.


## Instalación del módulo

```
npm install platzom
```


## Uso

```
import platzom form 'platzom'

platzom('Programar') //Program
platzom('Zorro') //Zorrope
platzom('Zarpar') //Zarppe
platzom('abecedario') //abece-dario
plazom('sometemos') //SoMeTeMoS
```


## Créditos

- [Platzi](https://twitter.com/Platzi)

## Licencia

[MIT](https://opensource.org/licenses/MIT)

