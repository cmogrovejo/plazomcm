# Platzom

Platzom es un idioma inventado para el curso fundamentos de js de [platzi](https://platzi.com), el mejor lugar de educacion online

## Descripcion del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## Instalacion

```
npm install platzomcm
```

## Uso

```
import platzomcm from 'platzomcm'

platzomcm("Programar") // Program
platzomcm("Zorro") // Zorrope
platzomcm("Zarpar") // Zarppe
platzomcm("abecedario") // abece-dario
platzomcm("sometemos") // SoMeTeMoS
```

## Creditos
- [Carlos Mogrovejo](http://twitter.com/cmogrovejo)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
