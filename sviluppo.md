## whoami

Free software developer
- Maintainer: django-admin-bootstrapped, bootchart2
- contributore: uwsgi, LibreOffice


## Oggi parliamo di Free Software

Libertà di:
- eseguire
- studiare e modificare
- ridistribuire l'originale
- ridistribuire le mie modifiche


## Mani avanti

Free Software != Supporto gratuito

Nessuna garanzia :)


# Come sono sviluppati i progetti?


## Linux

- gerarchia: dev -> maintainers -> Linus
- review: mailing list
- bugs: mailing list, bugzilla
- sviluppo: master + feature freeze
- rilasci: ogni 2 mesi
- installazioni: miliardi
- sviluppatore tipo: pagato


## LibreOffice

- gerarchia: orizzontale
- review: gerrit
- bugs: bugzilla
- sviluppo: master -> freeze -> branch
- rilasci: 6 mesi
- installazioni: milioni
- sviluppatore tipo: pagato


## django-admin-bootstrapped

- gerarchia: nessuna
- review: github
- bugs: github
- sviluppo: master
- rilasci: quando serve
- installazioni: migliaia
- sviluppatore tipo: volontario


## Doocracy

Chi fa decide (di solito)

Come si dirimono le questioni? Buonsenso?


## Questioni non tecniche

"Noi siamo a guardia della legge che vogliamo immutabile, scolpita nel tempo." (cit.)

- OpenOffice.org vs LibreOffice
- node.js vs io.js


## node.js vs io.js in numeri

(img/commit-nodejs.png)

(img/commit-iojs.png)


# Come si collabora in pratica?


## Strumenti: mailing list

Discussione su $qualcosa riguardante il $topic

Aiutati a farti aiutare:
- più contesto possibile
- netiquette


## Strumenti: bug tracker

PREREQUISITI:
- ho idea di cosa sto facendo
- **NON** è lo strumento per il supporto

USARE SE:
- ho trovato un bug
- c'è qualcosa che potrebbe essere fatto meglio


## Strumenti: irc

supporto, discussioni, socialità :)


## Strumenti: stack overflow

- **NON** ho idea di cosa sto facendo
- cerco una consulenza gratuita


## A chi appartiene il futuro?

(img/thefuture.jpg)

Stephanie Vacher CC BY-NC-ND 2.0


## Contribuire

Barriere di ingresso: Linux vs LibreOffice

Non solo codice: bug triaging, documentazione

FYI Roma non è stata fatta in un giorno


## Bug reporting

- Cosa ho fatto
- Cosa è successo
- Cosa mi sarei aspettato
- Step per riprodurre


## Feature requests

Senza patch o analisi approfondita

(img/umarell.jpg)

Stefano Petroni CC BY-NC-ND 2.0


# Contribuire codice


## Accettare i fallimenti

(img/nope.jpg)

Scott Beale CC BY-NC-ND 2.0


## Persistere

(img/overlay-pullreq.png)


## Commit

- Un commit per cambiamento "logico"
- Non mischiare bugfix e cleanup
- performance? numeri!
- reference a discussioni e bug


## Commit do: Linux

(img/commit-do-1.png)


## Commit do: bootchart2

(img/commit-do-2.png)


## Commit don't

(img/commit-dont-1.png)


## Commit don't

(img/commit-dont-2.png)


## Pull request

1 pull request ~= 1 feature

- Usate, scrivete, aggiornate i test
- Usate eventuali tool di linting (se richiesti dal progetto)


## Pull request do: django

(img/django-pullreq-do.png)


## Pull request don't: bootchart2

(img/bootchart2-pullreq-dont.png)


## Code review

Non siamo il nostro codice, accettiamo le critiche!


## Git to the rescue

~~~
# sistemare ultimo commit
git commit --amend

# lavorare sempre su un branch!
# pick, edit, squash, shuffle
git rebase --interactive $branch

# riscrivo la history
git push -f

# butto via tutto quello fatto dopo $sha1
git reset --hard $sha1
~~~


## FLOSS al lavoro

Upstream first! (o almeno provateci)

"It's the duty of all Free Software developers to steal as much time as they can from their employers for software freedom."

Jeremy Allison


## Happy Hacking :)

Riccardo Magliocchetti

riccardo@menodizero.it

@rmistaken


http://menodizero.it

https://github.com/xrmx
