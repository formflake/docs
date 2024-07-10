---
title: Fragen, Fragetypen
description: Entdecke alles über die Fragetypen und deren Einstellungen für deine **digitalen Formulare**.
categories: [Fragen, Konfiguration, Setup]
weight: 4
ressources:
  - src: "*.png"
---

Diese Seite bezieht sich auf das **Hinzufügen**, **Editieren** und **Konfigurieren von Fragen** in deinen Formularen.

## 1. Frage erstellen

Mit der [Konfiguration des Formulars](https://formflake.com/community/docs/forms) können Fragen hinzugefügt werden.

### 1.1 Titel der Frage

Der **interne Name** dient zur Orientierung der Editoren innerhalb des Formulars. Die **Frage / Titel / Überschrift** wird auf der Frageseite im Formular angezeigt und dient zur Einleitung der Antwort-Optionen. Füge die Überschrift in Deutsch und Englisch ein, um User mit entsprechenden Browsereinstellungen zu leiten.

{{% alert title="Hinweis" %}}Halte die Überschrift kurz und prägnant und sprich den User direkt an. So steigt die Verständlichkeit als konsequenterweise auch die Qualität der Antworten.{{% /alert %}}

### 1.2 Frage überspringen

Der Toggle zum **Überspringen der Frage** steuert, ob ein User ohne eine Antwort abzugeben zu einer andere Fragen springen darf. In der Konfiguration kannst du nur auf Fragen springen, die nachgelagert zur aktuellen Frage angeordnet sind. So werden **Endlosschleifen vermieden**.

Sobald du den Toggle aktivierst, werden die möglichen Ziele des Überspringens angezeigt. Auch die letzte Frage des Formulars kann übersprungen werden. Automatisch wird "Zur nächsten Frage" springen gesetzt. Diese nächste Frage entspricht in diesem Fall der **Abschlussseite**.

### 1.3 Bild zu einer Frage

Du kannst an jeder Frage ein Bild *oder* ein Icon hinzufügen. Dieses Bild wird zwischen der Überschrift der Frage und den Antwortoptionen angezeigt. Wähle über das Auswahlfeld **Layout der Frage**, ob das Bild maximiert oder in originaler Größe angezeigt werden soll. Weitere Layout-Optionen werden kontinuierlich ergänzt. 

<div class="row gap-3">
{{< imgproc "Question with image.png" Fit "350x350" >}}
Bild an einer Frage.
{{< /imgproc >}}

{{< imgproc "Question-maximized.png" Fit "350x350" >}}
Layout des maximierten Bildes an einer Frage.
{{< /imgproc >}}
</div>

## 2. Fragetypen

### 2.1 Multiselect / Single Select

**Konfiguration**:
* Fragetyp Multiselect; Max. Anzahl der Antworten >== 0 = Multiselect
* Fragetyp Multiselect; Max. Anzahl der Antworten === 1 = Single Select

Das Anbieten von **Antwortoptionen** anstelle von offenen Textfeldern in digitalen Formularen und Lead Funnels bietet erhebliche Vorteile. Zum einen verbessert es die **Benutzerfreundlichkeit**, da die User schneller und einfacher Antworten auswählen können, was die Abbruchrate verringert und die **Konvertierung** erhöht. Zum anderen sorgt es für eine höhere **Datenqualität** und -konsistenz, da vorgegebene Antwortoptionen Missverständnisse und Tippfehler vermeiden, die bei offenen Texteingaben häufig auftreten. Schließlich ermöglicht die Nutzung von Antwortoptionen eine effizientere und präzisere **Datenanalyse**, da die Antworten bereits strukturiert und kategorisiert sind, was eine schnellere und fundiertere Entscheidungsfindung unterstützt.

In Summe ist es empfehlenswert, den Prozess der Nutzerführung möglichst benutzerfreundlich und somit mit vielen Auswahlfragen zu gestalten. Optional können Sie an den Antwortoptionen die Texteingabe ermöglichen. Eine typische Auswahloption mit Texteingabe ist die Kachel: "Sonstiges" oder "Andere".

Ein gut gestaltetes Formular, das Vertrauen schafft und nur die notwendigen Informationen abfragt, kann die Bereitschaft der Nutzer zur Dateneingabe erhöhen und so die Lead-Generierung signifikant verbessern.

{{< imgproc Multiselect.png Fit "350x350" >}}
Schematisches Bild einer Frage mit **Mehrfachauswahl**.
{{< /imgproc >}}

### 2.2 Kontaktdetails

**Konfiguration**: Fragetyp Kontaktdetails

Das Abfragen von **Kontaktdetails** lässt sich ideal für Lead-Erfassungsformulare auf Messen nutzen. Diese sind entscheidender Bestandteil einer effektiven Vertriebs- und Marketingstrategie - speziell für Messen oder sonstige Events lassen sich formflake Formulare auf Smartphones als eine Art "**Lead-App**" einsetzen.

Durch die Erfassung von grundlegenden Informationen wie Name, E-Mail-Adresse und Telefonnummer können Unternehmen Leads dokumentieren und in wenigen Klicks **qualifizieren**. Diese Daten ermöglichen eine personalisierte Kommunikation, die die Kundenbindung stärkt und die Chancen auf eine erfolgreiche Konversion erhöht. Zudem erleichtern vollständige Kontaktdetails die Nachverfolgung und Pflege von Kundenbeziehungen über verschiedene Kanäle hinweg, was zu einer verbesserten **Kundenzufriedenheit** und langfristigen Geschäftserfolgen führt.

Für **Lead-Erfassungsformulare** bietet es sich an, die manuelle Eingabe von Kontaktdetails als Alternative zum Uploads eines Bildes (der Visitenkarte) einzusetzen. Mehr über die Upload-Fragen finden Sie [hier](#upload).

{{< imgproc "Contact details.png" Fit "350x350" >}}
Schematisches Bild einer Frage für die Eingabe von Kontaktdetails.
{{< /imgproc >}}

### 2.3 Bewertungen / Rating-Fragen

**Konfiguration**: Fragetyp Rating; Beliebige Antwortoptionen; Je Antwortoption wird automtaisch ein Sterne-Ranking angeboten (1-10 in 0,5-Sterne-Schritten)

Rating-Fragen sind ein leistungsstarkes Werkzeug in digitalen Formularen und Lead Funnels, da sie eine effiziente Methode zur Erfassung von **Nutzermeinungen und -erfahrungen** bieten. Durch die Verwendung einer **Skala**, beispielsweise von 1 bis 10, können Nutzer ihre **Zufriedenheit**, **Zustimmung** oder **Bewertung** zu einem bestimmten Thema einfach und intuitiv ausdrücken. Dies ermöglicht es Unternehmen, ein klareres und quantifizierbares Bild der Kundenzufriedenheit oder -präferenzen zu erhalten.

Rating-Fragen reduzieren die Antwortzeit und erhöhen die **Teilnahmebereitschaft**, da sie weniger Aufwand erfordern als offene Texteingaben. Zudem liefern sie konsistente und leicht **analysierbare Daten**, die Unternehmen dabei helfen, Trends zu erkennen, Schwachstellen zu identifizieren und **fundierte Entscheidungen** zu treffen. Indem sie das Nutzererlebnis verbessern und die Datenerhebung vereinfachen, tragen Rating-Fragen wesentlich zur Effizienz und Effektivität von Feedback- und Lead-Erfassungsprozessen bei.

{{< imgproc "Rating.png" Fit "350x350" >}}
Schematisches Bild einer Frage für die Bewertung einzelner Bereiche.
{{< /imgproc >}}

### 2.4 Texteingabe

**Konfiguration**: Fragetyp Multiselect; 1 Antwortoption; Erweiterung: Freitext-Eingabe oder Kurztext-Eingabe

**Offene Texteingaben** bieten Usern die Möglichkeit, detaillierte und spezifische Antworten zu geben, die über standardisierte Optionen hinausgehen. Diese Art von Fragen ist besonders wertvoll, wenn tiefere Einblicke in die Meinungen, Bedürfnisse und Erfahrungen der Nutzer gewonnen werden sollen. Häufig ist die Fragen um "in eigenen Worten" ergänzt, um auszudrücken, dass es um freie Beschreibungen geht. Diese Texteingaben ermöglichen es den Usern so, ihre Gedanken in ihren eigenen Worten auszudrücken, was zu reichhaltigeren und nuancierteren Daten führt.

Diese Art der Antworten sind können besonders dann nützlich sein, um **neue Trends**, **spezifische Anliegen** oder **innovative Ideen** zu identifizieren, die standardisierte Fragen möglicherweise ausschließen würden. Allerdings erfordern offene Texteingaben auch mehr Zeit und Mühe von den Usern, was die Antwortbereitschaft beeinflussen kann. Zudem stellt die Auswertung solcher Daten eine größere Herausforderung dar, da sie weniger strukturiert und schwieriger zu analysieren sind.

Dennoch bieten offene Texteingaben einen unschätzbaren Wert für **tiefgehende qualitative Analysen** und ein umfassendes Verständnis der Nutzerperspektiven.

{{< imgproc "Text.png" Fit "350x350" >}}
Schematisches Bild einer Frage für Freitext-Eingaben.
{{< /imgproc >}}

### 2.5 Datei-Upload <a id="upload"></a>

**Konfiguration**: Fragetyp Multiselect; 1 Antwortoption; Erweiterung: Datei-Upload

Der **Datei-Upload** als Fragetyp in digitalen Formularen und Lead Funnels bietet erhebliche Vorteile, insbesondere wenn spezifische **Dokumente**, **Bilder** oder **andere Dateien** für den Prozess erforderlich sind. Dies können Projekt-, Produktsizzen oder sonstige Mitschriften sein. Diese Funktion ermöglicht es Usern, direkt **relevante Dateien hochzuladen**, was den Informationsfluss vereinfacht und die Qualifizierung der Anfrage deutlich vereinfacht.

Für Unternehmen bedeutet dies eine effizientere Datenerfassung und -verarbeitung, da benötigte Dokumente sofort zur Verfügung stehen. Datei-Uploads sind besonders nützlich in Branchen wie Personalwesen, Maschinenbau, Immobilien oder Versicherungen, wo oft Identitätsnachweise, Lebensläufe oder andere wichtige Unterlagen eingereicht werden müssen. Sie bieten eine nahtlose Möglichkeit, **detaillierte und spezifische Informationen** zu sammeln, die sonst in Textform schwer zu erfassen wären. Die Einbindung dieser Funktion verbessert die Benutzerfreundlichkeit und erhöht die Wahrscheinlichkeit, dass Nutzer das Formular vollständig ausfüllen, da sie alles an einem Ort erledigen können. Zudem wird die **Datenintegrität** gewahrt, da die Gefahr von Übertragungsfehlern bei manueller Eingabe entfällt.

{{< imgproc "Upload.png" Fit "350x350" >}}
Schematisches Bild zum hochladen von Dokumenten und Dateien.
{{< /imgproc >}}

