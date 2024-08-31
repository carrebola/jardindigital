---
{"dg-publish":true,"permalink":"/modul-0373-llenguatges-de-marques-i-sistemes-de-gestio-d-informacio/conceptes/css/"}
---

![Pasted image 20240831155310.png](/img/user/M%C3%B2dul%200373%20Llenguatges%20de%20marques%20i%20sistemes%20de%20gesti%C3%B3%20d%E2%80%99informaci%C3%B3/Conceptes/adjuntos/Pasted%20image%2020240831155310.png)

**CSS (Cascading Style Sheets)** és el llenguatge utilitzat per definir l'aspecte i el format de les pàgines web creades amb HTML. Permet aplicar estils com colors, fonts, i disseny a diferents elements HTML.

### Exemple de Codi CSS:

```css
/* Defineix l'estil per al cos de la pàgina */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

/* Defineix l'estil per als títols */
h1 {
    color: #333;
    text-align: center;
}

/* Defineix l'estil per als enllaços */
a {
    color: #1a73e8;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

```

### Alguns components Clau:

- **Selectores**: Especifiquen quins elements HTML s'han de formatar (`body`, `h1`, `a`).
- **Propietats**: Defineixen l'estil aplicat (com `font-family`, `background-color`, `color`).
- **Valors**: Indiquen el valor de cada propietat (com `Arial`, `#f0f0f0`, `#333`).

CSS permet separar el contingut (HTML) de la presentació (estils), facilitant la creació d'una aparença coherent i atractiva per a les pàgines web.