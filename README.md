# Countries Select Custom Element

Es un "web Component" para hacer un campo select que ya viene poblado con los países del mundo.

## Instalar

bower install dw-countries-select

## Usar

Poder usar este componente requiere de dos pasos:

### HTML Import

```script
<link rel="import" href="bower_components/dw-countries-select/dw-countries-select.html">
```

### Usar el componente

```script
<select name="pais" is="dw-countries-select"></select>
```

You may also enter additional options in the HTML code of the component.

```script
<select is="dw-countries-select">
    <option value="-">Select your country</option>
</select>