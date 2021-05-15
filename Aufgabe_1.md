# Datenintensive und datenfokusierte Aktivitäten im Zentralen Aktenmagazin und Historischen Archiv der Deutschen Welle
   
Das Zentrale Aktenmagazin (ZAM) verwaltet als Altregistratur und Zwischenarchiv die geschlossenen und im täglichen Betrieb nicht mehr benötigten Akten der Deutschen Welle. Diese werden nach Ablauf der Aufbewahrungsfrist bewertet und falls archivierungswürdig an das Bundesarchiv oder das Historische Archiv der Deutschen Welle abgegeben. Das Historische Archiv sammelt, erfasst und bewahrt textbasierte, audiovisuelle und bildliche Zeugnisse wie auch Objekte zur Unternehmensgeschichte des Rundfunksenders.

**Inhaltsverzeichnis**

1. [Zentrales Aktenmagazin](#a1)  
1.1. [Umstellung auf digitale Verfahren](#a1.1)    
1.2. [Einsatzgebiet Aussonderung](#a1.2)  
1.3. [Einsatzgebiet Digitales Schriftgut](#a1.3)  
2. [Historisches Archiv](#a2)  
2.1. [Einsatzgebiet Metadatenimport aus Bestandsübersichten](#a2.1)  
2.2. [Einsatzgebiet Digitale Langzeitarchivierung](#a2.2)  
2.2. [Einsatzgebiet Aktualisierung des iServers](#a2.3)  
3. [Blick ins Medienarchiv](#a3)  
4. [Fazit](#a4)  
5. [Bildnachweise](#a5)  
6. [Fußnoten](#a6)  

## Zentrales Aktenmagazin<a id=a1></a> 
#### Umstellung auf digitale Verfahren<a id=a1.1></a>
Im ZAM wurden in den letzten fünf Jahren bereits viele Prozesse digitalisiert. Aktenabgaben erfolgten zuvor über ausgedruckte und zumeist handschriftlich ausgefüllte Word-Tabellen, welche Mitarbeitende mittels Hauspost an das ZAM schickten. Nach der Einarbeitung im ZAM wurden diese Listen um Zugangsnumnmern und Standortangaben ergänzt, kopiert, zurückgeschickt sowie das Original in der Eingangsdokumentation abgeheftet. Auch die Bearbeitung von Ausleihen erfolgte händisch auf vorgedruckten Ausleihformularen. Im Rahmen der jährlichen Aussonderung wurden Abgabelisten erneut kopiert und per Hauspost an die zuständigen Stellen verschickt.

Inzwischen werden abzugebende Akten von den registraturbildenden Stellen über ein *Formular in IBM Notes* erfasst. Auch die Beantragung der Abholung und die Weiterbearbeitung der physischen Akten erfolgt darüber. Metadaten wie Zugangsnummer, Enthält- und Darin-Vermerke, Archivwürdigkeit und Standort werden ergänzt. Die abgebenden Stellen können jederzeit den aktuellen Erfassungsstand einsehen und erhalten über IBM Notes eine Übersicht und Recherchemöglichkeit über ihre gesamten im ZAM befindlichen Akten. Ebenso werden die Ausleihen wie späterten Kassationsabfragen über IBM Notes abgewickelt. Das Verfahren wurde mit der Einführung vereinfacht, nachhaltiger und transparenter.
#### Einsatzgebiet Aktenaussonderung<a id=a1.2></a>
Eine Ausweitung der IT-gestützten Verfahren ist für den Altbestand denkbar. Die im physischen Eingangsbuch verzeichneten Aktenzugänge wurden bereits in eine Exceltabelle übertragen. Darauf aufbauend entstand eine Übersicht über die von der jährlichen Aussonderung betroffenen Akten. Aus diesen Listen könnten wiederum einzelne Übersichten pro Zuständigkeitsbereich automatisiert generiert werden. Im Vorfeld benötigt es dafür eine Definition bzw. ein Mapping, welche Provenienzen welcher aktuellen Abteilung zuzuordnen sind.<sup>[1](#FN1)</sup> Auch ein automatisiertes Befüllen der Anschreiben durch Einfügen der zuständigen Organisationseinheit und aktueller Leitungsperson mittels Abgleich über *SAP* und die Anreicherung der entsprechenden Einzelübersichten könnten den Prozess erleichtern und weniger fehleranfällig machen.<sup>[2](#FN2)</sup>

![Aussonderungsliste](https://pad.gwdg.de/uploads/upload_882afbec1dc3899a582af893889fc5a8.png "Aussonderungsliste für Akten mit im Jahr 2020 abgelaufener Aufbewahrungsfrist")
Aussonderungsliste der Akten mit im Jahr 2020 abgelaufener Aufbewahrungsfrist ([Quelle](#b1))

#### Einsatzgebiet Digitales Schriftgut<a id=a1.3></a>
Ein zukünftiges Einsatzgebiet für Software stellt das Records Management digitaler Unterlagen dar. Es beginnt bei der Analyse von Daten, Metadaten und Speicherstrukturen um einen Überblick zu erhalten, wie das Nutzungs- und Speicherverhalten in den verschiendenen Abteilungen gelebt wird. Um Dokumenttypen, Ablagestrukturen und verschiendene genutzte Tools zu ergründen kann der Einsatz von Software wie *[TreeSize](https://www.jam-software.de/treesize)* nützlich sein. Anhand der gewonnenen Erkenntnisse können Empfehlungen für die digitale Schriftgutverwaltung getätigt werden. Mithilfe der Analyse kann ebenfalls eine systematische manuelle intellektuelle Bewertung der Dokumente erfolgen. Die Ergebnisse der Ablageauswertung können außerdem Basis für die Erstellung eines bisher nicht vorhandenen Aktenplans sein. Dieser wiederum ist eine wichtige Komponente für die Einführung eines auf das Unternehmen zugeschnittenen *Dokumentenmanagementsystems*.

![Ablagestruktur](https://pad.gwdg.de/uploads/upload_2dd087c554967e18e781e52d2094732e.png "Ablagestruktur eines Abteilungslaufwerks mit Mixstruktur aus Prozess-, Funktions- und Objektorientierung, leeren Ordnern sowie nicht eindeutigen/trennscharfen Ordnerbezeichnungen")
Ablagestruktur eines Abteilungslaufwerks mit Mixstruktur aus Prozess-, Funktions- und Objektorientierung, leeren Ordnern sowie nicht eindeutigen/trennscharfen Ordnerbezeichnungen ([Quelle](#b2))

## Historisches Archiv<a id=a2></a>
#### Einsatzgebiet Metadatenimport aus Bestandsübersichten<a id=a2.1></a>
Viele Bestandsübersichten im Historischen Archiv liegen in *Worddateien* und *Exceltabellen* vor. Zumeist wurden diese als überschaubare Arbeitspakete im Rahmen von Praktikas oder Ausbildungsstagen der Fachangestellten für Medien- und Informationsdienste erstellt. Solche Bestandsübersichten ermöglichen ein eigenständiges Arbeiten ohne dass Zugang zu, Installation von sowie eine intensive Einarbeitung in die Datenbanken der Software *Faust* nötig sind. Es wäre sinnvoll die in den Listen aufgeführten Informationen direkt in Faust aufzunehmen. Dabei kann statt einer manuellen Übertragung ein Datenimport mittels Faust-Import Formates zum Einsatz kommen. Der zeitliche Aufwand sollte sich so deutlich verringern und das Verfahren weniger fehleranfällig als die Übertragung der Daten per Copy and Paste sein. Von Vorteil ist dabei, dass bei der Bestandserfassung keine inhaltliche Erschließung stattfand und die händisch eingegebenen Daten folglich nicht mit dem gebundenen Vokabular des Thesaurus gemappt werden müssen.

![Bestandsübersichten](https://pad.gwdg.de/uploads/upload_95068ac9ab16c9ebe826db544527bcc5.png "Übersicht über den Bestand der Gästebücher in einer Exceltabelle")
Übersicht über den Bestand der Gästebücher in einer Exceltabelle ([Quelle](#b3))

#### Einsatzgebiet Digitale Langzeitarchivierung<a id=a2.2></a>
Im Historischen Archiv existiert bisher kein fester Wortkflow für die Langzeitarchivierung von digitalem Schriftgut. Relevante Dokumente werden gesichert, indem sie aus dem *Intranet* oder *Sharepoint* heruntergeladen und auf dem Abteilungslaufwerk in einem geschützten Bereich gespeichert werden. Die Texte der Intranetmeldungen, die Basis für Einträge in die Unternehmenschronik sind, wurden als historische Quellen in ein Worddokument eingefügt und als .doc bzw. .docx abgelegt. Durchaus geeigneter für die Digitale Langzeitarchivierung ist das Dateiformat PDF/A. Neue Intranetmeldungen werden u.a. um nachträgliche Änderungen am Inhalt auszuschließen als solches gesichert. Um alte Word-Dokumente aber auch neue digitale Dokumente wie Personalberichte oder Aufgabenplanung zu sichern, erscheint der Einsatz eines Konverters oder Parsers lohnenswert.

#### Einsatzgebiet Aktualisierung des iServers<a id=a2.3></a>
Die Datenbanken des Historischen Archivs sind für Mitarbeitende über den Faust iServer einsehbar. Über einen Link im Intranet können sie durch Suchmasken und Indexlisten den Bestand durchsuchen. Neu angelegte Datensätze sind dort ohne zeitlichen Verzug einsehbar. Änderungen am kontrollierten Vokabular werden hingegen nicht übermittelt. Hierfür ist es nötig, dass das jeweilige Projekt auf dem iServer aktualisiert oder neu gestartet wird. Das wiederum setzt das Aufrufen des Servers über den Explorer, das Einloggen mit Adminkennung, die Auswahl des Projektes und die manuelle Aktualisierung voraus. Ein zwar nicht aufwendiger aber durchaus zeitraubender Vorgang. Um diesen manuellen Prozess im täglichen Arbeitsprozess auszusparen wurde daher ein Skript geschrieben, welches den iServer täglich um 23 Uhr neu startet. Aktive Sitzungen durch Nutzende werden dafür beendet. Da die Nutzung nachts aber nahezu ausgeschlossen werden kann, ist dies weniger problematisch als ein regelmäßiges manuelles Aktualisieren während der gewöhnlichen Bürozeiten.

## Blick ins Medienarchiv<a id=a3></a>
Archivierungen von Manuskripten, Audio- und Videoinhalten werden in den entsprechenden Produktionssystemen ausgelöst. Über Schnittstellen gelangen die Inhalte oder Essenzen mit den zugehörigen Metadaten automatisiert in das jeweilige Archivsystem. Teilweise werden die Datensätze mit weiteren in SAP hinterlegte Metadaten angereichert. Noch erfolgen Formalerfassung und Inhaltliche Erschließung intellektuell und händisch. Im Bereich der textbasieren Presse und bei Manuskripten kommt vorab ein Textminingverfahren zum Einsatz. Für die Indexierung werden u.a. Klassen und Deskriptoren der Normdatenbank vorgeschlagen. Dokumentar:innen können die Vorschläge übernehmen, ändern oder löschen. Ebenso laufen bereits Projekte zum Audio- und Videomining.

Mit *medas*<sup>[3](#FN3)</sup> werden Inhalte und KI-basierte Erschließungsdaten zukünftig medien- und (ARD-weit) institutionsübergreifend über eine zentrale Plattform durchsuchbar und verarbeitbar. Über das Setzen von Markierungen können so beispielsweise Ausschnitte von Videos in einen virtuelle Sammelkorb gelegt und anderen zur Weiterverwendung im Produktionssystem zur Verfügung estellt werden. Archivinhalte werden durch medas nicht nur sichtbarer und leichter zugänglich für Journalist:innen, auch der archivinterne Workflow für Auftragsrecherchen wird dadurch in vielerlei Hinsicht optimiert. Auch das Historische Archiv kann von dieser Entwicklung profitieren, da unternehmensgeschichtlich relevante Manuskripte sowie entsprechendes Audio- und Videomaterial in den einzelnen Archivdatenbanken vorgehalten werden, aus den Faust-Datenbanken des Historischen Archivs von Personen, Organisationseinheiten und Chronikereignissen jeweils nur auf entsprechendes Archvigut referenziert wird.

## Fazit<a id=a4></a>
Im Zentralen Aktenmagazin und im Historischen Archiv der Deutschen Welle existieren zahlreiche datenfokussierte Prozesse. Von der Sichtung über die Bewertung, Übernahme, Anreicherung, Erfassung und Erschließung über die Archivierung selbst bis hin zu Information Retrieval und erneuter Nutzbarmachung bzw. Übergabe an das Bundesarchiv muss der Umgang mit Daten und Metadaten genau bedacht werden. So sind physische Akten ohne dokumentierter Zugangsnummer und Standortangabe in den Magazinräumen schlichtweg nicht mehr auffindbar. Im Bereich der digitalen Unterlagen verlieren diese bereits nach ihrer Entstehung ihren Wert, wenn diese nicht bereits mit einem durchdachten Metadatenmanagement einher geht. Dateien wie Entwurf.doc, Entwurf-Ergänzung-IB.doc, Entwurf-Finish.doc, Entwurf-letzte-Fassung.doc und Entwurf-2021-05-15.doc verstreut auf verschiedene Ordner und Laufwerke machen jegliche Records Management Bestrebungen unmöglich. Daher sind neben einfachen Workflows und klaren Regeln auch maschinelle und softwaregestützte Verfahren wichtig und notwendig. Einsatzgebiete finden sich wie oben erläutert in nahezu allen Arbeitsbereichen von kleinen einfachen Implementierungen zur Arbeitserleichterung bis hin zum Rückgriff auf umfassender Softwarelösungen.
 
## Bildnachweise<a id=a5></a>
- Aussonderungsliste: Screenshot, Z:\Information und Archive\5 Ressort Bestand-Service\5. Zentrales Aktenmagazin_Historisches Archiv\Zentrales Aktenmagazin\Kassation\Übersicht Aussonderung Zukunft.xls<a id="b1"></a>
- Ablagestruktur: Screenshot, Z:\Information und Archive\5 Ressort Bestand-Service\5. Zentrales Aktenmagazin_Historisches Archiv\Arbeitsfassung Lageplan Magazinräume<a id="b2"></a>
- Bestandsübersichten: Screenshot, Z:\Information und Archive\5 Ressort Bestand-Service\5. Zentrales Aktenmagazin_Historisches Archiv\Historisches Archiv\Bestandsübersichten\Bestand_Gästebücher.xls<a id="b3"></a>

## Fußnoten<a id=a6></a>
<a name="FN1">1</a>: Die sich stetig wandelnde Unternehmensstruktur und Umbenennung von Organisationseinheiten stellt die größte Herausforderung im ZAM dar. Da die Akten vom ZAM nur verwaltet werden, benötigt die Aussonderung (d.h. Kassation oder Übernahme ins Archiv und ein damit einhergehender Eigentumswechsel) die Einwilligung der registraturbildenden Stelle bzw. ihres Funktionsnachfolgers. Nach bis zu dreißigjähriger Aufbewahrungsfrist kann dies mit einiger Recherchearbeit verbunden sein.  

<a name="FN2">2</a>: Änderungen von Intranetseiten der Abteilungen können bei personellen Wechsel zeitverzögert stattfinden. Die Personen- und Funktionspflege in SAP findet hingegen zuverlässig statt, weil die dort hinterlegten Daten auch für Gehaltszahlungen und Etatberechnungen genutzt werden.  

<a name="FN3">3</a>: Die Abkürzung *medas* steht für Mediendatensystem. Das [ARD Projekt](https://convit.de/projekte/ard-media-data-hub) zielt auf eine zentrale ARD-Metadatenplattform unter Einsatz aller ARD-Mining-Systeme.
