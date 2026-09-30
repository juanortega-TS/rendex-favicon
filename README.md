# rendex-favicon

Favicon público de **Rendex**, el asistente de rentabilidad de freído de
Alianza (Team Foods).

Existe solo porque Google Apps Script no acepta un favicon incrustado: la
aplicación (`juanortega-TS/rendex-gas`, privado) lo carga con
`HtmlOutput.setFaviconUrl`, que exige una URL https pública terminada en
`.png`:

```
https://raw.githubusercontent.com/juanortega-TS/rendex-favicon/main/icon.png
```

Este repositorio es público: no guardar aquí nada más que el ícono.

## El ícono

`icon.png` (512×512): el símbolo oficial de Alianza, escalado de forma
uniforme y centrado, con fondo transparente por decisión de marca. Si se
cambia, la URL sigue siendo la misma; el navegador puede tardar en
refrescarlo por su caché.
