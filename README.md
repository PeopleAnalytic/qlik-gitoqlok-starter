# Qlik Sense + Gitoqlok: Starter

Detta repo innehåller ett minimalt exempel med Qlik‑objekt som kan synkas via [Gitoqlok].
Struktur och filer är lätta att utöka.

## Mappstruktur
```
app-properties/AppProperties.json
load-script/Script.qvs
master-items/dimensions/Dim_Product.json
master-items/measures/Meas_Sales.json
objects/charts/CH01_SalesByProduct.json
sheets/Sheet_Overview.json
```

## Snabbguide (översikt)
1. Skapa ett tomt Qlik‑app i Qlik Sense (Client/Enterprise).
2. Anslut Gitoqlok till detta Git‑repo (Push/Pull via tillägget).
3. `Pull` för att läsa in kodobjekten i din app. Gitoqlok mappar filerna till Sense‑objekt.
4. `Push` från Gitoqlok när du gör ändringar i appen för att uppdatera filerna här.

> Tips: Behåll stabila `qId` för master‑objekt om ni vill kunna diff:a snyggt i Git.
