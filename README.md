# AI Developer Self-Study Roadmap

Statická HTML roadmapa pro samostatné studium AI developmentu na macOS. Hlavní soubor je `index.html`.

## Jak otevřít

Otevři `index.html` v prohlížeči, nebo spusť lokální server:

```bash
npm run serve
```

## Doporučená trasa

Core path: setup + L1-L6 -> L11-L14 -> L17-L18.

Volitelné / advanced: L7-L10, L15-L16, portfolio a open-source sekce.

## Validace

Po úpravách spusť:

```bash
npm install
npm run validate
```

`npm run validate` kontroluje HTML strukturu přes `html-validate`.

## Poznámky pro údržbu

- Model IDs a ceny rychle zastarávají. Při větší aktualizaci ověř OpenAI a Anthropic docs.
- Fine-tuning drž jako volitelnou pokročilou část, ne jako výchozí cestu.
- RAG lekce používá ChromaDB jako default, FAISS jen jako alternativu.
