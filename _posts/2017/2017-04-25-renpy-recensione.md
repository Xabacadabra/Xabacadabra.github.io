---
layout: article
title: "Ren'Py: Visual Novel Engine gratis per tutti"
modified: null
categories: [2017]
excerpt: "Creare videogiochi di tutto rispetto grazie allo splendido engine di PyTom Rothamel"
tags:
  - videogiochi
  - cyberspazio
image: 
  feature: renpy.jpg
  teaser: teaser-renpy.jpg
  thumb: null
published: true
comments: true
---

Vi risparmierò spiegoni della serie "Che cos'è una _Visual Novel_ ?" : 

viviamo nell'era del  [_wikipediamento perfetto_](https://it.wikipedia.org/wiki/Visual_novel), e del resto se siete piombati da queste parti con ogni probabilità un'idea dovreste averla già.

## Ren'Py

[**- Link al sito ufficiale - **](https://renpy.org/)

Lo conosco da sette anni all'incirca, e confesso che averci cavato fuori solo qualche magro esperimento è una di quelle faccende che mi molce il cuore:

**Ren'Py è infatti un engine potente, gratuito, facile da utilizzare e dalle enormi possibilità di _Racconto_, prima ancora che di gioco.**

Come se non bastasse, è **multipiattaforma** (Linux, Windows, OSX) e da qualche tempo garantisce pure **l'esportazione su sistemi Android**.

## Il Pitone non è un serpente 

Concepito e realizzato tramite il popolare linguaggio di programmazione **Python**, Ren'py focalizza il proprio _workflow_ sull'immediatezza e la semplicità di compilazione:

**Più che codice, quello che il programmatore si ritrova a scrivere è una vera e propria sceneggiatura**, strutturata esattamente come il più classico dei canovacci teatrali: 

```python
image bg villa = "arcore.jpg"

image silvio smile = "silvio-smile.png"

define b = Character('Berlusconi', color="#ffea00")

label start:
    scene bg villa
    show silvio smile

    "L'Italia è il paese che amo..."

```

<figure>
<img src='/images/renpysconi.jpg' alt='Renpysconi'>
</figure>

Insomma: personaggi che entrano ed escono, _fade_ delle luci sapientemente inseriti tra un cambio di scena e l'altro e via dicendo.

## Limite

Prego notare: ho usato il singolare e non ho scritto _difetto_.

Senza girarci troppo attorno, **l'unico vero e proprio punto debole di Ren'Py deriva dal suo punto di forza:**

Fa Visual Novel.

E sì, le fa dannatamente bene...

ma **quello delle Visual Novel  è un genere parecchio controverso**, appagante per la nicchia di _aficionados_ ma poco "giocato" nel vero senso della parola e lontano dai palati delle masse. 

Non a caso, tolte le contaminazioni con altri generi (emblematica la serie JRPG  _Persona_ ) in genere si diffondono anzitutto grazie al genere Hentai / Eroge. 

<figure>
<img src='' alt='welcome to the NHK'>
<figcaption> È UN COMPLOTTO!</figcaption>
</figure>

Quindi, per quanto le potenzialità dell'engine  si prestino a fare davvero un sacco di roba, bisogna sempre tenere a mente che spezzare i binari del genere su cui è basato è possibile, ma non per questo facile.

Un esempio analogo lo potremmo fare con [_Until I Have You_](http://xabacadabra.com/2016/until-i-have-you/), platform a scorrimento laterale sviluppato con _Adventure Game Studio_ (software chiuso e ben più vecchio di Ren'Py)

