# `xenon-masked-numeric`

Masks input to custom patterns

### License:

MIT

### Usage:

```html
<xenon-masked-numeric id="cellNumber"
                      mask="###-###-####"
                      regex="^\d{3}-\d{3}-\d{4}$"
                      value="{{cellNumberProperty}}"
                      label="Cell Number">
</xenon-masked-numeric>
```
