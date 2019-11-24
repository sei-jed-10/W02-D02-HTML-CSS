[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# HTML and CSS

## Objectives

By the end of this, developers should be able to:

- Identify and use HTML tags, elements, and attributes
- Select HTML elements with CSS selectors
- Style HTML elements with CSS properties
- Build a static web page

![slides/0008.jpg](slides/0008.jpg)
![slides/0009.jpg](slides/0009.jpg)
![slides/0008.jpg](slides/0010.jpg)
![slides/008.jpg](slides/0011.jpg)
![slides/008.jpg](slides/0012.jpg)
![slides/008.jpg](slides/0019.jpg)
![slides/008.jpg](slides/0020.jpg)
![slides/008.jpg](slides/0022.jpg)


## Common DOCTYPE Declarations
### HTML 5
```html
<!DOCTYPE html>
```

### HTML 4.01 Strict
This DTD contains all HTML elements and attributes, but does NOT INCLUDE presentational or deprecated elements (like font). Framesets are not allowed.
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

### HTML 4.01 Transitional
This DTD contains all HTML elements and attributes, INCLUDING presentational and deprecated elements (like font). Framesets are not allowed.

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```
### HTML 4.01 Frameset
This DTD is equal to HTML 4.01 Transitional, but allows the use of frameset content.

```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
```
### XHTML 1.0 Strict
This DTD contains all HTML elements and attributes, but does NOT INCLUDE presentational or deprecated elements (like font). Framesets are not allowed. The markup must also be written as well-formed XML.

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
```

### XHTML 1.0 Transitional
This DTD contains all HTML elements and attributes, INCLUDING presentational and deprecated elements (like font). Framesets are not allowed. The markup must also be written as well-formed XML.
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

### XHTML 1.0 Frameset
This DTD is equal to XHTML 1.0 Transitional, but allows the use of frameset content.
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">
```

### XHTML 1.1
This DTD is equal to XHTML 1.0 Strict, but allows you to add modules (for example to provide Ruby support for East-Asian languages).

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
```

![slides/008.jpg](slides/0023.jpg)
![slides/008.jpg](slides/0025.jpg)
![slides/008.jpg](slides/0026.jpg)
![slides/008.jpg](slides/0027.jpg)
![slides/008.jpg](slides/0028.jpg)
![slides/008.jpg](slides/0029.jpg)
![slides/008.jpg](slides/0029a.jpg)
![slides/008.jpg](slides/0029b.jpg)


![slides/008.jpg](slides/0031.jpg)

### Block-level Elements
A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

Block level elements in HTML:
```html
<address><article><aside><blockquote><canvas><dd><div><dl><dt><fieldset><figcaption><figure><footer><form><h1>-<h6><header><hr><li><main><nav><noscript><ol><p><pre><section><table><tfoot><ul><video> 
```

![slides/008.jpg](slides/0032.jpg)
![slides/008.jpg](slides/0033.jpg)
![slides/008.jpg](slides/0034.jpg)
![slides/008.jpg](slides/0035.jpg)
![slides/008.jpg](slides/0036.jpg)

![slides/008.jpg](slides/0037.jpg)

### CSS Example

[http://csszengarden.com/](http://csszengarden.com/)

![slides/008.jpg](slides/0038.jpg)
![slides/008.jpg](slides/0039.jpg)
![slides/008.jpg](slides/0040.jpg)
![slides/008.jpg](slides/0041.jpg)
![slides/008.jpg](slides/0042.jpg)
![slides/008.jpg](slides/0043.jpg)
![slides/008.jpg](slides/0044.jpg)
![slides/008.jpg](slides/0045.jpg)
![slides/008.jpg](slides/0046.jpg)
![slides/008.jpg](slides/0047.jpg)
![slides/008.jpg](slides/0048.jpg)
![slides/008.jpg](slides/0049.jpg)
![slides/008.jpg](slides/0050.jpg)
![slides/008.jpg](slides/0051.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0015.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0016.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0017.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0018.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0019.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0020.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0021.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0022.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0023.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0024.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0025.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0026.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0027.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0028.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0029.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0030.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0031.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0032.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0033.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0034.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0035.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0036.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0037.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0038.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0039.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0040.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0041.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0042.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0043.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0044.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0045.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0046.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0047.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class2Slides_pages-to-jpg-0048.jpg)

![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0028.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0029.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0030.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0031.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0032.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0033.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0034.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0035.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0036.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0037.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0038.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0039.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0040.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0041.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0042.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0043.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0044.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0045.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0046.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0047.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0048.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0049.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0050.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0051.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0052.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0053.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0054.jpg)
![/slides/Class2Slides_pages-to-jpg.jpg](/slides/Class3Slides_page-0055.jpg)

## CSS Selector Practice

[https://flukeout.github.io/](https://flukeout.github.io/)
