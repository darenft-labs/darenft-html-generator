## `assets`
This directory contains any assets your website needs. The layout can be completely custom.

> NOTE: If certain assets are unused in code (unimported), they WILL NOT BE COPIED over.
> 
> If you need the described behaviour (a simple asset copy), use the `static` directory. 

When wanting to use the assets, simply use them in HTML like so:
```html
<img src="../../assets/images/sample-image.jpg" alt="Some image." />
```
or in code like so:
```typescript
import image from "../../assets/images/sample-image.jpg";
```

In both cases use of the image will be detected, copied into the build directory and the url above rewritten to match.
