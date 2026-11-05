# Not now — presentatie

Een zelfstandige website. Alle lettertypen staan lokaal in de map `fonts`.
Geen installatie, database of externe lettertypedienst nodig.

## Lokaal

Open een terminal in deze map en voer `python3 -m http.server 3000` uit.
Open http://localhost:3000.

Pijltjestoetsen: vorige/volgende slide. F: volledig scherm. Home/End: eerste/laatste slide.

## GitHub Pages

1. Maak een GitHub-repository en plaats de inhoud van deze map op branch `main`, inclusief `.github/workflows/pages.yml`.
2. Kies in de repository **Settings → Pages → Source → GitHub Actions**.
3. Start **Actions → Publish presentation → Run workflow**, of push een wijziging naar `main`.
4. De publicatielink staat na afloop bij de workflow en onder **Settings → Pages**.

De website werkt ook onder een repository-subpad: alle eigen bestanden gebruiken relatieve paden.

## Na één dag offline

GitHub Pages verloopt niet automatisch. Kies na de presentatie in **Settings → Pages → Unpublish site**.
Push daarna geen nieuwe wijzigingen zolang je de website offline wilt houden.

## Lettertype

Kefa III, aangeleverd door de gebruiker. De meegeleverde licentie vermeldt 'Personal Use Only'.
