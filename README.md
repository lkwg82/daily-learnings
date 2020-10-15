# daily-learnings


#### 2020.10.14 - Keine Oracle Software einsetzen

Heute mit APEX und dem aktivieren des REST Listeners zu tun gehabt. Ein Krampf dazu sinnvolle Dokumnetation zu finden.

#### 2020.10.13 - Schlechte UI frustriert

Heute mit IBM Netcool versucht unser Monitoring zu integrieren. 
Die UI ist gelinde gesagt etwas aus der Zeit gefallen.

#### 2020.10.09 - Akzeptanzkriterien im Blick behalten

Ich habe die Akzeptanzkriterien nicht im Blick gehabt und zuviel implementiert. Habe es dabei etwas 
Mocking in Python geübt, den Code allerdings wieder weggeworfen.

#### 2020.10.07 - Viele Unterbrechungen kürzen die Zeit überproportional

Heute einen halben Tag für eine Sache Zeit gehabt. Dabei drei Unterbrechungen, so dass es sich im 
Endeffekt wie 2 Stunden angefühlt hat.

#### 2020.10.06 - Fallbacks sind nicht immer gut

Wir haben eine Logik für die Adressung von KMS Keys implementiert. Diese fällt 
auf einen Generalschlüssel zurück, wenn kein passender Schlüssel gefunden wird.
Zudem ist die Verwendung und Erstellung eben dieser in verschiedenen Repos getrennt umgesetzt. 
Infolgedessen wird nun nach den ersten initial erstellten Schlüsseln, nur noch
überall der Generalschlüssel verwendet.

#### 2020.10.05 - Timeboxen beim Debuggen machen Sinn

Habe zu lange an einem Weg festgehalten, statt eine Heuristik in Betracht zu ziehen.

#### 2020.10.02 - Netzwerksecurity mit Proxies ist ein "Heidenspaß"

Peu à peu Domain um Domain freigeschaltet, um renovatebot ohne Fehler zum Laufen zu bekommen. 

#### 2020.10.01 - Aufräumen und Vorarbeiten abschließen fühlt sich gut an

Haben heute eine Planskizze für ein Projekt abgehakt und einen wichtigen Meilenstein genommen.
Unbekannte Ideen, haben wir gelöscht und verworfen und nicht ins Backlog gepackt. Alle waren einverstanden.
"Lean" kommt langsam.
 
#### 2020.09.29 - TDD macht den Fortschritt stabil

Wieder erfahren, dass TDD den erreichten Fortschritt bei einer Implementierung sehr gut sichert. Zumal, wenn spät noch 
delikate Fehler erkannt werden. Somit ist das Refaktoring im Nu erledigt ;).

#### 2020.09.28 - Es ist nicht schlimm wenn ein PoC nicht gelingt

Wir haben letzte Woche zwei Tage einen PoC gemacht. Diese Umsetzung hat sich als nicht nachhaltig erwiesen. Dann machen wir 
heute noch einen. Waren ja nur zwei Tage. Zwei Tages Experimente. 

#### 2020.09.24 - Murphies Law - unbefriedigender Abschluss

Ich wußte, dass wenn ich bis 16 Uhr mit meinem Skript nicht fertig bin, dass
ich dann mit dem harten Termin um 18:00 höchstwahrscheinlich bei dem kleinsten
Problem nicht fertig werde und unbefriedigt abbrechen muss. War leider genau so. 

#### 2020.09.23 - Vorstellung PoC

Eine geplante Vorstellung der Arbeitsergebnisse bringt eine gewisse Verbindlichkeit. 

#### 2020.09.22 - Remote Mobprogramming

Stündliches rotieren hat alle bei Laune gehalten. Kann wiederholt werden.

#### 2020.09.21 - Effektives Taskbreakdown vor PoC

Wir haben vor einem 2 Tags PoC einen Taskbreakdown gemacht und 
etliche Lösungsvarianten angeschaut. War sehr effektiv.
 
#### 2020.09.18 - An automatisierten Tests führt letztendlich nichts vorbei

Ich habe versucht mir einzureden, die Tests später machen zu können. Geht aber dann gibt es eben 
öfter mal dumme blöde Fehler, die dann peinlich sind. 

#### 2020.09.17 - Nicht nutzbare CMK erzeugen ein Access Denied in S3

#### 2020.09.16 - KMS Schlüssel brauchen auch Berechtigungen

#### 2020.09.15 - Codegenerierung für Permissionmatrix

Ein kompliziertes Berechtigungsschema abzugleichen und zu dokumentieren ist schwierig.
Warum also nicht, aus der Dokumentation die Implementierung generieren?

Mal sehen, ob es sich als Schnapsidee herausstellt. 
 
#### 2020.09.14 - Incidentprozess 

Was gut war, wird gern wiederholt.

#### 2020.09.11 - renovatebot nice

Maintenance zu automatisieren fühlt sich gut an - erste Schritte.

#### 2020.09.10 - AWS Berechtigungen sind tricky

IAM Policy und Bucket Policy debugging ist schwer, zumal noch winzige Asynchronitäten dazu kommen.

#### 2020.09.09 - Pre-commit hooks sind gut

Die Feedbackschleife wieder etwas kleiner zu machen, macht produktiv.

#### 2020.09.08 - Ohne Backup fühlt sich im Fehlerfall doof an

Heute aus Versehen einige ungesicherte Arbeitsergebnisse von zwei Tagen gelöscht. Kein Backup --> kein Fallback.

#### 2020.09.04 - Gutes Tooling macht produktiv

Heute Pipeship mit der Auslieferung in die zentrale Dockerregistry ausprobiert und eingesetzt. Sehr smooth.

#### 2020.09.01 - Unsicherheit als verstecktes Hemmnis

Ich erkenne mehr und mehr, dass Überforderung in Situationen 
deutlich - auch für mich selbst - von großer Unsicherheit begleitet wird.
Gedanke: Eventuell kann über eine Selbstbefragung zu Selbstsicherheit Aufschluss geben?

#### 2020.08.28 - Oracle DB + APEX ist eine Bitch

Ich bin frustriert, wenn ich 1h für eine Iteration warten muss (Aufsetzen einer Oracle DB in AWS). 

#### 2020.08.27 - korrigierendes Feedback geben ist schwer

Habe heute Feedback zu gestrigem Meeting gegeben. Ich hätte es auch besser vorbereiten sollen. Wie einen Vortrag.

#### 2020.08.26 - Meetings brauchen Vorbereitung

Heute an einem Meeting teilgenommen, bei dem offensichtlich kein Gedanke an das Publikum verschwendet wurde.
Genauso hat es sich angefühlt: ohne roten Faden, ein Sammelsurium an Details.
Bin frustriert raus.  
 
#### 2020.08.25 - Renovatebot 

Heute den Renovatebot und einen Teil der Automatisierung der Wartung kennengelernt, 
die dadurch abgenommen werden kann. Cool. 

#### 2020.08.24 - Pulumi gibt es neben Terraform auch

Terraform als IaC Tool ist beliebt, allerdings Pulumi hat auch Potential.

#### 2020.08.21 - Remote Meetings müssen gelernt sein

In Meetings braucht es Mittel zur Fokusierung und Ergebnissicherung, 
sonst dreht sich alles im Kreis.

#### 2020.08.20 - Taskbreakdown und Storysplitting hilft bei Iterationen

Es hilft Ergebnisse zu kommunizieren, wenn Aufgaben nicht zu generisch sind und auch 
den aktuellen Stand abbilden. Somit ist auch ein Fokuswechsel möglich, auch wenn nicht wünschenswert. 

#### 2020.08.19 - Dysfunktionale Kundenbeziehung wirkt sehr stark

In einem Gespräch wurde klar, dass der Kunde so stark in das operative Arbeit drängt, dass es
sich wie Mikromanagement anfühlt. 
 
#### 2020.08.18 - In Terraform kann ich subnet-ids abrufen

Ich hatte erst Konstanten für die subnet ids im Code. Wurde daraufhin gewiesen, das vpc und die zugehörigen 
subnet ids abzurufen. Klappt wunderbar.  

#### 2020.08.17 - Loslassen und Konflikte ungelöst lassen ist nicht schlimm

Der Abschied eines Teammitgliedes ist immer etwas schmerzhaft. Allerdings enden damit auch 
Konflikte die sehr stark aus der Persönlichkeit des Mitgliedes getrieben wurden. Das ist auf der einen
Seite unbefriedigend, weil ungelöst und damit unfertig, auf der anderen Seite aber auch
befreiend, weil sie einfach "aufhören".  

#### 2020.08.14 - AWS Cloudwatch Loggroups werden von Lambda per Konvention benutzt 

Lambda Funktionen können nicht konfiguriert werden, gewisse Loggroups zu benutzen, sondern
 sie loggen (wenn sie dürfen) nach `/aws/lambda/<functionName>`.

#### 2020.08.13 - Verbindung zwischen AWS SNS und AWs Lambda

Die Verbindung zwischen sns topics und lambda ist eine subscription. War mir neu.

#### 2020.08.12 - Geringer Wortschatz in puncto "Bedürfnisse"

Bei einem Workshop zu "Gewaltfreier Kommunikation" habe ich in einer Paarübung gelernt, dass ich schlecht Bedürfnisse 
benennen kann. Mir fehlt teilweise Wortschatz um Bedürfnisse eigene, wie auch die anderer auszudrücken.

#### 2020.08.11 - Diskussion in der Zieldefinition aushalten

Als Gruppe haben wir das Ziel und den Rahmen eines Vorhabens ausdiskutiert. Obwohl es 
nach einer Stunde zu kippen drohte, weil einer der Teilnehmer ungeduldig wurden, haben wir weiter gemacht.
Zum Ende sagte genau dieser Teilnehmer: "Jetzt verstehe ich auch warum es vorhin unklar war.". Es hat sich gelohnt.

#### 2020.08.10 - Git debugging

Es bestand der Verdacht, dass git squash merges unbeabsichtigt Änderungen überschreiben. 
Nach zwei Stunden Fehlersuche, war ich mir sicher, dass ein Merge eines alten Branches Ursache war.
 