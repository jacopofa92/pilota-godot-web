# Prove tecniche Godot (versione web)

Due prove di una grafica fatta con Godot 4.7.2 (renderer Compatibility, WebGL 2, senza thread).

## `/` — Evocazione epica

Una sola scena: l'evocazione di un mostro di Livello 7+ (carta che sale, sospensione, schianto, onda d'urto,
ologramma). Due carte del set WW1 (Francesco Baracca, Godwin von Brumowski) sul campo di battaglia notturno della
Grande Guerra.

Comandi: **Spazio** rigioca · **Tab** cambia carta · **S** rallentatore. In alto a destra: fps e GPU.

## `/sandbox/` — Duello di prova

Un duello vero, solo carte WW1: **Regio Esercito** (25 carte italiane) contro **k.u.k. Armee** (25 austro-ungariche).
Regole, effetti e IA sono un motore JavaScript caricato da `gioco/`; Godot disegna il campo e le animazioni.

- Giochi tu contro l'IA: clic su una carta in mano o sul tuo Terreno per le azioni, bottoni delle fasi in basso a
  destra, una finestra per le scelte.
- `sandbox/?ia=1` — IA contro IA, da guardare.

Repository temporaneo, solo per provare le scene su PC e telefono.
