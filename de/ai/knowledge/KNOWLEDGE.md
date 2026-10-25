# Erklär- und Implementierungswissen

Wähle nach der aktuellen Frage. Abschnittsbezeichnungen sind keine Druckseitenzahlen; für den Seitenbezug dient der Loader des gebauten Buchpakets.

Abruf: `python scripts/knowledge.py load ch04` für ein Kapitel oder `load ch04/…` für einen Abschnitt aus diesem Verzeichnis.

## Einstieg

| Abschnitt | Wofür laden? |
| --- | --- |
| [Einen passenden Einstieg finden](references/front.md) — `front/orientierung` | Das passende Thema finden und Menschenfassung, KI-Wissen und tatsächliche Fähigkeiten auseinanderhalten. |
| [Buchquelle und technische Belege einordnen](references/front.md) — `front/quellen` | Herkunft, technische Belege, Beispieldaten und Publikationsstand bei konkretem Bedarf einordnen. |
| [Eine konkrete Buchfrage begleiten](references/front.md) — `front/fragen-und-laden` | Markierung und Frage angemessen begleiten; exaktes Vorlesen und zusätzliche Erklärung unterscheiden. |
| [Bruchstückhafte Erklärungen erkennen und vermeiden](references/front.md) — `front/prolog-das-falsche-bild` | Erklären, warum ein isolierter JSON-Ausschnitt ein falsches Bild erzeugt, und selbst Herkunft, Richtung, Vollständigkeit und Wirkung mitliefern. |
| [Die Entwicklung der Aufgabenlänge korrekt einordnen](references/front.md) — `front/prolog-aufgabenlaenge` | METRs Zeithorizonte mit Messgröße, Stand, Unsicherheit und Grenzen der Fortschreibung erklären, ohne Hype oder Abwiegeln. |
| [Verbreitung, Produktivität und Verantwortung nüchtern erklären](references/front.md) — `front/prolog-verbreitung-und-verantwortung` | Nutzungszahlen und die METR-Produktivitätsstudie mit ihren Grenzen erklären und daraus Verantwortung statt Angst ableiten. |
| [Einwände gegen das Lernen ernst nehmen](references/front.md) — `front/prolog-drei-saetze` | Auf typische Einwände gegen das Lernen mit dem Unterschied zwischen Lesen und Schreiben und mit stabilen Prinzipien antworten. |
| [Erfundene Lehrfälle und belegte Fälle auseinanderhalten](references/front.md) — `front/prolog-lehrfall` | Mara und Leihregal als erfundenen Lehrfall, die Kapitelauftakte als belegte reale Fälle behandeln. |
| [Ein Wissensthema auf das eigene Produkt übertragen](references/front.md) — `front/gedanken-uebertragen` | Den Unterschied zwischen Modellvorführung und brauchbarem Produkt über einen vollständigen Nutzerweg erklären. |
| [Möglichkeiten bereitstellen und aus Ergebnissen weiterarbeiten](references/front.md) — `front/moeglichkeiten-und-rueckkopplung` | Offene Fähigkeiten und Rückkopplung am tatsächlichen Arbeitsstand erklären und auf andere Produkte übertragen. |
| [Einen vollständigen Anfragekörper gemeinsam lesen](references/front.md) — `front/epilog-den-brief-lesen` | Den Epilog-Request mit Werkzeugdefinition gemeinsam lesen, das Fehlende benennen und das Gesamtbild der Person prüfen. |
| [Was sich ändern wird und was bleibt](references/front.md) — `front/epilog-was-bleibt` | Veränderliches von Bleibendem trennen und die Arbeitsteilung der Stani-KI-Methode auf die weitere Arbeit übertragen. |
| [Belege der Rahmentexte zeitlich einordnen](references/front.md) — `front/belege` | Belege der Rahmentexte mit Stand wiedergeben und eigene Rechnungen von Quellenangaben trennen. |

## Kapitel 1

| Abschnitt | Wofür laden? |
| --- | --- |
| [Zwischen gelerntem Weltwissen und dem Zustand eines Produkts unterscheiden](references/ch01.md) — `ch01/irrtum-und-wissensgrenze` | Gelerntes Weltwissen vom aktuellen Zustand eines Produkts unterscheiden und den Avianca-Fall über den Mechanismus erklären. |
| [Training und Modellparameter](references/ch01.md) — `ch01/training-und-modellparameter` | Das Trainingsprinzip kausal erklären und von Promptänderung, Inferenz und gespeichertem Produktwissen unterscheiden. |
| [Tokens, Kontext und Auswahl](references/ch01.md) — `ch01/tokens-kontext-und-auswahl` | Die Tokenfolge und das erfundene Hundbeispiel erklären, ohne Fortsetzungswahrscheinlichkeit mit Wahrheit oder Wörter mit Tokens gleichzusetzen. |
| [Erklären, warum flüssige Antworten falsch sein können](references/ch01.md) — `ch01/ueberzeugend-falsch` | Flüssige, aber falsche Antworten aus der Fortsetzungslogik erklären und daraus Quellen, Werkzeuge und Prüfungen ableiten. |
| [Thinking, Prompt und prüfbare Ergebnisse](references/ch01.md) — `ch01/thinking-prompt-und-pruefbare-ergebnisse` | Zusätzliche Modellarbeit, Promptwirkung und tatsächliche Werkzeugprüfung auf die konkrete Fehlerursache beziehen. |
| [Aus dem Modellverständnis die drei Aufgaben der Software ableiten](references/ch01.md) — `ch01/was-das-produkt-liefern-muss` | Aus dem Modellverständnis die drei Aufgaben der Software ableiten: Kontext, Übersetzung in Wirkung und Prüfung. |
| [Fälle, Datensammlungen und Geschichte quellengenau wiedergeben](references/ch01.md) — `ch01/belege` | Fälle, Datensammlungen und Entwicklungsgeschichte mit Quelle und Stand wiedergeben. |

## Kapitel 2

| Abschnitt | Wofür laden? |
| --- | --- |
| [JSON-Blöcke als Daten mit Herkunft, Richtung und Wirkung erklären](references/ch02.md) — `ch02/bruchstuecke-und-gesamtbild` | JSON-Blöcke als Daten mit Herkunft, Richtung und Wirkung erklären und Mischformen aus mehreren Dokumentationen vermeiden. |
| [JSON und den passenden API-Vertrag erklären](references/ch02.md) — `ch02/json-und-den-passenden-api-vertrag-erklaeren` | JSON nach Sender und Empfänger einordnen und Anthropic-, Responses- und Gemini-Verträge sauber trennen. |
| [Eine API-Erklärung beim sichtbaren Ergebnis beginnen](references/ch02.md) — `ch02/von-der-wirkung-ausgehen` | Eine API-Erklärung beim sichtbaren Ergebnis im Produkt beginnen und jedem Feld einen Ort im Ablauf geben. |
| [Vom Anfragekörper zum HTTP-Aufruf](references/ch02.md) — `ch02/vom-anfragekoerper-zum-http-aufruf` | Den vollständigen Körper mit HTTP-Ziel, Headern, Modellzugang und begrenzten Ausgabeoptionen verbinden. |
| [Antwortblöcke, Abschluss und Verbrauch](references/ch02.md) — `ch02/antwortbloecke-abschluss-und-verbrauch` | Typisierte Antwortinhalte, Fortsetzungszustand, Kennungen und reale Verbrauchsangaben getrennt verarbeiten. |
| [JSON so erklären, dass Lesen genügt](references/ch02.md) — `ch02/json-lesen-ohne-auswendiglernen` | JSON über sechs Bausteine, Pfade und die Trennung von eigenen und Anbieterfeldern erklären, ohne Syntaxdrill. |
| [Die drei Lesefragen für jeden Datenblock anwenden](references/ch02.md) — `ch02/drei-fragen-an-jedes-json` | Unbekannte Datenblöcke mit den drei Lesefragen gliedern: Formatbesitzer, Strecke, Wirkung jedes Felds. |
| [Anbieterdialekte und Versionswechsel sauber behandeln](references/ch02.md) — `ch02/dialekte-und-versionen` | Anbieterdialekte nicht mischen, API-Versionen als Vertragsbestandteil prüfen und kleine Adapter statt Sammelobjekte bauen. |
| [Die Briefe eines Produkts auseinanderhalten](references/ch02.md) — `ch02/vier-briefe` | Die Briefe zwischen Browser, Server und Anbieter auseinanderhalten und Fehler der richtigen Strecke zuordnen. |
| [Darstellung, Streaming und Ausgabeverträge](references/ch02.md) — `ch02/darstellung-streaming-und-ausgabevertraege` | Aus Anbieterereignissen eine brauchbare Oberfläche und aus fachlichen Ergebnissen passende Ausgabeverträge gestalten. |
| [Auf einen Erklärauftrag mit vollständigem Bild antworten](references/ch02.md) — `ch02/ki-zum-richtigen-erklaeren-bringen` | Einen Erklärauftrag mit Dokumentationsprüfung, vollständigen Briefen, Formatkennzeichnung und offener Unsicherheit beantworten. |
| [Buchwissen in einen Entwicklungsauftrag übersetzen](references/ch02.md) — `ch02/buchwissen-in-einen-entwicklungsauftrag-uebersetzen` | Eine Verständnisfrage oder einen erteilten Bauauftrag anhand des tatsächlichen Nutzerziels bearbeiten, ohne den Lehrchat vorzuschreiben. |
| [Eine fehlgeschlagene Folgefrage als Kontextproblem erkennen](references/ch02.md) — `ch02/die-zweite-frage` | Eine gescheiterte Folgefrage am tatsächlich gesendeten Request als fehlenden Verlauf erkennen. |
| [Versionsangaben und Entwicklungsgeschichte mit Stand nennen](references/ch02.md) — `ch02/belege` | Versionsangaben und Entwicklungsgeschichte strukturierter Ausgaben mit Stand und Geltungsbereich nennen. |

## Kapitel 3

| Abschnitt | Wofür laden? |
| --- | --- |
| [Zustandslose Modellaufrufe und angezeigten Verlauf unterscheiden](references/ch03.md) — `ch03/zustandslosigkeit-und-verlauf` | Zustandslose Modellaufrufe vom angezeigten Verlauf unterscheiden und wachsende Verläufe als Produktentscheidung erklären. |
| [Frontend, Backend und Modellaufruf verbinden](references/ch03.md) — `ch03/chat-frontend-backend-modell` | Eine Chatfunktion über ihre realen Komponenten und Datenwege erklären und eine konkrete Nutzerfrage von einem Bauauftrag unterscheiden. |
| [Das Begleitbeispiel starten und seinen Umfang kennen](references/ch03.md) — `ch03/begleitbeispiel-und-demogrenzen` | Den vorhandenen lokalen Demoweg nutzen und fest vorgegebene Antworten, echte Provideraufrufe und bereits belegte Prüfungen auseinanderhalten. |
| [Browseranfrage in einen Providerrequest übersetzen](references/ch03.md) — `ch03/browseranfrage-zu-providerrequest` | Eigene Chat-ID, kopierten Verlauf, Rollen und HTTP-Vertrag ohne Vermischung von Anwendungs- und Providerobjekten verfolgen. |
| [Antwortdarstellung und Verlaufsspeicherung trennen](references/ch03.md) — `ch03/antwortdarstellung-und-verlaufsspeicherung` | Typisierte Modellinhalte sicher darstellen und erfolgreiche Turns speichern, während Fehler und technische Hinweise eigene Ereignisse bleiben. |
| [Folgefragen mit dem richtigen Kontext bearbeiten](references/ch03.md) — `ch03/folgefragen-und-kontext` | Den zweiten vollständigen Request rekonstruieren und sichtbaren Verlauf, gesendeten Kontext sowie persistente Speicherung unterscheiden. |
| [Systemprompt und Wissenskontext richtig einordnen](references/ch03.md) — `ch03/systemprompt-und-wissenskontext` | Rollen durch den tatsächlichen Request bestimmen und Instruktionen, Gespräch und geladene Daten mit ihrer Herkunft erhalten. |
| [Systemtexte als brauchbare Arbeitsverträge schreiben](references/ch03.md) — `ch03/systemtext-als-arbeitsvertrag` | Ziel, Informationen, Fähigkeiten und Ergebnismaßstab so beschreiben, dass sinnvolle Auswahl möglich und reale Grenzen technisch umgesetzt bleiben. |
| [Teilantworten, Stop-Gründe und Kontextgrenzen behandeln](references/ch03.md) — `ch03/abbruch-und-teilantworten` | Erreichte Ausgabelimits und andere Abschlusszustände korrekt anzeigen und unvollständige Antworten nachvollziehbar fortsetzen. |
| [Getrennte Chats und gleichzeitig eintreffende Turns](references/ch03.md) — `ch03/getrennte-chats-und-nebenlaeufigkeit` | Die richtige Gesprächsidentität, serverseitige Zugriffsprüfung, Reihenfolge und dauerhafte Speicherung zusammen gestalten. |
| [Fehlerursachen finden und aussagekräftig prüfen](references/ch03.md) — `ch03/fehlerursachen-und-aussagekraeftige-tests` | Transport, Authentisierung, Parser und Modellqualität mit passenden Belegen prüfen, statt die Lehrfehlerfolge als ausgeführten Modelltest auszugeben. |
| [Last, Wiederholungen und unklare Ausgänge beherrschen](references/ch03.md) — `ch03/last-retries-und-unklare-ergebnisse` | Ratenlimit, Ausgabenlimit und Überlastung unterscheiden sowie Warteschlangen, Wiederholungsbudgets und doppelte Verarbeitung kontrollieren. |
| [Den Verlauf für eine Folgefrage gezielt einbauen](references/ch03.md) — `ch03/verlauf-im-erklaerfeld` | Den Verlauf für Folgefragen gezielt speichern, begrenzen und am tatsächlich gesendeten zweiten Request prüfen. |
| [Vom Chat zur tatsächlichen Aktion übergehen](references/ch03.md) — `ch03/vom-chat-zur-tatsaechlichen-aktion` | Eine hilfreiche reine Chatfunktion von einer benötigten ausführbaren Produktfähigkeit unterscheiden und den nächsten Ausbau begründen. |
| [Den Bing-Fall und die Cookie-Geschichte quellengenau erzählen](references/ch03.md) — `ch03/belege` | Den Bing-Fall und die Cookie-Geschichte quellengenau und mit damaligen Werten erzählen. |

## Kapitel 4

| Abschnitt | Wofür laden? |
| --- | --- |
| [Erklären, warum ein Verbot im Prompt keine Handlung verhindert](references/ch04.md) — `ch04/ankuendigung-ist-keine-sperre` | Den Replit-Vorfall über die Arbeitsteilung erklären und Schutz in der Ausführung statt im Prompt umsetzen. |
| [Den Unterschied zwischen einem Vorschlag und Projektarbeit erklären](references/ch04.md) — `ch04/vom-text-zur-projektarbeit` | Beim Einstieg erklären, welche konkrete Projektinformation und Ausführungsfähigkeit gegenüber einer bloßen Textantwort fehlen. |
| [Eine Werkzeugbeschreibung mit einer realen Funktion verbinden](references/ch04.md) — `ch04/werkzeugvertrag-und-implementierung` | Werkzeugdefinition, lesbare Description, Argumentschema und tatsächlich ausführenden Handler als zusammengehörigen Vertrag prüfen. |
| [Aufruf, Argumenttext und Kennungen sauber auseinanderhalten](references/ch04.md) — `ch04/aufrufkennungen-und-json` | Argumentzeichenkette dekodieren und Aufrufkennung, Antwortkennung sowie interne Anwendungskennungen korrekt auseinanderhalten. |
| [Vom Befehlstext zum wirklichen Prozess führen](references/ch04.md) — `ch04/terminal-shell-und-prozess` | Den Weg von Befehlstext über Arbeitsverzeichnis und Prozessstart zu beobachtbaren Ausgaben erklären oder implementieren. |
| [Die Runtime als Verbindung zwischen Entscheidung und Wirkung bauen](references/ch04.md) — `ch04/runtime-ausfuehrung-und-rechte` | Semantische Werkzeugwahl mit tatsächlicher Ausführung, Zugriffsprüfung und unterscheidbaren Fehler- oder Wartezuständen verbinden. |
| [Reale Werkzeugergebnisse in den nächsten Aufruf übernehmen](references/ch04.md) — `ch04/rueckgabe-und-fortsetzungsrequest` | Die echte Werkzeugrückgabe und ihren begrenzten Belegwert in einen korrekt zugeordneten Folge-Request überführen. |
| [Aus einer Fundstelle eine begründete Änderung ableiten](references/ch04.md) — `ch04/fundstelle-dateiinhalt-und-diagnose` | Gefundene Pfade, gelesenen Programmtext, Hypothese und begründete nächste Beobachtung im Preisfall unterscheiden. |
| [Projektanweisungen aus einer Datei zu wirksamem Kontext machen](references/ch04.md) — `ch04/projektanweisungen-einbinden` | Zeigen, wie Projektregeln tatsächlich gelesen, mit bestimmtem Geltungsbereich in Kontext eingebaut und von Quellenmaterial getrennt werden. |
| [Den Rundungsfehler kausal erklären und zielgerichtet beheben](references/ch04.md) — `ch04/rundungsfehler-und-gezielte-korrektur` | Die unzureichende Rundungsänderung anhand des konkreten Tests erklären und die geladene Fachregel ursächlich umsetzen. |
| [Einen Arbeitslauf sinnvoll fortsetzen oder beenden](references/ch04.md) — `ch04/fortschritt-warten-und-abschluss` | Fortschritt, offene Arbeit, Wartezustand, Limit und belegten Abschluss für einen sinnvollen Agentenlauf unterscheiden. |
| [Schlussfolgern, Toolprotokoll und Anbieterformat getrennt erklären](references/ch04.md) — `ch04/thinking-und-anbieteradapter` | Reasoning, sichtbaren Text und strukturierte Ausführung trennen und den tatsächlich gewählten Anbieteradapter korrekt fortsetzen. |
| [Den gebauten Zusammenhang auf ein anderes System übertragen](references/ch04.md) — `ch04/agentenbausteine-und-transfer` | Das Zusammenspiel von Ziel, Information, Modellentscheidung, Runtime-Wirkung und Rückgabe auf einen anderen Produktfall übertragen. |
| [Tool-Verträge, Projektregeln und ausgeführte Tests als verschiedene Belege lesen](references/ch04.md) — `ch04/belege-fuer-tool-und-test` | Quellen für Tool-Formate, konkrete Hostregeln, Rundungsursache und tatsächlich ausgeführte Tests passend einordnen. |

## Kapitel 5

| Abschnitt | Wofür laden? |
| --- | --- |
| [Überladene Prompts als Konstruktionsfehler erkennen](references/ch05.md) — `ch05/arbeitsvertrag-statt-regelwand` | Überladene, widersprüchliche oder schreiende Prompts als Konstruktionsfehler erkennen und Regeln an ihren Ort bringen. |
| [Einen offenen Handlungsraum verständlich machen](references/ch05.md) — `ch05/offene-entscheidungen` | Offenheit als situative Wahl anhand echten Zustands erklären und vom vorgegebenen Replay sowie einem unbegrenzten Zugriff abgrenzen. |
| [Notwendige Abhängigkeiten von starren Gesprächspfaden unterscheiden](references/ch05.md) — `ch05/workflows-und-agenten` | Entscheiden, welche Abhängigkeiten technisch gesichert werden müssen und welche fachlichen nächsten Schritte die KI sinnvoll selbst wählt. |
| [Den gespeicherten Verlauf als nachspielbare Evidenz lesen](references/ch05.md) — `ch05/nachspielbarer-lauf-und-provenienz` | Gespeicherten Gesamtverlauf, neun Request-Vorlagen, Werkzeugprotokoll und tatsächlich nachgespielte Operationen korrekt einordnen. |
| [Arbeitsregeln und ausführbare Fähigkeiten passend bereitstellen](references/ch05.md) — `ch05/arbeitsumgebung-und-werkzeugregister` | Den vom Host gebauten Arbeitskontext und die fünf konkreten Werkzeugverträge mit verständlichen Namen und realen Handlern verbinden. |
| [Bekannte Anforderungen und verfügbare Anleitungen im ersten Kontext zeigen](references/ch05.md) — `ch05/nutzerauftrag-und-skill-katalog` | Am ersten Request die schon bekannten Nutzeranforderungen und Skillbeschreibungen zeigen, ohne späteren Inhalt vorwegzunehmen. |
| [Schritt 1: Aus dem Auftrag eine überprüfbare Dateisuche machen](references/ch05.md) — `ch05/c01-datei-suchen` | Aufruf c01 mit Suchtext prices, seinen beiden Pfadtreffern und dem anschließend fünf Items langen Kontext nachvollziehen. |
| [Schritt 2: Den gefundenen Pfad in tatsächlichen Programmtext überführen](references/ch05.md) — `ch05/c02-preiscode-lesen` | Aufruf c02 und die erstmalige Beobachtung des Preisprogramms von einer bereits ausgeführten Änderung unterscheiden. |
| [Schritt 3: Vorhandene Erwartungen lesen, ohne einen Testlauf zu behaupten](references/ch05.md) — `ch05/c03-tests-lesen` | Die drei vorhandenen Testerwartungen und das Abbruchverhalten des Testprogramms lesen, ohne einen Testlauf vorzutäuschen. |
| [Schritt 4: Aus einem Katalogeintrag geladene Arbeitsanleitung machen](references/ch05.md) — `ch05/c04-skill-laden` | Den Übergang vom Katalogeintrag zum vollständigen geladenen Preis-Skill samt Rundungsregel und Testauftrag erklären. |
| [Schritt 5: Eine gespeicherte Änderung von ihrer fachlichen Richtigkeit trennen](references/ch05.md) — `ch05/c05-erste-dateiaenderung` | Die erste eindeutige Ersetzung und ihren Schreibnachweis erklären, während die fachlich fehlende Rundungsart noch offen bleibt. |
| [Schritt 6: Den tatsächlichen Testfehler in eine Diagnose überführen](references/ch05.md) — `ch05/c06-testfehler-auswerten` | Den echten ersten Testprozess, seine konkrete Fehlermeldung und die daraus begründete Diagnose auswerten. |
| [Schritt 7: Die fehlende Regel ergänzen, statt den Test umzudeuten](references/ch05.md) — `ch05/c07-rundung-korrigieren` | Die Korrektur auf ROUND_HALF_UP mit geladener Projektregel, Zwischenmeldung und bestätigtem neuen Dateistand verbinden. |
| [Schritt 8: Mit demselben Test die korrigierte Version überprüfen](references/ch05.md) — `ch05/c08-gleichen-test-wiederholen` | Die sinnvolle Testwiederholung am geänderten Zustand und den auf drei vorhandene Fälle begrenzten Erfolgsbeleg erklären. |
| [Aus bestätigten Ergebnissen eine passende Abschlussantwort bilden](references/ch05.md) — `ch05/belegte-abschlussantwort` | Eine Abschlussantwort auf bestätigte Änderungen und Testergebnisse stützen und vom vorherigen Kontext sowie einer Veröffentlichung unterscheiden. |
| [Gezielt ersetzen und Änderungen am beobachteten Stand absichern](references/ch05.md) — `ch05/eindeutiges-schreiben` | Textbasierte eindeutige Ersetzung, Konflikte, Readback und zusätzliche Anforderungen bei konkurrierenden Änderungen korrekt behandeln. |
| [Für jeden Modellaufruf genau den bereits entstandenen Kontext verwenden](references/ch05.md) — `ch05/kontext-fortsetzen` | Die neun Kontextpräfixe von 2 bis 20 Items und den gespeicherten Endzustand mit 21 Items beim Erklären und Implementieren auseinanderhalten. |
| [Text und strukturierte Daten als Beobachtungen der realen Umgebung nutzen](references/ch05.md) — `ch05/reale-beobachtungen` | Rückgaben als begrenzte Beobachtungen realer Zustände interpretieren und für die Aufgabe passende Information oder Modalität bereitstellen. |
| [Werkzeuge in der Sprache ihrer tatsächlichen Wirkung entwerfen](references/ch05.md) — `ch05/faehigkeitsschnittstellen` | Kombinierbare Tools nach fachlicher Domäne, konkreter Wirkung und anschließbaren Ein- und Ausgaben gestalten. |
| [Fehlendes Vorgehenswissen von fehlendem Zugriff unterscheiden](references/ch05.md) — `ch05/wissensbedarf-und-faehigkeit` | Fehlendes Vorgehenswissen von fehlendem Zugriff, geladener aber falsch umgesetzter Information und Ausführungsfehlern unterscheiden. |
| [Passende Arbeitsanleitungen laden und mit vorhandenem Wissen weiterarbeiten](references/ch05.md) — `ch05/skills-bei-bedarf` | Arbeitsanleitungen am konkreten Informationsbedarf auswählen, ihren tatsächlichen Inhalt verwenden und unnötige Rückfragen oder Wiederholungen vermeiden. |
| [Dateiformat, Ressourcenkennung und tatsächliche Integration auseinanderhalten](references/ch05.md) — `ch05/skillformat-und-ladeweg` | Skillformat, Metadatenparser, registrierte Ressourcenkennung und tatsächliche Hostintegration als getrennte Aufgaben verstehen. |
| [Wissen ändern, ohne versehentlich neue Befugnisse zu erzeugen](references/ch05.md) — `ch05/wissen-faehigkeit-und-befugnis` | Arbeitswissen und Toolfähigkeiten unabhängig pflegen, ohne aus geladenen Texten oder historischen Fehlern neue Befugnisse oder Verbote abzuleiten. |
| [Viele Fähigkeiten über verständliche Auswahl und echte Nachladung erschließen](references/ch05.md) — `ch05/werkzeuge-dynamisch-entdecken` | Große Werkzeugbestände über brauchbare Suchbeschreibungen und echte Nachladung erschließen, ohne Suchtreffer mit verfügbaren Fähigkeiten zu verwechseln. |
| [Spezialisierte Modellarbeit mit einem klaren Auftrag anschließen](references/ch05.md) — `ch05/weitere-ki-faehigkeiten-anfordern` | Spezialisierte Modellarbeit mit konkretem Kontext, Auftrag, Belegen und Rückgabe an den Hauptagenten sinnvoll anbinden. |
| [Den nächsten Schritt aus Zustand und Ergebnis entstehen lassen](references/ch05.md) — `ch05/offener-runtime-loop` | Eine Runtime bauen, die reale Ergebnisse zurückführt und fachliche nächste Schritte offen lässt, während sie Fortschritt und Abschluss verlässlich verwaltet. |
| [Fortschrittstext mit der tatsächlichen Arbeit verbinden](references/ch05.md) — `ch05/zwischenmeldungen-im-chat` | Assistant-Zwischenmeldungen und aus Toolereignissen erzeugte Statusanzeigen mit dem tatsächlichen Arbeitsfortschritt verbinden. |
| [Nachrichtenphase, Itemstatus und Darstellungsentscheidung auseinanderhalten](references/ch05.md) — `ch05/nachrichtenphasen-und-ui` | Nachrichtenphase, Itemstatus, Laufsteuerung und UI-Darstellung im konkreten Protokoll unterscheiden; fehlende Replay-Phasen nicht erfinden. |
| [Laufende, wartende und beendete Arbeit zuverlässig darstellen](references/ch05.md) — `ch05/laufende-wartende-und-beendete-arbeit` | Ende eines Items oder Laufs von erledigter Aufgabe, Wartezustand und tatsächlicher Wiederaufnahme unterscheiden. |
| [Technische Grenzen erkennen und innerhalb des erreichbaren Systems weiterarbeiten](references/ch05.md) — `ch05/verfuegbarkeitsgrenzen` | Reale Werkzeug-, Konto- und Wirkungsgrenzen korrekt auswerten und innerhalb vorhandener Befugnisse geeignete Alternativen verfolgen. |
| [Einen Prompt aufräumen und die Wirkung vergleichen](references/ch05.md) — `ch05/regeln-an-den-richtigen-ort` | Einen Agentenprompt Regel für Regel aufräumen und die Wirkung an denselben Aufgaben vorher und nachher belegen. |
| [Den vorgeführten Lauf und externe Schnittstellen getrennt belegen](references/ch05.md) — `ch05/replay-und-vertraege-belegen` | Den Replay-Nachweis, gespeicherten Verlauf, tatsächliche Request-Präfixe und verschiedene Herstellerverträge korrekt begründen. |

## Kapitel 6

| Abschnitt | Wofür laden? |
| --- | --- |
| [Modellausgabe als Stimme des Produkts behandeln](references/ch06.md) — `ch06/ausgabe-und-produktstimme` | Modellausgaben als Stimme des Produkts behandeln und verbindliche Zusagen nur über geprüfte Wege zulassen. |
| [Einen Produktlauf als zusammenhängenden Vorgang erklären](references/ch06.md) — `ch06/produktlauf` | Erklärt einen vollständigen Produktlauf vom sichtbaren Anliegen über interne Übergaben bis zur sichtbaren Wirkung und trennt Gesamtlog von aktuellem Request. |
| [Nachrichtenrolle, Anwendungskennung und sichtbare Blase auseinanderhalten](references/ch06.md) — `ch06/besuchernachricht` | Ordnet sichtbare Nachricht, Herkunft, Protokollrolle und interne Kennungen zu, ohne nicht übertragene IDs als Modellkontext auszugeben. |
| [Einen tatsächlichen Modellrequest lesbar aufschlüsseln](references/ch06.md) — `ch06/vollstaendige-anfrage` | Hilft, einen vollständigen Providerrequest zusammenhängend zu lesen und ihn von Ausschnitten, Antwortobjekten und erfundenen Anwendungsfeldern zu unterscheiden. |
| [Wo bereitgestellte Informationen herkommen und was sie belegen](references/ch06.md) — `ch06/kontextquellen` | Verbindet Kontextangaben mit ihrer Herkunft und Bedeutung und unterscheidet einen bekannten Katalogeintrag vom gelesenen Inhalt. |
| [Einen Tool Call als Anforderung der nächsten realen Handlung erklären](references/ch06.md) — `ch06/werkzeuganforderung` | Erklärt den Werkzeugwunsch des Modells, seine Argumente und Zuordnung sowie die anschließende tatsächliche Ausführung durch die Runtime. |
| [Die Rückgabe in den nächsten Modellkontext einbauen](references/ch06.md) — `ch06/fortsetzung-mit-wissen` | Zeigt, warum eine reale Rückgabe in die korrekte Fortsetzung gehört und wie fehlender Informationsfortschritt erkannt wird. |
| [Aus einer Modellantwort eine verständliche und geprüfte Oberfläche machen](references/ch06.md) — `ch06/antwort-und-oberflaeche` | Verbindet Providerantwort, eingelesene Felder und sichtbare UI mit der nötigen Datenprüfung und begrenzt die Aussage modellseitiger Bewertungen. |
| [Selbsteinschätzungen von kalibrierten Wahrscheinlichkeiten unterscheiden](references/ch06.md) — `ch06/kalibrierung` | Verlangte Selbsteinschätzungen von kalibrierten Wahrscheinlichkeiten unterscheiden und Kalibrierung an eigenen Fällen prüfen. |
| [Wissen, Vorgehensweisen und Fähigkeiten gezielt verfügbar machen](references/ch06.md) — `ch06/wissen-skills-tools` | Hilft, fehlende Information, Vorgehenswissen und ausführbare Fähigkeiten als verständliche und kombinierbare Angebote bereitzustellen. |
| [Einen Modellwechsel als neue Anfrage der Anwendung verstehen](references/ch06.md) — `ch06/modellwechsel` | Erklärt einen angeforderten Modellwechsel als neue Anfrage der Anwendung mit einem nachvollziehbaren Übergabestand. |
| [Eine spezialisierte KI-Fähigkeit in einen laufenden Agenten einbinden](references/ch06.md) — `ch06/modell-als-tool` | Unterscheidet eine spezialisierte KI-Teilaufgabe mit Rückgabe von der Übergabe der Hauptbearbeitung an ein anderes Modell. |
| [Den für das Modell verfügbaren Zustand einer Oberfläche erklären](references/ch06.md) — `ch06/oberflaechenzustand` | Ordnet die tatsächlich verfügbare UI-Beobachtung, ihre Zielkennungen und mögliche spätere Handlungen dem richtigen Kontext zu. |
| [Beschriftung, Klick und tatsächliche Aktion auseinanderhalten](references/ch06.md) — `ch06/button-wirkung` | Erklärt, wann ein Klick eine Nachricht erzeugt oder eine gespeicherte Aktion fortsetzt und wie Beschriftung und Wirkung zusammenpassen. |
| [Fähigkeiten nach ihrem Nutzen und ihrer Wirkung benennen](references/ch06.md) — `ch06/sinnvolle-faehigkeitsbeschreibung` | Leitet verständliche Namen, Beschreibungen und sparsame Datenfelder aus Zweck, Verbraucher und tatsächlicher Wirkung ab. |
| [Entscheidungen als typisierte Auswahl gestalten](references/ch06.md) — `ch06/entscheidungen-als-typisierte-auswahl-gestalten` | Jev-Fragen und beide Antwortcontainer erklären; Kategorien, Bedingungswerte und geordnete Scores in korrekt zugeordnete Produktwirkungen übersetzen. |
| [Entscheidungsangebote an der Aufgabe vergleichen](references/ch06.md) — `ch06/entscheidungsangebote-an-der-aufgabe-vergleichen` | Dieselbe Routingaufgabe in Jev- und OpenAI-Decisions-Verträge übersetzen und beobachtete Ergebnisse unter passenden Vergleichsbedingungen beurteilen. |
| [Jedem Antwortfeld eine Wirkung zuordnen](references/ch06.md) — `ch06/zahlen-im-produkt` | Jedem Antwortfeld eine Wirkung zuordnen und Zahlen nur mit gemessener Bedeutung verwenden. |
| [Tahoe-Fall, Kalibrierung und Entscheidungsschnittstellen belegen](references/ch06.md) — `ch06/belege` | Tahoe-Fall, Kalibrierung und den Stand der Entscheidungsschnittstellen belegen. |

## Kapitel 7

| Abschnitt | Wofür laden? |
| --- | --- |
| [KI an der Stelle der Arbeit einbauen statt daneben](references/ch07.md) — `ch07/hilfe-in-der-arbeit` | KI an der Stelle der Arbeit einbauen statt als Chat daneben und Modellausgaben durch Produktregeln führen. |
| [Vom vorhandenen Arbeitsweg ausgehen](references/ch07.md) — `ch07/vorhandenes-produkt` | Vom normalen Produktnutzen ausgehen und die KI in einen vorhandenen Arbeitsweg einbauen. |
| [Interpretation, Oberfläche und verbindlichen Zustand aufteilen](references/ch07.md) — `ch07/modellbeitrag` | Den Modellbeitrag von Oberfläche und verbindlicher Speicherung trennen, ohne einen Chat zu erzwingen. |
| [Entwicklungs-KI und eingebautes Modell auseinanderhalten](references/ch07.md) — `ch07/rollen` | Entwicklungsauftrag, Produktprompt und tatsächliche Fähigkeiten der beiden KI-Rollen auseinanderhalten. |
| [Einen vollständigen kleinen Bauabschnitt umsetzen](references/ch07.md) — `ch07/bauabschnitt` | Einen kleinen vollständigen Weg von Eingabe bis bearbeitbarem Ergebnis tatsächlich anschließen. |
| [Gerätekarten als bearbeitbare Produktobjekte erklären](references/ch07.md) — `ch07/sichtbares-ergebnis` | Vorschlagskarten an Katalogdaten anbinden und offene Geräteeigenschaften verständlich anzeigen. |
| [Nötige Modellinformationen von internen Verwaltungsdaten trennen](references/ch07.md) — `ch07/kontext-und-zuordnung` | Modellkontext auf nötige Inhalte begrenzen; Konto-, Zugriffs- und Objektzuordnung selbst korrekt implementieren. |
| [Den sichtbaren Fehler bis zu seiner Ursache verfolgen](references/ch07.md) — `ch07/fehler-lokalisieren` | Den Fehler zwischen Eingabe, Modellkontext, Antwort und Gerätekarte mit tatsächlichen Beobachtungen lokalisieren. |
| [Die Reparatur am ursprünglichen Fall und am Gegenfall prüfen](references/ch07.md) — `ch07/gegenfall` | Die ursächliche Reparatur mit Normalfall, unbekannter Eigenschaft und sinnvoller Alternative prüfen. |
| [Neue Angaben mit dem aktuellen Zustand verbinden](references/ch07.md) — `ch07/aktualisierte-eingabe` | Neue Angaben und aktuelle Auswahl verbinden; verspätete Ergebnisse nicht dem neuen Auftrag zuordnen. |
| [Die Modellausgabe auf vorhandene Gegenstände begrenzen](references/ch07.md) — `ch07/antwort-und-karte` | Dekodierte Modellausgaben auf erlaubte Katalogobjekte abbilden und Form von Richtigkeit unterscheiden. |
| [Modellausgaben durch die Regeln des Produkts führen](references/ch07.md) — `ch07/kasse-fuer-modellausgaben` | Fachliche Prüfungen für Modellausgaben aus ihrer Bedeutung ableiten und mit ungültigen Ausgaben testen. |
| [Die gesamte Benutzerhandlung bis zum gespeicherten Ergebnis prüfen](references/ch07.md) — `ch07/reservierung-und-abnahme` | Den tatsächlichen Benutzerweg bis zur Speicherung und den Ausfallweg ohne KI prüfen. |
| [Den nächsten Ausbau aus der offenen Aufgabe ableiten](references/ch07.md) — `ch07/naechster-ausbau` | Die nächste Erweiterung aus einer offenen Informations- oder Wirkungsfrage statt aus einer Technikliste ableiten. |
| [Architekturquellen und Nachweis des Lehrfalls unterscheiden](references/ch07.md) — `ch07/belege` | Technische Sachquellen vom Nachweis des konstruierten Lehrfalls und einer echten Produktprüfung unterscheiden. |

## Kapitel 8

| Abschnitt | Wofür laden? |
| --- | --- |
| [Erklären, warum eine erreichbare Quelle noch keine verwendete Quelle ist](references/ch08.md) — `ch08/quelle-in-reichweite` | Eine erreichbare Quelle von einer im Kontext verwendeten unterscheiden und die Leitfrage Wissen oder Erreichbarkeit anwenden. |
| [Die Behauptung bis zu ihrer tatsächlichen Grundlage verfolgen](references/ch08.md) — `ch08/fehlende-grundlage` | Bedarfsangabe und belegte Geräteeigenschaft trennen; eine fehlende Grundlage nicht mit Textkosmetik reparieren. |
| [Eine bekannte Quelle direkt lesen](references/ch08.md) — `ch08/direkte-anleitung` | Eine bekannte Anleitung direkt lesen und Zugriff, Fassung, Extraktion und fehlende Angabe unterscheiden. |
| [„Unbekannt“ als vollwertiges Ergebnis behandeln](references/ch08.md) — `ch08/unbekannt-ist-ein-ergebnis` | „Unbekannt“ als vollwertiges Ergebnis ausgeben, Quellen dem richtigen Gerät zuordnen und Widersprüche sichtbar halten. |
| [Den Informationsumfang vor der Suchtechnik bestimmen](references/ch08.md) — `ch08/groesserer-bestand` | Den nötigen Kontextumfang bestimmen und vorhandene Beziehungen sowie einfache Suchwege zuerst prüfen. |
| [Die Lücke zwischen Alltagswunsch und Katalogbezeichnung erkennen](references/ch08.md) — `ch08/suchluecke` | Die Lücke zwischen Alltagswunsch und Katalogbezeichnung am Suchfehler und seinem Gegenfall erklären. |
| [Erklären, was die Zahlen leisten und was nicht](references/ch08.md) — `ch08/embedding` | Embedding, Originaltext und Ähnlichkeit als verschiedene Gegenstände erklären, ohne Zahlen als Wahrheitsbeleg zu verwenden. |
| [Vorbereitung und einzelne Suchanfrage als zwei Wege erklären](references/ch08.md) — `ch08/vorbereiten-und-suchen` | Vorbereitung, Anfrage-Embedding, Vergleich und Nachladen verbinden; Quellfassung und Modellkompatibilität sichern. |
| [Exakte Auswahl, Ähnlichkeit und aktuelle Zustände passend kombinieren](references/ch08.md) — `ch08/exakte-daten` | Exakte Daten, semantische Treffer und zugängliche Suchräume passend kombinieren. |
| [Einen Suchtreffer mit seiner Einschränkung lesbar halten](references/ch08.md) — `ch08/ausschnitt` | Bedeutung und Einschränkungen beim Aufteilen und Nachladen von Dokumenten erhalten. |
| [Abruf, Generierung und Aussagebeleg getrennt anschließen](references/ch08.md) — `ch08/rag-und-quellen` | Abruf und Generierung mit nachprüfbaren Aussage- und Quellenbezügen anschließen. |
| [Geladene Dokumente als Daten behandeln und Prompt Injection begrenzen](references/ch08.md) — `ch08/handbuch-ist-kein-befehl` | Geladene Dokumente als Daten behandeln und Prompt Injection über Befugnisse statt Filter begrenzen. |
| [Eignung und Verfügbarkeit zeitlich unterscheiden](references/ch08.md) — `ch08/verfuegbarkeit` | Fachliche Eignung von zeitabhängiger Verfügbarkeit und verbindlicher Reservierung unterscheiden. |
| [Zusätzliche Fähigkeiten nach der tatsächlichen Lücke wählen](references/ch08.md) — `ch08/gezielte-faehigkeiten` | Reranking, Skills oder Lesewerkzeuge nur zur tatsächlich beobachteten Lücke ergänzen. |
| [Suchkandidaten gezielt neu ordnen](references/ch08.md) — `ch08/kandidaten-neu-ordnen` | Einen Reranker nur für gefundene Kandidaten einsetzen, Indizes korrekt auflösen und die Reihenfolge an bekannten Fällen prüfen. |
| [Die nächste Änderung aus dem beobachteten Informationsweg ableiten](references/ch08.md) — `ch08/diagnose-und-transfer` | Die erste fehlende Informationsvoraussetzung identifizieren und an wiederholbaren Fällen weiterarbeiten. |
| [Suchquellen nicht als Nachweis der Beispielqualität verwenden](references/ch08.md) — `ch08/belege` | Technische Sachquellen vom Nachweis des konstruierten Lehrfalls und einer echten Produktprüfung unterscheiden. |

## Kapitel 9

| Abschnitt | Wofür laden? |
| --- | --- |
| [Erklären, warum gute Testzahlen ein Problem übersehen können](references/ch09.md) — `ch09/tests-finden-was-man-prueft` | Den GPT-4o-Fall nutzen, um zu zeigen, dass Tests nur finden, was sie prüfen, und aus Einzelerfolgen keine Qualität folgt. |
| [Eine Verbesserung als prüfbare Behauptung formulieren](references/ch09.md) — `ch09/vergleichsfrage` | Einen überzeugenden Eindruck in eine konkrete überprüfbare Verbesserungsbehauptung übersetzen. |
| [Aus Nutzeranforderungen passende Prüffälle ableiten](references/ch09.md) — `ch09/faelle` | Prüffälle aus echten Anforderungen sowie normalen Situationen und Gegenfällen ableiten. |
| [Einen Versuch wiederholbar vorbereiten](references/ch09.md) — `ch09/ausgangszustand` | Wiederholbare Eingaben, Quellenfassungen, Zeit- und Speicherzustände für einen fairen Vergleich vorbereiten. |
| [Den ersten verlorenen Zusammenhang in der Ablaufspur finden](references/ch09.md) — `ch09/fehlerort` | Die erste Abweichung in einer zusammengehörigen Ablaufspur ohne erfundene Modellgedanken finden. |
| [Den Auswahlauftrag nur bei passendem Befund verändern](references/ch09.md) — `ch09/ursachengerechte-aenderung` | Eine Promptänderung nur aus einem dazu passenden Befund begründen und gegen ursprüngliche Erwartungen prüfen. |
| [Ausgangsstand und Kandidat fair vergleichen](references/ch09.md) — `ch09/baseline` | Ausgangsstand und Kandidat bei dokumentierten Bedingungen und vollständigen Wiederholungen vergleichen. |
| [Inhaltliche Anforderungen von erlaubter sprachlicher Variation trennen](references/ch09.md) — `ch09/bedeutung-statt-wortlaut` | Inhaltliche Anforderungen mit erlaubten Alternativen prüfen, exakte Werte dagegen unverändert erhalten. |
| [Harte Softwareverträge ohne zufälligen Modellfehler testen](references/ch09.md) — `ch09/softwaregrenzen` | Ungültige Modellausgaben gezielt einspeisen und harte Softwaregrenzen am tatsächlichen Zustand testen. |
| [Suche, Auswahl und ganzen Produktweg getrennt beurteilen](references/ch09.md) — `ch09/teilversuche` | Suche, Generierung mit festem Kontext und vollständige Oberfläche als getrennte Prüfungen verbinden. |
| [Fachliche Bewertung mit überprüfbaren Kriterien unterstützen](references/ch09.md) — `ch09/urteilspruefung` | Fachliche und modellgestützte Bewertungen mit Quellen, klaren Kriterien und offenem Ausgang absichern. |
| [Kennzahlen als Hinweise verwenden, nicht als Ziel](references/ch09.md) — `ch09/kennzahl-als-ziel` | Kennzahlen als Hinweise statt als Ziel verwenden und mehrere Kriterien getrennt betrachten. |
| [Entwicklungsfälle und unabhängigen Vergleich auseinanderhalten](references/ch09.md) — `ch09/unverbrauchte-faelle` | Entwicklungsfälle von noch unbenutzten Prüffällen nach ihrer tatsächlichen Verwendung trennen. |
| [Verbesserungen und neue Fehler gemeinsam sichtbar machen](references/ch09.md) — `ch09/abwaegung` | Gewinne und neue Fehlertypen gemeinsam statt nur über eine Gesamtnote beurteilen. |
| [Aus dem Vergleich einen präzisen nächsten Bauauftrag machen](references/ch09.md) — `ch09/weiterarbeiten` | Aus belegten Vergleichsergebnissen die nächste passende Verbesserung des eigenen Produkts ableiten. |
| [Prüfmethoden und konkrete Ergebnisse getrennt belegen](references/ch09.md) — `ch09/belege` | Technische Sachquellen vom Nachweis des konstruierten Lehrfalls und einer echten Produktprüfung unterscheiden. |

## Kapitel 10

| Abschnitt | Wofür laden? |
| --- | --- |
| [Fehlende Bestätigung von ausgebliebener Wirkung unterscheiden](references/ch10.md) — `ch10/verlorene-bestaetigung` | Nach Antwortverlust gespeicherte Wirkung und Wissensstand der Oberfläche getrennt untersuchen. |
| [Den bestehenden Reservierungsweg weiterverwenden](references/ch10.md) — `ch10/vorhandener-schreibpfad` | Vorhandene Reservierungsfunktionen wiederverwenden und Modellvorschlag nicht als Freigabe behandeln. |
| [Antwortverlust nach dem Speichern gezielt prüfen](references/ch10.md) — `ch10/fehler-nachstellen` | Den Verbindungsabbruch nach dem Speichern gezielt nachstellen und tatsächliche Wirkungen zählen. |
| [Die Oberfläche mit dem belastbaren Zustand abgleichen](references/ch10.md) — `ch10/reconciliation` | Denselben begonnenen Vorgang wiederfinden, den Ausgang prüfen und unbekannten Status sichtbar erhalten. |
| [Einen logischen Auftrag über mehrere Übertragungen erhalten](references/ch10.md) — `ch10/idempotenz` | Wiederholte Übertragungen eines logischen Auftrags gegen doppelte Speicherung absichern. |
| [Werkzeuge eines Agenten wiederholungsfest bauen](references/ch10.md) — `ch10/idempotente-werkzeuge` | Schreibende Werkzeuge eines Agenten wiederholungsfest bauen und unklare Ausgänge ehrlich zurückmelden. |
| [Gleichzeitige Zugriffe auf den letzten Bestand absichern](references/ch10.md) — `ch10/gleichzeitige-reservierung` | Unterschiedliche gleichzeitige Aufträge an Bestand und Ganz-oder-gar-nicht-Regel prüfen. |
| [Laufende und verspätete Vorschläge richtig zuordnen](references/ch10.md) — `ch10/laufender-vorschlag` | Laufstatus, vollständige Ausgabe und Zuordnung verspäteter Antworten zur richtigen Eingabe sichern. |
| [Dauerhafte Arbeit nur bei tatsächlichem Bedarf einrichten](references/ch10.md) — `ch10/hintergrundauftrag` | Dauerhafte Hintergrundarbeit nur bei Bedarf mit Quellfassung und überprüfbarem Arbeitsstand einrichten. |
| [Abbruch über seine sichtbare und gespeicherte Wirkung definieren](references/ch10.md) — `ch10/abbrechen` | Abbruch, Schließen und Stornierung nach ihrer tatsächlichen Wirkung unterscheiden. |
| [Wiederholungen nach Fehlerart und Wirkung begrenzen](references/ch10.md) — `ch10/wiederholungen` | Wiederholungen nach Fehlerklasse, zulässiger Wirkung und begrenztem Aufwand gestalten. |
| [Aufwand an den tatsächlich ausgeführten Schritten messen](references/ch10.md) — `ch10/laufzeit-und-kosten` | Gesamten benutzbaren Weg messen, Kosten schätzen oder belegen und Änderungen gegen Qualität prüfen. |
| [Das Produkt ohne die zusätzliche KI benutzbar halten](references/ch10.md) — `ch10/ausfallweg` | Den vorhandenen manuellen Produktweg bei Modellausfall tatsächlich benutzbar halten. |
| [Verhaltensänderungen einer verwendeten Fassung zuordnen](references/ch10.md) — `ch10/aenderungsstand` | Verhaltensänderungen einer Konfiguration zuordnen und Rückkehr ohne Datenverlust vorbereiten. |
| [Änderungen schrittweise und umkehrbar einführen](references/ch10.md) — `ch10/schrittweise-einfuehren` | Änderungen an KI-Funktionen nachvollziehbar, schrittweise und mit passenden Rückwegen einführen. |
| [Die Wirkungskette auf ein anderes Produkt übertragen](references/ch10.md) — `ch10/transfer` | Die Trennung von Auftrag, Wirkung und Rückmeldung auf das nächste konkrete Produkt übertragen. |
| [Technische Garantien am eingesetzten System prüfen](references/ch10.md) — `ch10/belege` | Technische Sachquellen vom Nachweis des konstruierten Lehrfalls und einer echten Produktprüfung unterscheiden. |

## Kapitel 11

| Abschnitt | Wofür laden? |
| --- | --- |
| [Medienmodelle an der eigenen Umgebung messen](references/ch11.md) — `ch11/eigene-umgebung-statt-werbeversprechen` | Medienmodelle nach Ein- und Ausgabe ordnen und an der eigenen Umgebung statt an Demos messen. |
| [Vom Mikrofon zum Transkript](references/ch11.md) — `ch11/vom-mikrofon-zum-transkript` | Aufnahme, Transkription, Eingabefeld und Senden mit überprüfbarer Format- und Segmentverarbeitung verbinden. |
| [Transkripte in die Anwendung übernehmen](references/ch11.md) — `ch11/transkripte-in-die-anwendung-uebernehmen` | Providerdaten in einen klaren Transkriptvertrag übersetzen und Herkunft, Zeitbezug sowie Korrektur gezielt erhalten. |
| [Originalsignale für die Aufgabe erhalten](references/ch11.md) — `ch11/originalsignale-fuer-die-aufgabe-erhalten` | Die für eine Aufgabe nötigen Originalsignale wählen und multimodale Interpretation von gemessener Erkennungsqualität unterscheiden. |
| [Unsichere Wörter präzise bearbeiten](references/ch11.md) — `ch11/unsichere-woerter-praezise-bearbeiten` | Fach/Bach-Korrekturen an Textversion, eindeutige Bereiche und eine vereinbarte Unicode-Zähleinheit binden. |
| [Antworttext in hörbare Sprache überführen](references/ch11.md) — `ch11/antworttext-in-hoerbare-sprache-ueberfuehren` | Fachlich vorbereiteten Text über Synthese und Wiedergabe in verständliche, steuerbare Audioausgabe überführen. |
| [Bilder und Videos als Eingabe verarbeiten](references/ch11.md) — `ch11/bilder-und-videos-als-eingabe-verarbeiten` | Tatsächlich übergebene Bilder oder Videosegmente samt Auflösung, Zeitpunkt und Quellenbezug verarbeiten. |
| [Bildbeobachtungen von Ursachen trennen](references/ch11.md) — `ch11/beobachtung-im-bild` | Bildbeobachtungen von Ursachen trennen und beide Aufnahmen nachweisbar in den Request geben. |
| [Eine Bilddatei erzeugen und bereitstellen](references/ch11.md) — `ch11/eine-bilddatei-erzeugen-und-bereitstellen` | Gelernte Bilderzeugung und OpenAI-Images-Vertrag erklären; Base64-Daten in eine tatsächlich verfügbare, prüfbare Bilddatei überführen. |
| [Vorhandene Bilder kontrolliert bearbeiten](references/ch11.md) — `ch11/vorhandene-bilder-kontrolliert-bearbeiten` | Ausgangsbild und Änderungsauftrag im Gemini-Interactions-Vertrag verbinden, typisierte REST-Bildinhalte auslesen und Erhalt sowie Versionen prüfen. |
| [Bildfunktionen in ein vorhandenes Produkt einbauen](references/ch11.md) — `ch11/bildfunktionen-in-ein-produkt-einbauen` | Motivänderung und Bildflächenerweiterung an Shopify-/Photoshop-Funktionen erklären und mit Medienauswahl, Varianten, Layout und tatsächlicher Übernahme verbinden. |
| [Zeitliche Konsistenz bei Videos prüfen](references/ch11.md) — `ch11/zeitliche-konsistenz-bei-videos-pruefen` | Handlung, Motiverhalt und Filmzeit einer Videogenerierung erklären und vollständige Sequenzen von gezeichneten Lehrbildern unterscheiden. |
| [Lange Medienaufträge als Zustand verwalten](references/ch11.md) — `ch11/lange-medienauftraege-als-zustand-verwalten` | Asynchrone Medienaufträge über Kennung, Statusabfrage und gesicherte Ergebnisdatei verwalten; keine abgeschalteten Vorschauwege verwenden. |
| [Rückkopplung und Weltmodelle unterscheiden](references/ch11.md) — `ch11/rueckkopplung-und-weltmodelle-unterscheiden` | Genie 3 und Project Genie über Zustand, Handlung und nächste Ansicht erklären und generierte Anschlussfähigkeit von verlässlicher Simulation unterscheiden. |
| [Spezialisten und normale Software kombinieren](references/ch11.md) — `ch11/spezialisten-und-normale-software-kombinieren` | Machine Learning als Oberbegriff einordnen und spezialisierte Ergebnisse mit normalen Softwarefunktionen an klaren Datenübergaben kombinieren. |
| [Tabellenfälle als Vorhersageaufgabe formulieren](references/ch11.md) — `ch11/tabellenfaelle-als-vorhersageaufgabe-formulieren` | Datenzeile, Zielwert und zum Vorhersagezeitpunkt bekannte Merkmale bestimmen; Leckage vermeiden und Schätzung gegen eine passende Ausgangslösung prüfen. |
| [Zeitreihen mit passendem Horizont prognostizieren](references/ch11.md) — `ch11/zeitreihen-mit-passendem-horizont-prognostizieren` | Zeitbezug, Messabstand, Horizont und bekannte Zusatzvariablen für Prognosen verbinden; historische Prüfung und tatsächliche Warenplanung auseinanderhalten. |
| [Empfehlungen an den tatsächlichen Produktzustand binden](references/ch11.md) — `ch11/empfehlungen-an-produktzustand-binden` | Personalisierte oder artikelbezogene Vorschläge mit Katalog, Voraussetzungen, Verfügbarkeit und beurteilbaren Produktzielen verbinden. |
| [Bildmasken in eine Bearbeitung übernehmen](references/ch11.md) — `ch11/bildmasken-in-die-bearbeitung-uebernehmen` | Box, Maske, Bildversion, Koordinaten und zeitliche Objektidentität in eine tatsächliche Bild- oder Videobearbeitung überführen. |
| [Eine Spracheingabe am Ausgaberegal verantwortlich bauen](references/ch11.md) — `ch11/leihregal-hoert-zu` | Eine Spracheingabe mit sichtbarer Bestätigung, begrenzter Aufbewahrung und echten Testaufnahmen bauen; Produktfotos nicht erfinden. |
| [Medienangaben mit Datum und Dokumentation belegen](references/ch11.md) — `ch11/belege` | Medienfälle und Modellangaben mit Datum, Dokumentation und Lizenzhinweis belegen. |

## Kapitel 12

| Abschnitt | Wofür laden? |
| --- | --- |
| [Sperren und Warnungen bewusst unterscheiden](references/ch12.md) — `ch12/sperre-oder-warnung` | Sperren und Warnungen als bewusste Entscheidung unterscheiden und physische Grenzen nicht in Prompts verlagern. |
| [Angekündigte Handlungen von ausführbaren Fähigkeiten trennen](references/ch12.md) — `ch12/angekuendigt-ist-nicht-ausgefuehrt` | Angekündigte Handlungen von angebotenen Fähigkeiten trennen und Erfolge nur mit Nachweis der ausführenden Software melden. |
| [Erkennen, wann eine Entscheidung keine KI braucht](references/ch12.md) — `ch12/keine-ki-beim-oeffnen` | Erkennen, wann eine Entscheidung gespeicherter Zustand ist und keine KI braucht, und wo Interpretation trotzdem hilft. |
| [Den Nachweisstand einer physischen Wirkung anzeigen](references/ch12.md) — `ch12/nachweisstufen` | Die Anzeige an den tatsächlich vorliegenden Nachweis einer physischen Wirkung binden und Wiederholungen nach Antwortverlust klären. |
| [Messwerte, Beobachtungen und Erklärungen auseinanderhalten](references/ch12.md) — `ch12/messwert-und-ursache` | Messwerte, Beobachtungen und Erklärungen trennen und automatische Wirkungen nicht auf einen einzigen ungeprüften Wert stützen. |
| [Harte Grenzen in Steuerung und Runtime umsetzen](references/ch12.md) — `ch12/harte-grenzen-in-der-steuerung` | Harte Grenzen in Steuerung und Runtime umsetzen, unmittelbar vor der Wirkung erneut prüfen und die Fälle des Bauauftrags testen. |
| [Die Fragen des Buchs auf ein anderes Produkt übertragen](references/ch12.md) — `ch12/dieselben-fragen-anderes-produkt` | Die Fragen des Buchs an einer Drohnen-Dachinspektion auf ein anderes Produkt übertragen, ohne Techniken blind mitzunehmen. |
| [Mit dem vorhandenen Projekt der Person weiterarbeiten](references/ch12.md) — `ch12/eigener-naechster-schritt` | Den nächsten Bauabschnitt am vorhandenen Projekt und dem bereits erteilten Auftrag der Person ausrichten. |
| [Fälle zu physischen Systemen vorsichtig belegen](references/ch12.md) — `ch12/belege` | Fälle zu physischen Systemen vorsichtig belegen und Lehrfälle von realer Hardware trennen. |

