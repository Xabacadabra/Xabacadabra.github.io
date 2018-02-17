---
title: "Ren'Py: Visual Novel Engine gratis per tutti"
last_modified_at: null
categories: [2017]
excerpt: "Creare videogiochi di tutto rispetto grazie allo splendido engine di PyTom Rothamel"
tags:
  - videogiochi
  - cyberspazio
header:  
  image:  images/renpy.jpg
  teaser: images/teaser-renpy.jpg
published: true
comments: true
toc: true
---

Vi risparmierò spiegoni della serie "Che cos'è una _Visual Novel_ ?" : 

viviamo nell'era del  [_wikipediamento perfetto_](https://it.wikipedia.org/wiki/Visual_novel), e del resto se siete piombati da queste parti con ogni probabilità un'idea dovreste averla già.

## Ren'Py

[- **Link al sito ufficiale** - ](https://renpy.org/)

Lo conosco da sette anni all'incirca e devo confessare che l'averci cavato fuori giusto magri esperimenti mi molce sempre il cuore:

**Ren'Py è infatti un engine potente, gratuito ed opensource, facile da utilizzare e dalle enormi possibilità di _Racconto_, prima ancora che di gioco.**

Come se non bastasse, è **multipiattaforma** (Linux, Windows, OSX) e da qualche tempo garantisce pure **l'esportazione su sistemi Android**.

## Il Pitone non è un serpente 

Concepito e realizzato tramite il popolare linguaggio di programmazione **Python**, Ren'py focalizza il proprio _workflow_ sull'immediatezza e la semplicità di compilazione:

**Più che codice, quello che il programmatore si ritrova a scrivere è una vera e propria sceneggiatura**, strutturata esattamente come il più classico dei canovacci teatrali: 

## Esempio Pratico

```python
# prima di tutto vengono definiti i personaggi e le immagini impiegate dal gioco
image bg villa = "arcore.jpg"

image silvio smile = "silvio-smile.png"

define b = Character('Berlusconi', color="#ffea00")

# con il label start (volendo interpretabile come il cinematografico "motore, azione!") inizia la visual novel vera e propria

label start:
    scene bg villa
    show silvio smile

    b "L'Italia è il paese che amo..."

```

<figure>
<img src='/images/renpysconi.jpg' alt='Renpysconi'>
</figure>

Insomma: personaggi che entrano ed escono, _fade_ delle luci sapientemente inseriti tra un cambio di scena e l'altro e via dicendo.

## Limite

Prego notare: **ho usato il singolare e non ho scritto _difetto_.**

Senza girarci troppo attorno, **l'unico vero e proprio punto debole di Ren'Py deriva dal suo punto di forza:**

Fa _Visual Novel._

E sì, le fa dannatamente bene...

ma **quello delle Visual Novel  è un genere parecchio controverso**, appagante per la nicchia di _aficionados_ ma poco "giocato" nel vero senso della parola ed **abbastanza lontano dai palati delle masse.**

Non a caso, tolte le contaminazioni con altri generi (emblematica in questo senso la serie JRPG  _Persona_ ) si diffondono anzitutto grazie al genere _Hentai / Eroge_. 

<div style="position:relative;height:0;padding-bottom:56.25%"><iframe src="https://www.youtube.com/embed/LsgwD4ehYI4?ecver=2" width="640" height="360" frameborder="0" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>

<small> È UN COMPLOTTO!</small>

Quindi, per quanto le potenzialità dell'engine  si prestino a fare davvero un sacco di roba, bisogna sempre tenere a mente che spezzare i binari del genere su cui è basato è possibile, ma non per questo facile.

Un esempio analogo lo potremmo fare con [_Until I Have You_](/2016/until-i-have-you/), platform a scorrimento laterale sviluppato con _Adventure Game Studio_ (software chiuso e ben più vecchio di Ren'Py)

## Conclusioni

Detto ciò, **lo consiglio caldamente ad ogni aspirante creatore di videogiochi**, fermo restando che nulla può davvero sostituire l'apprendimento di un linguaggio di programmazione: 

Tuttavia, anche in questo senso, **Ren'Py potrebbe risultare un grandioso apripista.**

<div class="hreview" style="display: none;">
<span class="item"> <span style="font-size: xx-small;"><span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><span class="fn">Ren'Py</span><br /> </span></span></span><span style="font-size: xx-small;"><span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"> Recensito da: <span class="reviewer">Andrea Corinti</span> Data: <span class="dtreviewed">Apr 25 2017<br /> </span> Voto: <span class="rating">5</span></span></span></div>
