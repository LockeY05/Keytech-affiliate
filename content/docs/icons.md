+++
title = "Icons"
date = "2026-05-29T08:43:40Z"
draft = true

author = "KeyTech"

description = ""
summary = ""

tags = []
categories = ["docs"]

# Opzionale:
series = []

ShowToc = true
TocOpen = false

ShowBreadCrumbs = true
ShowReadingTime = true
ShowWordCount = true
ShowShareButtons = true

cover = ""
coverAlt = ""
coverCaption = ""

keywords = []

canonicalURL = ""

comments = false

[schema]
type = "NewsArticle"

+++

## Come utilizzare le icone

Verranno aggiunte icone man mano alle necessita.
Faró un elenco per vedere le icone disponibili.

Le icone possono essere aggiunte a file markdown e info-box
Per aggiungere una icona occorre sempre sapere il nome. **Il nome della svg viene rappresentato dalla sua cartella.

Possiamo inoltre modificarne il **colore**
Ecco un esempio:

{{< icon name="pros" color="#c93434" size="18" >}}

Questo é il codice da utilizzare:

```md
{{< icon name="minus-circle" color="#c93434" size="18" >}}
```

Questo se si volesse modificare il colore delle **icone**
Se si volesse mantenere lo stile di colori del sito utilizzare invece questo comando:

```markdown
{{< icon name="minus-circle" color="currentColor" >}}

```
Il risultato sará questo:

{{< icon name="minus-circle" color="currentColor" >}}