---
{"dg-publish":true,"permalink":"/modul-0373-llenguatges-de-marques-i-sistemes-de-gestio-d-informacio/projecte/histories/historia-2/resum-de-conceptes-html-per-estructurar-i-formatar-pagines-web-de-manera-semantica/"}
---


HTML proporciona etiquetes semàntiques que ajuden a estructurar el contingut d'una manera clara i comprensible, tant per a usuaris com per a motors de cerca. A continuació s'explica com utilitzar algunes de les etiquetes més comunes.

#### 1. **Estructura bàsica d'una pàgina HTML**

L'estructura típica d'una pàgina HTML comença amb la declaració del tipus de document i es divideix en dues parts principals: `<head>` i `<body>`.

```html
<!DOCTYPE html> 
<html lang="ca"> 
<head>   
	<meta charset="UTF-8">   
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Títol de la pàgina</title> 
</head> 
<body>   
	<!-- Contingut principal va aquí --> 
</body> 
</html>
```

- **`<head>`**: Conté metadades sobre la pàgina (jocs de caràcters, títol, enllaços a CSS, etc.).
- **`<body>`**: On es troba el contingut visible, com text, imatges, seccions, etc.


#### 2. **Encapçalaments** (`<h1>` a `<h6>`)

Els encapçalaments són utilitzats per estructurar el contingut en seccions jeràrquiques.

```html
<h1>Títol principal de la pàgina</h1>
<h2>Subtítol</h2>
<h3>Encapçalament de nivell 3</h3>

```

- **`<h1>`** és el títol principal d'una pàgina, i **`<h2>`** a **`<h6>`** indiquen subseccions.

#### 3. **Pàragraf** (`<p>`)

Els paràgrafs són la manera principal de presentar text en blocs.

```html
<p>Aquest és un paràgraf de text. Es pot combinar amb altres etiquetes per formatar el text.</p>

```

