Spuštění frontendu aplikace
Frontend této aplikace je vytvořen pomocí frameworku Next.js s využitím TypeScriptu a Tailwind CSS. Aplikace je koncipována jako progresivní webová aplikace (PWA).

1. Předpoklady
Pro úspěšné spuštění frontendu je potřeba mít nainstalováno:

Node.js ve verzi 18.x nebo vyšší

npm (součástí Node.js)

2. Instalace závislostí
Otevřete terminál ve složce projektu (např. my-pwa-app) a spusťte příkaz:

bash
Zkopírovat
Upravit
npm install
Tím se nainstalují všechny potřebné balíčky uvedené v package.json.

3. Spuštění vývojového serveru
Po úspěšné instalaci závislostí spusťte vývojový server pomocí příkazu:

bash
Zkopírovat
Upravit
npm run dev
Pokud je vše v pořádku, v terminálu se zobrazí informace podobná následující:

arduino
Zkopírovat
Upravit
Local: http://localhost:3000
4. Ověření funkčnosti
Otevřete webový prohlížeč (např. Google Chrome) a zadejte adresu:

http://localhost:3000

Pokud se zobrazí úvodní stránka aplikace, je frontend úspěšně spuštěn. V případě této aplikace může jít např. o úvodní obrazovku s přehledem cílů, kurzy nebo formulářem pro přihlášení.

5. Úprava obsahu
Základní stránka aplikace se nachází v souboru:

bash
Zkopírovat
Upravit
src/app/page.tsx
Jakékoli úpravy v tomto souboru se projeví okamžitě v prohlížeči díky funkci automatického přenačítání (hot reload).

6. Vývojové prostředí
Projekt je možné otevřít v libovolném editoru kódu, doporučuje se však Visual Studio Code (VS Code), který poskytuje podporu pro TypeScript, ESLint a integraci s Git.

