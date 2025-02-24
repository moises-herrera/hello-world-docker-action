# Docker action "Hello World"

Esta acción imprime "Hello World" o "Hello " + el nombre que recibe como argumento.

## Inputs

### `who-to-greet`

**Requerido** El nombre de la persona a saludar. Por defecto `"World"`

## Outputs

### `time`

La fecha del saludo.

## Example usage

```
uses: moises-herrera/hello-world-docker-action@v4
with:
  who-to-greet: 'Moises'
```
