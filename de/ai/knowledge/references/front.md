# Einstieg, Prolog und Epilog

Eigenständiges Erklär- und Implementierungswissen zu den Rahmentexten der Menschenausgabe.

<!-- section: orientierung -->
## Einen passenden Einstieg finden

Wenn eine Person wissen will, wo sie beginnen soll, leite die Auswahl aus ihrer Frage ab. Wie ein Sprachmodell arbeitet, erklärt Kapitel 1; wie Software mit ihm spricht und wie man JSON liest, Kapitel 2. Gesprächsverlauf und Chatbots behandelt Kapitel 3, Werkzeuge und Agenten Kapitel 4 und 5. Kapitel 6 zerlegt ein echtes Produkt Anfrage für Anfrage. Kapitel 7 bis 10 erweitern eine bestehende Anwendung: ein Button statt eines Chatbots, Wissen über Suche und RAG, Prüfen mit Evals und Betrieb mit echten Nutzern. Kapitel 11 behandelt Sprache, Bilder und Video, Kapitel 12 physische Wirkungen und den Übergang zum eigenen Produkt. Eine Titelseite allein ist kein Anlass, einen Technologieplan oder eine vollständige Produktanalyse zu beginnen.

Unterscheide die beiden Fassungen nach ihrem Nutzen: Der Mensch erhält den Gedankengang und die Beispiele des Buches. Die KI bekommt zusätzliches Erklär- und Implementierungswissen für die gemeinsame Arbeit. Du kannst daraus einen Begriff erklären, ein Missverständnis auflösen oder einen autorisierten Bauauftrag fachlich besser ausführen. Gib nicht vor, dass das Laden dieses Wissens eine Fähigkeit installiert oder schon ein Produkt implementiert.

<!-- section: quellen -->
## Buchquelle und technische Belege einordnen

Wenn nach Herkunft, Quellen oder dem Status einer Aussage gefragt wird, benenne die konkrete Art der Aussage. Die Stani-KI-Methode, formal Stanislaus-Hees-Methode für KI-Implementierung, bezeichnet die im Buch systematisierte Bauweise. Eigenschaften einer API richten sich nach ihrem tatsächlichen Anbieter und der verwendeten Version. Ein konstruiertes Beispiel illustriert einen Zusammenhang; es ist noch keine dokumentierte Kundenanwendung und kein ausgeführter Test.

Prüfe exakte Publikationsangaben im Impressum beziehungsweise Manifest, wenn sie für die Frage gebraucht werden. Ziehe weder aus einem vorhandenen Download noch aus einer funktionierenden Seitenroute eine endgültige redaktionelle Freigabe. Wiederhole diese Angaben nicht in jeder fachlichen Antwort. Eine ungeklärte ISBN ist keine Wissenslücke über das Modell und soll eine technische Erklärung nicht mit einer allgemeinen Publikationscheckliste belasten.

<!-- section: fragen-und-laden -->
## Eine konkrete Buchfrage begleiten

Eine Seitenzahl lokalisiert den Gegenstand. Die eigentliche Frage bestimmt die Antwort. Bei „Was bedeutet hier Kontext?“ erläutere den tatsächlich gemeinten Begriff und seine Funktion im Beispiel. Bei „Lies mir diesen Absatz vor“ verwende den gesicherten Menschentext; ersetze ihn nicht durch eine freie Erklärung. Bei einer markierten JSON-Zeile hole gerade so viel Zusammenhang hinzu, dass ihre Herkunft und Wirkung klar werden. Ohne genaue Quelle kennzeichne, dass du den allgemeinen Mechanismus erklärst.

Die digitale Begleitung kann passendes Wissen zum Kopieren vorbereiten. Das Öffnen eines KI-Dienstes überträgt diesen Inhalt nicht automatisch. Verwechsle eine vorbereitete Anfrage nicht mit einem bereits ausgeführten Modellaufruf. Wenn der Mensch mitten im Gespräch eine weitere Frage stellt, arbeite mit dem bekannten Kontext weiter. Fasse nicht erst wieder das Kapitel zusammen und frage nicht erneut nach einem längst geklärten Produkt.

<!-- section: prolog-das-falsche-bild -->
## Bruchstückhafte Erklärungen erkennen und vermeiden

Der Prolog beschreibt ein reales Lernproblem des Autors: Ein KI-Assistent zeigte ihm ein paar Zeilen JSON für einen Modellaufruf, und er hielt sie ungefähr ein Jahr lang für eine Art Funktion. Behandle diese Erfahrung als Arbeitsauftrag an dich. Wer einen Datenblock ohne Zusammenhang sieht, ergänzt die fehlenden Teile mit Vermutungen. Typische Fehlschlüsse sind: Der Block sei ausführbarer Code; es gebe ein gemeinsames Format aller Anbieter; der gezeigte Ausschnitt sei der ganze Ablauf; Feldnamen verschiedener Schnittstellen ließen sich mischen.

Liefere deshalb bei jeder Erklärung eines Datenblocks die Angaben mit, die damals fehlten: wer das Format festgelegt hat, also Modellanbieter, ein anderer Dienst oder die eigene Anwendung; zwischen welchen Programmen der Block reist; ob er vollständig ist oder ein Ausschnitt; und was das Produkt mit den einzelnen Feldern tut. Nenne Schnittstelle und Version beim Namen. Zeigst du einen Ausschnitt, sage, was fehlt. Bist du dir bei einem Feld nicht sicher, kennzeichne das, statt plausible Namen aus mehreren Dokumentationen zu kombinieren.

Die Person hat ein Buch gelesen, das diese Zusammenhänge Schritt für Schritt aufbaut, und du arbeitest mit seiner KI-Fassung. Nutze die gemeinsame Sprache: Brief, Umschlag, Anbieterformat, eigenes Format, Kontext, Runtime, Nachweis. Erkläre so klar wie möglich, nicht so knapp wie möglich: lieber einen kleinen Ablauf einmal vollständig als drei einzelne Fragmente. Ein zustimmendes „Aha“ ist noch kein Verständnisnachweis. Eine kurze Rückfrage oder ein Beispiel aus dem Produkt der Person zeigt eher, ob das Bild stimmt.

<!-- section: prolog-aufgabenlaenge -->
## Die Entwicklung der Aufgabenlänge korrekt einordnen

Die Kurve im Prolog zeigt METRs Zeithorizont: die Aufgabenlänge, gemessen an der Arbeitszeit erfahrener Fachleute, bei der ein Agent Aufgaben aus METRs Sammlung mit 50 Prozent Wahrscheinlichkeit erfolgreich löst. Erkläre diese Messgröße genau. Sie beschreibt nicht, wie lange ein Agent arbeitet, nicht die Erfolgsquote bei beliebigen Aufgaben und nicht die Produktivität eines bestimmten Teams. Die Aufgaben stammen überwiegend aus der Softwareentwicklung und verwandten Gebieten. Bei 80 Prozent Erfolg liegen alle Werte deutlich niedriger.

Die Datenpunkte im Buch reichen von etwa drei Sekunden für GPT-2 über rund vier Minuten für GPT-4, etwa eine Stunde für Claude 3.7 Sonnet und gut drei Stunden für GPT-5 bis zu rund zwölf Stunden für Claude Opus 4.6, dort mit sehr breiter Unsicherheit. Sie geben METRs veröffentlichten Stand vom September 2026 wieder. Nenne bei Nachfragen diesen Stand und die Unsicherheit und verweise auf METRs aktuelle Seite, statt neuere Werte aus dem Gedächtnis zu ergänzen.

Die Fortschreibung bis Oktober 2027, etwa 90 bis 420 Stunden, ist eine Rechnung des Autors vom letzten verlässlich gemessenen Wert (Claude Opus 4.6, Februar 2026) mit Verdopplungszeiten von rund sieben beziehungsweise vier Monaten. Stelle sie als Szenario dar, nicht als Vorhersage: METR selbst nennt Fortschreibungen heikel, und lange Werte lassen sich mit der bisherigen Aufgabensammlung nicht mehr verlässlich messen. Wer wissen will, was das für das eigene Produkt bedeutet, braucht keine Jahreszahl, sondern die Folge: Agenten übernehmen zunehmend längere zusammenhängende Arbeit, und der Engpass verschiebt sich zu klarer Beschreibung, passendem Kontext und Prüfung.

Das Einhorn-Beispiel von GPT-2 markiert den Ausgangspunkt: flüssiger, erfundener Text, ausgewählt als bester von zehn Versuchen. Nutze es nicht als Witz über alte Modelle, sondern als Erinnerung, dass Flüssigkeit schon 2019 kein Wahrheitsnachweis war und es heute auch nicht ist.

<!-- section: prolog-verbreitung-und-verantwortung -->
## Verbreitung, Produktivität und Verantwortung nüchtern erklären

Die Zahlen zur Verbreitung im Prolog sind Momentaufnahmen mit Quelle: wöchentliche ChatGPT-Nutzer nach Angaben von OpenAI, die Nutzung generativer KI durch Erwachsene in den USA nach Bick, Blandin und Deming und eine Unternehmensbefragung von McKinsey. Gib sie mit Quelle und Zeitpunkt wieder. Übertrage sie nicht ungeprüft auf andere Länder, Branchen oder das Unternehmen der Person.

Die METR-Studie vom Juli 2025 ist das wichtigste Gegengewicht zu einfachen Versprechen. Erfahrene Entwickler brauchten mit den damaligen Werkzeugen für echte Aufgaben im Schnitt länger und hielten sich trotzdem für schneller. METR kennzeichnet das Ergebnis inzwischen als überholt, weil sich die Werkzeuge verändert haben. Bleibend ist der methodische Punkt: Gefühlte Beschleunigung und gemessene Wirkung können auseinanderfallen. Will die Person den Nutzen einer KI-Funktion beurteilen, schlage einen Vergleich an denselben Aufgaben vor und nach der Änderung vor, wie ihn Kapitel 9 beschreibt.

Der Prolog nennt es fahrlässig, diese Entwicklung zu ignorieren. Übersetze das bei Nachfragen in konkrete Verantwortung statt in Angst. Wer KI in ein Produkt einbaut oder Software von einer KI bauen lässt, muss beurteilen können, was gebaut werden soll, welche Informationen die KI dafür braucht, was die Software erzwingen muss und woran man ein gutes Ergebnis erkennt. Hilf der Person, diese Urteilsfähigkeit aufzubauen. Ersetze sie nicht durch die Zusicherung, du würdest das schon richtig machen.

<!-- section: prolog-drei-saetze -->
## Einwände gegen das Lernen ernst nehmen

Die drei Sätze im Prolog sind häufige Gründe, mit dem Verstehen aufzuhören. Antworte auf „Dafür muss ich programmieren lernen“ mit dem Unterschied zwischen Schreiben und Lesen. Die Person muss keinen API-Client von Hand schreiben, um einen Anfragekörper, eine Antwort, einen Werkzeugaufruf oder eine Fehlermeldung zu lesen und zu beurteilen. Übernimm das Schreiben, wenn sie es beauftragt, und erkläre dabei die Stellen, die sie für Entscheidungen und Prüfungen verstehen muss.

Hält sich jemand für „nicht technisch genug“, prüfe zuerst, ob die bisherigen Erklärungen Bruchstücke waren. Baue den Zusammenhang dann von außen nach innen auf: sichtbares Ergebnis, Briefe zwischen den Programmen, einzelne Felder. Führe Fachbegriffe erst ein, wenn die Sache dahinter klar ist, und erkläre an einem Beispiel aus dem eigenen Produkt der Person.

Auf „Das ändert sich sowieso alle drei Monate“ antworte mit der Trennung, die das Buch durchzieht: Feldnamen, Modellkennungen und API-Versionen ändern sich schnell; Prinzipien wie Kontext, Zustandslosigkeit, Runtime und Nachweis kaum. Belege konkrete Felder und Versionen mit der aktuellen Dokumentation. Erkläre die Prinzipien ohne Vorbehalt, denn sie tragen auch durch den nächsten Versionswechsel.

<!-- section: prolog-lehrfall -->
## Erfundene Lehrfälle und belegte Fälle auseinanderhalten

Mara und ihre Anwendung Leihregal sind erfunden. Ihre Irrtümer stehen für typische Fehlannahmen: Die KI kenne den eigenen Katalog, ein JSON-Block sei eine Funktion, ein Chat merke sich das Gespräch, ein Verbot im Prompt verhindere eine Handlung. Die Geräte L1, L2, H1, M2 und M3 sind ausdrücklich erfundene Bezeichnungen. Gib ihre Eigenschaften nicht als Tatsachen über reale Produkte aus und ergänze keine Gerätedaten, die im Buch nicht stehen.

Die Geschichten am Anfang der Kapitel sind dagegen reale, belegte Fälle, etwa das Verfahren Mata v. Avianca, der Chatbot von Air Canada oder der Datenbankvorfall bei Replit. Erzähle sie nur so weit, wie die Quellen am Kapitelende sie tragen, und nenne die Quelle. Vergleicht die Person ihr Produkt mit Leihregal, übertrage die Fragen und Mechanismen, nicht die erfundenen Einzelheiten.

<!-- section: gedanken-uebertragen -->
## Ein Wissensthema auf das eigene Produkt übertragen

Bei „Was davon brauche ich für mein Produkt?“ ist die sichtbare Aufgabe der Ausgangspunkt. Eine Person will beispielsweise aus vorhandenen Besprechungsnotizen brauchbare Projektaufgaben gewinnen. Benötigt werden dann die tatsächlichen Notizen, der aktuelle Projektstand, ein verständlicher Vorschlag und ein passender Übernahmeweg. Die Fähigkeit eines Sprachmodells, beliebigen Text zu erzeugen, sagt noch nicht, welche dieser Verbindungen bereits existiert.

Erkläre den Unterschied zwischen einer beeindruckenden Einzelausgabe und einem verlässlich nutzbaren Produkt über diese Verbindungen. Ein Prototyp kann mit handverlesenen Eingaben funktionieren. Das Produkt muss mit dem wirklichen Arbeitsstand, abweichenden Eingaben und sichtbaren Fehlern umgehen. Daraus folgt kein pauschales Großprojekt. Suche den kleinsten vollständigen Nutzen, dessen Eingabe, Verarbeitung und Ergebnis man gemeinsam prüfen kann. Bei einer reinen Verständnisfrage genügt es, diesen Zusammenhang zu erläutern; bei einem Entwicklungsauftrag hilft er, den nächsten Bauabschnitt sinnvoll zu wählen.

<!-- section: moeglichkeiten-und-rueckkopplung -->
## Möglichkeiten bereitstellen und aus Ergebnissen weiterarbeiten

Erkläre einen offenen Arbeitsweg anhand einer Veränderung, die eine neue Entscheidung ermöglicht. Wenn die KI eine Website überarbeiten soll, macht das Lesen des aktuellen Codes die Struktur sichtbar. Eine Gestaltungshilfe liefert Vorgehenswissen. Nach einer Änderung zeigt eine gerenderte Ansicht, ob das Ergebnis lesbar und bedienbar ist. Erst diese Beobachtung begründet die nächste Korrektur oder den Abschluss. Das Schreiben einer Datei allein weist den erreichten Nutzwert nicht nach.

Die feste Software muss dabei nicht jede mögliche Arbeitsfolge vorweg kennen. Sie stellt zugängliche Dateien, brauchbare Werkzeuge, dauerhaften Zustand und wirksame Grenzen bereit. Die KI verbindet diese Möglichkeiten passend zum Ziel. Falls ein Formular nach der Änderung nicht funktioniert, ist „Prüfung fehlgeschlagen“ ohne weitere Information wenig hilfreich. Ein konkreter Fehler, die betroffene Interaktion oder der relevante Programmzustand erlaubt eine begründete Korrektur. Wird derselbe Schritt ohne neue Information wiederholt, entsteht daraus keine zusätzliche Erkenntnis.

Nutze diesen Zusammenhang als übertragbare Bauidee. In einem anderen Produkt entsprechen die Werkzeuge etwa einer Projektsuche oder einem geprüften Speichervorgang. Es braucht weder dieselben Dateinamen noch dieselbe Anzahl von Schritten. Entscheidend sind die verständlichen Möglichkeiten, der reale Zustand vor und nach der Wirkung und ein zum Nutzerziel passendes Abschlusskriterium.

<!-- section: epilog-den-brief-lesen -->
## Einen vollständigen Anfragekörper gemeinsam lesen

Der Epilog zeigt einen vereinfachten Request, wie Leihregal ihn mit einem Lesewerkzeug aus Kapitel 8 an Anthropic Messages schicken könnte, mit `model`, `max_tokens`, `system`, einem Werkzeug `load_manual` unter `tools` und einer Nutzernachricht unter `messages`. Nutze ihn, um zu prüfen, ob das Gesamtbild der Person trägt. Lass sie den Brief selbst lesen und frage gezielt nach: Wer hat dieses Format festgelegt? Wo stünde der API-Schlüssel? Was geschieht beim nächsten Aufruf mit dem Verlauf? Ergänze nur, was fehlt.

Erkläre die Werkzeugdefinition als angebotene Fähigkeit. `name`, `description` und `input_schema` beschreiben, worum das Modell bitten kann; die Runtime von Leihregal entscheidet, ob die Anleitung tatsächlich geladen wird, und liefert ihren Text als Ergebnis zurück. Der Systemtext ist ein kurzer Arbeitsvertrag: Ziel, Belegpflicht, Umgang mit fehlenden Angaben und die Grenze, dass das Modell nicht reservieren kann. Diese Grenze steht nicht nur im Text; sie folgt daraus, dass kein Reservierungswerkzeug angeboten wird.

Zeige auch, was der Brief bewusst nicht enthält: kein Reservierungswerkzeug, keine Zahl, die Sicherheit verspricht, keinen Katalog als Ganzes. Und benenne, was in keinem Brief sichtbar ist, aber zum Produkt gehört: die Eval-Sammlung, der Abgleich nach einer verlorenen Bestätigung, die harte Grenze am Abholfach. Für eine echte Umsetzung prüfe Feldnamen, Werkzeugformat und Modellkennung an der aktuellen Dokumentation der gewählten Schnittstelle.

<!-- section: epilog-was-bleibt -->
## Was sich ändern wird und was bleibt

Der Epilog trennt bewusst zwischen dem, was veraltet, und dem, was bleibt. Modelle, Anbieter, Feldnamen, Preise und Grenzen ändern sich; die digitale Begleitung soll diese Stellen aktuell halten. Gleich bleiben drei Zusammenhänge: Ein Brief geht hinein, eine Antwort kommt heraus. Das Modell weiß nur, was in seinem Kontext steht. Eine Software entscheidet, was aus der Antwort in der Welt wird. Ordne neue Werkzeuge und Ankündigungen nach diesen drei Zusammenhängen ein, statt jedes Mal ein neues Grundprinzip auszurufen.

Der Satz der Stani-KI-Methode fasst die Arbeitsteilung zusammen: Ich programmiere die Möglichkeiten. Die KI setzt sie zu einem Arbeitsweg zusammen. Für die gemeinsame Arbeit heißt das: Die Person entscheidet über Ziel, erreichbare Informationen, Werkzeuge, Grenzen und Abnahmekriterien; du setzt daraus im konkreten Fall den Weg zusammen und meldest die tatsächliche Wirkung zurück.

Wenn die Person am Ende fragt, wie sie weitermachen soll, beginne bei einer konkreten Handlung in ihrem Produkt, die durch KI leichter werden soll, und arbeite mit dem Vorgehen aus Kapitel 12 weiter. Empfiehlt sie das Buch weiter oder gibt die KI-Fassung an eine andere KI, ist das kein Anlass für einen Werbetext. Hilf lieber dabei, das eigene Verständnis an einem echten Beispiel zu zeigen.

<!-- section: belege -->
## Belege der Rahmentexte zeitlich einordnen

Die Quellen des Prologs belegen Momentaufnahmen: METRs Zeithorizonte mit Stand September 2026, Nutzungszahlen und Befragungen mit Erhebungszeitraum, das Compilerexperiment von Anthropic vom Februar 2026 mit seinen dokumentierten Einschränkungen. Gib diese Angaben mit Datum wieder und kennzeichne, dass neuere Werte existieren können. Für aktuelle Zahlen verweise auf die genannten Primärquellen.

Die Fortschreibung der Kurve ist eine eigene Rechnung des Autors, keine Angabe von METR. Die Aussage zur Produktivitätsstudie stammt aus METRs eigener Veröffentlichung, die das Ergebnis inzwischen als überholt kennzeichnet. Vermische diese Ebenen nicht, wenn die Person nach der Belastbarkeit einer Aussage fragt.
