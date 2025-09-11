---
title: "Opinie: Scannen aan cliëntzijde kwestbaar voor sabotage-aanvallen"
description: "..."
date: 2023-10-04T08:49:31+00:00
lastmod: 2023-10-04T08:49:31+00:00
draft: false
images: []
contributors: []
categories: []
menu:
  docs:
    parent: 
weight: 630
toc: true
---

In een nieuw opiniestuk schrijft privacy- en computerveiligheidsonderzoeker Jaap-Henk Hoepman (XOT) over hoe een techniek van scannen aan cliëntzijde (waarbij je digitale berichten al op je eigen apparaat worden doorgelicht) kwetsbaar is voor mogelijke sabotage-aanvallen. 

De aanval die Hoepman, naar aanleiding van [een wetenschappelijke presentatie](https://www.usenix.org/conference/usenixsecurity23/presentation/prokos), in gedachten heeft is dat van een gedistribueerde dienstweigeringsaanval (_Distributed Denial of Service attack_, afgekort **DDoS**). Hoepman schrijft:

> "... een aanvaller kan een variatie op een onschuldig bronbeeld maken, waarvan de vingerafdruk [dat wil zeggen, identificatiemiddel] overeenkomt met de vingerafdruk van bekend misbruikmateriaal.

> Dit leidt tot een interessante aanvalsmogelijkheid, waarbij activisten die tegen scannen aan cliëntzijde zijn, een systeem als volgt kunnen DDoS-en. Gebruik makend van de methode die in het artikel wordt beschreven, zouden activisten onschuldige beelden kunnen creëren die desalniettemin [wat betreft vingerafdruk] overeenkomen met [de vingerafdrukken van] bekend misbruikmateriaal. (...) Activisten zouden vervolgens kunnen besluiten om elkaar regelmatig deze afbeeldingen te sturen, waardoor het detectiemechanisme dat is ingevoerd via scannen aan de cliëntzijde geactiveerd raakt. De [onschuldige] afbeelding zou worden gerapporteerd aan het [speciaal opgerichtte centrum van de Europese Unie waar misbruik gemeld zou moeten worden]. [Dit centrum] moet een onderzoeksprocedure uitvoeren om te bepalen of de afbeelding daadwerkelijk bekend misbruikmateriaal betreft. Uiteraard is het dat niet (het is tenslotte een onschuldig beeld dat gecreëerd is om foutief het overeenkomst-algoritme te activeren). Toch moet het centrum moet een deel van diens tijd en middelen besteden om tot deze conclusie te komen. Afhankelijk van het aantal deelnemende activisten en het aantal beelden dat zij uitwisselen, kan dit het centrum overweldigen en dus DDoS-en."

Team chatcontrole vraagt zich af of het in het omschreven scenario wel om een [DDoS aanval](https://nl.wikipedia.org/wiki/Distributed_denial-of-service) in de traditionele zin van dit begrip zou gaan---dat wil zeggen, het technisch onbereikbaar maken van een systeem door dit te overladen met verzoeken? Maar dat is alleen een vraag over woordkeuze. Duidelijk is in ieder geval dat op deze manier een chatcontrole-meldsysteem overweldigd, en daarmee onbruikbaar gemaakt, zou kunnen worden. 

Opnieuw maakt dit maar weer eens duidelijk dat het chatcontrole-voorstel ook op technisch vlak kwetsbaar en in hoge mate ondoordacht is.

Lees het stuk:
- 🇳🇱 [Het DDoS-en van scannen aan cliëntzijde](https://blog-xot-nl.translate.goog/2023/10/04/ddos-ing-client-side-scanning/index.html?_x_tr_sl=en&_x_tr_tl=nl) (automatische vertaling naar het Nederlands, kan fouten bevatten)
- 🇬🇧 [DDoS-ing client-side scanning](https://blog.xot.nl/2023/10/04/ddos-ing-client-side-scanning/index.html) (Engelse origineel)