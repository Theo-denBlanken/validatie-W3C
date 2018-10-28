# Validatie-code

In te voegen voor validatie van HTML en CSS bij het W3C.
Het is gebruikelijk deze in de footer van je webpagina in te voegen.

Voor het geval de afbeeldingen er niet meer zijn, zijn kopietjes in de map afbeeldingen.
De CSS verkleint de afbeeldingen enigszins en is eigenlijk niet nodig.

Je kunt een en ander overnemen en naar eigen inzicht in jouw trainingsdocumenten in voegen.

### HTML

```
<div id="validatie">
    <a href="http://validator.w3.org/check?uri=referer" target="_blank">
        <img src="https://blanken5.home.xs4all.nl/afb/valid-html5-blue.png" alt="Valide HTML5"></a>
    <a href="http://jigsaw.w3.org/css-validator/check/referer" target="_blank">
        <img src="http://jigsaw.w3.org/css-validator/images/vcss-blue.gif" alt="Valide CSS">
    </a>
</div>
```

### CSS

```
#validatie img {
    height: 1em;
    width: auto;
    border: 0;
    margin: 0 .3em;
}
```

![icoon Theo](https://lh4.googleusercontent.com/-8OFSrEMe-K8/AAAAAAAAAAI/AAAAAAAAAAA/JQWwoy-hKc0/s128-c-k/photo.jpg)
[Theo den Blanken](http://blanken5.home.xs4all.nl/ "Site van Theo") 
