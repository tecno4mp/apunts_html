# Configuració de l'entorn

1. Descarregar Visual Studio Code: Seguir les instruccions per cada plataforma.
2. Instal·lar l'extensió `Live Preview` de *Microsoft*: **Vigileu que estigui firmada per Microsoft**



# Creació d'una pàgina web a partir d'HTML bàsic

- Obrir i crear una nova carpeta: File -> Open folder: Crear una nova carpeta, que podem anomenar `web01`
- Botó secundari sobre l'explorador i seleccionar opció de crear un nou fitxer, anomenar-lo `berenguer.html`. És important l'extensió (`.html`).
- Editar aquest fitxer: Escriure `!` i apretar `Enter`.

Si fins aquí s'han seguit els passos correctes apareix el següent codi, escrit de forma automàtica:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## Fonaments bàsics sobre HTML

HTML no és un llenguatge de programació, si no que simplement defineix l'estrucutra i el contingut d'una pàgina web. Per això s'utilitzen etiquetes que organitzen el contingut.

Una estructura bàsica d'una etiqueta és com segueix:

```html
<etiqueta atribut="valor">Contingut</etiqueta>
```
Aquesta estructura pot variar, però en general, fixem-nos que `<nom_etiqueta>` defineix l'**obertura** de l'etiqueta i pot contenir atributs de forma opcional. `</nom_etiqueta>` és el **tancament** de l'etiqueta. Entre la obertura i el tancament hi ha contingut. El contingut pot ser text, així com altres etiquetes. Quan el contingut són altres etiquetes es defineix una **jerarquía**.

Sobre l'estructura inicial que se'ns ha creat, anem a comentar-la:


```html
<!--Aquesta primera línia indica al navegador que això és un document HTML-->
<!DOCTYPE html> 

<!--Aquesta segona és una etiqueta, és única per tot el document i conté la resta del document HTML.
Té habitualment un atribut, lang, que indica l'idioma del document web. En aquest cas anglès.-->
<html lang="en"> 

<!--Aquesta etiqueta <head> conté altres etiquetes dins que donen informació més per al navegador que 
no per l'usuari-->
<head> 
    <!--Una etiqueta que indica el conjunt de caràcters que s'utilitzen-->
    <meta charset="UTF-8"> 
    
    <!--Indica al navegador com visualitzar la web-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    
    <!--El títol de la web-->
    <title>Document</title>
</head>

<!--Dins aquesta etiqueta, hi posarem el contingut, el cos del document: Text, imatges...-->
<body>
    
</body><!--Indica al navegador com visualitzar la web-->

<!--Fixa't que estem tancant la etiqueta <html>-->
</html>
```

## Posem contingut a la web

Per veure com queda el contingut pots obrir una previsualització amb, de les opcions que tens a dalt a la dreta del document, la del mig, que té una lupa.

![alt text](image.png)

Ara, al document web, posa algo així (procura crear contingut propi):

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
        <h1>El meu nom és Berenguer</h1>
    <p>Sóc un <strong>gat</strong> de color taronja, però no m'hauries de confondre amb Garfield. Potser som parents, però
        jo tinc els meus propis dibuixos animats i cómics. Algunes coses que hauries de saber són:
    </p>
    <ul>
        <li>M'argada dormir</li>
        <li>M'agrada menjar</li>
        <li>M'agrada el peix</li>
        <li>Freqüento els cubells d'escombraries</li>
    </ul>
    <img src="https://www.enfocamp.es/newsletter/img/boletin/gato-isidoro.jpg" alt="">

    <p>En el seu dia, vaig arribar a ser cèlebre.
        <a href="https://en.wikipedia.org/wiki/Heathcliff:_The_Movie">Fins i tot em van fer una pel·lícula.</a></p>
</body>
</html>
```

També pots, des del sistema d'arxius, fer doble click al fitxer i esperar que s'obri amb el navegador per defecte del teu ordinador.
