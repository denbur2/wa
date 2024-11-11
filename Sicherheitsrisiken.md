# Sicherheit Cloud Computing

## Risiken und Bedrohungen im Cloud Computing

Die Nutzung von Cloud-Diensten ist mit zahlreichen Risiken verbunden, die sowohl technische als auch rechtliche und organisatorische Herausforderungen darstellen. Zu den zentralen Risiken zählen Datendiebstahl und Datenverlust, Sicherheitslücken in der Software und Angriffe auf APIs sowie auf Netzwerkebene.

#### Datendiebstahl und Datenverlust

Einer der schwerwiegendsten Bedrohungen im Cloud-Computing-Bereich ist der Verlust oder Diebstahl von Daten. Laut einer Studie von [^1]Subashini und Kavitha (2011) entstehen Datenverluste häufig durch Hardwarefehler, menschliche Fehler und durch gezielte Angriffe. Ein prominentes Beispiel ist der Datenverlust bei Dropbox im Jahr 2011, als durch einen Softwarefehler alle Nutzerkonten für eine gewisse Zeit ohne Passwort zugänglich waren. Solche Vorfälle unterstreichen die Notwendigkeit robuster Datenverschlüsselungs- und Zugriffskontrollsysteme.

#### Sicherheitslücken und Schwachstellen

Schwachstellen in der Software und in den verwendeten Sicherheitsprotokollen stellen eine weitere große Bedrohung dar. Ein umfassendes Patch-Management und regelmäßige Sicherheitsüberprüfungen sind entscheidend, um bekannte Schwachstellen zu beheben und Angreifern potenzielle Einstiegspunkte zu verwehren [^6](Takabi et al., 2010). Besonders APIs, die für den Zugang zu Cloud-Diensten genutzt werden, können Schwachstellen aufweisen und sind ein häufiges Angriffsziel [^5](Zissis & Lekkas, 2012).

#### Angriffe auf APIs und Netzwerke

APIs sind essenziell für die Interaktion zwischen Cloud-Nutzern und -Diensten, doch durch unzureichend geschützte Schnittstellen werden sie häufig zum Ziel von Angriffen. Durch den Einsatz von Verschlüsselung und strengen Authentifizierungsverfahren lässt sich die Sicherheit von APIs deutlich erhöhen [^2](Fernandes et al., 2014). Angriffe auf Netzwerke, insbesondere DDoS-Attacken, können zudem die Verfügbarkeit von Diensten beeinträchtigen und zu erheblichen Ausfällen führen.

## Maßnahmen und Sicherheitsstrategien im Cloud Computing

Zur Absicherung von Cloud-Computing-Umgebungen werden verschiedene technische und organisatorische Maßnahmen eingesetzt, darunter Verschlüsselungstechniken, Identitäts- und Zugriffsmanagement sowie die Einhaltung von Sicherheitsstandards.

#### Verschlüsselungstechniken

Verschlüsselung ist eine der grundlegendsten Sicherheitsmaßnahmen im Cloud Computing. Sie gewährleistet, dass sensible Daten auch dann geschützt bleiben, wenn sie in ungesicherten Netzwerken übertragen oder auf den Servern des Cloud-Anbieters gespeichert werden. [^7]Juels und Kaliski (2007) betonen, dass sowohl die Ende-zu-Ende-Verschlüsselung als auch die Verschlüsselung auf Dateiebene essenziell für die Sicherheit sensibler Daten sind. Die Herausforderung besteht darin, eine Balance zwischen Sicherheit und Performance zu finden, da die Verschlüsselung auch die Datenverarbeitung verlangsamen kann.

#### Identitäts- und Zugriffsmanagement (IAM)

Ein effektives Identitäts- und Zugriffsmanagement (IAM) ist entscheidend, um sicherzustellen, dass nur autorisierte Benutzer auf die Cloud-Ressourcen zugreifen können. IAM-Lösungen basieren häufig auf rollenbasierten Zugriffskontrollmechanismen (RBAC), die eine feingranulare Verwaltung von Benutzerrechten ermöglichen [^11](Chen & Zhao, 2012). Zusätzlich sind Multi-Faktor-Authentifizierungen mittlerweile gängige Praxis, um den Zugriff auf sensible Daten weiter zu schützen.

#### Sicherheits- und Compliance-Standards

Regelwerke wie die ISO 27001 und die Richtlinien der Cloud Security Alliance (CSA) bieten Unternehmen und Anbietern von Cloud-Diensten klare Richtlinien, um Sicherheitsstandards einzuhalten und Risiken zu minimieren. Durch die Einhaltung dieser Standards können Anbieter ein hohes Maß an Vertrauen schaffen und ihre Cloud-Dienste als sicher positionieren. Die CSA bietet beispielsweise mit dem Security, Trust & Assurance Registry (STAR) ein Zertifizierungssystem, das Transparenz und Sicherheit gewährleistet [^8](CSA, 2020).

## Fallstudien und Beispiele aus der Praxis

Zur Veranschaulichung der Sicherheitsrisiken und Schutzmaßnahmen im Cloud-Computing-Bereich werden im Folgenden einige reale Vorfälle und Präventionsmaßnahmen bekannter Cloud-Anbieter betrachtet.

#### Datenverlust bei Amazon Web Services (AWS)

Ein Beispiel für die Sicherheitsrisiken ist der Vorfall bei Amazon Web Services (AWS) im Jahr 2011, bei dem durch einen Stromausfall und Fehler im Wiederherstellungssystem zahlreiche Daten verloren gingen. AWS konnte durch diese Erfahrungen seine Sicherheitsprotokolle verbessern und setzt seitdem auf redundante Systeme und eine verbesserte Datenreplikation [^12](AWS, 2011).

#### Microsoft Azure und API-Angriffe

Ein weiteres Beispiel ist ein Angriff auf Microsoft Azure im Jahr 2020, bei dem durch eine Schwachstelle in der API-Dokumentation Angreifer potenziell Zugang zu Daten erhielten. Microsoft reagierte darauf, indem es die API-Authentifizierung verstärkte und Sicherheitsbewertungen bei der Entwicklung neuer Funktionen vorschrieb [^13](Microsoft, 2020).

#### Google Cloud und Compliance-Strategien

Google Cloud zählt zu den Anbietern, die sich aktiv für Compliance und Sicherheit einsetzen. Durch die Einführung von Transparenzberichten und einer Zusammenarbeit mit der CSA STAR-Zertifizierung schafft Google Cloud Vertrauen und erhöht die Sicherheit durch ein umfassendes Compliance-Framework, das regelmäßige Überprüfungen und Audits beinhaltet [^14](Google Cloud, 2021).

### Ausblick und zukünftige Entwicklungen

Die Zukunft der Cloud-Sicherheit verspricht weitere Innovationen, aber auch neue Herausforderungen. Eine der spannendsten Entwicklungen ist der Einsatz von Künstlicher Intelligenz (KI) und maschinellem Lernen zur Erkennung von Anomalien und Bedrohungen in Echtzeit. KI kann dabei helfen, untypische Aktivitäten automatisch zu identifizieren und Sicherheitsmaßnahmen einzuleiten, bevor ein Angriff Schaden anrichtet [^9](Bertino, 2021).

Ein weiterer Trend ist die zunehmende Verbreitung der Blockchain-Technologie, die im Bereich Cloud Computing zur Absicherung von Transaktionen und zur dezentralen Speicherung sensibler Daten genutzt wird. Blockchain kann dazu beitragen, die Integrität und Transparenz von Daten in der Cloud zu gewährleisten und die Sicherheit auf ein neues Niveau zu heben [^10](Yaga et al., 2019).

Regulierungen und gesetzliche Anforderungen werden ebenfalls eine Rolle spielen, insbesondere im Hinblick auf Datenschutz und Datensouveränität. Mit zunehmender Verbreitung von Cloud-Diensten steigen die Anforderungen an den Datenschutz, weshalb nationale und internationale Regulierungen weiter an Bedeutung gewinnen werden. Cloud-Anbieter werden verstärkt in Sicherheitstechnologien investieren, um gesetzliche Vorgaben einzuhalten und sich auf dem Markt zu differenzieren.

---

### Quellenangaben mit Links

[^1]:**Jansen, W., & Grance, T. (2011).** _Guidelines on Security and Privacy in Public Cloud Computing._ NIST Special Publication 800-144.  
    Link: [https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-144.pdf](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-144.pdf)

[^2]:**Fernandes, D. A. B., Soares, L. F. B., Gomes, J. V., Freire, M. M., & Inácio, P. R. M. (2014).** _Security Issues in Cloud Environments: A Survey._ International Journal of Information Security, 13(2), 113-170.  
    DOI-Link (Zugang via Uni-Bibliothek oder ResearchGate): https://doi.org/10.1007/s10207-013-0208-7

[^3]:**Mell, P., & Grance, T. (2011).** _The NIST Definition of Cloud Computing._ NIST Special Publication 800-145.  
    Link: [https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)

[^4]:**Subashini, S., & Kavitha, V. (2011).** _A Survey on Security Issues in Service Delivery Models of Cloud Computing._ Journal of Network and Computer Applications, 34(1), 1-11.  
    DOI-Link (Zugang via Uni-Bibliothek oder ResearchGate): https://doi.org/10.1016/j.jnca.2010.07.006

[^5]:**Zissis, D., & Lekkas, D. (2012).** _Addressing Cloud Computing Security Issues._ Future Generation Computer Systems, 28(3), 583-592.  
    DOI-Link (Zugang via Uni-Bibliothek oder ResearchGate): https://doi.org/10.1016/j.future.2010.12.006

[^6]:**Takabi, H., Joshi, J. B. D., & Ahn, G. J. (2010).** _Security and Privacy Challenges in Cloud Computing Environments._ IEEE Security & Privacy, 8(6), 24-31.  
    DOI-Link (Zugang via Uni-Bibliothek oder IEEE Xplore): https://doi.org/10.1109/MSP.2010.186
    
[^7]:**Juels, A., & Kaliski, B. S. (2007).** _PORs: Proofs of Retrievability for Large Files._ In Proceedings of the 14th ACM Conference on Computer and Communications Security (CCS '07).  
    DOI-Link (Zugang via Uni-Bibliothek oder ACM Digital Library): https://doi.org/10.1145/1315245.1315317

[^8]:**Cloud Security Alliance (CSA). (2020).** _Security, Trust & Assurance Registry (STAR)._  
    Link: https://cloudsecurityalliance.org/star/

[^9]:**Bertino, E. (2021).** _AI and Machine Learning for Cybersecurity: Prospects and Challenges._ IEEE Security & Privacy, 19(2), 16-23.  
    DOI-Link (Zugang via Uni-Bibliothek oder IEEE Xplore): https://doi.org/10.1109/MSEC.2020.3042301

[^10]:**Yaga, D., Mell, P., Roby, N., & Scarfone, K. (2019).** _Blockchain Technology Overview._ NIST Special Publication 800-308.  
    Link: [https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8202.pdf](https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8202.pdf

[^11]:**Chen, D., & Zhao, H. (2012).** _Data Security and Privacy Protection Issues in Cloud Computing._ In Proceedings of the 2012 International Conference on Computer Science and Electronics Engineering (ICCSEE), Vol. 1, 647-651. IEEE.  
	DOI-Link: https://doi.org/10.1109/ICCSEE.2012.193

[^12]:**Amazon Web Services (AWS). (2011).** _Summary of the Amazon EC2 and Amazon RDS Service Disruption in the US East Region._  
	Link: [https://aws.amazon.com/message/65648/](https://aws.amazon.com/message/65648/)

[^13]:**Microsoft. (2020).** _Microsoft Azure Security Documentation._  
	Link: [https://docs.microsoft.com/en-us/azure/security/](https://docs.microsoft.com/en-us/azure/security/)

[^14]:**Google Cloud. (2021).** _Security and Compliance on Google Cloud._  
	Link: https://cloud.google.com/security/
