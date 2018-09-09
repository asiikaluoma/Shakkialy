# Shakkialy

Ohjelma toteuttaa yksinkertaisen shakki tekoälyn. Tekoälyä vastaan voi pelata yksinkertaisen käyttöliittymän avulla, joka on toteutettu komentorivillä. 

## Minimax
Toteutukseen käytetään minimax-algoritmia, jossa algoritmi hakee rekursiivisesti siirtoja luokitellen niiden arvon käyttäen nappuloiden arvoja (esim. hevonen = 3, sotilas = 1, … .) Sen toteutukseen tarvitsemma hakupuun tietorakenteeksi.  Maksimoimme ja minimoimme vuorotellen siirtojen tuottaman arvon riippuen onko valkoisen vai mustan vuoro.

[a link](https://en.wikipedia.org/wiki/Minimax)

## Alpha-beta pruning
Prosessin avulla voimme minimoida haarojen lukumäärän. Jätämme käymättä kohdat, joissa löydämme siirron, joka tuottaa pienemmän arvon kuin jokin aiemmin löytämämme siirto. 

[a link](https://en.wikipedia.org/wiki/Alpha–beta_pruning)
