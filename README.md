# hetproperekomitee.github.io
# Wetboek Sluikstort & Bales — Online versie

Deze repository host de online landingspagina en de meest recente PDF-versie van het **Wetboek Sluikstort & Stickers**.

**Website:** https://hetproperekomitee.github.io/  
**Laatste PDF:** https://hetproperekomitee.github.io/LATEST.pdf

---

## Bestandsstructuur

- `index.html` — landingspagina (QR-bestemming)
- `LATEST.pdf` — steeds de meest recente PDF
- `archive/` — (optioneel) oudere versies

---

## Updaten naar een nieuwe versie (kort stappenplan)

1. Exporteer het wetboek naar PDF.
2. Upload de nieuwe PDF naar deze repo als **`LATEST.pdf`** (vervang het oude bestand).
3. Pas in `index.html` de cache-parameter aan (zodat smartphones zeker de nieuwste versie laden), bv.:
   - `LATEST.pdf?v=2026-01-01-2`
4. Commit & push.
5. Test:
   - https://hetproperekomitee.github.io/
   - https://hetproperekomitee.github.io/LATEST.pdf

---

## Opmerking

Dit is een informatief naslagwerk. Voor bindende regels gelden de officiële publicaties van Stad Gent/IVAGO.
