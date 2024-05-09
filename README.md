# ucim sa gitovat o 100 sest

## mensi nadpis
### mensi mensi

Je toho vela, ale verim, ze to **zvladnem**.
[Tu je moj Youtube kanal](https://www.youtube.com/@t4s178).

* toto
* su
* odrazky
* v zozname

Tu su prikazy, ktore som sa ucil v kurze.
---

###IŠTALÁCIA


Pre Windows odporúčam [cmder](https://cmder.net).

Na Macu spusti prvý príkaz cez Terminál a mal by sa nainštalovať Git.
Ak nie, spusti druhý príkaz.
```
git --version
xcode-select --install
```
Ak sa nedarí, nainštaluj [odtiaľto](https://git-scm.com/download/).

###GIT NASTAVENIA

Otestuj, či ho máš nainštalovaný.

```
git --version
```

Nastav **meno** a __heslo__ (ak požívaš Github, _použi_ *github údaje*).

```
git config --global user.name "tvojemeno"
git config -- global user.email "tvojemail.hu"
```

###GIT ZÁKLADY

Aktivuj git pre projekt.

```
git init
```

Over stav / pozri, čo sa zmenilo.

```
git status
```

Ak spravíš zmenu v súbore, **a chceš ho v novej verzii projektu**, označ ho.

```
git add index.html
```

Vytesaj zmenu do kameňa. **Vždy pridaj skutočný popis zmeny**.

```
git commit -m "pridal som index.html"
```

Pozri si vývoj projektu.

```
git log
```

Opakuj naveky;)