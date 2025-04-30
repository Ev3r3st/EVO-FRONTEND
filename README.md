# Frontend aplikace pro seberozvoj (Next.js + TypeScript + Tailwind CSS)

Tato aplikace je progresivní webová aplikace (PWA) vytvořená pomocí frameworku **Next.js**. Kód je psán v **TypeScriptu** a stylování je řešeno pomocí **Tailwind CSS**.

## Spuštění frontendu aplikace

Tato část popisuje, jak spustit frontend projektu v lokálním prostředí a ověřit jeho funkčnost.

### 1. Předpoklady

Pro úspěšné spuštění frontendové části aplikace je nutné mít nainstalováno:

- **Node.js** ve verzi 18.x nebo vyšší  
  [Stáhnout Node.js](https://nodejs.org/)
- **npm** – správce balíčků (je součástí Node.js)
- Doporučené vývojové prostředí: [Visual Studio Code](https://code.visualstudio.com/)

### 2. Klonování repozitáře (volitelné)

Pokud projekt stahujete z Git repozitáře, použijte:

```bash
git clone https://github.com/uzivatel/nazev-projektu.git
cd nazev-projektu
3. Instalace závislostí
V kořenové složce projektu spusťte v terminálu následující příkaz:

bash
Zkopírovat
Upravit
npm install
Tím se nainstalují všechny potřebné závislosti definované v souboru package.json.

4. Spuštění vývojového serveru
Po úspěšné instalaci spusťte vývojový server příkazem:

bash
Zkopírovat
Upravit
npm run dev
Pokud je vše v pořádku, terminál zobrazí výstup podobný následujícímu:

nginx
Zkopírovat
Upravit
ready - started server on http://localhost:3000
5. Ověření funkčnosti
Otevřete webový prohlížeč (např. Google Chrome) a přejděte na adresu:

👉 http://localhost:3000

Zobrazí se úvodní stránka aplikace. Pokud se zobrazí rozhraní aplikace (např. přihlašovací formulář, úvodní obrazovka nebo přehled cílů), frontend je úspěšně spuštěn.

6. Struktura projektu
Hlavní soubor, který se zobrazuje na doméně /, je:

bash
Zkopírovat
Upravit
src/app/page.tsx
Jakékoli úpravy tohoto souboru se automaticky projeví díky funkci hot reload.

7. Build pro produkci (volitelně)
Pro vytvoření produkční verze aplikace spusťte:

bash
Zkopírovat
Upravit
npm run build
A následně spuštění buildu pomocí:

bash
Zkopírovat
Upravit
npm start
Produkční build slouží např. pro nasazení na server nebo hostingovou platformu.

8. Doporučený způsob nasazení
Aplikaci je možné nasadit na platformu Vercel, která je oficiálně podporována tvůrci Next.js. Alternativně je možné použít např. Netlify nebo vlastní VPS server s podporou Node.js.

Technologie použité v projektu
Next.js

TypeScript

Tailwind CSS

PWA (Progressive Web App)

Visual Studio Code (doporučený editor)

Autor
Bc. Matyáš Krotil
Fakulta informatiky a managementu, Univerzita Hradec Králové
Rok odevzdání: 2025
