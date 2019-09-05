# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (5/5)
- Link für Telefon, der Telefon-Anwendung öffnet (0/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (1/5)
```diff
- Ist kein Download-Link
```
- Links zu Social Media Profilen
  - Haben Icons der Dienste (10/10)
  - Sollen in einem neuen Tab öffnen (5/5)
  
- Foto, das im Kreis dargestellt wird, mit border-radius (5/5)
- Navigation zu den Abschnitten mit Hash-Links (10/10)
- Bilder im Portfolio sollen verlinkt sein (10/10)

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
```diff
- Bitte keine heading-Tags(h4) in li verwenden
```
- Padding in den Links der Hauptnavigation (10/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (5/10)
```diff
- Portfolio-Bild und Header-Bild sind bei den meisten Fenstergrößen viel Breiter als das Fenster und werden abgeschnitten angezeigt.
```
- Korrekte html-Grundstruktur (html, head, body) (9/10)
```diff
- Kein title-Tag im head
```
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**85**/100)
