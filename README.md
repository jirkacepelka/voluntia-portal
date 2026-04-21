# Voluntia portál

Statická HTML/CSS verze webu bez build kroku a bez frameworků.

## Struktura

- `index.html` – hlavní entrypoint (funguje i přes `file://`)
- `pages/kulaty_stul.html` – stránka s obsahem
- `css/kulaty_stul.css` – styly (relativně linkované)

## Spuštění lokálně

1. Stáhni repozitář (např. jako ZIP) a rozbal ho.
2. Otevři `index.html` v prohlížeči.

### Volitelné: jednoduchý lokální server

Pokud chceš server (není nutný):

```bash
python -m http.server 8000
```

A pak otevři `http://localhost:8000`.
