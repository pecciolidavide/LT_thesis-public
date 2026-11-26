# Flusso di campi vettoriali su varietà e parentesi di Lie: un approccio non standard

Tesi di Laurea Triennale in Matematica — Università degli Studi di Torino, Dipartimento di Matematica "Giuseppe Peano".

- **Candidato:** Davide Peccioli
- **Relatore:** Prof. Luca Motto Ros
- **Anno accademico:** 2023-24 (discussione: 11 novembre 2024)

## Documenti

| Documento | PDF | Sorgenti |
|---|---|---|
| Tesi | [`tesi.pdf`](tesi.pdf) | [`tesi/`](tesi) |
| Presentazione | [`presentazione.pdf`](presentazione.pdf) | [`presentazione/`](presentazione) |

## Contenuto

La tesi dimostra, con gli strumenti dell'analisi non standard, il classico risultato di geometria differenziale secondo cui i flussi di due campi vettoriali di classe $C^2$ su una varietà differenziabile commutano se e solo se la loro parentesi di Lie è identicamente nulla.

1. **Introduzione** — cenni storici e idea del campo degli iperreali
2. **Prerequisiti**
3. **Campo dei reali non standard** — costruzione di $^\ast\mathbb{R}$
4. **Universo matematico e controparte non standard** — generalizzazione all'universo $V(\mathbb{R})$
5. **Varietà differenziabili** — estensione non standard di una varietà, campi vettoriali e flussi come cammini a passi infinitesimi

## Struttura del repository

```
.
├── tesi.pdf                    # tesi compilata
├── presentazione.pdf           # slide della discussione
├── tesi/
│   ├── peccioli_tesi.tex       # file principale
│   ├── frontbackmatter/        # preambolo, frontespizio, bibliografia, logo
│   └── mainmatter/             # introduzione, prerequisiti e capitoli
└── presentazione/
    ├── PECCIOLI.tex            # file principale (Beamer)
    └── header_beamer.tex       # preambolo
```

## Compilazione

Serve una distribuzione TeX completa (TeX Live o MacTeX) con `latexmk` e `biber`.

```bash
cd tesi && latexmk -pdf peccioli_tesi.tex
```

```bash
cd presentazione && latexmk -pdf PECCIOLI.tex
```
