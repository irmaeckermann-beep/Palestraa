# Changelog — Tonifit Website

Alle wesentlichen Änderungen an www.tonifit.it werden hier dokumentiert (neueste zuerst).

## 2026-10-07

- **Hero-Video getrimmt**: erste 5 Sekunden (Decke) entfernt — startet jetzt direkt mit dem Saal und dem Tonifit-Palestra-Schriftzug
- **Hero-Video in HD**: Neu-Encoding in voller 1080p-Qualität (WebM 13 MB + MP4 17 MB statt 720p/4 MB) — nicht mehr verpixelt
- **Hero-Feinschliff**: Video sichtbarer (75% statt 50%), Überschrift kompakter, Textschatten für Lesbarkeit — die Schrift verdeckt das Video nicht mehr
- **Hero-Video**: 28-Sekunden-Drohnenflug durchs Studio als Hintergrund (stumm, Loop, 4 MB weboptimiert, Foto als Fallback/Standbild)
- **Marktanalyse umgesetzt (Ziel: Neukunden)** — echte Studio-Daten recherchiert (Google Maps, Facebook, Instagram) und integriert:
  - **Telefon** 0831 366662 (klickbar), **Öffnungszeiten** (Lun–Ven 8–22, Sab 9–13, Dom chiuso), **Google-Maps-Karte** in der Kontakt-Sektion
  - **Social Proof**: ★ 4,9 bei 111 Google-Rezensionen (Hero-Karte + Kontakt, verlinkt), echte Instagram-/Facebook-Links (@tonifitpalestra)
  - **Vertrauen**: 30+ Jahre Erfahrung, Giudice IFBB (Bio), 100% Panatta-Ausstattung
  - **Kontaktformular funktionsfähig** (FormSubmit an info@tonifit.it; Aktivierung folgt sobald Mailbox existiert) + Danke-Seite (grazie.html)
  - **SEO**: Meta-Description, Open-Graph-Tags, Favicon, Canonical, JSON-LD LocalBusiness (Name, Adresse, Telefon, Öffnungszeiten, Geo) für Google-Suche
  - **Datenschutz**: Privacy-Seite (privacy.html, GDPR) + Footer-Links korrigiert
- **Fix**: Hero-Überschrift wird auf keiner Bildschirmbreite mehr abgeschnitten (fluide Größe mit Obergrenze)
- **Changelog** eingeführt
- **Hero-Foto**: echtes Foto der Sala mit "Tonifit Palestra"-Schriftzug (in Farbe) als Hintergrund
- **Mobile-Fix**: Hero-Überschrift skaliert jetzt mit der Bildschirmbreite (wurde vorher abgeschnitten); "Team"-Link in Navigation und Handy-Menü ergänzt
- **Echte Fotos eingebaut** (ersetzen Unsplash-Platzhalter): Tony als "Il Fondatore", neue Sektion **"Il Team"** mit 3 Trainer-Porträts, Trainingsfoto im Hero; alle Bilder fürs Web komprimiert (gesamt ~1 MB statt 160 MB)
- Offen: Hero-Video (Datei fehlt noch), Trainer-Namen, echter Google-Kurskalender, E-Mail info@tonifit.it

## 2026-08-06

- **Domain tonifit.it registriert** (Infomaniak, CHF 9.95/Jahr, Inhaber DOMA Consulting & Marketing GmbH; Registrierungsfehler behoben: korrekte UID CHE-269.264.432 als Identifikationsnummer)
- **Website live geschaltet**: GitHub Pages (Actions-Deployment), DNS bei Infomaniak (4× A-Record + CNAME www), HTTPS erzwungen → https://www.tonifit.it
- **Farbe**: kurzer Test mit Bordeaux (#a4161a), auf Wunsch zurück zum originalen Neonrot (#eb0000)
- **Kalender-Sektion** "Il Calendario" mit eingebettetem Google Kalender (noch Demo-Kalender, wartet auf echte Kalender-ID)
- **Kurs Pilates** ergänzt (Nr. 09)
- **Rebranding zu "Tonifit"**: Name, Titel, Fondatore Antonio Urso, Adresse Via Sacerdote Spina 7, Ceglie Messapica, E-Mail-Platzhalter info@tonifit.it
- **Mobile-Menü** (Hamburger) ergänzt, "Inizia Ora"-Button verlinkt zum Kontaktformular
- **Sektion "I Nostri Corsi"** mit 8 Kursen (Bodybuilding, Fitness Bikini, TRX, Push Power, Muay Thai, Funzionale, GAG, Pole Dance) + Nav-Link
- **Servizi** auf echte Angebote umgestellt: Personal Coaching und Personal Trainer
- **Start**: Stitch-Export als Website eingerichtet, GitHub-Repo erstellt (öffentlich für kostenloses Hosting), Repo: github.com/irmaeckermann-beep/Palestraa
