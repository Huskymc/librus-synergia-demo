# LIBRUS Synergia – panel szkolny (demo)

Statyczny panel w stylu Librus Synergia (HTML + JS). Dane zapisują się w `localStorage` przeglądarki.

## Logowanie

| Rola | Login | Hasło |
|------|--------|--------|
| Dyrektor | `adminu100` | `admin@#` |
| Nauczyciel | `a.nowak` | `nauczyciel1` |
| Uczeń | `123456u` | `uczen1` |

## Uruchomienie lokalnie

Otwórz `index.html` w przeglądarce albo:

```bash
npx serve .
```

## Deploy na Vercel

1. Zaloguj się na [vercel.com](https://vercel.com) (kontem GitHub).
2. **Add New Project** → wybierz to repozytorium.
3. Framework: **Other** (static).
4. Deploy – bez builda, root = katalog z `index.html`.

Albo CLI:

```bash
npm i -g vercel
vercel
```

Na adresie `https://….vercel.app` zapis danych (`localStorage`) działa stabilnie.

## Funkcje

- Role: uczeń, nauczyciel, dyrektor
- Klasy, grupy, uczniowie, nauczyciele, przedmioty
- Plan lekcji, terminarz, ogłoszenia, zastępstwa
- Generowanie loginów i haseł
- Eksport / import kopii zapasowej JSON (pulpit dyrektora)

> To lokalne / demo UI – nie jest oficjalnym systemem Librus.
