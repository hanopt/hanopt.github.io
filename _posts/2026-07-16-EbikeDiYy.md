---
layout: post
title: "E-Bike DIY"
categories: [Natur und Outdoor]
lang: de
---

# Der Kettler-Oldtimer zum selbstgebauten Elektro-Rad

## Der Kettler-Oldtimer

Angefangen hat alles mit einem Flohmarktfund: ein gebrauchtes Kettler-Fahrrad in einem wunderschönen metallic Hellblau. Schon beim ersten Probesitzen war klar, dass die Rahmengröße perfekt zu mir passt – im Vergleich zu meinem Gravel Bike sitze ich darauf deutlich aufrechter und entspannter, was gerade für längere Touren ein echter Gewinn ist.

Was mich zusätzlich überrascht hat: Obwohl das Rad schon einige Jahre auf dem Buckel hat, sind die verbauten Komponenten überraschend hochwertig. Besonders die Schutzbleche und der Gepäckträger aus Aluminium haben mich von der Stabilität her positiv überrascht – kein Wackeln, kein Rost, solide verarbeitet. Genau dieser gute Grundzustand hat mich davon überzeugt, dass sich der Umbau zum E-Bike lohnt, statt einfach ein neues Rad zu kaufen. Bei einem Selbstbau hat man volle Kontrolle über die Komponenten, welche man verbaut. Bei einem vermeintlichen Schnäppchen, welches man (vor allem online) kauft, stellt sich erst im Nachhinein heraus, wo besonders günstige und kurzlebige Komponenten eingebaut wurden.

<div style="display: flex; gap: 10px; justify-content: space-between; align-items: center;">
  <img src="/assets/img/Ebike/a-kettler.jpg" alt="Kettler-Fahrrad in metallic Hellblau" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/A-alteNabe.jpg" alt="Alte Sachs-Nabenschaltung" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/A-Trettlager.jpg" alt="Tretlager vor Motoreinbau" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
</div>
*Von links nach rechts: das Ausgangs-Kettler-Rad, die alte Sachs-Nabenschaltung, das Tretlager vor dem Motoreinbau. (Zum Vergrößern anklicken)*


## Der erste Anlauf – und die erste Hürde

Voller Vorfreude habe ich den ersten Mittelmotor eingebaut – und direkt danach kam die Ernüchterung. Beim Treten fingen die Pedale plötzlich an durchzurutschen, als würde die Kraftübertragung komplett aussetzen. Der Übeltäter war schnell gefunden: die im Rad verbaute Sachs-Nabenschaltung kam mit dem Drehmoment des Motors nicht zurecht und rutschte immer wieder durch.

Ich habe die Nabenschaltung daraufhin teilweise zerlegt, um den genauen Fehler zu finden. Trotz einiger Stunden Fummelei und Recherche blieb der Erfolg aus – die alte Sachs-Nabe war für den Einsatz mit einem Mittelmotor schlicht nicht ausgelegt. Anstatt weiter Zeit in die Fehlersuche zu stecken, habe ich mich entschieden, komplett auf ein moderneres Schaltsystem umzusteigen. 

## Bremse und Gangschaltung

Da mein Rahmen keine Aufnahme für eine Scheibenbremse besitzt, musste ich eine Lösung finden, die sowohl die Schaltung als auch die Bremse platzsparend im Hinterrad unterbringt. Herausgekommen ist folgendes Setup:

- **Hinten:** Shimano Nexus SG-C3001-7R Nabenschaltung (7-Gang, Einbaubreite 130 mm) in Kombination mit einer Shimano Rollenbremse (BR-C6000-R, Nexus Roller Brake). 
- **Vorne:** die klassische Seilzugbremse bleibt erhalten

Die Entscheidung für eine Nabenschaltung war bewusst: Ich wollte ein robustes System, bei dem – anders als bei einer Kettenschaltung – kein Kettenspringen auftritt. Gerade in Kombination mit einem Mittelmotor, der hohe Drehmomentspitzen liefert, ist das ein bekanntes Problem, das ich von vornherein umgehen wollte. Die Nabenschaltung sitzt geschützt im Inneren der Nabe, ist wartungsarm und liefert auch unter Last zuverlässig ihre Gänge.

<div style="display: flex; gap: 10px; justify-content: space-between; align-items: center;">
  <img src="/assets/img/Ebike/B-brake.jpg" alt="Shimano Rollenbremse hinten" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/B-Nabe.jpg" alt="Shimano Nexus 7-Gang-Nabenschaltung" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/B-WIP.jpg" alt="Einbau von Nabenschaltung und Bremse in Arbeit" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
</div>
*Von links nach rechts: die Shimano Rollenbremse, die neue Shimano Nexus 7-Gang-Nabenschaltung, der Einbau im Arbeitsprozess. (Zum Vergrößern anklicken)*

## Das Batterypack

Ursprünglich bin ich mit einem fertig gekauften Akkupack gefahren, das auf möglichst große Reichweite ausgelegt war (bestehend aus 90 Zellen). Praktisch verstaut habe ich es einfach in einer Fahrradtasche – eine pragmatische, aber nicht besonders elegante Lösung. Ich begann mich intensiver in die Theorie des Akku-Selbstbaus einzuarbeiten.

**Mein Zell-Layout:** eine 10S5P-Konfiguration mit Samsung-35E-Zellen (INR18650, 2900 mAh, 8,25 A). Dabei habe ich zehn Zellen in Serie und fünf Zellen parallel geschaltet, verbunden mit einem Punktschweißgerät und Nickelstreifen.
Bei der Auswahl der Li-Ion-Zellen habe ich mich etwas schwergetan, weil die Auswahl sehr groß ist. Meine Wahl fiel auf einen Zelltyp, welcher keine besonders großen Ströme (Ampere) auf einmal abgeben kann, aber dafür langlebiger ist.
Je mehr Strom auf einmal durch die Zellen fließt, desto mehr Hitze entsteht auch, wodurch die Langlebigkeit sinkt.

<div style="display: flex; gap: 10px; justify-content: space-between; align-items: center;">
  <img src="/assets/img/Ebike/C-cell-delivery.jpg" alt="Gelieferte 18650-Zellen für den Akku-Eigenbau" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/c-battery-grid.jpg" alt="Zellhalter-Grid für die 10S5P-Konfiguration" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/c-assembly.jpg" alt="Zusammenbau des Akku-Packs" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
</div>
*Von links nach rechts: die gelieferten 18650-Zellen, das Zellhalter-Grid, der fertige Zusammenbau des Akku-Packs. (Zum Vergrößern anklicken)*

Ein paar technische Eckdaten zum fertigen Pack:

- Nennspannung: 36 V
- Maximalspannung (voll geladen): 42 V (10 × 4,2 V pro Zelle)
- BMS-Limit: 30 A max. Arbeitsstrom, 20 A Dauerstrom
- Ladegerät: 2 A, max. 42 V – bewusst etwas langsamer gewählt, dafür schonender für die Zellen

Fixiert habe ich die Zellen mit zwei wabenförmigen 5×10-Zellhaltern, die ich von oben und unten aufgesetzt habe, sodass jede Zelle sicher an ihrem Platz bleibt.

Nachdem ich mit dem Punktschweißen des Akkupacks fertig war, dauerte es noch eine Woche, weil ich noch das passende Battery-Management-System (BMS) gesucht habe. Das BMS schützt das Akkupack vor Überladen und vor dem Tiefenentladen.
Auch der Bafang-Motor hat eine Schutzeinstellung, welche verhindert, dass das Akkupack komplett entladen wird. Also ein doppelter Tiefenentladeschutz. Das Gleiche gilt für das Netzteil. Es wird ebenfalls eine Überladung verhindert. Das BMS unterbricht ebenfalls den Stromkreis, sollte es zu einem Kurzschluss kommen.
Auf Englisch: Overcharge Protection, Short Circuit Protection und Over Discharge Protection.


<div style="display: flex; gap: 10px; justify-content: space-between;">
  <img src="/assets/img/Ebike/d -BMS.jpg" alt="Verbautes BMS für das Akku-Pack" style="width: 32%; object-fit: contain; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/d-BMS2.jpg" alt="BMS-Verkabelung im Detail" style="width: 32%; object-fit: contain; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/d-measurement.jpg" alt="Messung der Zellspannung mit dem Innenwiderstand-Messgerät" style="width: 32%; object-fit: contain; cursor: zoom-in;" onclick="openLightbox(this)">
</div>
*Von links nach rechts: BMS, BMS-Verkabelung, Messung der Zellwerte. (Zum Vergrößern anklicken)*


Sicherheit ist beim Eigenbau ein wichtiges Thema: Bei einem 36-V-System fließen ordentliche Ströme, und ich hatte anfangs tatsächlich ein paar unschöne Momente durch Unachtsamkeit beim Zusammenbau. Ich erzeugte versehentlich einen Kurzschluss, bei dem es ordentlich gefunkt hat. Es ging eher glimpflich aus, da durch die Hitzeentwicklung eine Lötverbindung direkt abschmolz. Die geschmolzene Lötverbindung war in diesem Fall wie eine Sicherung, welche den Stromkreis nach einer Sekunde unterbrach. Tatsächlich habe ich einen großen Anfängerfehler gemacht. Ich verwendete bei der Spannungsmessung die falsche Einstellung beim Messgerät, wodurch ein Kurzschluss durch das Gerät entstand. Aber aus Fehlern lernt man bekanntlich am besten.

Das war für mich der Anstoß, mich noch intensiver mit dem Thema Akkusicherheit auseinanderzusetzen. Unter anderem habe ich eine zusätzliche 30-A-Sicherung verbaut, die im Fall eines Kurzschlusses am Motor greift. Natürlich hilft trotzdem keine Sicherung, wenn man direkt an den Akkuzellen Spannungen misst und das Gerät falsch eingestellt ist. Man sollte beachten, in welche Buchse man beim Messgerät seine Messkabel steckt ;).

Für die Verkabelung habe ich bewusst unterschiedliche Steckertypen gewählt: einen XT60-Stecker für die Entladeseite zum Motor und einen separaten DC-Stecker zum Laden – so ist ein Vertauschen von Laden und Entladen praktisch ausgeschlossen.

Ein schöner Nebeneffekt des Eigenbaus: Das selbstgebaute Pack passt direkt in den Rahmen, statt umständlich in einer Fahrradtasche mitgeschleppt zu werden. Das Rad ist dadurch windschnittiger, aufgeräumter und insgesamt leichter.

Aktuell ist noch ein 3D-gedrucktes Battery-Case geplant und ein Heizsystem. Das Heizsystem für das Battery-Pack wird einen besonders großen Mehrwert im Winter liefern, da bei niedrigen Temperaturen die Lithium-Ionen-Chemie im Inneren der Zellen nur noch sehr langsam abläuft. Es können nur geringe Ströme erzeugt werden, und die Reichweite des E-Bikes nimmt deutlich ab.

## Beleuchtung

Das im Motor-Kit mitgelieferte Frontlicht war, ehrlich gesagt, ziemlich schwach. Also gab es an dieser Stelle ein klares Upgrade:

- **Frontlicht:** ADDVIEW Nova E100, 100 Lux, StVZO-zugelassen, IP65, 6–48 V DC
- **Rücklicht:** SYACHI E-Bike-Rücklicht mit Bremssensorik, 6–58 V, StVZO-zugelassen, IPX6 – beim Bremsen leuchtet das rote Licht spürbar heller auf

Beide Lichter habe ich zentral miteinander verbunden, sodass ich sie gemeinsam bequem über das Display des Motor-Kits steuern kann. Mein Bafang-System hat nur ein Kabel am Kabelbaum, welches für Licht vorgesehen ist, weshalb ich beide Lichter dort parallel angeschlossen habe.

<div style="display: flex; gap: 10px; justify-content: space-between; align-items: center;">
  <img src="/assets/img/Ebike/e - display.jpg" alt="Steuerung der Beleuchtung über das Display" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/e - front.jpg" alt="Frontlicht ADDVIEW Nova E100" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/e - red.jpg" alt="Rücklicht mit Bremssensorik" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
</div>
*Von links nach rechts: Steuerung über das Display, das Frontlicht, das Rücklicht mit Bremssensorik.*

## Antriebsmotor, Ritzel und E-Bike-Kette

Als Motor kommt ein Bafang BBS01B 36V250W (68–73mm) zum Einsatz. E-Bike-Motoren sind in der Regel sehr wartungsarm. Ich habe dennoch mal den Motor geöffnet und das Fett im Getriebe gewechselt. Übersetzt wird die Kraft über ein Kettenblatt mit 46 Zähnen vorne und ein Ritzel mit 18 Zähnen hinten – eine Übersetzung, die einen guten Kompromiss aus flottem Anfahren und guter Endgeschwindigkeit bietet. 

Bei der Kette bin ich bewusst nicht bei irgendeiner Standardkette geblieben, sondern habe zu einer e101-EPT-Kette gegriffen, 1/2" × 1/8", mit 112 Gliedern und einem MissingLink-Verschlussglied. Diese Kette ist speziell für E-Bikes mit Mittelmotor ausgelegt und damit deutlich besser für die höheren Kräfte und Belastungsspitzen gerüstet als eine normale Fahrradkette – ein Detail, das man leicht unterschätzt, das aber langfristig über Verschleiß und Standfestigkeit entscheidet.

<div style="display: flex; gap: 10px; justify-content: space-between; align-items: center;">
  <img src="/assets/img/Ebike/f-ritzel_vorne.jpg" alt="Kettenblatt vorne mit 46 Zähnen" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/f-18.jpg" alt="Ritzel hinten mit 18 Zähnen" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
  <img src="/assets/img/Ebike/f-chain.jpg" alt="e101 EPT E-Bike-Kette mit MissingLink" style="width: 32%; height: 220px; object-fit: cover; border-radius: 6px; cursor: zoom-in;" onclick="openLightbox(this)">
</div>
*Von links nach rechts: das Kettenblatt (47-Zähne) vorne, das 18-Zähne-Ritzel hinten, die e101 EPT E-Bike-Kette. (Zum Vergrößern anklicken)*