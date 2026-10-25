# Stimme

Regeln auf Satzebene mit Beleg (Konzept § 7.13).

Es gibt keine Textproben der Autorin. Jede Regel ist **(abgeleitet)** aus Genre-Profil `heftroman`, Stilvorlage `style/presets/heftroman.yaml`, Genre-Recherche (`research/handwerk/heftroman.md`), BRIEF.md und Welt (`bible/welt/grundlage.md`). Die letzte Spalte heißt darum **Herkunft**, nicht Beleg. Die Autorin kann jede Regel später mit bb-style und eigenen Proben ersetzen.

## Rhythmus
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Kurze, klare Sätze, im Schnitt 9 bis 14 Wörter; etwa jeder zweite Satz unter 8 Wörtern | liest sich in einem Zug, auch abends müde | durchgehend | Telegrammstil über ganze Absätze; oder verschachtelte Satzgefüge mit drei Nebensätzen | Stilvorlage `sentence_words`; Genre-Hinweis „Kurze Sätze“ |
| (abgeleitet) Ein längerer, fließender Satz für Sinneseindruck oder Gefühl, danach ein kurzer | Atem holen, dann Pointe | Gartenbilder, Annäherung, Szenenende | jeder Absatz im selben Muster lang-kurz | Stilvorlage `variation`; BRIEF „Wärme, klare Gefühle“ |
| (abgeleitet) Höchstens selten „und … und …“-Ketten; Handlungen lieber in eigene Sätze | Klarheit, Tempo | Arbeit im Garten, Bewegungsfolgen | Aufzählung von fünf Handgriffen in einem Satz | Stilvorlage `and_chain_max: 0.06` |
| (abgeleitet) Kurze Absätze, ein Gedanke je Absatz; Dialogzeile oft eigener Absatz | luftiges Satzbild im Heftformat | durchgehend | Absatzblöcke über eine halbe Seite | Stilvorlage `paragraph_words`; Recherche § 1 (Heftsatz zweispaltig) |

## Dialog
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Dialog trägt die Handlung und den Streit; etwa ein Fünftel bis ein Drittel des Texts | Nähe, Tempo, Funken zwischen Marie und Jonas | jede Begegnung des Paars | Dialog als Informationsabgabe („Wie du weißt …“); Szenen ganz ohne Rede | Recherche § 2 „Dialog treibt die Handlung“, gemessen 19–22 %; Stilvorlage `dialogue_share` |
| (abgeleitet) Schlagabtausch kurz und witzig: Repliken von einem Satz, die das Wort des anderen aufnehmen und umdrehen | Schmunzeln beim Streit | Streit über Weg, Bogen, Budget (Akt 1, Akt 2) | Beleidigung, Zynismus, Herabsetzung | BRIEF „beim Streit der beiden schmunzeln“; Welt „Gummistiefel gegen Lederschuhe“ |
| (abgeleitet) Begleitsätze schlicht: „sagte“, „fragte“ oder eine Geste statt Redeverb | Rede bleibt im Vordergrund | durchgehend | „hauchte“, „zischte“, „knurrte“ gehäuft; Adverb an jedem Begleitsatz | Genre-Hinweis „warme, klare Sprache“ |
| (abgeleitet) Gefühl im Gespräch oft im Ungesagten: Pause, Blick, Hand am Rosenstock | Herzklopfen ohne Erklärung | Annäherung, Krise ch08 | Figuren sprechen ihre Gefühle in ganzen Absätzen aus | Recherche § 4 „Telling statt Showing“ |

## Beschreibung
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Sinnlich und konkret: Erde, Rosenduft, Lindenblüte, Heu, Gewitterluft, warmer Kies; ein bis zwei Sinne je Bild | die Leserin riecht den Garten und ist zu Hause | Szeneneinstieg im Garten, Ruhepunkte | Kataloge von Pflanzen; Adjektivreihen; Postkartenkitsch | BRIEF „eine Welt, in der es nach Erde und Rosen riecht“; Welt „Ton“ |
| (abgeleitet) Beschreibung in Bewegung: die Figur sieht, schneidet, riecht, statt dass die Erzählung stillsteht | Kulisse ohne Anlauf | durchgehend | Absatz reiner Landschaftsbeschreibung vor der Handlung | Recherche § 4 (lange Kulisse ohne Paar) |
| (abgeleitet) Jahreslauf als Zeitmarke: Lindenblüte, Gewitter, Erntestaub, Morgennebel und Hagebutten zeigen, wo im Sommer wir sind | Countdown zum Erntefest spürbar | Kapitelanfänge | Datumsangaben statt Bild; falsche Blüte zur falschen Zeit | Welt „Zeit“ und „Rosengarten im Einzelnen“ |

## Perspektive
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Dritte Person, enges Präteritum, eine Perspektive je Szene: Marie oder Jonas | Nähe zur Figur, klare Führung | jede Szene | Kopfspringen in einer Szene; Erzähler weiß mehr als die Figur | book.yaml `voice: third/past`, `knowledge_access: limited`; Genre-Hinweis |
| (abgeleitet) Erlebte Rede für Gedanken, ohne Kursivsatz und ohne „dachte sie“ an jedem Satz | Gefühl von innen | Zweifel, Ärger, Verliebtsein | Gedankenzitate in Anführungszeichen; Ich-Form außerhalb der Rede | Recherche § 6 (Ich-Form 0) |
| (abgeleitet) In Jonas-Szenen sein Blick: Maße, Lasten, Kosten, Termine; der Garten erscheint ihm zuerst als Fläche, dann zunehmend als Ort | Leserin sieht seine Zweifel und seinen Wandel | Jonas-Szenen | Jonas klingt wie Marie; oder kalt und berechnend | STORYBOARD (Jonas Bauingenieur, Wandel); Perspektive laut book.yaml |

## Wortwahl
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Alltagsdeutsch, warm, wenig Fremdwörter; Gartenwörter nur, wenn die Szene sie erklärt | jede Leserin versteht alles beim ersten Lesen | durchgehend | Fachsprache (Gärtnerei, Bau, Recht) ohne Erklärung; Anglizismen | Genre-Hinweis „wenig Fremdwörter“; `style.jargon-density narration_max 0.3` |
| (abgeleitet) Norddeutsche Färbung sparsam: „Moin“, „Knick“, „Deern“ einzeln, kein durchgehendes Platt | Landleben und Region hörbar | Rede von Grete, Hannes | ganze Sätze auf Platt; Klischee-Norddeutsch | Welt (Holsteinische Schweiz); BRIEF Landleben |
| (abgeleitet) Echte Rosennamen in Hochkommas ('New Dawn'), sparsam, eine Sorte je Bild | Kennerschaft Maries ohne Liste | Maries Szenen im Garten | Sortenkataloge | Welt „Rosengarten im Einzelnen“ |

## Tempo
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Spät einsteigen: die Szene beginnt mitten in Tun oder Gespräch, Ort und Zeit in ein, zwei Sätzen nachgereicht | kein Anlauf, sofort im Garten | jeder Szenenanfang | Aufwachen, Wetterbericht, Anfahrt | Recherche § 2 „Leserin sofort in die Geschichte werfen“ |
| (abgeleitet) Zeitsprünge zwischen Szenen knapp überbrücken (ein Satz mit Bild), nicht erzählen | der Sommer vergeht spürbar, ohne Leerlauf | Szenen- und Kapitelwechsel | Zusammenfassungen über Absätze | Szenenmaß 950 Wörter (book.yaml) |
| (abgeleitet) Jede Szene endet mit einem Haken: offene Frage zwischen den beiden, Blick, halber Satz, neue Nachricht | Sog zum nächsten Abschnitt | Szenenende; etwa jede dritte Szene ein echter Cliffhanger | jede Szene endet gleich; Ende mit Zusammenfassung des Gefühls | Stilvorlage `end`, `moves`; Genre-Hinweis „Haken“ |

## Humor
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Leiser Situationshumor aus Gegensätzen: Lederschuhe im Matsch, Laptop auf der Gartenbank, Gartenschere gegen Zollstock | Schmunzeln, Wärme | Akt 1, Begegnungen des Paars, Lena-Szenen | Slapstick, Spott über eine Figur, Ironie gegen die Leserin | Welt „Ton“; BRIEF „schmunzeln“ |
| (abgeleitet) Lena darf direkter sein; ihre Pointen benennen, was Marie nicht zugibt | Leserin fühlt sich verstanden | Lena-Szenen | Lena als Witzmaschine ohne eigene Wärme | STORYBOARD (Lena „leichter Humor“) |

## Intensität
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Gefühle klar und benennbar, aber über Körper und Handlung gezeigt: Herzklopfen, warme Wangen, Hände, die nicht stillhalten | Geborgenheit mit Herzklopfen | Annäherung, Kuss ch05, Erntefest | Gefühlsetiketten Satz für Satz; Melodram, Tränenströme | BRIEF „Wirkung“; Recherche § 4 |
| (abgeleitet) Sinnlichkeit Tür zu (heat 1): Blicke, Berührung, Küsse; die Szene blendet vor mehr ab | sicher für die Zielgruppe | Liebesszenen | Körperbeschreibung über den Kuss hinaus | book.yaml `params.heat: 1` |
| (abgeleitet) Krise schmerzt kurz und ehrlich, ohne Bitterkeit; der Ton bleibt warm, auch im Zorn | die Leserin verliert kurz das Herz und vertraut dem Ende | ch08, ch09 | Schreiduelle, Zynismus, Verzweiflung über Seiten | BRIEF „beim Kaufvertrag kurz das Herz verlieren“ |

## Genre
| Zug | Wirkung | Wann | Fehlerbild | Herkunft |
|---|---|---|---|---|
| (abgeleitet) Heile Welt mit echtem Konflikt: das Problem ist Vertrauen und Bleiben, nicht Bosheit; Steinhagen höflich, kein Schurke | Heftroman-Vertrag, sichere Lektüre | durchgehend | Intrige, Bösewicht, Zufallsrettung | Recherche § 2 (Grundschema, Tabus); STORYBOARD |
| (abgeleitet) Jede Szene bringt die Geschichte des Paars voran, auch Dorf- und Gartenszenen | Paarfokus | jede Szene | Nebenhandlung ohne Bezug zu Marie und Jonas | Genre `liebesroman` Hinweis; Recherche § 2 Paarfokus |

## Tabu
- (abgeleitet) Keine Kontrastformeln in der Erzählung („nicht X, sondern Y“). muster: /nicht\s+\p{L}+,\s+sondern/
- (abgeleitet) Keine „Schmetterlinge im Bauch“ und ähnliche Verliebtheitsfloskeln. muster: /Schmetterlinge\s+im\s+Bauch/
- (abgeleitet) Kein expliziter Sex; nichts über den Kuss und die Umarmung hinaus.
- (abgeleitet) Keine Flüche, keine Gewalt, keine Polizei, keine schweren Krankheiten in der Gegenwartshandlung.
- (abgeleitet) Keine Religion, keine Politik, keine gesellschaftspolitischen Reizthemen (die Kirche des Dorfes ist Kulisse, kein Thema).
- (abgeleitet) Kein Meer, keine Küste, keine Möwen, keine Fähre, kein Strand.
- (abgeleitet) Keine realen Orte, Städte, Straßen oder Betriebe mit Namen; Hamburg nur genannt.
- (abgeleitet) Keine Ich-Form in der Erzählung, kein Präsens als Erzähltempus.
- (abgeleitet) Kein Zynismus, kein Großstadtspott, kein Herabsetzen des Landlebens oder der Stadt.
- (abgeleitet) Keine Wetter- oder Aufwach-Einstiege ohne Figur im Tun.
