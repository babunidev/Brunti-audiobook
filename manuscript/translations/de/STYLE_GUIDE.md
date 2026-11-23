# Übersetzungsleitfaden — Brunti (Deutsch)

**Status: redaktioneller Arbeitsvorschlag, 23. November 2026.** Von Babuni ist die Anlage der deutschen Übersetzungsvorbereitung autorisiert; konkrete Formulierungen und Terminologie wurden noch nicht einzeln freigegeben.

## Literarische Absicht

Die deutsche Fassung soll wie eigenständige, natürliche Fantasy-Prosa klingen, ohne eine andere Handlung zu erzählen. Rhythmus, Zurückhaltung, greifbare Sinneseindrücke und kleine Veränderungen der Wahrnehmung tragen die Atmosphäre. Nicht jedes Bild braucht eine zusätzliche Erklärung, nicht jede Spannung stärkere Adjektive.

- Sinn, Informationen, Handlungsfolge, Blickwinkel, Erzählzeit, Dialogabsicht und Szenenzäsuren der **jeweiligen englischen Romanfassung** erhalten.
- Idiomatisches literarisches Hochdeutsch schreiben; keine wörtlich nachgebauten englischen Satzstellungen, künstlich altertümlichen Redensarten oder spieltypischen UI-Begriffe in die Romanstimme eintragen.
- Lange Sätze dürfen fließen, kurze Sätze dürfen stehen. Das englische Tempo und die Wirkung einer Pause sind wichtiger als die Zahl der Satzzeichen.
- Humor und zarte Vertrautheit nicht durch Erklärung oder Komikverstärkung verändern. Brunti, Nemi, Darrik, Sira und Velen müssen in der deutschen Sprache unterscheidbar bleiben.
- Die Perspektive des **Romans** beibehalten: Erzählen in der dritten Person, grundsätzlich in der vom Original vorgegebenen Vergangenheit; keine zusätzlichen Leseransprachen. Die gesonderten Morkahja-Begegnungstextregeln für Präsens gelten nicht automatisch für diese Romanübersetzung.
- Die Grimnir sind lebendige Wesen aus Mineral, Metall und Kristall, keine Menschen in Steinrüstung. Körper-, Nahrungs-, Pflege- und Resonanzsprache entsprechend der etablierten Welt prüfen.
- Offene Fragen (etwa Blackwood, Atranor oder ungeklärte Identitäten) offen lassen. Keine Erklärungen, Ursachen, Fähigkeiten, Sicherheiten oder Gefühle ergänzen, die der Text nicht trägt.

## Namens- und Begriffsdisziplin

1. Die englische **Romanstelle** ist Übersetzungsgegenstand. Für etablierte Weltbegriffe ist MorkahjaWorld maßgeblich; für ID, Begegnungsspezifik und Follow-Reihenfolge Morkahja. Romanfiktion darf nicht als neue Weltkanon-Aussage ausgegeben werden.
2. Eigennamen nicht ohne belegte Entscheidung übersetzen oder umbenennen. Deutsch klingende beschreibende Ortsnamen nur nach Glossar-/Kanonsichtung festlegen. Unklare Fälle in [GLOSSARY.md](GLOSSARY.md) mit Beleg, Kandidat und Status markieren.
3. Wiederkehrende Motive wie **resonance**, **memory stone**, **Skyland** und **convergence** über Kapitel hinweg einheitlich führen; vorerst keine dieser Wortformen als endgültige deutsche Kanonübersetzung deklarieren.
4. Keine fremde oder alte Übersetzung als verbindlich behandeln, solange sie nicht ausdrücklich geprüft wurde. Konflikte zwischen Roman und Quellen in einem Prüfvermerk dokumentieren, nicht still glätten.

## Textgestaltung und Dialog

- Deutsches Anführungszeichenpaar `„…“` für direkte Rede; Interpunktion nach deutschem Sprachgebrauch. Gedankenstriche und Auslassungen sparsam, aber natürlich setzen.
- Die im englischen Manuskript verwendeten eigenständigen `***`-Zeilen als **unhörbare Szenentrenner der Romanfassung** erhalten; nicht im Kapiteltext durch ElevenLabs-Cues ersetzen.
- Keine erklärenden Kapitelmetadaten, Quellen-IDs, Regiehinweise, Klammer-Anweisungen oder Produktions-Tags in den eigentlichen Romantext setzen.
- Anredeformen (du/Sie), Titel, grammatisches Geschlecht, Bildsprache und Anspielungen aus Figur, Situation und Weltzusammenhang erschließen; eine globale Du-/Sie-Regel wäre voreilig.
- Die Kapitel behalten ihre Nummer und eine eindeutige Zuordnung zur englischen Datei. Deutsche Überschrift wird beim Übersetzen bewusst gesetzt; der Dateiname kann zur einfachen Zuordnung den englischen Slug behalten.
- Keine neuen Szenen, Ereignisse oder Charakterbiografien als unmarkierte „Übersetzungskorrektur“. Falls die Quelle inhaltlich fehlerhaft erscheint, Problem als separate editorische Beobachtung dokumentieren.

## Prüfroutine pro Kapitel

1. **Quelle fixieren:** englischen Kapitelpfad, konkreten Commit/SHA und den Stand des Glossars im [Register](STATUS.md) erfassen.
2. **Literarisch übersetzen:** Absätze und Szenen vollständig übertragen; vor allem Dialogabsicht, Rhythmus und beschreibbare Ereignisse erhalten.
3. **Fidelity-Check:** Englisch/Deutsch absatz- und szenenweise vergleichen. Prüfen auf fehlende/verdoppelte Passagen, Dialogzeilen, Namen, Aussagen, Negationen, räumliche und zeitliche Übergänge sowie bewusst ungelöste Fragen.
4. **Kanon-/Kontinuitätscheck:** Entsprechende Quellen und die bestehenden Buchregister bei problematischen Namen, Anatomie, Reisen, Erinnerungen und Begegnungsbezügen heranziehen. Konflikte protokollieren.
5. **Vorleseprobe:** deutsche Prosa laut lesend auf Stolperstellen, Atem, Dialogunterscheidbarkeit und undeutliche Bezüge prüfen. Ein selbstständiger Hörtest ist erst nach tatsächlichem Audio-Render möglich.
6. **Status ehrlich setzen:** *Nicht begonnen → Übersetzt (Entwurf) → intern geprüft → menschlich freigegeben → für Narration abgeleitet → Audio geprüft → veröffentlicht*. Die Stufen werden nicht automatisch durch eine Datei oder KI-Prüfung aufgewertet.

## Trennung von Roman und Hörbuch

Die deutschen `.md`-Kapitel bleiben saubere Prosa. Erst nach Prüfung entsteht je Kapitel eine separate `.txt`-Fassung für ElevenLabs v3/v4. Die 271 englischen Szenen-Pausenmarker und 53 englischen Performance-Cues sind **keine verbindliche deutsche Cue-Liste**: Die deutschen Textgrenzen und der tatsächlich gewählte Sprecher bestimmen die Produktion. Spätere Pausen-/Regie-Tags und Kapitelverbindungen getrennt dokumentieren und durch tatsächliches Anhören verifizieren.

## Änderungsdisziplin

Bei englischen Revisionen den betreffenden deutschen Stand als **Synchronisierung zu prüfen** markieren; neue englische Sätze nicht heimlich in bereits freigegebenes Deutsch einarbeiten. Entscheidungen und eventuelle Freigaben nach [docs/DECISIONS.md](../../../docs/DECISIONS.md), Entwicklungsnachweise nach [docs/DEVLOG.md](../../../docs/DEVLOG.md) und konkrete Änderungen im [CHANGELOG.md](../../../CHANGELOG.md) führen. [docs/AI_COLLABORATION.md](../../../docs/AI_COLLABORATION.md) bleibt unverändert, sofern kein neues Tool/Modell dort aufgenommen werden muss.

## Quellenbasierte Terminologie — Arbeitsstand Stufe 2

Das [Begriffsregister](GLOSSARY.md) enthält nun aus dem gepinnten Weltkanon und **13 gezielt geprüften** englischen Kapiteln abgeleitete Namensbelege und deutsche Formulierungsvorschläge. Die Kürzel **B (Quellschreibweise belegt), V (literarischer Vorschlag), O (offen)** bezeichnen **keine menschliche Freigabe**. Insbesondere „Skyland“, „Erinnerungsstein“, „Gedenkstein“, „Konvergenz“ sowie Ortsnamen in Keldor sind beim Übersetzen als unterschiedliche Bedeutungsfelder zu lesen, nicht per Suchen-und-Ersetzen zu lokalisieren.

Die fünf Schutzregeln im Glossar gelten als **Prüfkriterien**, nicht als neu erfundener Kanon. Frühere Gottheiten-/Atranor-Bestimmungen, Figurennamen und die unaufgelösten sieben Buchstaben `A H K J O M A` bleiben unverändert in ihrer Bedeutung. Besonders auf Satzrhythmus und natürliche deutsche Genitiv- und Kompositabildung ist erst am tatsächlichen Kapiteltext zu entscheiden; hier ist noch kein Versmaß oder Stil endgültig bestätigt.
