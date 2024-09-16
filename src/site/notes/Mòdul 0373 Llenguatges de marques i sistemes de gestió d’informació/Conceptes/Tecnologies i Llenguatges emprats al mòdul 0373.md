---
{"dg-publish":true,"permalink":"/modul-0373-llenguatges-de-marques-i-sistemes-de-gestio-d-informacio/conceptes/tecnologies-i-llenguatges-emprats-al-modul-0373/"}
---



![Pasted image 20240831133123.png](/img/user/M%C3%B2dul%200373%20Llenguatges%20de%20marques%20i%20sistemes%20de%20gesti%C3%B3%20d%E2%80%99informaci%C3%B3/adjuntos/Pasted%20image%2020240831133123.png)

# Desenvolupament d'una Aplicació Web: Procés Integrat


Desenvolupar una aplicació web implica una sèrie de processos que combinen diverses tecnologies i llenguatges per aconseguir una solució funcional i eficient. A continuació, es descriu el procés de desenvolupament d'una aplicació web, integrant els diferents llenguatges i tecnologies utilitzades en cada fase.





## 1 . Estructura del Contingut ([[Frontend\|Frontend]])


Una vegada que s'ha establert el disseny, es procedeix a construir la interfície d'usuari utilitzant els següents tecnologies:

- **[[Mòdul 0373 Llenguatges de marques i sistemes de gestió d’informació/Conceptes/HTML\|HTML]] (HyperText Markup Language)**: Utilitzat per definir l'estructura bàsica de les pàgines web. HTML crea els elements com capçaleres, paràgrafs, llistes i enllaços, formant l'esquelet de la pàgina.
    
- **[[XHTML\|XHTML]] (Extensible HyperText Markup Language)**: És una variant de HTML que segueix les regles de XML, oferint una sintaxi més estricta per garantir una millor coherència en la creació de documents web.
    
- **[[Mòdul 0373 Llenguatges de marques i sistemes de gestió d’informació/Conceptes/CSS\|CSS]] (Cascading Style Sheets)**: Utilitzat per aplicar estils als documents HTML. CSS controla l'aspecte visual de la pàgina, incloent colors, fonts, marges, i disposició. Permet crear un disseny atractiu i coherent amb el prototip establert.
    
- **[[Cicle formatiu DAW (Organtzació)/MODULS/M06 JSCliente/Conceptos/JavaScript\|JavaScript]]**: Afegeix interactivitat i dinàmica a les pàgines web. Permet la manipulació del DOM (Document Object Model), la gestió d'esdeveniments, i la realització de comunicacions asincròniques amb el servidor mitjançant AJAX. Això permet actualitzar parts de la pàgina sense necessitat de recarregar-la.

## 2. Gestió de Dades i [[Backend\|Backend]]

Després de crear la interfície d'usuari d'una aplicació web, el següent pas crucial és gestionar les dades que l'aplicació utilitzarà. Aquesta fase implica treballar amb formats de dades, tipus de bases de dades, i llenguatges de consulta. A continuació, es detalla com es gestiona aquesta part essencial del desenvolupament web.

### 2.1 Formats de Dades

Els formats de dades són utilitzats per emmagatzemar, transmetre i manipular la informació dins de l'aplicació web. Dos formats comuns són JSON i XML:

- **[[JSON\|JSON]] (JavaScript Object Notation)**: És un format lleuger i fàcil de llegir per humans que s'utilitza principalment per intercanviar dades entre el client i el servidor. JSON és popular en aplicacions web modernes per la seva simplicitat i la seva integració senzilla amb JavaScript.
    
- **[[Mòdul 0373 Llenguatges de marques i sistemes de gestió d’informació/Conceptes/XML\|XML]] (Extensible Markup Language)**: És un format més flexible i extensible per emmagatzemar dades estructurades. XML utilitza etiquetes per organitzar dades i és utilitzat en configuracions i serveis web. Els documents XML poden ser validads i estructurats utilitzant **[[XSD\|XSD]] (XML Schema Definition)** o **[[DTD\|DTD]] (Document Type Definition)**.

	Existeixen diversos vocabularis XML que són àmpliament utilitzats al web per gestionar i representar dades en formats específics. Aquests vocabularis permeten estructurar i presentar informació de manera estandarditzada i interoperable. A continuació es presenten **alguns dels més comuns**:

	- **[[RSS\|RSS]] (Really Simple Syndication)**: Un format XML utilitzat per distribuir contingut actualitzat com notícies i articles. RSS permet als usuaris rebre les actualitzacions de contingut des de llocs web sense haver de visitar el lloc web directament, utilitzant lectors de RSS que recullen i mostren les novetats.
	    
	- **[[SVG\|SVG]] (Scalable Vector Graphics)**: Un format XML per a la creació de gràfics vectorials que es poden escalar a qualsevol mida sense perdre qualitat. SVG és utilitzat per representar imatges, gràfics i gràfics d'ús web, permetent la creació d'icones, gràfics animats i altres elements visuals interactius.
	    
	- **[[XHTML\|XHTML]] (Extensible HyperText Markup Language)**: Un vocabulari XML que combina HTML amb XML per proporcionar una estructura més estricta i ben definida per a pàgines web. XHTML és utilitzat per garantir que les pàgines web compleixin amb les regles de sintaxi XML, millorant la compatibilitat amb diferents agents d'usuari.
	    
	- **[[DOCX\|DOCX]] (Microsoft Word Open XML Document)**: Un format de document XML utilitzat per emmagatzemar documents creats amb Microsoft Word. DOCX és una part de l'estàndard Open XML de Microsoft i és utilitzat per la creació, edició i intercanvi de documents de text amb formats i estils avançats.
		    
	- **[[SOAP\|SOAP]] (Simple Object Access Protocol)**: Un protocol de comunicació basat en XML utilitzat per a l'intercanvi de missatges entre aplicacions web. SOAP és utilitzat per implementar serveis web que poden comunicar-se de manera segura i fiable a través de la xarxa.
	       
	- **[[XSLT\|XSLT]] (Extensible Stylesheet Language Transformations)**: És un llenguatge que transforma documents XML en altres formats com HTML. Això és útil quan es vol presentar dades XML en una forma visual com una pàgina web.
    
    
### 2.2 Bases de Dades

Les bases de dades són sistemes dissenyats per emmagatzemar i gestionar grans quantitats de dades de manera eficient. Es poden classificar en dues grans categories: bases de dades relacionals i no relacionals. Cada tipus de base de dades utilitza formats de dades i llenguatges de consulta específics que influeixen en com es manipulen i es consulten les dades.

#### - Bases de Dades Relacionals

Les [[bases de dades relacionals\|bases de dades relacionals]] emmagatzemen dades en taules amb una estructura definida. Utilitzen llenguatges de consulta estructurats com SQL per gestionar i manipular les dades. Alguns exemples son:

- **[[MySQL\|MySQL]]**: Una base de dades relacional que utilitza **[[SQL\|SQL]] (Structured Query Language)** per gestionar dades. SQL permet executar consultes per afegir, modificar, eliminar o obtenir dades dins de les taules. MySQL és coneguda per la seva eficàcia en la gestió de dades estructurades i la seva integració amb aplicacions web.
    
- **[[PostgreSQL\|PostgreSQL]]**: Una base de dades relacional avançada que ofereix suport per a tipus de dades complexos i funcions avançades. Utilitza SQL com a llenguatge de consulta però inclou extensions i capacitats addicionals per treballar amb dades més complexes i diversos formats. PostgreSQL és valorada per la seva robustesa i flexibilitat.
    

#### - Bases de Dades No Relacionals

Les [[bases de dades no relacionals\|bases de dades no relacionals]], també conegudes com a NoSQL, utilitzen models de dades flexibles i no estructurats. Són adequades per a dades que no s'ajusten bé a una estructura de taules rígides.

- **[[MongoDB\|MongoDB]]**: Una base de dades NoSQL que utilitza **BSON (Binary JSON)**, una extensió binària de JSON, per emmagatzemar dades. MongoDB és ideal per a dades no estructurades i flexibles, com documents i dades de gran volum. Ofereix un llenguatge de consulta propi que facilita la gestió i recuperació de dades.
    
- **[[BaseX\|BaseX]]**: Una base de dades nativa XML que permet emmagatzemar i consultar documents XML de manera eficient. Utilitza **XQuery** per consultar i manipular dades XML, la qual cosa la fa adequada per a aplicacions que treballen amb dades XML o necessiten manipulació avançada de documents XML.
    

### 2.3 Llenguatges de Consulta

Els llenguatges de consulta són utilitzats per extreure i manipular dades emmagatzemades en les bases de dades. Cada tipus de base de dades pot utilitzar un llenguatge de consulta específic:

- **[[SQL\|SQL]] (Structured Query Language)**: Utilitzat per bases de dades relacionals com MySQL i PostgreSQL. Permet executar consultes per seleccionar, insertar, actualitzar i eliminar dades en taules estructurades. SQL és essencial per gestionar dades dins d'estructures relacionals de manera eficient.
    
- **[[XQuery\|XQuery]]**: Utilitzat per **BaseX** per consultar i manipular dades emmagatzemades en format XML. Ofereix funcions per extreure informació de documents XML i transformar-los en formats utilitzables. XQuery és adequat per treballar amb dades XML complexos i estructurats.
    
- **[[XPath\|XPath]]**: Utilitzat juntament amb **XQuery** per navegar i seleccionar dades dins de documents XML. XPath proporciona una sintaxi per a l'accés a elements i atributs dins de l'arbre XML, permetent una manipulació precisa de la informació emmagatzemada.

### 3. Validació i Control de Qualitat

Abans de desplegar l'aplicació, és fonamental assegurar-se que el codi compleixi els estàndards establerts i funcioni correctament. Aquest procés inclou:

-[[ **W3C Validator**\| **W3C Validator**]]: Aquesta eina valida documents HTML, XHTML i CSS per garantir que compleixin amb els estàndards del W3C. L'ús del W3C Validator ajuda a assegurar la compatibilitat del codi amb diferents navegadors i dispositius, millorant la qualitat i la consistència de l'aplicació web.

### 4. Desenvolupament i Gestió del Codi

El desenvolupament col·laboratiu i la gestió de versions són crucials en projectes amb múltiples desenvolupadors. Aquest aspecte inclou:

- **[[Git\|Git]]**: És un sistema de control de versions distribuït que permet seguir els canvis en el codi, gestionar branques de desenvolupament i integrar les modificacions realitzades per diferents membres de l'equip. Git facilita el treball en equip i el manteniment del codi al llarg del temps.
    
- **[[GitHub\|GitHub]]**: És una plataforma basada en Git que ofereix emmagatzematge en el núvol per repositoris de codi. GitHub proporciona eines per a la col·laboració com els pull requests i issues, facilitant la revisió del codi, la gestió de versions i la coordinació entre els desenvolupadors.
    

### 5. Eines de Desenvolupament

Els editors de codi i IDEs (Integrated Development Environments) ofereixen entorns dedicats per a la creació i edició de codi. Aquestes eines inclouen:

- **[[Visual Studio Code\|Visual Studio Code]]**: Editor de codi popular amb suport per a HTML, CSS, JavaScript, i moltes extensions que permeten personalitzar l'entorn de treball segons les necessitats del desenvolupador.
- **[[GitHub Codespaces\|GitHub Codespaces]]**: Entorn online que permet fer servir Visual Studio Code en linea.
- **Altres IDEs**: Sublime Text, Atom, WebStorm, Brackets
    

