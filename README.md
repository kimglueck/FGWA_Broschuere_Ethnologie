## Formale Gestaltung wissenschaftlicher Arbeiten

Eine [Broschüre](http://www2.uni-frankfurt.de/45426646/Broschuere-Wissenschaftliches-Arbeiten.pdf) des [Instituts für Ethnologie](http://www2.uni-frankfurt.de/42991918/ie) der Goethe-Universität Frankfurt am Main.

### Inhalt
Die Grundlagen dieser Broschüre bildet der Kurs **Wissenschaftliche Arbeitstechniken**. In diesem werden wissenschaftliche Arbeitstechniken vermittelt und formale Richtlinien festgelegt, die bei der Erstellung von Aufsätzen, Hausarbeiten und Thesenpapieren, am Institut für Ethnologie, einzuhalten sind.

Die vorliegende Broschüre sammelt diese formalen Richtlinien und stellt sie dem Leser in kompakter Weise zur Verfügung. 

### Hinweis
Die Broschüre wurde mit dem Textsatzsystem _Latex_ erstellt. Änderungen des Materials können mit Hilfe dieses GitHub Repositorys nachvollzogen werden. 

**Einführende Informationen zu Latex und GitHub:**

* [Was ist LaTeX?](https://de.wikipedia.org/wiki/LaTeX)
* [Was ist GitHub?](http://t3n.de/news/eigentlich-github-472886/)
* [Wieso verwenden wir GitHub wenn wir doch gar keine Software entwickeln?](http://www.schlosser.info/git-latex-versionieren/)

### Voraussetzungen
Um Änderungen am Inhalt der Broschüre durchzuführen und um daraus ein PDF zu erzeugen müssen zuerst folgende Vorbereitungen getroffen werden.

1. Installation einer LaTeX Umgebung
2. Installation eines Text Editors 
3. Installation eines PDF Reader
4. Installation der GitHub Software

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

##### Ubuntu Linux

1. Starten Sie eine Konsole
2. Führen Sie in der Konsole den folgenden Befehl aus `sudo apt-get install texlive-full`

Nun wird die Installation vollautomatisch durchgeführt. Sobald die Installation abgeschlossen ist, wird dies in der Konsole angezeigt.

#### Text Editor Installation

Als Text Editor wird [Sublime Text 3](http://www.sublimetext.com/3) empfohlen. Das Programm kann von der Webseite des Herstellers heruntergeladen werden. **Sublime Text 3** ist für alle gängigen Betriebsysteme erhältlich. Die Webseite des Hersteller erkennt automatisch, welches Betriebsystem Sie aktuell verwenden und hilft Ihnen mit einem ausgefüllten, schwarzen Punkt bei der Auswahl der richtigen Version (siehe Beispielgrafik für Windows 8).

Nachdem der Download abgeschlossen ist, führen Sie die Installation durch.

Markieren Sie nun den folgenden Text vollständig und kopieren Sie ihn in Ihre Zwischenablage (Tastenkombination `Strg + c`).

    import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())

Starten Sie nun das Programm Sublime Text 3. Dort klicken Sie in der Menüzeile auf `View` und danach `Show Console`. Im unteren Bereich des Sublime Text 3 Fensters erscheint nun ein schmales Textfeld, in das Sie den vorher kopierten Text einfügen (Tastenkombination `Strg + v`). Bestätigen Sie die Eingabe mit der Enter-Taste.

Nachdem der Befehl erfolgreich ausgeführt wurde, starten Sie Sublime Text neu.

Nun öffnen Sie die Kommando Palette, entweder mit Hilfe der Tastenkombination `Strg + Shift + P` oder über den Menüpunkt `Tools > Command Palette`. Wählen Sie in diesem Dialog den Punkt `Package Controll: Install Package` und in der darauf folgenden Liste `LaTeXTools` aus und bestätigen Sie Ihre Auswahl jeweils mit der Enter-Taste.

Zum Abschluss Laden Sie folgende Konfigurationsdateien auf Ihre Festplatte herunter:

* [LaTeX.sublime-build](https://gist.github.com/oliverh855/1ba49d75f2b4e21246b3/raw/b6c6e0405340e272e56c5a8882f2f0b9a925aaab/LaTeX.sublime-build)
* [Preferences.sublime-settings](https://gist.github.com/oliverh855/1ba49d75f2b4e21246b3/raw/35fe6df31ec1914b9f75173a8cee5ec08a536ff2/Preferences.sublime-settings)

Mit dem Menüpunkt `Preferences > Browse Packages...` öffnen Sie den Konfigurationsordner. Kopieren Sie nun die beiden oben genannten Konfigurationsdateien in den Ordner `User`.

Somit ist die Installation von Sublime Text 3 abgeschlossen und Sie können das Programm nun nutzen, um automatisch PDF Dateien aus Ihrem LaTeX Text zu erzeugen.

#### GitHub Software Installation

Für Windows und Mac steht ein Programm bereit, dass die Arbeit mit GitHub sehr komfortabel macht. Beide Versionen stehen kostenfrei zum Download bereit und lassen sich sehr einfach installieren.

Während der ersten Ausführung des Programms wird man dazu aufgefordert ein bestehendes GitHub Benutzerkonto anzugeben oder ein neues zu registrieren. Hierbei entstehen keine Kosten.

* [GitHub Windows.](http://windows.github.com/)
* [GitHub Mac](http://mac.github.com/)

#### PDF Reader Installation

Adobe Reader ist für viele der standard PDF Reader. Im Schreibprozess mit LaTeX ist er jedoch nicht die passende Wahl. Deshalb stellen wir jedes Betriebssystem einen kleinen und schnellen PDF Reader vor und setzen in folgenden Abschnitten voraus, dass diese erfolgreich auf ihrem Computer installiert wurden.

Alle PDF Reader stehen kostenlose zum Download auf den Webseiten der Hersteller bereit.

##### Windows

[Sumatra PDF](http://blog.kowalczyk.info/software/sumatrapdf/)

##### Mac

[Skim](http://skim-app.sourceforge.net/)

##### Linux

[Evince](https://projects.gnome.org/evince/)

### Anwendung

*In diesem Punkt setzen wir voraus, dass Sie alle Schritte des Punkts Voraussetzungen erfolgreich ausgeführt und bereits ein Benutzerkonto bei GitHub registriert haben.*

Um das Material der Broschüre bearbeiten zu können bestehen mehrere Möglichkeiten. Im Folgenden werden wir eine Methode beschreiben, die eine kontinuierliche und verteile Arbeitsweise erlaubt.

### Lizenz 
![cc-by-sa](http://i.creativecommons.org/l/by-sa/4.0/80x15.png)

Dieses Material steht unter der Creative-Commons-Lizenz Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International. Um eine Kopie dieser Lizenz zu sehen, besuchen Sie http://creativecommons.org/licenses/by-sa/4.0/deed.de.
