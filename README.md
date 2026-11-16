# vps server mieten: Was ein VPS wirklich kostet – Vultr-Preise ab $5, das $300-Startguthaben und die versteckten Kosten im Vergleich

Ein VPS bei Vultr beginnt bei $5,00 pro Monat: 1 vCPU, 1 GB RAM, 25 GB SSD und 1 TB Traffic, stundenweise abgerechnet. Wer NVMe-Speicher will, zahlt einen Dollar mehr. Das viel beworbene $300-Guthaben für neue Konten ist ein Testbudget: Es verfällt 30 Tage nach der Aktivierung, lässt sich nicht auszahlen und setzt ein hinterlegtes Zahlungsmittel voraus.

Wer „vps server mieten" in eine Suchmaschine tippt, hat meist schon drei Preisseiten offen und drei Fragen: Was kostet der erste Monat, was danach, und was kommt obendrauf. Dieser Text beantwortet die drei für Vultr, mit den aktuell gelisteten Tarifen, und stellt die deutschen Preismodelle daneben, weil dort die teuersten Missverständnisse stecken.

> **Kurzentschlossen:** Der Einstieg mit IPv4-Adresse kostet $5,00/Monat (1 vCPU, 1 GB RAM, 25 GB SSD), die NVMe-Variante $6,00. Für kleine Projekte reicht einer der beiden. Das Guthaben planen Sie als 30-Tage-Test, nicht als halbes Jahr Gratis-Hosting. 👉 [Alle Vultr-Tarife und aktuellen Preise ansehen](https://bit.ly/VuLtr)

## Die Tariflinien im Überblick

Vultr verkauft Rechenleistung in sieben Produktlinien: Cloud Compute Regular Performance, High Performance, High Frequency, VX1, Optimized Cloud Compute, Bare Metal und Cloud GPU. Für gemietete virtuelle Server sind die ersten vier relevant. Alle Preise sind Monatspreise in US-Dollar, abgerechnet wird stündlich.

| Tarif | Geprüfte Konfiguration | Preis pro Monat | Tarif ansehen |
| --- | --- | --- | --- |
| Cloud Compute Regular | 1 vCPU, 1 GB RAM, 25 GB SSD, 1 TB Traffic | $5,00 | [Einstiegstarif prüfen](https://bit.ly/VuLtr) |
| Cloud Compute High Performance | 1 vCPU, 1 GB RAM, 25 GB NVMe, AMD EPYC oder Intel Xeon | $6,00 | [NVMe-Tarif prüfen](https://bit.ly/VuLtr) |
| High Frequency | Intel Xeon ab 3 GHz, NVMe, 10 Größen | $6,00 bis $320,00 | [High-Frequency-Tarife prüfen](https://bit.ly/VuLtr) |
| Größte gelistete Konfiguration | 12 vCPU, 24 GB RAM, NVMe | $216,00 | [Oberes Ende der Preisliste prüfen](https://bit.ly/VuLtr) |
| VX1 | dedizierte AMD-EPYC-Kerne | ab $120,00 | [VX1-Tarife prüfen](https://bit.ly/VuLtr) |
| Cloud Compute IPv6-only | ohne IPv4, nur wenige Standorte | $2,50 | [IPv6-Tarif prüfen](https://bit.ly/VuLtr) |

Zwei Zeilen in dieser Tabelle brauchen eine Erklärung, weil sie in Anzeigen gern als „ab $2,50" auftauchen. Der $2,50-Tarif hat keine IPv4-Adresse und läuft nur an wenigen Standorten; ein $3,50-Variantenpreis mit IPv4 existiert an einem dieser Standorte. Für alles, was eine Domain oder eine öffentlich erreichbare Webanwendung trägt, starten Sie realistisch bei $5,00.

Die Preisliste ist außerdem nicht überall identisch. São Paulo liegt für dieselbe Konfiguration rund die Hälfte höher als die übrigen Regionen. Wer einen Standort in Europa braucht, bleibt bei den europäischen Preisen.

## So rechnet Vultr ab: stündlich, aber mit einer Falle

Abgerechnet wird pro Stunde, mit einer Obergrenze von 672 Stunden pro Monat. Wer eine Maschine dauerhaft laufen lässt, zahlt also den Monatspreis und nicht mehr. Wer sie wenige Tage braucht, zahlt nur diese Stunden.

Die Falle steckt im Unterschied zwischen *stopped* und *destroyed*. Ein gestoppter Server bleibt abgerechnet, weil vCPU, RAM, NVMe-Speicher und die zugewiesene IPv4-Adresse weiter reserviert sind. Die Uhr läuft beim Ausschalten weiter. Erst das Löschen der Instanz beendet die Kosten. Wer einen Tarif eine Woche lang testet und dann nur „Power Off" klickt, zahlt trotzdem weiter.

Das ist der Punkt, an dem sich entscheidet, ob ein Stundenpreis günstig ist. Bei einem Testlauf mit drei Tagen Laufzeit sparen Sie gegenüber einem Jahresvertrag deutlich. Bei einem Server, der ohnehin durchläuft, ist der Unterschied zum Monatspreis null.

## Das $300-Guthaben: was wirklich drinsteckt

Die Bedingungen sind enger, als die Zahl vermuten lässt:

- **Nur für neue Konten.** Wer schon ein Konto hat oder ein zweites anlegt, bekommt nichts.
- **Zahlungsmittel nötig.** Kreditkarte oder PayPal müssen hinterlegt sein, auch wenn die Abbuchung bei $0,00 startet.
- **30 Tage Laufzeit.** Nicht genutztes Guthaben verfällt danach. Es ist kein langfristiges Hosting-Budget, sondern ein Testzeitraum.
- **Nicht rückzahlbar.** Guthaben ist kein Geld. Was am Ende übrig bleibt, ist weg, und bereits geleistete Zahlungen werden nicht erstattet.
- **Ein Code pro Nutzer.** Rabattcodes lassen sich nicht stapeln.

Praktisch heißt das: Sie können in den 30 Tagen mehrere Konfigurationen ausprobieren, auch die teureren, solange Sie die Instanzen danach löschen. Was Sie nicht tun sollten, ist, sich auf das Guthaben zu verlassen und nach Ablauf ein laufendes Projekt weiterzubetreiben, ohne den dann greifenden Monatspreis einzukalkulieren.

👉 [Das $300-Guthaben für ein neues Konto aktivieren](https://bit.ly/VuLtr)

## Was ein VPS in Deutschland wirklich kostet

Der Vergleich mit dem deutschen Markt scheitert selten am Listenpreis, sondern an zwei Angaben, die in Anzeigen fehlen: Steuer und Laufzeit. netcup zeigt beides offen, und zwar für denselben Tarif:

| netcup VPS 500 G12.5 | Preis |
| --- | --- |
| monatlich, ohne MwSt. | 8,26 € |
| monatlich, inkl. 19 % MwSt. | 9,50 € |
| Vertragslaufzeit | 12 Monate |

Die Differenz zwischen den beiden Spalten beträgt rund 15 %. Wer die 8,26 € in einen Vergleich einträgt und die 9,50 € eines anderen Anbieters danebenlegt, vergleicht zwei verschiedene Dinge. Bei den größeren Tarifen derselben Reihe läuft es identisch: 14,50 € netto stehen 16,68 € brutto gegenüber, 26,92 € netto entsprechen 30,96 € brutto. Rechnen Sie alles auf den Bruttopreis um, sonst ist der Vergleich wertlos.

Die zweite Angabe ist die Laufzeit. Diese netcup-Tarife binden Sie 12 Monate, dafür liegt der Monatspreis niedriger als bei monatlicher Kündbarkeit. Vultr rechnet stündlich ab und verlangt keine Jahresvorauszahlung. Das ist der eigentliche Unterschied: Sie zahlen bei Vultr mehr pro Monat als bei einem 12-Monats-Vertrag, kaufen sich dafür aber die Möglichkeit, in vier Wochen wieder auszusteigen.

Eine dritte Differenz, die in Euro-Vergleichen untergeht: Die Rechnung von Vultr lautet auf US-Dollar. Der Betrag, der am Ende auf Ihrem Kontoauszug steht, hängt vom Wechselkurs und vom Verhalten Ihrer Bank ab. Prüfen Sie im Bestellprozess, welche Währung und welcher Endbetrag dort angezeigt werden, bevor Sie abschicken.

## Drei Posten, die in keiner „ab 2 €"-Anzeige stehen

**Backups.** Bei IONOS kostet die Backup-Lösung ab 6 Cent pro GB und Monat. Für einen Server mit 100 GB Daten sind das rund 6 € monatlich zusätzlich, dauerhaft. Vultr sichert nicht automatisch mit; rechnen Sie den Speicher für Sicherungen in Ihre Kalkulation ein, wenn Sie ihn brauchen.

**Zusätzliche IP-Adressen.** IONOS liefert pro Server eine IPv4-Adresse und berechnet jede weitere mit 5 € pro Monat. Bei Vultr ist eine IPv4-Adresse im Tarif enthalten, ausgenommen der $2,50-Tarif, der ausschließlich über IPv6 läuft. Wenn Sie mehrere Dienste mit eigenen Adressen betreiben, ist das ein laufender Posten, kein Einmalbetrag.

**Arbeitszeit.** STRATO und netcup schreiben beide ausdrücklich, dass Konfiguration, Updates, Sicherheitspatches und Backups in der Verantwortung des Kunden liegen. Beim günstigsten Tarif ist das einkalkuliert, solange Sie wissen, was Sie tun. Wenn nicht, ist der Aufpreis für ein Managed-Angebot keine Marketinggebühr, sondern der Preis für die Stunden, die Sie sonst selbst investieren.

Bei Vultr kommt ein vierter Posten dazu, der oft übersehen wird: Traffic ist begrenzt. Der günstigste Tarif enthält 2 TB, danach wird zusätzlicher Traffic berechnet. Für eine normale Website ist das reichlich. Für Video, Downloads oder ein Projekt mit plötzlichem Besucheransturm ist es eine Grenze, die Sie kennen sollten, bevor sie greift.

👉 [Vultr-Tarif mit NVMe-Speicher wählen](https://bit.ly/VuLtr)

## Was deutsche Anbieter anders machen

**netcup** liefert für 8,26 € netto (9,50 € brutto) monatlich 2 vCores, 4 GB RAM, 64 GB SSD und inkludierten Traffic, gebunden auf 12 Monate. Snapshots, Remote-Konsole und DDoS-Schutz sind enthalten. Dedizierte CPU-Kerne, eine Zufriedenheitsgarantie und die bei den Root-Servern beworbene Mindestverfügbarkeit von 99,9 % im Jahresmittel gehören bei den VPS-Tarifen nicht dazu.

**IONOS** nennt eine Verfügbarkeit von 99,99 %, Rechenzentren in der EU, in den USA und in Großbritannien, NVMe-Speicher, unbegrenzten Traffic und eine Anbindung mit bis zu 1 Gbit/s. Linux-Images reichen von AlmaLinux über Debian und Rocky Linux bis Ubuntu, dazu Windows Server 2022 oder 2025. Plesk Obsidian kostet 5 € pro Monat extra und setzt mindestens den Tarif VPS Linux S voraus.

**STRATO** betreibt KVM-Virtualisierung mit NVMe-Speicher, bis zu 1.000 MBit/s Anbindung ohne Traffic-Limit, eine vorgelagerte Firewall, ein Rettungssystem mit VNC-Konsole und ein SSL-Zertifikat in jedem Tarif. Der Standort ist im Bestellprozess wählbar: Deutschland, Spanien oder Frankreich. Eine Einrichtungsgebühr fällt nicht an. Bei den Aktionspreisen lohnt ein zweiter Blick auf die Laufzeit der Aktion und den danach geltenden Preis.

Diese Anbieter sind keine schlechtere Wahl. Sie sind eine andere: europäische Rechenzentren mit DSGVO-Bezug, deutschsprachiger Vertragspartner, teils Managed-Optionen. Wer eine Rechnung in Euro und einen Ansprechpartner in Deutschland braucht, findet das dort und nicht bei Vultr.

## Wer bei Vultr falsch ist

Drei Konstellationen, in denen ich vom Kauf abraten würde:

- **Sie brauchen mehr als 24 GB RAM oder mehr als 12 vCPU auf einer Maschine.** Das ist das obere Ende der gelisteten Konfigurationen. Wer darüber hinaus will, muss zu einer anderen Produktlinie oder einem anderen Anbieter.
- **Sie brauchen unbegrenzten Traffic.** Vultr deckelt das Volumen pro Tarif. Wer nicht abschätzen kann, wie viel Traffic sein Projekt erzeugt, fährt mit einem Anbieter ohne Limit risikoärmer.
- **Sie wollen nichts administrieren.** Ohne verwalteten Service bedeutet ein VPS bei jedem Anbieter: Sie kümmern sich um Betriebssystem, Updates und Sicherungen. Wer das nicht will, sollte ein Managed-Angebot wählen, auch wenn es mehr kostet.

Umgekehrt passt Vultr, wenn Sie mehrere Standorte testen wollen: Die Liste umfasst 32 Rechenzentren, darunter Frankfurt, Amsterdam, London, Manchester, Madrid, Paris, Stockholm und Warschau. Für ein Projekt, das aus Deutschland heraus mit kurzer Latenz nach Europa bedient werden soll, ist Frankfurt der naheliegende Punkt.

## Häufige Fragen

**Wie lange ist das $300-Guthaben gültig?**
30 Tage ab Aktivierung. Nicht genutztes Guthaben verfällt, eine Auszahlung ist nicht möglich.

**Wird sekunden- oder stündlich abgerechnet?**
Stündlich, mit einer Obergrenze von 672 Stunden pro Monat. Ein dauerhaft laufender Server kostet damit den Monatspreis.

**Kann ich jederzeit kündigen?**
Es gibt keine Jahresbindung, Sie löschen die Instanz und die Abrechnung endet. Bereits gezahlte Beträge werden nicht erstattet, Guthaben ist nicht rückzahlbar.

**Fällt deutsche Mehrwertsteuer an?**
Das hängt von Ihrer steuerlichen Situation und vom Bestellvorgang ab. Prüfen Sie den Endbetrag und die Währung, die im Checkout angezeigt werden, bevor Sie bestätigen. Die Preise auf der Tarifseite sind Nettopreise in US-Dollar.

**Gibt es ein Rechenzentrum in Deutschland?**
Ja, Frankfurt. Weitere europäische Standorte sind Amsterdam, London, Manchester, Madrid, Paris, Stockholm und Warschau.

## Die Entscheidung in drei Sätzen

Für eine statische Website, ein Testsystem oder einen kleinen Dienst reicht der $5,00-Tarif mit 1 vCPU und 1 GB RAM; wer von der schnelleren NVMe-Schreibleistung profitieren will, nimmt die $6,00-Variante. Für ein WordPress-Projekt mit Datenbank und etwas Reserve ist die 2-GB-Konfiguration für $10,00 pro Monat die sinnvollere Untergrenze. Wer dedizierte Kerne braucht, landet bei VX1 ab $120,00, und wer mit 24 GB RAM nicht auskommt, ist bei Vultr an der falschen Adresse.

Bevor Sie bestellen, zwei Dinge prüfen: das Ablaufdatum des Guthabens in der Abrechnungsübersicht und die Währung des Endbetrags. Und wenn Sie nur testen wollen, löschen Sie die Instanz rechtzeitig. Ausschalten reicht nicht.

👉 [Zu den aktuellen Vultr-Preisen und Tarifen](https://bit.ly/VuLtr)
