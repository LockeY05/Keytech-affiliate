+++
title       = "{{ replace .Name "-" " " | title }}"
date        = "{{ .Date }}"
lastmod     = "{{ .Date }}"
publishDate = "{{ .Date }}"
# expiryDate = ""  # Decommenta per far scadere il contenuto

draft = true

# linkTitle: versione breve del titolo per menu/liste
linkTitle = ""

# weight: 0 = ordine cronologico | >0 = pinna il post in cima alla lista
#weight = 0

# aliases: redirect da vecchi URL verso questo — fondamentale in caso di migrazione
aliases = []

============================================================
# AUTORE E TASSONOMIA
============================================================
author     = "KeyTech"
tags       = []
categories = []
series     = []

============================================================
# SEO — META TAGS (generati da Hugo nel <head>)
===========================================================

# <meta name="description"> — 150-160 caratteri, include keyword primaria
description = ""

# <meta name="keywords"> — peso basso per Google, utile per Bing e motori minori
keywords = []

# summary: usato nelle liste e come og:description se description è vuota
# In Papermod è anche il testo che appare nelle card delle liste
summary = ""

# slug: sovrascrive la parte finale dell'URL — ottimizza per keyword
# Lascia vuoto per usare il filename come slug
slug = ""

# canonicalURL: <link rel="canonical"> — critica contro duplicate content
# Lascia vuoto: Hugo la genera automaticamente con il permalink
canonicalURL = ""

# Mostra il testo "Pubblicato originariamente su [hostname]" nel post
ShowCanonicalLink  = false
CanonicalLinkText  = ""

# robotsNoIndex = true → aggiunge <meta name="robots" content="noindex">
# Usare per pagine thin, tag pages, contenuti duplicati
robotsNoIndex = false

============================================================
# OPEN GRAPH + TWITTER CARDS
# Papermod genera questi automaticamente dalla cover.
# "images" è il FALLBACK se cover.image è vuota.
# Ordine priorità: cover.image → images[] → Page Bundle (feature/cover/thumbnail)
============================================================

images = []

# Per pagine (non post): supporta anche audio e video per og:audio / og:video
# audio  = []
# videos = []


============================================================
# COVER IMAGE
============================================================

[cover]
  # Path relativo a /static/ OPPURE URL assoluto
    # Es: image = "/images/news/titolo-post.webp"
      # Es: image = "https://example.com/img.jpg"
        image    = ""
          alt      = ""      # Testo alt — SEO immagini + accessibilità
            caption  = ""      # Didascalia (supporta Markdown)

              # relative = true → obbligatorio se usi Page Bundle (index.md nella stessa cartella)
                relative = false

                  # responsiveImages = true → Hugo genera srcset automatico (ottimizza LCP / Core Web Vitals)
                    responsiveImages = true

                      # hidden = true → nasconde la cover visivamente MA la mantiene in og:image / twitter:image
                        hidden = false

============================================================
# PAPERMOD — UI E COMPORTAMENTO
============================================================

                        ShowToc            = true
                        TocOpen            = false
                        ShowBreadCrumbs    = true
                        ShowReadingTime    = true
                        ShowWordCount      = true
                        ShowPostNavLinks   = true
                        ShowCodeCopyButtons = true

                        # ShareButtons: lista esplicita dei bottoni abilitati
                        # Valori supportati: "linkedin", "x", "whatsapp", "telegram", "pinterest", "reddit"
                        # Oppure usa ShowShareButtons = true per abilitarli tutti (da config globale)
                        disableShare = false

                        # searchHidden = true → esclude questo post dalla ricerca interna Fuse.js
                        searchHidden = false

                        # hideSummary = true → nasconde il summary nelle pagine lista
                        hideSummary = false

                        # hidemeta = true → nasconde data, reading time, author, traduzioni
                        hidemeta = false

                        # disableAnchoredHeadings = true → rimuove i link # dai titoli H2/H3
                        disableAnchoredHeadings = false

                        comments = false

                        +++


