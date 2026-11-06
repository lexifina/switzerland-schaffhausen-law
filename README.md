# Schaffhausen: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Schaffhausen, Switzerland, which global-law reads at `switzerland/schaffhausen/acts/`.

The law of the canton of Schaffhausen (Kanton Schaffhausen, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-sh/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

282 acts with 407 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 194 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `101-000/` | Verfassung des Kantons Schaffhausen (SHR 101.000) | 3 | oldest version available, then each consolidated version: 9 February 2020 to 1 January 2027 |
| `120-100/` | Gemeindegesetz (SHR 120.100) | 3 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2026 |
| `130-100/` | Gesetz über die Ausrichtung von Beiträgen an die Landeskirchen (SHR 130.100) | 1 | one version (the oldest available), 1 January 2015 |
| `141-100/` | Bürgerrechtsgesetz (SHR 141.100) | 1 | one version (the oldest available), 1 January 2023 |
| `160-100-wahlgesetz/` | Gesetz über die vom Volke vorzunehmenden Abstimmungen und Wahlen sowie über die Ausübung der Volksrechte (SHR 160.100) | 1 | one version (the oldest available), 1 July 2019 |
| `160-200/` | Gesetz über die Durchführung von Wahlen ohne Wahlgang (stille Wahlen) (SHR 160.200) | 1 | one version (the oldest available), 1 February 2000 |
| `170-100/` | Gesetz über die Gewaltentrennung (SHR 170.100) | 1 | as enacted, 1 January 1969 |
| `170-200/` | Gesetz über die Ombudsstelle (Ombudsgesetz) (SHR 170.200) | 2 | as enacted, then each consolidated version: 15 September 2025 to 1 January 2026 |
| `170-300-haftungsgesetz/` | Gesetz über die Haftung des Staates und der Gemeinden sowie ihrer Behördemitglieder und Arbeitnehmer (SHR 170.300) | 1 | one version (the oldest available), 1 January 2013 |
| `171-100/` | Gesetz über den Kantonsrat (SHR 171.100) | 2 | oldest version available, then each consolidated version: 1 April 2024 to 1 January 2025 |
| `172-100-organisationsgesetz/` | Gesetz über die Organisation der Regierungs- und Verwaltungstätigkeit (SHR 172.100) | 1 | one version (the oldest available), 1 September 2004 |
| `172-200-verwaltungsrechtspflegegesetz/` | Gesetz über den Rechtsschutz in Verwaltungssachen (SHR 172.200) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 November 2025 |
| `172-500/` | Einführungsgesetz zum Bundesgesetz über den Binnenmarkt (BGBM) (SHR 172.500) | 1 | one version (the oldest available), 1 July 2007 |
| `172-700-itsh-gesetz-itshg/` | Gesetz über die Informatik Schaffhausen (SHR 172.700) | 1 | one version (the oldest available), 1 January 2024 |
| `173-100/` | Gesetz über den Fristenablauf (SHR 173.100) | 1 | as enacted, 14 November 1965 |
| `173-200-jg/` | Justizgesetz (SHR 173.200) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 May 2026 |
| `173-800/` | Gesetz über das Anwaltswesen (SHR 173.800) | 1 | one version (the oldest available), 1 January 2011 |
| `174-100-kantonales-datenschutzgesetz/` | Gesetz über den Schutz von Personendaten (SHR 174.100) | 1 | one version (the oldest available), 1 December 2021 |
| `180-100-personalgesetz/` | Gesetz über das Arbeitsverhältnis des Staatspersonals (SHR 180.100) | 2 | oldest version available, then each consolidated version: 1 July 2016 to 1 January 2026 |
| `185-100/` | Pensionskassengesetz (SHR 185.100) | 1 | one version (the oldest available), 1 July 2016 |
| `210-100/` | Gesetz über die Einführung des Schweizerischen Zivilgesetzbuches (SHR 210.100) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2026 |
| `211-412-eg-bewg/` | Einführungsgesetz zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (SHR 211.412) | 1 | as enacted, 1 November 1988 |
| `211-500-kgeoig/` | Kantonales Geoinformationsgesetz (SHR 211.500) | 1 | as enacted, 1 January 2014 |
| `311-100/` | Gesetz über die Einführung des Schweizerischen Strafgesetzbuches (StGB) (SHR 311.100) | 1 | one version (the oldest available), 1 January 2024 |
| `354-100/` | Polizeigesetz (SHR 354.100) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2025 |
| `360-100-gso/` | Gesetz über den Solidaritätsbeitrag an Opfer von fürsorgerischen Zwangsmassnahmen und Fremdplatzierungen vor 1981 und an Betroffene von Medikamentenversuchen in der psychiatrischen Klinik Breitenau zwischen 1950 und 1980 (SHR 360.100) | 1 | as enacted, 1 January 2026 |
| `410-100/` | Schulgesetz (SHR 410.100) | 2 | oldest version available, then each consolidated version: 1 April 2023 to 1 June 2026 |
| `410-500/` | Gesetz über die Subventionierung von Schulbauten sowie von Kindergärten, Schülerhorten und Kinderkrippen (SHR 410.500) | 1 | one version (the oldest available), 1 January 2024 |
| `412-100/` | Einführungsgesetz zum Berufsbildungsgesetz (SHR 412.100) | 3 | oldest version available, then each consolidated version: 1 August 2022 to 1 June 2026 |
| `414-100/` | Gesetz über die Ausrichtung von Beiträgen an kantonale Hochschulen (SHR 414.100) | 1 | as enacted, 1 January 1993 |
| `414-200-hgsh/` | Hochschulgesetz (SHR 414.200) | 1 | one version (the oldest available), 1 August 2020 |
| `441-100/` | Kulturgesetz (SHR 441.100) | 1 | as enacted, 1 July 2006 |
| `444-100-musikschulgesetz/` | Gesetz über die Ausrichtung von Beiträgen an Musikschulen im Kanton Schaffhausen (SHR 444.100) | 1 | one version (the oldest available), 1 July 2007 |
| `451-100/` | Gesetz über den Natur- und Heimatschutz im Kanton Schaffhausen (SHR 451.100) | 1 | one version (the oldest available), 1 January 2019 |
| `455-200/` | Gesetz über das Halten von Hunden (SHR 455.200) | 1 | one version (the oldest available), 1 January 2010 |
| `500-100-bevsg/` | Bevölkerungsschutzgesetz (SHR 500.100) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `520-100-zsg/` | Zivilschutzgesetz (SHR 520.100) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `550-100-brandschutzgesetz-bsg/` | Gesetz über den Brandschutz und die Feuerwehr (SHR 550.100) | 1 | one version (the oldest available), 1 March 2017 |
| `611-100/` | Finanzhaushaltsgesetz (SHR 611.100) | 4 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `611-104/` | Gesetz über den Finanzhaushalt des Kantons und der Gemeinden (Noch in Kraft stehende Bestimmungen) (SHR 611.104) | 1 | one version (the oldest available), 1 January 2018 |
| `621-100/` | Gesetz über den Finanzausgleich (SHR 621.100) | 1 | one version (the oldest available), 1 January 2008 |
| `621-200/` | Gesetz über die Verwendung eines Anteils aus dem Verkauf der Goldreserven der Schweizerischen Nationalbank zugunsten der Gemeinden (SHR 621.200) | 1 | as enacted, 1 August 2006 |
| `621-300-nfa-gesetz/` | Gesetz über die Einführung der Neugestaltung des Finanzausgleichs und der Aufgabenteilung zwischen Bund und Kantonen im Kanton Schaffhausen (SHR 621.300) | 1 | one version (the oldest available), 1 January 2012 |
| `641-100/` | Gesetz über die direkten Steuern (SHR 641.100) | 4 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `643-100/` | Gesetz über die Erbschafts- und Schenkungssteuer (SHR 643.100) | 1 | one version (the oldest available), 1 January 2008 |
| `645-100/` | Gesetz über die Strassenverkehrssteuern (SHR 645.100) | 1 | one version (the oldest available), 1 January 2007 |
| `646-100/` | Gesetz über die Besteuerung von Wasserfahrzeugen (SHR 646.100) | 1 | one version (the oldest available), 1 January 2007 |
| `680-100/` | Gesetz über das Salzregal (SHR 680.100) | 1 | as enacted, 8 December 1974 |
| `700-100-baugesetz/` | Gesetz über die Raumplanung und das öffentliche Baurecht (SHR 700.100) | 3 | oldest version available, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `700-200-mag/` | Mehrwertausgleichsgesetz (SHR 700.200) | 1 | as enacted, 1 January 2019 |
| `711-100/` | Enteignungsgesetz für den Kanton Schaffhausen (SHR 711.100) | 1 | one version (the oldest available), 1 January 2019 |
| `721-100/` | Wasserwirtschaftsgesetz (SHR 721.100) | 2 | oldest version available, then each consolidated version: 1 October 2022 to 1 August 2026 |
| `725-100/` | Strassengesetz (SHR 725.100) | 1 | one version (the oldest available), 1 January 2022 |
| `730-100/` | Energiegesetz (SHR 730.100) | 1 | as enacted, 1 January 2026 |
| `740-100/` | Gesetz über die Verbesserung der Verkehrsinfrastruktur (SHR 740.100) | 1 | as enacted, 1 November 2011 |
| `741-100/` | Einführungsgesetz zum Bundesgesetz über den Strassenverkehr (SHR 741.100) | 1 | as enacted, 1 September 2004 |
| `743-100/` | Gesetz über die Förderung des öffentlichen Verkehrs (SHR 743.100) | 2 | oldest version available, then each consolidated version: 1 November 2011 to 1 January 2026 |
| `810-100-gesg/` | Gesundheitsgesetz (SHR 810.100) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2025 |
| `811-100-eg-fap/` | Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (SHR 811.100) | 1 | as enacted, 1 January 2025 |
| `813-100/` | Spitalgesetz (SHR 813.100) | 2 | oldest version available, then each consolidated version: 1 March 2021 to 1 January 2026 |
| `813-500-abpg/` | Altersbetreuungs- und Pflegegesetz (SHR 813.500) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 November 2026 |
| `814-100-einfuhrungsgesetz-zum-usg/` | Gesetz über die Einführung des Bundesgesetzes über den Umweltschutz (SHR 814.100) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `814-200/` | Einführungsgesetz zum Gewässerschutzgesetz (SHR 814.200) | 1 | one version (the oldest available), 1 January 2014 |
| `814-500/` | Gesetz gegen Atommüll-Lagerstätten (SHR 814.500) | 1 | one version (the oldest available), 1 April 2011 |
| `817-100-einfuhrungsgesetz-zum-lebensmittelgesetz-eg-lmg/` | Gesetz über die Einführung des Bundesgesetzes über Lebensmittel und Gebrauchsgegenstände (SHR 817.100) | 1 | as enacted, 1 September 2021 |
| `831-100/` | Einführungsgesetz zu den Bundesgesetzen über die Alters- und Hinterlassenenversicherung und über die Invalidenversicherung (SHR 831.100) | 4 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2028 |
| `831-300/` | Gesetz über Ergänzungsleistungen zur AHV und IV (SHR 831.300) | 2 | oldest version available, then each consolidated version: 1 July 2016 to 1 January 2027 |
| `832-100/` | Krankenversicherungsgesetz (SHR 832.100) | 1 | one version (the oldest available), 1 January 2014 |
| `832-110/` | Dekret über den Vollzug des Krankenversicherungsgesetzes (SHR 832.110) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2025 |
| `836-100-fsg/` | Gesetz über Familien- und Sozialzulagen (SHR 836.100) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2027 |
| `837-100-ahg/` | Arbeitslosenhilfegesetz (SHR 837.100) | 3 | oldest version available, then each consolidated version: 31 December 2019 to 1 January 2027 |
| `850-100-sheg/` | Gesetz über die öffentliche Sozialhilfe und soziale Einrichtungen (SHR 850.100) | 1 | one version (the oldest available), 1 July 2018 |
| `860-100/` | Gesetz zur Förderung der familienergänzenden Kinderbetreuung im Vorschulalter (SHR 860.100) | 1 | as enacted, 1 January 2021 |
| `900-100/` | Wirtschaftsförderungsgesetz (SHR 900.100) | 1 | one version (the oldest available), 1 October 2020 |
| `900-200-ruhetagsgesetz/` | Gesetz betreffend die öffentlichen Ruhetage und den Ladenschluss (SHR 900.200) | 1 | one version (the oldest available), 1 January 2007 |
| `900-300/` | Gesetz zur Förderung der Regional- und Standortentwicklung im Kanton Schaffhausen (SHR 900.300) | 1 | one version (the oldest available), 1 January 2018 |
| `900-400-kantonales-parkgesetz/` | Gesetz über Pärke von nationaler Bedeutung im Kanton Schaffhausen (SHR 900.400) | 1 | as enacted, 1 January 2020 |
| `900-500/` | Gesetz über Sofortmassnahmen zur Bewältigung der Coronavirus-Krise (SHR 900.500) | 1 | one version (the oldest available), 25 January 2021 |
| `910-100-kantonales-landwirtschaftsgesetz-lwg/` | Gesetz über die Förderung der Landwirtschaft (SHR 910.100) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 April 2026 |
| `921-100/` | Kantonales Waldgesetz (SHR 921.100) | 1 | one version (the oldest available), 1 January 2014 |
| `922-100-kantonales-jagdgesetz/` | Gesetz über die Jagd und den Schutz wildlebender Säugetiere und Vögel (SHR 922.100) | 1 | one version (the oldest available), 1 January 2011 |
| `932-100/` | Gesetz über Warenhandel und Schaustellungen (SHR 932.100) | 1 | one version (the oldest available), 1 September 2021 |
| `935-100-gastgewerbegesetz/` | Gesetz über das Gastgewerbe und den Kleinhandel mit alkoholhaltigen Getränken (SHR 935.100) | 1 | one version (the oldest available), 1 September 2021 |
| `935-200/` | Tourismusförderungsgesetz (SHR 935.200) | 1 | as enacted, 1 January 2018 |
| `935-500-eg-bgs/` | Einführungsgesetz zum Bundesgesetz über Geldspiele (SHR 935.500) | 1 | one version (the oldest available), 1 January 2024 |
| `951-100/` | Gesetz über die Schaffhauser Kantonalbank (SHR 951.100) | 1 | one version (the oldest available), 1 January 2011 |
| `951-200/` | Gesetz über eine Jubiläumsausschüttung 2008 der Schaffhauser Kantonalbank (SHR 951.200) | 1 | as enacted, 1 September 2008 |
| `960-100-gebaudeversicherungsgesetz-gebvg/` | Gesetz über die Gebäudeversicherung im Kanton Schaffhausen (SHR 960.100) | 1 | one version (the oldest available), 1 January 2018 |
| `120-101/` | Gemeindearchivverordnung (SHR 120.101) | 1 | as enacted, 1 January 2010 |
| `141-111/` | Verordnung zum Bürgerrechtsgesetz (SHR 141.111) | 1 | as enacted, 1 January 2018 |
| `142-201-vollziehungsverordnung-aig/` | Vollziehungsverordnung zum Bundesgesetz über die Ausländerinnen und Ausländer und über die Integration vom 16. Dezember 2005 und dem Abkommen zwischen der Europäischen Gemeinschaft und ihren Mitgliedstaaten einerseits und der Schweizerischen Eidgenossenschaft andererseits über die Freizügigkeit vom 21. Juni 1999 (SHR 142.201) | 2 | oldest version available, then each consolidated version: 1 January 2019 to 1 January 2026 |
| `143-112-ausweisverordnung/` | Vollziehungsverordnung über die Ausstellung von Ausweisen für Schweizer Staatsangehörige (SHR 143.112) | 2 | oldest version available, then each consolidated version: 1 August 2012 to 2 November 2026 |
| `160-101/` | Verordnung über die versuchsweise Einführung der elektronischen Stimmabgabe für Auslandschweizerinnen und Auslandschweizer (SHR 160.101) | 1 | as enacted, 1 May 2010 |
| `160-102-tpvo/` | Transparenzverordnung (SHR 160.102) | 1 | as enacted, 1 July 2026 |
| `160-112/` | Verordnung über die Zustellung der eidgenössischen und kantonalen Abstimmungsvorlagen und Erläuterungen (SHR 160.112) | 1 | as enacted, 1 August 1995 |
| `161-111-proporzwahlverordnung/` | Verordnung über die Wahl des Kantonsrates und die Wahl der Einwohnerräte nach dem proportionalen Wahlverfahren (SHR 161.111) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `165-111/` | Verordnung über die Durchführung der Nationalratswahlen (SHR 165.111) | 1 | one version (the oldest available), 9 December 1994 |
| `170-501/` | Verordnung betreffend die Einsichtnahme in die Sammlungen des Bundesrechts (SHR 170.501) | 1 | as enacted, 1 January 1988 |
| `170-502/` | Verordnung über die Herausgabe des Amtsblattes des Kantons Schaffhausen und weiterer offizieller Drucksachen (SHR 170.502) | 1 | as enacted, 1 January 2024 |
| `171-112/` | Reglement betreffend elektronische Abstimmungsanlage im Kantonsratssaal (SHR 171.112) | 1 | as enacted, 1 January 2018 |
| `172-101-organisationsverordnung/` | Verordnung über die Organisation der kantonalen Verwaltung (SHR 172.101) | 2 | oldest version available, then each consolidated version: 1 March 2024 to 1 August 2026 |
| `172-103/` | Verordnung über Sofortmassnahmen zur Bewältigung der Coronavirus-Krise (SHR 172.103) | 1 | one version (the oldest available), 17 April 2020 |
| `172-201-verwaltungsgebuhrenverordnung/` | Verordnung über die Gebühren im kantonalen Verwaltungsverfahren (SHR 172.201) | 1 | one version (the oldest available), 1 January 2014 |
| `172-202-verv/` | Verordnung über den elektronischen Rechtsverkehr in Verfahren vor Verwaltungsbehörden (SHR 172.202) | 2 | as enacted, then each consolidated version: 1 January 2014 to 15 March 2026 |
| `172-301-archivverordnung/` | Verordnung über das Staatsarchiv und die Archivierung der Verwaltungsakten (SHR 172.301) | 1 | one version (the oldest available), 1 January 2020 |
| `172-302/` | Verordnung über die Gebühren für Beglaubigungen durch die Staatskanzlei (SHR 172.302) | 1 | one version (the oldest available), 1 August 2012 |
| `173-122-entschadigungsverordnung/` | Verordnung des Obergerichts über Entschädigungen im Gerichtsverfahren (SHR 173.122) | 1 | one version (the oldest available), 1 January 2011 |
| `173-151-akzessistenverordnung/` | Verordnung des Obergerichts über die Akzessistinnen und Akzessisten (SHR 173.151) | 3 | oldest version available, then each consolidated version: 1 March 2024 to 1 January 2026 |
| `173-201-ejustizaktenverordnung-ejav/` | Verordnung über die elektronische Aktenführung der Justizbehörden (SHR 173.201) | 1 | as enacted, 1 October 2026 |
| `173-811-honorarverordnung-honv/` | Verordnung des Obergerichts über das Honorar für unentgeltliche Vertretung und amtliche Verteidigung (SHR 173.811) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 September 2024 |
| `173-812-anwaltsverordnung-rav/` | Verordnung des Obergerichts über das Anwaltswesen (SHR 173.812) | 1 | one version (the oldest available), 1 January 2014 |
| `174-101-kantonale-datenschutzverordnung/` | Verordnung über den Schutz von Personendaten (SHR 174.101) | 1 | as enacted, 1 December 2021 |
| `174-102-informatiksicherheitsverordnung-isv/` | Verordnung betreffend Informatiksicherheit (SHR 174.102) | 1 | as enacted, 1 January 2015 |
| `180-101-lohnverordnung/` | Verordnung über die Entlöhnung des Staatspersonals (SHR 180.101) | 4 | oldest version available, then each consolidated version: 1 January 2023 to 1 May 2026 |
| `180-111-personalverordnung/` | Verordnung über die Arbeitsverhältnisse des Staatspersonals (SHR 180.111) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2026 |
| `180-112-spesenverordnung/` | Verordnung über die Spesenvergütungen beim Kanton Schaffhausen (SHR 180.112) | 1 | as enacted, 1 January 2007 |
| `180-113-arbeitszeitverordnung/` | Verordnung über die Arbeitszeit des Staatspersonals (SHR 180.113) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2026 |
| `180-115/` | Verordnung über die Zuteilung von Parkplätzen in der kantonalen Verwaltung (SHR 180.115) | 1 | one version (the oldest available), 1 December 2015 |
| `180-131-ubergangsrentenverordnung-urv/` | Verordnung über die Ausrichtung einer Übergangsrente bei vorzeitigem Rücktritt aus dem Staatsdienst (SHR 180.131) | 4 | oldest version available, then each consolidated version: 1 January 2024 to 1 July 2026 |
| `211-111/` | Kantonale Zivilstandsverordnung (SHR 211.111) | 1 | one version (the oldest available), 1 January 2021 |
| `211-121/` | Verordnung betreffend die Aufsicht über die Stiftungen (SHR 211.121) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `211-221/` | Kantonale Adoptionsverordnung (SHR 211.221) | 1 | one version (the oldest available), 1 January 2018 |
| `211-222-alimentenbevorschussungsverordnung/` | Verordnung über die Inkassohilfe und Bevorschussung von Unterhaltsbeiträgen für Kinder (SHR 211.222) | 1 | one version (the oldest available), 1 January 2017 |
| `211-223/` | Verordnung über die Zusammenarbeit in der Jugendpolitik und Jugendhilfe (SHR 211.223) | 1 | one version (the oldest available), 1 March 2024 |
| `211-224/` | Kantonale Pflegekinderverordnung (SHR 211.224) | 2 | oldest version available, then each consolidated version: 1 August 2024 to 1 January 2026 |
| `211-231/` | Erbschaftsverordnung (SHR 211.231) | 1 | as enacted, 1 May 2016 |
| `211-232/` | Erbschaftsgebührenverordnung (SHR 211.232) | 1 | as enacted, 1 May 2016 |
| `211-233-beistandsentschadigungsverordnung/` | Verordnung über die Entschädigung und den Spesenersatz der Beistände (SHR 211.233) | 1 | as enacted, 1 January 2013 |
| `211-431/` | Grundbuchverordnung (SHR 211.431) | 1 | one version (the oldest available), 1 January 2014 |
| `211-433/` | Grundbuchgebührenverordnung (SHR 211.433) | 1 | one version (the oldest available), 1 January 2011 |
| `211-441/` | Verordnung über die amtliche Vermessung (SHR 211.441) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2025 |
| `211-501-kgeoiv/` | Kantonale Geoinformationsverordnung (SHR 211.501) | 1 | one version (the oldest available), 1 January 2024 |
| `221-101-notariatsgebuhrenverordnung/` | Verordnung über die Gebühren für öffentliche Beurkundungen (SHR 221.101) | 1 | one version (the oldest available), 1 January 2016 |
| `221-201/` | Verordnung über die Einführung des Konsumkreditgesetzes (SHR 221.201) | 1 | as enacted, 1 January 2004 |
| `221-215/` | Verordnung zum Bundesgesetz über die Allgemeinverbindlicherklärung von Gesamtarbeitsverträgen (SHR 221.215) | 1 | as enacted, 1 June 2011 |
| `281-101/` | Verordnung über die Betreibungskreise (SHR 281.101) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2025 |
| `311-101/` | Verordnung über den unmittelbaren Busseneinzug (SHR 311.101) | 1 | one version (the oldest available), 1 January 2020 |
| `311-102-kobv/` | Kantonale Verordnung über das Ordnungsbussenverfahren (SHR 311.102) | 1 | one version (the oldest available), 1 January 2024 |
| `320-111/` | Verordnung des Obergerichts über die Archivierung der Justizakten (SHR 320.111) | 1 | one version (the oldest available), 1 January 2016 |
| `320-412-dna-verordnung/` | Verordnung über den Vollzug der Bundesgesetzgebung über die DNA-Analyse (SHR 320.412) | 1 | one version (the oldest available), 1 January 2011 |
| `320-511/` | Verordnung des Obergerichts über die Zulassung und Stellung von Gerichtsberichterstattern (SHR 320.511) | 1 | one version (the oldest available), 1 January 2011 |
| `331-101/` | Verordnung über das Strafregister (SHR 331.101) | 1 | as enacted, 1 January 2019 |
| `341-101-jvv/` | Justizvollzugsverordnung (SHR 341.101) | 2 | oldest version available, then each consolidated version: 1 April 2022 to 1 January 2026 |
| `354-111-polv/` | Polizeiverordnung (SHR 354.111) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2025 |
| `354-112-poldatv/` | Verordnung über die polizeiliche Datenbearbeitung (SHR 354.112) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 June 2026 |
| `360-101-kohv/` | Kantonale Verordnung über die Opferhilfe (SHR 360.101) | 1 | one version (the oldest available), 1 January 2023 |
| `410-102-tagesstrukturverordnung/` | Verordnung betreffend die Ausrichtung von Kantonsbeiträgen an schulergänzende Tagesstrukturen (SHR 410.102) | 2 | oldest version available, then each consolidated version: 1 March 2024 to 1 January 2027 |
| `410-112/` | Verordnung des Erziehungsrates betreffend private Schulen und privater Unterricht (SHR 410.112) | 1 | as enacted, 1 April 2023 |
| `410-115/` | Verordnung des Erziehungsrates betreffend den Vollzug des Förderungskonzepts zum Programm des Bundes «Junge Talente Musik» (SHR 410.115) | 1 | as enacted, 1 June 2025 |
| `410-302-konferenzreglement/` | Verordnung des Erziehungsrates über die Lehrerkonferenzen (SHR 410.302) | 3 | oldest version available, then each consolidated version: 1 April 2022 to 1 August 2026 |
| `410-303/` | Verordnung des Erziehungsrates über das Schulinspektorat (SHR 410.303) | 1 | one version (the oldest available), 1 March 2024 |
| `410-304/` | Verordnung über die Aufgaben der Abteilung Schulische Abklärung und Beratung (Schulpsychologischer Dienst) (SHR 410.304) | 1 | one version (the oldest available), 1 August 2023 |
| `410-305/` | Verordnung über den schulischen Sozialdienst des Kantons Schaffhausen (SHR 410.305) | 1 | one version (the oldest available), 1 March 2024 |
| `410-306/` | Verordnung des Erziehungsrates betreffend die Schulleitungen der Primar- und Sekundarstufe I des Kantons Schaffhausen (SHR 410.306) | 1 | as enacted, 1 August 2017 |
| `410-401-lehrerverordnung/` | Verordnung über die Arbeitsverhältnisse der Lehrpersonen an den öffentlichen Schulen (SHR 410.401) | 5 | oldest version available, then each consolidated version: 1 August 2024 to 1 August 2027 |
| `410-403-berufseinfuhrungsverordnung/` | Verordnung des Erziehungsrates über die Berufseinführung der Lehrpersonen der Volksschule und die Einführung der Wiedereinsteigerinnen und Wiedereinsteiger (SHR 410.403) | 2 | as enacted, then each consolidated version: 1 February 2004 to 1 August 2027 |
| `410-404/` | Verordnung des Erziehungsrates über die Zusatzausbildung von Primarlehrpersonen zu Lehrpersonen der Sekundarstufe I (SHR 410.404) | 1 | as enacted, 1 January 2021 |
| `410-407/` | Verordnung über die Intensivweiterbildung der Lehrpersonen (SHR 410.407) | 1 | as enacted, 1 August 2021 |
| `410-408/` | Verordnung betreffend die Beurteilung der Lehrpersonen an der Kantonsschule sowie an den Berufsfachschulen und den Höheren Fachschulen (SHR 410.408) | 2 | oldest version available, then each consolidated version: 1 August 2020 to 1 October 2025 |
| `410-409/` | Verordnung betreffend die Beurteilung der Lehrpersonen an Kindergärten, Primar- und Orientierungsschulen (SHR 410.409) | 1 | one version (the oldest available), 1 August 2017 |
| `410-410/` | Verordnung betreffend die Beurteilung der Logopädinnen und Logopäden im Ambulatorium (SHR 410.410) | 1 | as enacted, 1 November 2005 |
| `410-411-berufsschullehrerverordnung/` | Verordnung über die Arbeitsverhältnisse der Lehrpersonen an den kantonalen Berufsfachschulen und Höheren Fachschulen (SHR 410.411) | 1 | one version (the oldest available), 1 August 2024 |
| `410-413/` | Verordnung über die Weiterbildung der Lehrpersonen (SHR 410.413) | 2 | oldest version available, then each consolidated version: 1 August 2017 to 1 August 2024 |
| `410-414/` | Verordnung über die Weiterbildung der Lehrpersonen an der Kantonsschule (SHR 410.414) | 2 | oldest version available, then each consolidated version: 1 August 2020 to 1 August 2024 |
| `410-511/` | Verordnung über die Subventionierung von Schulbauten (SHR 410.511) | 2 | as enacted, then each consolidated version: 17 January 1968 to 1 January 2024 |
| `410-621/` | Verordnung über den Betrieb und das Behandlungsangebot der Schulzahnklinik (SHR 410.621) | 1 | one version (the oldest available), 1 August 2014 |
| `411-001-kindergartenverordnung/` | Verordnung des Erziehungsrates betreffend die Kindergärten (SHR 411.001) | 1 | one version (the oldest available), 1 August 2017 |
| `411-101/` | Verordnung des Erziehungsrates betreffend die Schulordnung der Primar- und Orientierungsschulen des Kantons Schaffhausen (SHR 411.101) | 2 | oldest version available, then each consolidated version: 1 August 2023 to 1 August 2025 |
| `411-102/` | Verordnung des Erziehungsrates über Zeugnisse und Beförderung der Schülerinnen und Schüler an der Primar- und Sekundarstufe I (SHR 411.102) | 1 | one version (the oldest available), 1 August 2018 |
| `411-111/` | Verordnung über die Bildung von Schulkreisen für die Orientierungsschulen und die Sonderklassen (SHR 411.111) | 1 | one version (the oldest available), 1 August 2023 |
| `411-121/` | Verordnung des Erziehungsrates über die Sonderklassen (SHR 411.121) | 1 | one version (the oldest available), 1 August 2023 |
| `411-222-sonderschulverordnung/` | Verordnung des Erziehungsrates über die Sonderschulung (SHR 411.222) | 2 | oldest version available, then each consolidated version: 1 September 2023 to 1 June 2026 |
| `411-225/` | Verordnung über die Beiträge des Kantons an die Sonderschulung (SHR 411.225) | 1 | one version (the oldest available), 1 September 2023 |
| `412-101/` | Verordnung zum Einführungsgesetz zum Berufsbildungsgesetz (SHR 412.101) | 2 | oldest version available, then each consolidated version: 1 April 2023 to 1 April 2025 |
| `412-102/` | Verordnung über die Schul- bzw. Studiengelder und die Gebühren im Berufsbildungswesen (SHR 412.102) | 1 | one version (the oldest available), 1 February 2023 |
| `412-103-schulgeldbeitragsverordnung/` | Verordnung über die Beiträge an das Schul- bzw. Studiengeld für den Besuch ausserkantonaler Schulen und Kurse im Bereich der Berufsbildung (SHR 412.103) | 1 | one version (the oldest available), 1 January 2015 |
| `412-105/` | Verordnung über die Entschädigung der Mitglieder des Berufsbildungsrates und der kantonalen Kommissionen im Bereich der Berufsbildung (SHR 412.105) | 1 | as enacted, 1 January 2021 |
| `413-101/` | Verordnung des Erziehungsrates betreffend die Schulordnung der Kantonsschule Schaffhausen (SHR 413.101) | 2 | oldest version available, then each consolidated version: 1 August 2020 to 1 August 2025 |
| `413-102/` | Verordnung des Erziehungsrates betreffend die Aufsichtskommission der Kantonsschule (SHR 413.102) | 1 | one version (the oldest available), 1 August 2007 |
| `413-103/` | Verordnung betreffend die Schulleitung der Kantonsschule (SHR 413.103) | 1 | one version (the oldest available), 1 January 2024 |
| `413-105-konferenzreglement-der-kantonsschule/` | Verordnung des Erziehungsrates betreffend die Lehrerkonferenzen der Kantonsschule (SHR 413.105) | 2 | oldest version available, then each consolidated version: 1 October 2022 to 1 August 2024 |
| `413-106/` | Verordnung betreffend die Schulgelder an gymnasialen Mittelschulen und Fachmittelschulen (SHR 413.106) | 1 | as enacted, 1 October 2018 |
| `413-107/` | Verordnung der Aufsichtskommission über die Schülerorganisation der Kantonsschule (SHR 413.107) | 1 | as enacted, 1 August 1993 |
| `413-201-promotions-und-maturitatsverordnung/` | Verordnung des Erziehungsrates über Aufnahme, Promotionen und Zeugnisse der Schülerinnen und Schüler der Maturitätsschule sowie über die Maturitätsprüfungen an der Kantonsschule Schaffhausen (SHR 413.201) | 2 | oldest version available, then each consolidated version: 1 August 2022 to 1 August 2026 |
| `413-401-fms-verordnung/` | Verordnung des Erziehungsrates über Aufnahme, Zeugnisse und Promotion der Schülerinnen und Schüler der Fachmittelschule sowie über den Abschluss mit Fachmittelschulausweis oder mit Fachmaturität (SHR 413.401) | 2 | oldest version available, then each consolidated version: 1 August 2022 to 1 August 2026 |
| `414-201/` | Verordnung über die Pädagogische Hochschule Schaffhausen (SHR 414.201) | 1 | one version (the oldest available), 1 January 2023 |
| `414-202-personalverordnung-phsh/` | Verordnung über die Arbeitsverhältnisse von Dozierenden, wissenschaftlichen Mitarbeitenden und Assistierenden der Pädagogischen Hochschule Schaffhausen (SHR 414.202) | 1 | as enacted, 1 August 2020 |
| `414-203-hochschul-und-disziplinarordnung/` | Verordnung des Hochschulrates betreffend die Hochschul- und Disziplinarordnung für Studierende der Pädagogischen Hochschule Schaffhausen (SHR 414.203) | 1 | one version (the oldest available), 1 February 2023 |
| `414-204-studiengangverordnung/` | Verordnung des Hochschulrates betreffend die Studiengänge im Leistungsbereich Ausbildung der Pädagogischen Hochschule Schaffhausen (SHR 414.204) | 2 | oldest version available, then each consolidated version: 1 February 2023 to 1 September 2025 |
| `414-205-zulassungsverordnung/` | Verordnung des Hochschulrates über die Zulassung und die Anmeldung zum Studium im Leistungsbereich Ausbildung an der Pädagogischen Hochschule Schaffhausen (SHR 414.205) | 2 | oldest version available, then each consolidated version: 1 September 2022 to 1 February 2026 |
| `414-206-prufungsverordnung/` | Verordnung des Hochschulrates betreffend Eignungsabklärung und Leistungsbeurteilung im Leistungsbereich Ausbildung an der Pädagogischen Hochschule Schaffhausen (SHR 414.206) | 3 | oldest version available, then each consolidated version: 1 February 2023 to 1 February 2026 |
| `414-207/` | Verordnung des Hochschulrates betreffend die Hochschulleitung der Pädagogischen Hochschule Schaffhausen (SHR 414.207) | 2 | as enacted, then each consolidated version: 1 August 2020 to 1 July 2025 |
| `414-208-verordnung-cas-schulleitung/` | Verordnung betreffend die Zusatzausbildung Certificate of Advanced Studies in Schulleitung der Pädagogischen Hochschule Schaffhausen (SHR 414.208) | 1 | as enacted, 1 August 2023 |
| `415-101-sportfondsverordnung/` | Verordnung über die Verwendung der Mittel aus dem Swisslos-Sportfonds (SHR 415.101) | 1 | as enacted, 1 January 2023 |
| `415-201/` | Verordnung über Turnen und Sport in der Schule (SHR 415.201) | 1 | as enacted, 1 April 1974 |
| `416-011-stipendienverordnung/` | Verordnung betreffend die Ausrichtung von Stipendien und Studiendarlehen (SHR 416.011) | 1 | one version (the oldest available), 1 August 2021 |
| `431-101/` | Verordnung über das Einwohnerregister (SHR 431.101) | 1 | one version (the oldest available), 1 July 2016 |
| `441-101/` | Verordnung zum Kulturgesetz (SHR 441.101) | 1 | as enacted, 1 January 2007 |
| `451-101-naturschutzverordnung/` | Verordnung über den Naturschutz (SHR 451.101) | 1 | one version (the oldest available), 1 January 2021 |
| `451-102/` | Vollziehungsverordnung zum Natur- und Heimatschutzgesetz (NHG) (SHR 451.102) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 November 2025 |
| `451-105/` | Verordnung über den Schutz von Pilzen in den Gemeinden Buchberg und Rüdlingen (SHR 451.105) | 1 | one version (the oldest available), 1 January 2007 |
| `452-001/` | Verordnung betreffend den Schutz der Kulturdenkmäler (SHR 452.001) | 1 | as enacted, 22 September 1939 |
| `455-101/` | Vollzugsverordnung zum Tierschutzgesetz (SHR 455.101) | 1 | as enacted, 1 January 2009 |
| `455-201-hundeverordnung/` | Verordnung zum Gesetz über das Halten von Hunden (SHR 455.201) | 1 | one version (the oldest available), 1 January 2017 |
| `500-101-kbevsv/` | Kantonale Bevölkerungsschutzverordnung (SHR 500.101) | 2 | oldest version available, then each consolidated version: 1 July 2019 to 1 January 2026 |
| `500-102-kav/` | Kantonale Alarmierungsverordnung (SHR 500.102) | 1 | one version (the oldest available), 1 July 2019 |
| `510-101/` | Kantonale Militärverordnung (SHR 510.101) | 2 | oldest version available, then each consolidated version: 1 July 2019 to 1 July 2025 |
| `514-521-wafv/` | Kantonale Waffenverordnung (SHR 514.521) | 1 | one version (the oldest available), 1 December 2008 |
| `520-101-kzsv/` | Kantonale Zivilschutzverordnung (SHR 520.101) | 2 | oldest version available, then each consolidated version: 1 July 2019 to 1 January 2026 |
| `550-101-bsv/` | Brandschutzverordnung (SHR 550.101) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2026 |
| `611-103/` | Finanzhaushaltsverordnung (SHR 611.103) | 3 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2025 |
| `641-111/` | Verordnung über die direkten Steuern (SHR 641.111) | 4 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2026 |
| `641-301/` | Verordnung über die Bewertung der Grundstücke (SHR 641.301) | 1 | one version (the oldest available), 1 August 2014 |
| `642-111/` | Verordnung zum Bundesgesetz über die direkte Bundessteuer (SHR 642.111) | 1 | one version (the oldest available), 1 January 2016 |
| `642-211/` | Verordnung über den Vollzug des Bundesgesetzes über die Verrechnungsteuer (SHR 642.211) | 1 | one version (the oldest available), 1 January 2022 |
| `643-111/` | Verordnung zum Gesetz über die Erbschafts- und Schenkungssteuer (SHR 643.111) | 1 | one version (the oldest available), 1 January 2010 |
| `645-101/` | Verordnung über die Strassenverkehrssteuern (SHR 645.101) | 1 | one version (the oldest available), 1 January 2018 |
| `646-101/` | Verordnung zum Gesetz über die Besteuerung von Wasserfahrzeugen (SHR 646.101) | 1 | as enacted, 21 February 1986 |
| `672-111/` | Verordnung über die Anrechnung ausländischer Quellensteuern (SHR 672.111) | 1 | one version (the oldest available), 1 January 2021 |
| `700-101-bauv/` | Verordnung zum Baugesetz (SHR 700.101) | 3 | oldest version available, then each consolidated version: 1 January 2024 to 1 July 2026 |
| `700-105/` | Verordnung betreffend Unfallverhütung bei Bauten (SHR 700.105) | 1 | one version (the oldest available), 1 January 2000 |
| `700-108-baubewilligungsgebuhrenverordnung/` | Verordnung über die Gebühren im Baubewilligungsverfahren (SHR 700.108) | 1 | one version (the oldest available), 1 April 2003 |
| `700-201-mav/` | Mehrwertausgleichsverordnung (SHR 700.201) | 1 | as enacted, 1 September 2023 |
| `704-101/` | Verordnung betreffend den Vollzug des Bundesgesetzes über Fuss- und Wanderwege (SHR 704.101) | 1 | one version (the oldest available), 1 January 2020 |
| `711-101/` | Verordnung über die Zuständigkeit zur Beurteilung von Schadenersatzansprüchen gemäss Art. 15 des eidgenössischen Enteignungsgesetzes (SHR 711.101) | 1 | one version (the oldest available), 1 July 1999 |
| `721-103/` | Verordnung zum Wasserwirtschaftsgesetz (SHR 721.103) | 1 | one version (the oldest available), 1 January 2022 |
| `725-101-strassenverordnung/` | Verordnung betreffend den Vollzug des Strassengesetzes (SHR 725.101) | 2 | oldest version available, then each consolidated version: 1 January 2022 to 1 October 2024 |
| `730-001-envv/` | Vollziehungsverordnung zum Bundesbeschluss für eine sparsame und rationelle Energienutzung (SHR 730.001) | 1 | as enacted, 20 March 1992 |
| `730-101-energieverordnung-enerv/` | Energieverordnung (SHR 730.101) | 3 | oldest version available, then each consolidated version: 1 January 2024 to 1 December 2026 |
| `741-011-kantonale-strassenverkehrsverordnung/` | Verordnung zum Bundesgesetz über den Strassenverkehr (SHR 741.011) | 2 | oldest version available, then each consolidated version: 1 July 2016 to 1 May 2026 |
| `741-012/` | Verordnung über die Gebühren im Strassenverkehr (SHR 741.012) | 1 | one version (the oldest available), 1 July 2015 |
| `743-101/` | Verordnung zum Gesetz über die Förderung des öffentlichen Verkehrs (SHR 743.101) | 2 | as enacted, then each consolidated version: 1 January 2006 to 1 January 2026 |
| `744-115/` | Verordnung über das Bewilligungsverfahren nach der Verordnung über die Personenbeförderung (SHR 744.115) | 1 | as enacted, 1 March 2010 |
| `747-201-schifffahrtsverordnung/` | Verordnung über den Vollzug des Schifffahrtsrechts im Kanton Schaffhausen (SHR 747.201) | 1 | one version (the oldest available), 1 January 2001 |
| `748-011/` | Verordnung zum Bundesgesetz vom 21. Dezember 1948 über die Luftfahrt und zur Verordnung des Bundesrates vom 14. November 1973 über die Luftfahrt (SHR 748.011) | 1 | one version (the oldest available), 1 January 2011 |
| `810-101/` | Verordnung zum straflosen Schwangerschaftsabbruch (SHR 810.101) | 1 | one version (the oldest available), 1 April 2007 |
| `810-102-gesv/` | Verordnung zum Gesundheitsgesetz (SHR 810.102) | 1 | one version (the oldest available), 1 January 2022 |
| `811-111-veg-fap/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (SHR 811.111) | 2 | as enacted, then each consolidated version: 1 January 2025 to 15 August 2025 |
| `812-201-heilmittelverordnung-hmv/` | Verordnung über den Verkehr mit Heilmitteln (SHR 812.201) | 2 | oldest version available, then each consolidated version: 1 July 2023 to 1 March 2026 |
| `813-101-spitalverordnung/` | Verordnung zum Spitalgesetz (SHR 813.101) | 1 | one version (the oldest available), 1 January 2022 |
| `813-501-abpv/` | Verordnung zum Altersbetreuungs- und Pflegegesetz (SHR 813.501) | 4 | oldest version available, then each consolidated version: 1 January 2024 to 1 January 2026 |
| `814-101-kantonale-umweltschutzverordnung-usgv/` | Verordnung zum Einführungsgesetz zum Umweltschutzgesetz (SHR 814.101) | 1 | one version (the oldest available), 1 October 2018 |
| `814-102/` | Einführungsverordnung zur Bundesgesetzgebung über den Schutz vor Gefährdungen durch nichtionisierende Strahlung und Schall (SHR 814.102) | 1 | as enacted, 1 July 2023 |
| `814-201-kantonale-gewasserschutzverordnung-gschvv/` | Vollziehungsverordnung zum Einführungsgesetz zum Gewässerschutzgesetz (SHR 814.201) | 1 | one version (the oldest available), 1 July 2010 |
| `814-801/` | Kantonale Chemikalienverordnung (SHR 814.801) | 1 | one version (the oldest available), 1 July 2016 |
| `817-101-kantonale-lebensmittelverordnung-lmv/` | Verordnung zum Einführungsgesetz zum Lebensmittelgesetz (SHR 817.101) | 1 | as enacted, 1 January 2023 |
| `817-102/` | Verordnung über die Gebühren für die Fleischkontrolle und über die Entschädigung der Fleischkontrollorgane (SHR 817.102) | 1 | as enacted, 1 January 2023 |
| `817-402/` | Kantonale Weinverordnung (SHR 817.402) | 2 | oldest version available, then each consolidated version: 15 September 2019 to 1 July 2024 |
| `818-101-kantonale-epidemienverordnung-epv/` | Verordnung über den Vollzug der eidgenössischen Epidemiengesetzgebung (SHR 818.101) | 1 | as enacted, 1 January 2017 |
| `818-301/` | Einführungsverordnung zur Bundesgesetzgebung über Tabakprodukte und elektronische Zigaretten (SHR 818.301) | 2 | as enacted, then each consolidated version: 1 October 2024 to 1 September 2026 |
| `818-601/` | Verordnung über die Leichenschau und die Bestattung (SHR 818.601) | 2 | oldest version available, then each consolidated version: 1 June 2016 to 1 July 2024 |
| `821-401/` | Verordnung betreffend das kantonale Einigungsamt (SHR 821.401) | 1 | one version (the oldest available), 1 January 2017 |
| `822-101/` | Verordnung zum Arbeitsgesetz und zum Bundesgesetz über die Unfallversicherung (SHR 822.101) | 1 | one version (the oldest available), 1 January 2015 |
| `822-301/` | Verordnung zum Bundesgesetz über die Heimarbeit (SHR 822.301) | 1 | one version (the oldest available), 1 January 2000 |
| `823-201/` | Vollziehungsverordnung zu den Bundesgesetzen über die minimalen Arbeits- und Lohnbedingungen für in die Schweiz entsandte Arbeitnehmerinnen und Arbeitnehmer und flankierende Massnahmen sowie über Massnahmen zur Bekämpfung der Schwarzarbeit (SHR 823.201) | 1 | one version (the oldest available), 1 January 2008 |
| `831-101/` | Verordnung über die Alters- und Hinterlassenenversicherung und über die Invalidenversicherung (SHR 831.101) | 2 | oldest version available, then each consolidated version: 1 January 2000 to 1 August 2026 |
| `831-301/` | Verordnung über Ergänzungsleistungen zur AHV und IV (SHR 831.301) | 3 | oldest version available, then each consolidated version: 1 January 2024 to 1 August 2026 |
| `832-111/` | Verordnung über den Vollzug des Krankenversicherungsgesetzes (SHR 832.111) | 4 | oldest version available, then each consolidated version: 1 January 2024 to 1 August 2026 |
| `836-101-fsv/` | Verordnung zum Gesetz über Familien- und Sozialzulagen (SHR 836.101) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 August 2026 |
| `837-101/` | Verordnung zum Arbeitslosenhilfegesetz (SHR 837.101) | 2 | oldest version available, then each consolidated version: 1 August 2011 to 1 August 2026 |
| `837-201/` | Arbeitsvermittlungsverordnung (SHR 837.201) | 1 | one version (the oldest available), 1 June 2004 |
| `850-111-shev/` | Verordnung über die öffentliche Sozialhilfe und soziale Einrichtungen (SHR 850.111) | 1 | one version (the oldest available), 1 July 2018 |
| `857-501/` | Verordnung über die Schwangerschaftsberatungsstellen (SHR 857.501) | 1 | one version (the oldest available), 1 April 2007 |
| `860-101-betreuungsgutschriftenverordnung/` | Verordnung betreffend die Ausrichtung von Betreuungsgutschriften zur Förderung der familienergänzenden Kinderbetreuung im Vorschulalter (SHR 860.101) | 1 | one version (the oldest available), 1 March 2024 |
| `900-101/` | Verordnung zum Wirtschaftsförderungsgesetz (SHR 900.101) | 1 | one version (the oldest available), 1 October 2020 |
| `900-301/` | Verordnung zum Gesetz zur Förderung der Regional- und Standortentwicklung im Kanton Schaffhausen (SHR 900.301) | 1 | one version (the oldest available), 1 January 2018 |
| `910-101/` | Landwirtschaftsverordnung (SHR 910.101) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 May 2025 |
| `913-101/` | Verordnung über Beitragsleistungen an Hofdüngeranlagen (SHR 913.101) | 1 | one version (the oldest available), 1 January 2000 |
| `916-431-kantonale-tierseuchenverordnung/` | Verordnung zum Bundesgesetz über die Bekämpfung von Tierseuchen (SHR 916.431) | 1 | one version (the oldest available), 1 January 2017 |
| `916-432/` | Verordnung über die Entsorgung von tierischen Nebenprodukten aus dem Kanton Schaffhausen (SHR 916.432) | 1 | one version (the oldest available), 1 January 2024 |
| `916-441/` | Verordnung über die Entschädigung der Beauftragten im Bereich des Veterinärwesens (SHR 916.441) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2025 |
| `921-101-kwav/` | Kantonale Waldverordnung (SHR 921.101) | 1 | one version (the oldest available), 1 January 2013 |
| `922-101/` | Verordnung über die Jagd und den Schutz wildlebender Säugetiere und Vögel (SHR 922.101) | 1 | one version (the oldest available), 1 April 2023 |
| `923-101/` | Verordnung über die Fischerei (SHR 923.101) | 3 | oldest version available, then each consolidated version: 1 September 2021 to 23 October 2026 |
| `935-101-gastgewerbeverordnung/` | Verordnung über das Gastgewerbe und den Kleinhandel mit alkoholhaltigen Getränken (SHR 935.101) | 1 | one version (the oldest available), 1 January 2023 |
| `935-501-verordnung-eg-bgs/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über Geldspiele (SHR 935.501) | 1 | one version (the oldest available), 1 January 2024 |
| `935-521-lotteriegewinnfonds-verordnung-lgv/` | Verordnung über die Verwendung der Mittel aus dem Lotteriegewinnfonds (SHR 935.521) | 1 | one version (the oldest available), 1 January 2023 |
| `935-901/` | Vollzugsverordnung zum Bundesgesetz über das Bergführerwesen und Anbieten weiterer Risikoaktivitäten (SHR 935.901) | 1 | one version (the oldest available), 1 April 2024 |
| `941-292/` | Verordnung zum Bundesgesetz über das Messwesen (SHR 941.292) | 1 | one version (the oldest available), 1 January 2020 |
| `941-401-sprengstoffverordnung/` | Verordnung zum Bundesgesetz über explosionsgefährliche Stoffe (SHR 941.401) | 1 | one version (the oldest available), 1 January 2001 |
| `952-001-pfandleihverordnung/` | Verordnung über das Pfandleihgewerbe (SHR 952.001) | 1 | as enacted, 1 February 2013 |
| `960-111-gebaudeversicherungsverordnung-gebvo/` | Verordnung zum Gesetz über die Gebäudeversicherung im Kanton Schaffhausen (SHR 960.111) | 1 | one version (the oldest available), 1 January 2019 |

## Source

The SHR (systematic collection) of the canton, published by the canton at <https://Lexifina's code.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist. Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
