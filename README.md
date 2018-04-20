#Platzom

Platzom es un idioma inventado para el Curso [Fundamendos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educación online

## Descripción del idioma
- Si la palabra termina en "ar", se le quitan esos dos carácteres.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras se debe partir a la mitad y unir con un guión.
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas.

## Instalación
```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("programar") // Program
platzom('programar'); // program
platzom('zorro'); // zorrope
platzom('zarpar'); // zarppe
platzom('abecedario'); // abece-dario
platzom('sometemos'); // SoMeTeMoS
```

## Créditos
- [Jhan Karlo](https://jhankarlo.com)

##Licencia
[MIT](https://opensource.org/licenses/MIT)