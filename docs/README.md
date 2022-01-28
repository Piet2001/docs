---
title: Allgemein
lang: de
sidebarDepth: 2
---

# Wiki :de: <Badge text="LSSM Stable 3.3.7"/>


## Über den LSSM

Der LSS MANAGER V3 ist eine Erweiterung für das [Leitstellenspiel.de](https://www.leitstellenspiel.de) und dessen anderssprachige Versionen.

Mit dieser Erweiterung wird ein Appstore zum Spiel hinzugefügt, welcher das Installieren von Plugins ermöglicht. Dabei sind alle Funktionen modular aufgebaut - man kann bis auf den letzten Baustein bestimmen, was alles aktiviert werden soll.

Plugins die nicht aktiviert sind, werden auch nicht geladen - das macht die Verwaltung natürlich sehr einfach und sorgt für eine bessere Performance.

::: danger
Die [Polizeiversion](https://polizei.leitstellenspiel.de) wird von uns aktuell nicht supported!
:::

## End of Life
Da der LSS-Manager V4 kurz vor dem Release steht, ist der LSS-Manager V3 nun im End of Life. Das heißt, dass es keine neuen Features mehr für den LSS-Manager V3 geben wird. Dringende Bugfixes werden aber weiterhin durchgeführt.

## Installation :inbox_tray:
Mit der Nutzung des LSSM bist du damit einverstanden, dass wir Metadaten erheben. Mehr Informationen hierzu findest du unter [Metadaten](./metadaten)

Eine Tabelle mit welchen Browsern der LSSM kompatibel ist, findest du in unseren [FAQ](./faq#in-welchen-browsern-funktioniert-der-lss-manager)

::: tip Den LSSM am Handy nutzen
Offiziell unterstützen wir keine mobile Version. Jedoch bietet der Browser Firefox auch in seiner mobilen Version die Möglichkeit, Add-Ons zu nutzen. Wir übernehmen jeddoch keine Garantie für ein ansprechendes Design, sowie die volle Funktionalität bei mobilen Browsern.

Eine offizielle Unterstützung mobiler Browser ist derzeit **nicht** geplant.
:::

### Schritt 1: Tampermonkey
Sofern du Tampermonkey in deinem Browser noch nicht installiert hast, musst du dies noch tun. Hier eine Übersicht der Links für die häufigsten Browser:

Browser|Link
-------|----
Chrome | [Download](https://chrome.google.com/webstore/detail/dhdgffkkebhmkfjojejmpbldmpobfkfo)
Firefox| [Download](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
Safari | [Download](https://safari.tampermonkey.net/tampermonkey.safariextz)
Opera  | [Download](https://addons.opera.com/en/extensions/details/tampermonkey-beta/)

Für sonstige Browser kann man Tampermonkey auf [tampermonkey.net](https://www.tampermonkey.net/) herunterladen.

::: warning
Bitte beachte, dass wir ältere Browser, sowie mobile Browser und Microsoft Edge bzw. Internet Explorer nicht offiziell unterstützen. Der Support für diese Browser ist also weder garantiert, noch wahrscheinlich.
:::

### Schritt 2: Userscript
Wenn Tampermonkey in deinem Browser erfolgreich installiert wurde klickt du [hier](https://github.com/LSS-Manager/lss-manager-v3/raw/master/lssm-v3.user.js).

### Schritt 3: Aktivieren
Folgendes ist der Indikator für einen aktiven LSS-Manager: ![LSSM-Indikator](/img/lssm_navbar.png)
Solltest du dich im Leitstellenspiel befinden, aber diesen Indikator nicht in der oberen rechten Ecke sehen, so klicke auf das Tampermonkey-Icon in deinem Browser und überprüfe, ob der Schalter für das LSS-Manager Script auf "an" gestellt ist.

Bei Problemen kannst du dich jederzeit an den [Support](/support) wenden.
