---
{"dg-publish":true,"permalink":"/modul-0373-llenguatges-de-marques-i-sistemes-de-gestio-d-informacio/projecte/histories/historia-2/historia-2-actualitzacio-de-continguts/"}
---




## Objectiu: 

Actualitza les pàgines HTML que mostrin els articles proporcionats, així com la pàgina principal, utilitzant les etiquetes HTML adequades per estructurar i formatar el contingut de manera semàntica.

### Tasca 1. Actualització dels continguts dels articles

-  Actualitza les tres pàgines HTML individuals (`article1.html`, `article2.html`, `article3.html`), cada una amb el títol i el contingut d'un article específic.
- Utilitzar etiquetes HTML com `<h1>`, `<h2>`, `<p>`, `<strong>`, `<em>`, `<blockquote>`, i llistes `<ul>` o `<ol>` per formatar el contingut adequadament.

	*Exemple de com quedaria la pàgina ``article1.html``*
	![Pasted image 20240826165922.png](/img/user/M%C3%B2dul%200373%20Llenguatges%20de%20marques%20i%20sistemes%20de%20gesti%C3%B3%20d%E2%80%99informaci%C3%B3/Projecte/Hist%C3%B2ries/adjuntos/Pasted%20image%2020240826165922.png)


### Tasca 2. Actualització dels continguts textuals de la pàgina 'Home' (``index.html``)

-  Actualitza la pàgina Home amb els contiguts que trovaràs a l'apartat 'Continguts' d'aquest document. La estructura principal hauria de ser com aquesta:

```html
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Glamour Camping</title>
</head>
<body>
  <header>
   Aquí tindrem la part superior de la web
  </header>
  <main>
    <section id="about"> 

    </section>
    <section id="activity">
  
    </section>
    <section id="action">

    </section>
    <section id="booking">

    </section>
    <section id="news">

    </section>
    <section id="gallery">

    </section>
  </main>

  <footer>
    Subscribe to our newletter
    Pàgina creada per: Carlos Arrebola
  </footer>
</body>
</html>
```

- Utilitza els divs que consideris necessaris per agrupar els continguts. Per exemple:

```html
	<div id="iconos">
	  <div id="autocarava">
		<img src="images/iconoAutocaravana.png" alt="icono autocaravana">
		<p>30 CAMPER SITES</p>
	  </div>
```

*El resultat de la pàgina home amb una part dels continguts de les seccions **about** i **booking** seria semblant al següent:*

![Pasted image 20240826175742.png](/img/user/M%C3%B2dul%200373%20Llenguatges%20de%20marques%20i%20sistemes%20de%20gesti%C3%B3%20d%E2%80%99informaci%C3%B3/Projecte/Hist%C3%B2ries/hist%C3%B2ria%202/adjuntos/Pasted%20image%2020240826175742.png)
![Pasted image 20240826175823.png](/img/user/M%C3%B2dul%200373%20Llenguatges%20de%20marques%20i%20sistemes%20de%20gesti%C3%B3%20d%E2%80%99informaci%C3%B3/Projecte/Hist%C3%B2ries/hist%C3%B2ria%202/adjuntos/Pasted%20image%2020240826175823.png)
![Pasted image 20240826175857.png](/img/user/M%C3%B2dul%200373%20Llenguatges%20de%20marques%20i%20sistemes%20de%20gesti%C3%B3%20d%E2%80%99informaci%C3%B3/Projecte/Hist%C3%B2ries/hist%C3%B2ria%202/adjuntos/Pasted%20image%2020240826175857.png)
![Pasted image 20240826175919.png](/img/user/M%C3%B2dul%200373%20Llenguatges%20de%20marques%20i%20sistemes%20de%20gesti%C3%B3%20d%E2%80%99informaci%C3%B3/Projecte/Hist%C3%B2ries/hist%C3%B2ria%202/adjuntos/Pasted%20image%2020240826175919.png)
