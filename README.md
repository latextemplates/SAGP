SAGP
====

Inoffizielle LaTeX-Vorlage für Bachelor- und Master-Arbeiten der Fakultät "Soziale Arbeit, Gesundheit und Pflege" der HS-Esslingen, Deutschland.
Die Vorlage wurde nach bestem Wissen und Gewissen erstellt. Sie folgt den Formvorschriften Anfang 2012 an der Fakultät SAGP.
Anmerkungen und Änderungswünsche werden gerne entgegen genommen.

Die Vorlage kann durch den Klick auf [ZIP](https://github.com/latextemplates/SAGP/zipball/master) heruntergeladen werden.

Als Programme werden "lualatex" und "biber" benötigt. Diese sind bei [MiKTeX](http://miktex.org/) dabei.

Zum **Editieren** gibt es verschiedene Editoren. [TeXstudio](http://texstudio.sourceforge.net/) ist gut. [TeXnicCenter](http://www.texniccenter.org/) ist OK, wenn man die neueste Alpha installiert. Erfolge wurden auch bei [TeXlipse](http://texlipse.sourceforge.net/) vermeldet.

Als **Literaturverwaltung** wird [JabRef](http://jabref.sourceforge.net/) empfohlen.

Nach der Installation kann man unter C:\MiKTeX29\doc\latex die Dokumentation zu diversen Paketen finden.

Installation
============

MiKTeX
------
- http://miktex.org/
- Download der neuesten Version. Derzeit MiKTeX 2.9: http://miktex.org/2.9/setup
- "Basic MiKTeX 2.9" Installer herunterladen und starten
- Lizenzvereinbarung aktzeptieren, "Next >" klicken
- Unbedingt "Only for: <Benutzername>" statt "Anyone who uses this computer (all users)" auswählen. "Next >" klicken
- Installationsverzeichnis "C:\MiKTeX29". "Next >" klicken
- "Preferred paper: A4" und "Install missing packages on the fly: Yes". "Next >" klicken
- "Start" klicken
- Abwarten
- Am Ende "Close" klicken

TeXstudio
---------
- http://texstudio.sourceforge.net/
- "Download" klicken
- Herunterladen und installieren


JabRef
------
- Java installieren, falls noch nicht installiert
 - http://java.com/de/
 - "Kostenloser Java-Download" klicken
 - "Einverstanden und mit kostenlosem Download beginnen" klicken
 - Das heruntergeladene Programm installieren
- Unter http://jabref.sourceforge.net/ "Download latest stable version" klicken.
- JabRef-...-setup.exe herunterladen
- JabRef-...-setup.exe starten und JabRef installieren



Verwendung
==========
- Im LaTeX-Editor "lualatex" als latex-Programm konfigurieren


"Händisch" das pdf erstellen
----------------------------
Voraussetzung: `C:\MiKTeX29\miktex\bin\` ist im Pfad

- `lualatex ausarbeitung`
- `biber ausarbeitung`
- `lualatex ausarbeitung`
- `lualatex ausarbeitung`
