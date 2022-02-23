
## Rollen und Rechte in trustkey

Rollen und Berechtigungen können in trustkey auf verschiedenen Ebenen gesteuert werden:

## Admin

- 



### Builder - Template-Ebene (T-) - Mitglieder:

- Template-Besitzer:
  - Kann Template-Rechte vergeben und ändern
  - Kann Template veröffentlichen
  - Kann Neue Version des Templates hinzufügen
  - Kann Template im Entwurf-Status bearbeiten
  - Kann veröffentlichtes Template launchen

- Template-Bearbeiter:
  - Kann Template im Entwurf-Status bearbeiten
  - Kann veröffentlichtes Template launchen
 
- Template-Leser
  - Kann Template anzeigen (Entwurf und Veröffentlichung)
  - Kann veröffentlichtes Template launchen

> **Hinweis:**
> Alle anderen Nutzer von trustkey können das Template nur launchen, wenn es Bestandteil eines Boards oder einer Wissenseite ist und das Board oder die Wissenseite mit ihnen geteilt worden ist.

### Workspace - Aktionspaket-Ebene (A-) - Mitglieder:

- Manager:
  - Kann Rechte für das Aktionspaket hinzufügen und verwalten
  - Kann alle Funktionen des Aktionspakets nutzen:
    - Navigation einblenden
    - Verknüpfte Informationen hinzufügen und entfernen
    - Aktionspaket Titel und Beschreibung ändern
    - Altionspaket terminieren bzw. Terminierung ändern
    - Labels hinzufügen
    - Feature Bild hinzufügen
    - Aktionspaket duplizieren
    - Aktionspaket löschen
    - Vorschau-Drucken anzeigen
    - Vorschau-PDF anzeigen
  - Kann Kommentare erstellen und seine Kommentare verwalten.
  - Kann alle Komponenten des Aktionspakets bearbeiten und Aktionspaket abschließen.


- Empfänger:
  - Kann folgende Funktionen des Aktionspakets nutzen:
    - Navigation einblenden
    - Verknüpfte Informationen hinzufügen und entfernen
    - Labels hinzufügen
    - Vorschau-Drucken anzeigen
    - Vorschau-PDF anzeigen
  - Kann Kommentare erstellen und seine Kommentare verwalten.
  - Kann in Abhängigkeit der durch den Manager vergebenen Rechte:
    - alle oder ausgewählte Komponenten bearbeiten (Standard: alle Komponenten)
    - das Aktionspaket abschließen (Standard: Kann Aktionspaket abschließen)

- Mitwirkender:
  - Kann die gleichen Funktionen wie der Empfänger nutzen.
  - Kann Kommentare erstellen und seine Kommentare verwalten.
  - Kann in Abhängigkeit der durch den Manager vergebenen Rechte:
    - alle oder ausgewählte Komponenten bearbeiten (Standard: alle Komponenten)

- Leser:
  - Kann die gleichen Funktionen wie der Empfänger nutzen.
  - Kann Kommentare erstellen und seine Kommentare verwalten.
  - Kann in Abhängigkeit der durch den Manager vergebenen Rechte:
    - alle oder ausgewählte Komponenten einsehen (Standard: alle Komponenten)

> **Hinweis**:
> Gäste - also Nutzer ohne Lizenz - können nur Empfänger, Mitwirkender oder Leser eines Aktionspakets sein und können Kommentare weder einsehen noch nutzen.
