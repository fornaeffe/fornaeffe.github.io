---
layout: post
title: 'Il voto utile'
date: 2024-05-08
draft: false
tags: 
- I Care - A me importa
- Verso le elezioni
---

<div class="figura" style="text-align: center">
    <img src="/assets/use_your_vote.jpg" alt= "Usa il tuo voto" style="width: 480px;" />
</div>

Si avvicinano le [elezioni europee](https://elections.europa.eu/it/), e i sondaggi danno [Alleanza Verdi e Sinistra](https://verdisinistra.it/) molto vicina al 4%, ma il superamento della soglia non è certo.

Mi sono quindi chiesto: il voto ad Alleanza Verdi e Sinistra è un **voto utile**? Votando AVS contribuisco davvero ad eleggere candidati che rappresentino le mie idee, oppure il mio voto verrà sprecato, aumentando la possibilità che vengano elette persone che non mi rappresentano?

Ho fatto [due conti](https://fornaeffe.github.io/valore_voto), e la risposta è **sì, il voto ad Alleanza Verdi e Sinistra è un voto utile**, almeno per me.

Come faccio a dirlo?

Ho fatto una simulazione: partendo dai sondaggi, ho simulato un milione di possibili risultati elettorali. In ciascuno dei possibili risultati elettorali ho aggiunto un voto[^1] ad Alleanza Verdi e Sinistra, e ho verificato se quel voto in più aggiungeva o toglieva seggi a qualche lista: ovviamente nella maggior parte dei casi non cambia nulla, ma ci sarà quel caso particolare nel quale un voto in più è sufficiente per far scattare il seggio in più per la lista votata (e in meno per un'altra lista).

Facendo la media tra tutti i possibili risultati elettorali scopro così quanti seggi in media aggiunge o toglie, a ciascuna lista, un voto dato ad Alleanza Verdi e Sinistra.

Ho quindi dato un valore a ciascuna lista: a quelle dalle quali mi sento rappresentato ho dato un valore positivo (+2 se mi ci ritrovo molto, +1 se mi ci ritrovo solo in parte), a quelle che sento lontane dalle mie idee ho dato un valore negativo (-2 se sono del tutto opposte, -1 se ci mi ritrovo poco).

Dopodiché ho pesato i seggi in più o in meno in base al valore che ho dato io a ciascuna lista, scoprendo così se il voto ad AVS rende complessivamente il Parlamento Europeo più o meno rappresentativo delle mie idee.[^2]

Ho ripetuto questo procedimento per il voto a ciascuna lista, scoprendo così di quanto aumentava (o diminuiva) il punteggio che indica quanto gli eletti mi rappresentano a seconda della lista votata.

Ho scoperto che il voto ad **Alleanza Verdi e Sinistra** è, di gran lunga, **il voto che più probabilmente riesce ad aumentare il numero di persone che mi rappresentano** nel Parlamento Europeo.

E questo è vero nonostante la lista non riesca con certezza a superare la soglia: è più probabile riuscire a mandare in parlamento tre o quattro candidati di AVS cercando di superare la soglia, piuttosto che alzare così tanto i voti del PD da far eleggere tre o quattro candidati del PD in più.

Se qualcuno volesse provare a fare lo stesso, ho reso disponibile una [web app](https://fornaeffe.github.io/valore_voto) per calcolare automaticamente qual è il voto più utile dato il valore che ciascuno dà alle liste.


[^1]: in realtà ne ho aggiunti mille, e poi ho diviso per mille il numero di seggi aggiunti o tolti. Pur con un milione di simulazioni, beccare proprio la situazione nella quale basta un voto per eleggere un candidato in più sarebbe troppo difficile!