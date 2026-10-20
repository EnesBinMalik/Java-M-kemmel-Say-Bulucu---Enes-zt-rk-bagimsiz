# Java M?kemmel Say? Bulucu

Bir say?n?n kendisi hari? pozitif b?lenlerinin toplam?n?n say?n?n kendisine e?it olup olmad???n? inceleyen interaktif uygulama.

## ?zellikler

- B?lenlerin g?rsel analizi
- m?kemmel say? testi
- Java terminal sim?lat?r?
- teori ve senaryo ?rnekleri.

## Teknolojiler

- React
- TypeScript
- Vite

Bu depo, Java algoritmalar?n? taray?c? tabanl? bir aray?zde a??klamak ve sim?le etmek i?in haz?rlanm??t?r. Java ?rnek kodlar? uygulama i?inde incelenebilir; web aray?z?n? ?al??t?rmak i?in Node.js gerekir.

## Kurulum ve ?al??t?rma

**Gereksinimler:** G?ncel bir Node.js LTS s?r?m? ve npm.

```bash
npm install
npm run dev
```

Geli?tirme sunucusunu ba?latt?ktan sonra terminalde g?sterilen yerel adresi taray?c?da a??n.

## Kontroller ve ?retim derlemesi

```bash
npm run lint
npm run build
```

`npm run lint` TypeScript denetimini, `npm run build` ise da??t?m dosyalar?n?n olu?turulmas?n? ?al??t?r?r. Derlemeyi yerel olarak g?r?nt?lemek i?in ?nce `npm run build`, ard?ndan `npm run preview` komutlar?n? kullan?n.

## Proje yap?s?

- `src/components/` ? aray?z, sim?lat?r ve g?rselle?tirme bile?enleri
- `src/utils/perfectNumber.ts, src/components/DivisorVisualizer.tsx, src/components/ScenarioCards.tsx` ? algoritman?n temel uygulama bile?enleri
- `src/main.tsx` ? uygulama ba?lang?? noktas?
- `package.json` ? ba??ml?l?klar ve npm komutlar?

## Katk?

De?i?iklik ?nermeden ?nce ilgili algoritma ad?mlar?n?n do?ru ?al??t???n? do?rulay?n. Kod bi?imini ve mevcut TypeScript tiplerini koruyun.
