# 🐾 CatNalyze

Final project for the Building AI course

## Summary

CatNalyze ist eine KI-Idee zur automatisierten Analyse von Katzenbildern und -verhalten. Sie soll helfen, Stimmungen, Aktivitäten oder mögliche Gesundheitsprobleme von Katzen zu erkennen – aus Fotos, Videos oder kurzen Textnotizen.

## Background

Viele Katzenbesitzer*innen machen regelmäßig Fotos und Videos von ihren Haustieren – sei es aus Freude oder Sorge. Doch es ist nicht immer leicht zu erkennen, ob die Katze einfach nur schläft, gelangweilt ist oder womöglich Schmerzen hat.

* Problem 1: Katzen zeigen Krankheiten oft sehr subtil – frühe Warnzeichen werden übersehen.
* Problem 2: Emotionale Zustände wie Angst, Spieltrieb oder Unruhe sind für Laien schwer zu deuten.
* Problem 3: Es gibt bisher kaum einfach zugängliche Tools zur Analyse von Katzenverhalten.

Meine Motivation: Ich bin selbst Katzenfreundin und fände ein KI-Tool zur Unterstützung im Alltag praktisch – nicht als Diagnoseinstrument, sondern als Hinweisgeber.

## How is it used?

Katzenbesitzer*innen könnten ein Bild oder ein kurzes Video ihrer Katze hochladen (oder eine Beschreibung eingeben). Die KI analysiert es und gibt eine Einschätzung zurück, z. B.:

* „Klingt nach entspanntem Verhalten.“
* „Auffällige Körperhaltung, bitte beobachten.“
* „Zeichen für Unwohlsein möglich.“

Die Anwendung könnte mobil oder im Browser laufen. Wichtig wäre eine benutzerfreundliche Oberfläche und ein Hinweis, dass dies kein medizinischer Ratschlag ist.

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

## Data sources and AI methods

* Datenquelle: Bilder und Videos von Katzen aus offenen Quellen mit Creative Commons (z. B. Flickr, Kaggle).
* Mögliche KI-Techniken:
  * Bilderkennung mit Convolutional Neural Networks (CNNs)
  * Transfer Learning mit Modellen wie MobileNet oder ResNet
  * Textklassifikation bei kurzen Nutzerbeschreibungen
* Trainingsdaten könnten mit Hilfe der Community erweitert und klassifiziert werden (z. B. „Diese Katze sieht müde aus“).

## Challenges

* Die KI kann keine echten Diagnosen stellen – sie darf nur Hinweise geben.
* Emotionen von Tieren sind schwer objektiv zu messen.
* Datenqualität und ethische Fragen: Bilder müssen korrekt lizenziert und anonymisiert sein.
* Gefahr von Fehlinterpretationen oder Übervertrauen in die KI-Ausgabe.

## What next?

Zukünftig könnte das System:

* Videos analysieren (nicht nur Einzelbilder)
* Verhalten über Zeit erfassen (z. B. tägliche Routinen)
* Weitere Haustiere integrieren (z. B. Hunde)
* In Zusammenarbeit mit Tierärzt*innen verbessert werden
* Eine App entwickeln mit Tagebuchfunktion für Katzenverhalten

Ich würde Unterstützung bei der Datenaufbereitung, Modelltraining und UX/UI-Design benötigen.

## Acknowledgments

* Idee inspiriert durch meine eigenen Katzen
* CC BY 2.0 Bild von [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg)
* Building AI course by Reaktor and University of Helsinki![314F89CD-0B77-4DB7-8157-A5037EFFA651](https://github.com/user-attachments/assets/941e23b6-e5e6-4395-8a30-fef1091bc98e)
