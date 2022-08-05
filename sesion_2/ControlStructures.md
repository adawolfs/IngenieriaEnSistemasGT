# Control Structures

# Expressions and Statements

## Expressions

Las expresiones tienen valor.
```
2+2
PI * radius ** 2
Math.min(PI, 2)
```

## Statements
Las declaraciones no tienen valor y representan un efecto
```
let sumatoria = 2 + 2;
let diameter = PI * radius ** 2;
```
        
## Semicolons ;

A diferencia de C y Java en JavaScript los punto y coma pueden omitirse, 
esto debido a que el interprete lo agrega por nosotros.

Los punto y coma solo se agregan antes de final de linea o un `}`, Si tienes multiples declaraciones en una misma linea, deberan de utilizar punto y coma.

## Branch

Bloque de codigo
```
{
    ....
}
```
## Boolishness

### Comparison
```
> NaN < 4
false
> NaN >= 4
false
> NaN <= NaN
false
```

```
> `Manuel` < `Rodas` 
true

> `Fernando` < `Fernandez`
```
### `===` & `!==`
```
> '23' === 23 
false

> undefined === null
false

> '42' === '4' + 2 
true
```

```
> 1 === NaN
false
> NaN === NaN
false
> Number.isNaN(NaN)
true
```