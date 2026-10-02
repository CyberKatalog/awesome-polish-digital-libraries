# Współtworzenie

Dziękujemy za każdy nowy wpis. Zasady są krótkie.

## Kryteria przyjęcia wpisu

- Serwis jest polski lub posiada polskie zbiory cyfrowe.
- Serwis jest publicznie dostępny online.
- Serwis jest aktywnie utrzymywany.
- Link prowadzi bezpośrednio przez https do samego serwisu, nie do pośrednika.

## Dwie wersje językowe

Lista ma wersję angielską w [README.md](README.md) i polską w [README.pl.md](README.pl.md). Każdy wpis dodajesz w obu plikach, w tej samej sekcji i na tej samej pozycji.

## Format wpisu

Każdy wpis ma dokładnie taką postać:

```
- [Nazwa](https://adres) - opis.
```

- Nazwa to oryginalna polska nazwa serwisu, w obu wersjach językowych.
- Opis to 1-2 zdania zakończone kropką: po angielsku w README.md, po polsku w README.pl.md.
- Wpis trafia do właściwej sekcji tematycznej.
- Wpisy w sekcji są posortowane alfabetycznie według nazwy.
- Jeden serwis na jeden pull request.

## Styl

- Wyłącznie zwykły myślnik `-`, bez myślników typograficznych.
- Wyłącznie proste cudzysłowy `"`.
- Bez komentarzy HTML.
- Bez pogrubień i innych ozdobników w opisach.

## Proces

1. Zrób fork repozytorium.
2. Utwórz osobną gałąź na swój wpis.
3. Otwórz pull request.
4. Tytuł pull requesta po angielsku w konwencji Conventional Commits, np. `feat: add Academica`. Opis pull requesta może być po polsku.
5. CI sprawdzające linki (link-check) musi przejść, zanim wpis zostanie scalony.

## Martwe linki

Jeśli znajdziesz nieaktywny link, zgłoś to jako issue albo otwórz pull request z poprawką lub usunięciem wpisu.
