# Nasazení aplikace se ještě připravuje, zatím frontend - server(offline) - problém railway - opravy v řešení
```bash
https://evo-theta.vercel.app/
```
# Frontend aplikace pro seberozvoj (Next.js + TypeScript + Tailwind CSS)

Tato aplikace je progresivní webová aplikace (PWA) vytvořená pomocí frameworku **Next.js**. Kód je psán v **TypeScriptu** a stylování je řešeno pomocí **Tailwind CSS**.

## Spuštění frontendu aplikace

Tato část popisuje, jak spustit frontend projektu v lokálním prostředí a ověřit jeho funkčnost.

---

### 1. Předpoklady

Pro úspěšné spuštění frontendové části aplikace je nutné mít nainstalováno:

- **Node.js** ve verzi 18.x nebo vyšší  
  [Stáhnout Node.js](https://nodejs.org/)
- **npm** – správce balíčků (je součástí Node.js)
- Doporučené vývojové prostředí: [Visual Studio Code](https://code.visualstudio.com/)

---

### 2. Klonování repozitáře (volitelné)

Pokud projekt stahujete z Git repozitáře, použijte:

```bash
https://github.com/Ev3r3st/EVO-FRONTEND.git
cd nazev-projektu
```

---

### 3. Instalace závislostí

V kořenové složce projektu spusťte v terminálu následující příkaz:

```bash
npm install
```

Tím se nainstalují všechny potřebné závislosti definované v souboru `package.json`.

---

### 4. Spuštění vývojového serveru

Po úspěšné instalaci spusťte vývojový server příkazem:

```bash
npm run dev
```

Pokud je vše v pořádku, terminál zobrazí výstup podobný následujícímu:

```
ready - started server on http://localhost:3000
```

---

### 5. Ověření funkčnosti

Otevřete webový prohlížeč (např. Google Chrome) a přejděte na adresu:

👉 [http://localhost:3000](http://localhost:3000)

Zobrazí se úvodní stránka aplikace. Pokud se zobrazí rozhraní aplikace (např. přihlašovací formulář, úvodní obrazovka nebo přehled cílů), frontend je úspěšně spuštěn.

---

### 6. Struktura projektu

Hlavní soubor, který se zobrazuje na doméně `/`, je:

```
src/app/page.tsx
```

Jakékoli úpravy tohoto souboru se automaticky projeví díky funkci **hot reload**.

---

### 7. Build pro produkci (volitelně)

Pro vytvoření produkční verze aplikace spusťte:

```bash
npm run build
```

A následně spuštění buildu pomocí:

```bash
npm start
```

Produkční build slouží např. pro nasazení na server nebo hostingovou platformu.

---

## Technologie použité v projektu

- Next.js  
- TypeScript  
- Tailwind CSS  
- PWA (Progressive Web App)  
- Visual Studio Code (doporučený editor)

---

## Autor

** Matyáš Krotil**  
Fakulta informatiky a managementu, Univerzita Hradec Králové  
Rok odevzdání: 2025
