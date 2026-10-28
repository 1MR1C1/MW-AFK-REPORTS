# MW AFK — reports drop-box

Diagnostic data the macro uploads by itself. **Nothing here is source code, and
nothing here is precious.**

Each phone writes into its own folder, named by a random id the app makes up on
first run. That id is not tied to a person or to the hardware — it exists only
so two phones' reports can be told apart.

What lands here:

- `record.txt` — what happened and when: sessions, stalls and how long each one
  cost, battles, and a flag when the game updated
- `worst-screens.txt` — the screens that could not be recognised, ranked by how
  often they blocked a run
- `*.txt` notes — for each screenshot, what the phone could *tell* us about that
  screen: which app put it there, what the buttons said
- `*.png` — screenshots of screens the macro did not recognise

## On privacy

The app only photographs the game, adverts, and the store and system screens
that adverts pretend to be. If the phone is picked up and used for something
else, the written note is still filed but **no picture is taken**.

## This repo is disposable

It is public so the app can write to it with a password that can reach nothing
else. If that password ever leaks, the worst anyone can do is write rubbish
here — then we delete this repo and make another. It holds no secrets and
nothing that cannot be thrown away.
