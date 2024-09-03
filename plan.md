# Plan voor GitHub en Vercel Deployment

## Stap 1: GitHub Repository Voorbereiden
1. Controleer of we in de juiste map staan:
   ```
   pwd
   ```
   Zorg ervoor dat de output eindigt met `/PP-01`

2. Initialiseer Git als dit nog niet is gedaan:
   ```
   git init
   ```

3. Voeg alle bestanden toe aan de staging area:
   ```
   git add .
   ```

4. Maak de eerste commit:
   ```
   git commit -m "Initiële commit"
   ```

## Stap 2: Verbinden met GitHub Repository
1. Voeg de remote repository toe:
   ```
   git remote add origin https://github.com/Sjaaak777/pp-01.git
   ```

2. Verifieer de toegevoegde remote:
   ```
   git remote -v
   ```

3. Push de code naar GitHub:
   ```
   git push -u origin main
   ```

## Stap 3: Vercel Deployment Voorbereiden
1. Zorg ervoor dat Node.js is geïnstalleerd:
   ```
   node --version
   ```

2. Installeer Vercel CLI globaal:
   ```
   npm install -g vercel
   ```

## Stap 4: Vercel Deployment
1. Log in op Vercel via de CLI:
   ```
   vercel login
   ```

2. Deploy het project:
   ```
   vercel
   ```

3. Volg de prompts en kies de juiste opties voor uw project.

## Stap 5: Verifiëren en Testen
1. Open de gedeployde URL in een browser om te controleren of alles correct werkt.

2. Test de responsiviteit en functionaliteit van de website.

## Stap 6: Toekomstige Updates
1. Maak wijzigingen in uw lokale project.

2. Commit de wijzigingen:
   ```
   git add .
   git commit -m "Beschrijving van de wijzigingen"
   ```

3. Push de wijzigingen naar GitHub:
   ```
   git push
   ```

4. Vercel zal automatisch de nieuwe versie deployen.
