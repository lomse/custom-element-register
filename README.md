# Custom Element Register

This script dynamically loads a script tag (to be used to serve a custom element) and creates a custom element tag inside another HTML element for the custom element.

[GitHub](https://github.com/chriskitson/custom-element-register)

## Usage

```
import { RegisterCustomElement } from 'custom-element-register';

RegisterCustomElement(document.getElementBy('#myContainer'), 'my-app', 'http://my.app/element.js');
```