# Docker action "Hola Mundo"

Este actions imprime un "Hola Mundo" o "Hola" + el nombre que se le pase por parametro

## Inputs

### `who-to-greet`

**Requerido** El nombre de la persona a saludar.  Por defecto Mundo

## Outputs

### `time`

La fecha en la que te salude

## Ejemplo de uso

```
uses: saqpsaqp/helloworld-githubactions@v1
with:
  who-to-greet: 'Mundo Cruel'
```
