# VanBouwNaarBeter

Statische website (één HTML-bestand) voor VanBouwNaarBeter — renovatie & installatie in Oost-Nederland.

## Bestanden

- `index.html` — de volledige website (HTML, CSS en JS in één bestand)

## Lokaal bekijken

Open `index.html` gewoon in je browser, of start een eenvoudige server:

```bash
python3 -m http.server 8000
```

Ga daarna naar <http://localhost:8000>.

## Publiceren via GitHub Pages

1. Maak een nieuwe repository aan op GitHub en push deze bestanden (of upload de zip-inhoud).
2. Ga naar **Settings → Pages**.
3. Kies bij **Source** de branch `main` en map `/ (root)`.
4. Sla op. Na een minuut staat de site live op `https://<gebruikersnaam>.github.io/<repo-naam>/`.

Omdat het bestand `index.html` heet, wordt het automatisch als startpagina geserveerd.
