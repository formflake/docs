---
title: Formulare
description: Hier erfährst du alles zu den **digitalen Formularen** von formflake.
categories: [Formulare, Konfiguration, Setup]
weight: 3
---

Diese Seite bezieht sich auf das Erstellen und Konfigurieren von Formularen: [Formular erstellen](https://formflake.com/designer/forms/create).

<!-- TODO don't embed images from the main site, copy them -->

## 1. Formular erstellen

Nach dem Login navigierst du im Flow Designer in den Bereich Forumalre und klickst auf den Button [Formular erstellen](https://formflake.com/designer/forms/create). Wähle einen **Slug** für das Formular. Dieser Slug wird von Suchmaschinen erkannt - schreibe ihn also möglichst prägnant zu dem Thema, welches dein Formular behandelt. Dein Account-Slug wird ebenfalls in der URL berücksichtigt, daher brauchst du in diesem Formular-Slug keinen Bezug auf deinen Account nehmen.

Dies ist der Aufbau der Formular-URLs: `https://formflake.com/f/`**[account-slug]**/[form-slug]

## 2. Formular konfigurieren

Es öffnet sich das Editierfenster deines Formulars. Nachfolgend findest du die Informationen zu sämtlichen Einstellungsmöglichkeiten:

### 2.1 Interner Name

Der Interne Name ist, wie der Name schon sagt, nur für User deines Accounts zu sehen. Dieser dient zur schnellen Findung einzelner Formulare.

### 2.2 E-Mail Adresse

Hinterlege je Formular eine **E-Mail-Adresse**, die E-Mails zu abgeschlossenen Formularen erhalten soll. Lässt du das Feld leer wird automatisch die E-Mail-Adresse aus deinem [Account Setup](https://formflake.com/designer/accounts) verwendet, wenn du die [E-Mail Benachrichtigung](#benachrichtigung) aktiviert hast.

### 2.3 Einstellungen 

#### 2.3.1 E-Mail-Benachrichtigungen

Verpassen Sie nichts zu Ihrem Formular und aktiviere die E-Mail-Benachrichtigung. Bei jedem erfolgreichen Abschluss eines Formulars wird eine E-Mail verschickt, in der die Antorten des Users zusammengefasst werden. Die Ergebnisse findest du ansonsten über den Bereich [Ergebnisse](https://formflake.com/results).

Aktiviert = E-Mails werden verschickt

#### 2.3.2 Deaktivieren

Sie arbeiten noch am Formular und wollen nicht, dass User (auch intern) darauf zugreifen können. Aktiviere den Toggle, um das Formular komplett zu deaktivieren.

#### 2.3.4 Privates Formular

Private Formulare sind nur für angemeldete User innerhalb deines Accounts zugänglich. Daher kannst du diese Einstellung zur Anpassung interner Formulare oder zu Testzwecken mit anderen Account-Users verwenden.

Aktiviert = Formular ist privat

#### 2.3.5 Firmen-Logo auf Frage-Seiten anzeigen

Ist in deinem [Account Setup](https://formflake.com/designer/accounts) ein Logo hinterlegt, kann dieses auf jeder Frage deines Formulars angezeigt werden.

![Formflake Formulare mit Logo](https://formflake.com/res/info-images/show-logo.svg)

Aktiviert = Logo wird angezeigt

#### 2.3.6 Erweiterte Einstellungen

#### 2.3.7 Fortschrittsbalken anzeigen

Aktiviere die Option, um den Usern anzuzeigen, wie viele Fragen noch ausstehen bzw. wie viele Fragen bereits erledigt wurden. Die Anzeige erfolgt anhand der Frage-Nummer gegenüber der Gesamtzahl an Fragen des Formulars.

![Formflake Formulare mit Fortschrittsbalken](https://formflake.com/res/info-images/progress-bar.svg)

Aktiviert = Fortschrittsbalken wird angezeigt.

{{% alert title="Hinweis" %}}Wenn du deinem Formular benutzerdefinierte Pfade hinzufügst, kann der Fortschrittsbalken irreführend sein, da er immer den Fortschritt in Bezug auf die Gesamtanzahl der Fragen anzeigt.{{% /alert %}}

#### 2.3.8 Startseite vor der ersten Frage anzeigen

Beginne dein Formular mit einer eigenen Startseite. Diese Seite zeigt den **Beschreibungstext des Formulars**. Solltest du ein **Bild** am Formular hochgeladen oder ein **Icon** zugewiesen haben, wird auch dieses angezeigt. Der User kann die Fragen mit einem Klick auf "Los geht's" beginnen, das du in der Formularkonfiguration hinzufügen kannst.

![Formflake Formulare mit eigener Startseite](https://formflake.com/res/info-images/starting-page.svg)

Aktiviert = Startseite wird angezeigt.

#### 2.3.9 Vorschau auf öffentlicher Account-Seite

Füge dieses Formular deiner **öffentlichen Account-Landingpage** hinzu. Aktiviere die Einstellung, damit das Formular angezeigt wird. Das Formular darf weder deaktiviert noch privat sein, damit es sichtbar ist.

Aktiviert = Formular wird auf der Landing-Page angezeigt.

#### 2.3.10 Einbetten des Formulars erlauben

Erlaube das **Einbetten dieses Formulars**, um die Verwendung innerhalb von iframes auf externen Websites zu ermöglichen. Aktiviere den Toggle, so erhältst du eine formular-spezifische URL in folgendem Aufbau:

`https://formflake.com/embed/[formularId]`

Diese URL fügen Sie in einem iframe auf einer externen Webseite ein. Beispielhafter Aufbau:

```html
<div style="width:auto !important;min-width:475px;max-width:1200px;height:915px;">
  <iframe
    sandbox="allow-scripts allow-forms allow-same-origin"
    style="width:100%;height:100%;"
    frameborder="0"
    scrolling="no"
    src="https://formflake.com/embed/[formularId]"
  >
  </iframe>
</div>
```

### 2.4 Hintergrundfarbe der Überschrift

Wähle die **Hintergrundfarbe der Überschrift in der Kopfzeile** auf der Landing Page deines Formulars. Du kannst jedes Formular individuell anpassen oder eine globale Standardfarbe in deinen Organisationseinstellungen festlegen.

### 2.5 Überschrift

Die **Überschrift des Formulars** ist über den gesamten Fragenverlauf hinweg in einer farbig hinterlegten Zeile zu sehen.

### 2.6 Beschreibungstext des Formulars

Ergänze eine möglichst **aussagekräftige Beschreibung** zum Ergebnis des Formulars. Ziel ist es, dass die User alle Fragen beantworten. Daher ist es sinnvoll, sich auf die Vorteile für die User zu beziehen.

Der Beschreibungstext wird über ein Info-Zeichen hinter der Überschrift aufgerufen und öffnet sich in einem Popup. Solltest du die Startseite aktiviert haben, erscheint der Beschreibungstext auf dieser Startseite.

### 2.7 Bild

Ergänze ein **Vorschaubild** zu dem Formular, um es für Besucher auf der Startseite noch attraktiver zu machen. Dieses Vorschaubild wird außerdem in den **[Metadaten](#)** eingebunden. So kannst du dein Formular über beliebige Kanäle wirksam teilen.

### 2.8 Einstellungen zu teilbaren Links

Nutze temporäre Link oder Pins, um den Zugang zu deinen Formularen einzuschränken und zu kontrollieren.

#### 2.8.1 Pins

Schicke Usern die URL `https://formflake.com/share` und den vergebenen **Pin** für dein Formular, um den Users Zugriff zu gestatten. Achte darauf, dass fremde User den Pin erraten könnten. Daher ist diese Variante nicht für sensible Formulare gedacht.

1. Klick auf Share Bereich
2. Klick auf "Temporären Link hinzufügen"
3. Vergebe einen Namen für die interne Verwaltung
4. Ergänze einen Pin über "Pin generieren"
5. Teile die /share-URL mitsamt deines Pins, um Users Zugriff auf dein Formular zu geben.

#### 2.8.2 Temporäre Links

Nutze für sensible Formulare oder Einmal-Abfragen **temporär gültige Links**. Navigiere dazu auf der Konfigurationsseite des Formulars auf den Share-Bereich und generiere den Link:

1. Klick auf Share Bereich
2. Klick auf "Temporären Link hinzufügen"
3. Vergebe einen Namen für die interne Verwaltung
4. Ergänze einen Link über "Link generieren"
5. Kopiere und teile den Link mit den betroffenen Usern

{{% alert title="Note" %}}Temporäre Links sowie Pins sind **auch für private Formulare** nutzbar. Auf diese Weise müssen User den Link oder Pin kennen, um das Formular zu öffnen.{{% /alert %}}


## 3. Abschlusseite / Ending
