# Docker action "Hola Mundo"

Esta action imprime "Hola mundo" u "Hola" + el nombre de la persona al log.

## Inputs

### `who-to-greet`

**Requerido** El nombre de la persona a quien saludar. Por defecto `"Mundo"`

## Outputs

### `time`

La fecha en la que te salude.

## Example usage

```
uses: pablokbs/hello-world-docker-action@v1
with:
  who-to-greet: 'Peladonerd'
```
