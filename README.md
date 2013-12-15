## Formale Gestaltung wissenschaftlicher Arbeiten

Eine [Broschüre](http://www2.uni-frankfurt.de/45426646/Broschuere-Wissenschaftliches-Arbeiten.pdf) des [Instituts für Ethnologie](http://www2.uni-frankfurt.de/42991918/ie) der Goethe-Universität Frankfurt am Main.

### Inhalt
Die Grundlagen dieser Broschüre bildet der Kurs **Wissenschaftliche Arbeitstechniken**. In diesem werden wissenschaftliche Arbeitstechniken vermittelt und formale Richtlinien festgelegt, die bei der Erstellung von Aufsätzen, Hausarbeiten und Thesenpapieren, am Institut für Ethnologie, einzuhalten sind.

Die vorliegende Broschüre sammelt diese formalen Richtlinien und stellt sie dem Leser in kompakter Weise zur Verfügung. 

### Hinweis
Die Broschüre wurde mit dem Textsatzsystem _Latex_ erstellt. Änderungen des Materials können mit Hilfe dieses GitHub Repositorys nachvollzogen werden. 

Einführende Informationen zu Latex und GitHub:
* [Was ist LaTeX?](https://de.wikipedia.org/wiki/LaTeX)
* [Was ist GitHub?](http://t3n.de/news/eigentlich-github-472886/)
* [Wieso verwenden wir GitHub wenn wir doch gar keine Software entwickeln?](http://www.schlosser.info/git-latex-versionieren/)

### Anwendung
Um Änderungen am Inhalt der Broschüre durchzuführen und um daraus ein PDF zu erzeugen müssen zuerst folgende Vorbereitungen getroffen werden.

1. Installation einer LaTeX Umgebung
2. Installation eines Text Editors (optional, aber empfohlen)
3. Installation der GitHub Software (optional, aber empfohlen)

#### LaTeX Installation
LaTeX ist *freie Software* und kann für alle gängigen Computerplattformen wie *Windows*, *Linux* und *Mac* kostenlos aus dem Internet bezogen werden.

Im Folgenden finden Sie Schritt-für-Schritt Anleitungen anhand derer sich die LaTeX Umgebung **Tex Live 2013**  bzw. **MacTeX 2013** installieren lässt. Da es sich hierbei um eine vollständige LaTeX Umgebung handelt, beträgt der Bedarf an Festplattenspeicher ca. 4GB. Diese 4GB werden während der Installation aus dem Internet geladen. Es empfiehlt sich daher eine schnelle Internetanbindung, wie sie z.B. durch das Universitätsnetzwerk bereitgestellt wird.

##### Windows

1. Laden Sie folgende Datei herunter: [install-tl.zip](http://mirror.ctan.org/systems/texlive/tlnet/install-tl.zip)
2. Entpacken Sie die zip-Datei *install-tl.zip*
3. Öffnen Sie den Ordner *install-tl-datum* (datum kann hierbei variabel sein)
4. Führen Sie einen Doppelklick auf die Datei *install-tl* oder *install-tl.bat* aus (die richtige Datei ist zu erkennen an den zwei kleinen Zahnrädchen im Icon und das sie vom Typ Windows-Batchdatei ist)
5. Bestätigen Sie im folgenden Dialog alle Fragen mit *Weiter* und starten Sie die Installation mit einem klick auf *Installation*

Nun wird die Installation vollautomatisch durchgeführt. Schalten Sie in der Zwischenzeit Ihren PC nicht aus. Die Dauer der Installation kann durchaus 30 bis 60 Minuten betragen und ist abhängig von der Geschwindigkeit der Internetverbindung. Sobald die Installation abgeschlossen ist, wird dies durch ein Dialogfenster angezeigt.

##### Mac

1. Laden Sie folgende Datei herunter: [MacTeX.pkg](http://mirror.ctan.org/systems/mac/mactex/MacTeX.pkg) (Die Größe der Datei Beträgt ca. 2,3GB und kann deshalb einige Zeit in Anspruch nehmen)
2. Führen Sie einen Doppelklick auf die Datei *MacTeX.pkg* aus, um die Installation zu starten
3. Bestätigen Sie im folgenden Dialog alle Fragen mit *Weiter* und starten Sie die Installation mit einem klick auf *Installation*

Nun wird die Installation vollautomatisch durchgeführt. Sobald die Installation abgeschlossen ist, wird dies durch ein Dialogfenster angezeigt.

#### Text Editor

Als Text Editor wird [Sublime Text 3](http://www.sublimetext.com/3) empfohlen. Das Programm kann von der Webseite des Herstellers heruntergeladen werden. Die richtige Version wird hierbei durch einen ausgefüllten, schwarten Punkt angezeigt (siehe Beispielgrafik für Windows 8).

Nachdem der Download abgeschlossen ist, führen Sie die Installation durch und starten Sie danach das Programm **Sublime Text 3**.

Markieren Sie nun vollständig den folgenden Text und kopieren Sie ihn in die Zwischenablage.

    import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())


### Lizenz 
![cc-by-sa](http://i.creativecommons.org/l/by-sa/4.0/80x15.png)

Dieses Material steht unter der Creative-Commons-Lizenz Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International. Um eine Kopie dieser Lizenz zu sehen, besuchen Sie http://creativecommons.org/licenses/by-sa/4.0/deed.de.
