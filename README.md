# 🎸 Investiční AI punk s Jardou

Interaktivní webová stránka pro **60minutový praktický workshop**. Účastníci si na vlastním PC, tabletu nebo iPadu vyzkoušejí 4 konkrétní AI prompty pro práci s investicemi. Jeden klik = zkopírovaný prompt připravený k vložení do AI nástroje.

🔗 **Live:** `https://<tvuj-nick>.github.io/<repo>/`

---

## Co web umí

- **4 připravené kroky** — každý jako rozbalovací karta s kontextem, promptem a tlačítkem ke kopírování
- **Kopírování jedním klikem** — účastník nic nepřepisuje, jen vloží prompt do AI (s potvrzením „✓ Zkopírováno")
- **Sledování postupu** — progress bar `0/4` a zaškrtávátko u každého kroku, ať každý vidí, kde je
- **Funguje offline** — vše v jednom HTML souboru, žádné externí knihovny ani CDN (ideální pro nespolehlivou wifi na workshopu)
- **Mobilní i dotykové ovládání** — velké klikací plochy, fallback kopírování pro starší iOS

---

## 4 kroky workshopu

| # | Krok | Nástroj | Co potřebuješ | Čas |
|---|------|---------|---------------|-----|
| 1 | 💼 Analýza portfolia | AI bankéř | Přehled produktů (PDF/export) | ~10 min |
| 2 | 📜 Analýza dluhopisu v emisi | Copilot Chat | Prospekt / emisní podmínky (~150 stran) | ~18 min |
| 3 | 📈 Technická analýza akcie | Copilot Chat | Screenshot grafu akcie | ~18 min |
| 4 | 🎙️ Podcast na míru | NotebookLM | Vlastní zdroje + živá ukázka | ~14 min |

---

## Jak to spustit

### Lokálně
Stáhni `index.html` a otevři ho v prohlížeči. Hotovo — nic se neinstaluje.

### Na GitHub Pages
1. Vytvoř repozitář a nahraj do něj `index.html` (a tento `README.md`).
2. Jdi do **Settings → Pages**.
3. V sekci *Build and deployment* zvol zdroj **Deploy from a branch**.
4. Vyber větev `main` a složku `/ (root)`, ulož.
5. Po chvíli bude web na `https://<tvuj-nick>.github.io/<repo>/`.

---

## Použití na workshopu

1. Pošli účastníkům odkaz (nebo QR kód na plátno).
2. Každý si web otevře na svém zařízení.
3. Klikne na krok → přečte kontext → **Kopírovat prompt**.
4. Vloží prompt do příslušného AI nástroje a přiloží svůj dokument / screenshot.
5. Krok se automaticky odškrtne, progress bar poskočí.

> Krok 4 (NotebookLM) je **živá ukázka** — vede ji lektor, účastníci sledují a zkoušejí potom sami.

---

## Struktura souborů

```
.
├── index.html    # celá aplikace (HTML + CSS + JS v jednom souboru)
└── README.md     # tento soubor
```

---

## Úpravy

Prompty jsou napsané přímo v `index.html` uvnitř bloků `<div class="promptbox">`. Pro změnu textu promptu stačí upravit obsah příslušného boxu.

Barvy se ladí přes CSS proměnné v bloku `:root` na začátku `<style>` (např. `--neon`, `--pink`, `--yellow`).

---

## ⚠️ Disclaimer

Tento web je **vzdělávací nástroj**, nikoli investiční doporučení. Výstupy AI je vždy nutné ověřit. Investice nesou riziko ztráty.

---

*/// Investiční AI punk · Jarda ///*
