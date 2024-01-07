# Select2 - Bootstrap 5 theme

[![GitHub tag (with filter)](https://img.shields.io/github/v/tag/apih/select2-bootstrap5?style=flat-square)](https://github.com/apih/select2-bootstrap5)
[![jsDelivr hits (GitHub)](https://img.shields.io/jsdelivr/gh/hm/apih/select2-bootstrap5?style=flat-square)](https://www.jsdelivr.com/package/gh/apih/select2-bootstrap5)
[![GitHub](https://img.shields.io/github/license/apih/select2-bootstrap5?style=flat-square)](LICENSE.md)

A Bootstrap 5 theme for Select2. It is tailored for usage with the default Bootstrap 5. If you want to use it with custom Bootstrap 5 theme, you will need to override certain classes.

## Requirements

- Select2 4.0.13
- Bootstrap 5

## Installation

Get the file from [jsDelivr CDN](https://www.jsdelivr.com/package/gh/apih/select2-bootstrap5) and include it in your HTML page. Set the `theme` option to `bootstrap5` when initializing the component.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/apih/select2-bootstrap5@latest/dist/style.min.css">

<script>
    $('#element').select2({
        theme: 'bootstrap5',
    });
</script>
```
