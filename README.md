# Einleitung

## Ziele des Dokuments

Das Dokument soll dabei helfen, einen Einstieg in die Kubernetes und die "cloud-native" zu finden. Es sollen in möglichst einfacher Sprache Informationen und Quellen gesammelt und Grundkonzepte erläutert werden.

Ziel ist es, im Laufe des Dokuments dem Leser einen roten Faden aufzuzeigen, durch den er die ersten Erfahrungen mit Design Patterns, Clusterobjekten und Best-Practices machen kann. 

## Vorwort

Kubernetes ist eine Container Orchestrierungs- und Schedulinglösung, welche weltweit immer mehr an Relevanz gewinnt und heute der de-facto Standard für Container Orchestrierung ist. Zwischen 2013 und 2014 wurde Googles interner Container Scheduler \(Codename _Borg_ \) als Open-Source Software unter dem Namen Kubernetes veröffentlicht und damit der Allgemeinheit zu Verfügung gestellt. 

Der Name des Ursprungsprojekts geht auf die Sci-Fi Serie _Star Treck_ zurück. Die Borg sind in der Serie eine mächtige, ausserirdische "Schwarmintelligenz", deren Hauptziel es ist, andere Lebensformen unter zwang in den Schwarm aufzunehmen. Um dem Projekt einen "freundlicheren" Namen zu geben, wurde es intern auch _Project Seven of Nine_ genannt - eine wohlgesonnene Version der Borg. Die sieben Speichen des Steuerrads im Logo sind eine Referenz auf diesen Codenamen.

![Das Kubernetes Steuerrad](assets/1200px-kubernetes_logo_without_workmark.svg.png)

## Bevor wir beginnen

Um möglichst viel von dem Guide mitnehmen zu können, wird folgendes vorrausgesetzt:

* Basisverständnis von Linux
* Übliche Linux CLI Kommandos
* Einen Linux/Mac Client, das Windows Subsystem Linux oder einen Linux Jumphost
* Administrator Privilegien auf dem Client

Soweit möglich, wird die **Kubernetes Version v.1.18** genutzt. Bei Abweichung wird darauf hingewiesen.

##  Quellen, Inspirationen, Vorträge & "good-to-reads"

* Matt Stine's [Migrating to Cloud Native Application Architectures](https://www.oreilly.com/library/view/migrating-to-cloud-native/9781492047605/)
* Brendan Burns, Craig Tracey [Managing Kubernetes](https://www.oreilly.com/library/view/managing-kubernetes/9781492033905/)
* Kelsey Hightower, Brendan Burns, Joe Beda [Kubernetes: Up & Running](https://www.oreilly.com/library/view/kubernetes-up-and/9781491935668/)
* Carson Endersons [Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down](https://vimeo.com/245778144/4d1d597c5e) 
* Kelsey Hightower's [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)

#### Nächste Seite: [Cloud-Native Applikationen](2_cloud-native-apps.md)
 

