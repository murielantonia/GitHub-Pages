#GitHub-Pages

[Vierzehnte Informatikstunde](#vierzehn)

[Fünfzehnte Informatikstunde](#fünfzehn)

[Zusätzliche Informatikstunde](#zusatz)

[Sechzehnte informatikstunde](#sechzehn)

[Siebzehnte Informatikstunde](#siebzehn)

[Zusätzliche Informatikstunde](#zusätzlich)

[Weitere Informatikstunde](#weitere)

##Vierzehnte Informatikstunde<a name="vierzehn"><a/>                                                               26.01.2017

Frohes Neues Jahr 2017!!! Mit guten Vorsätzen starten wir in das neue Jahr!
Heute haben wir uns das erste Mal mit GitHub Pages auseinander gesetzt, da wir uns zum Ziel gesetzt haben, unser Tic-Tac-Toe Spiel und die dazugehörigen Dokumentationen / Erklärungen auf einer eigenen Website zu präsentieren. Zuerst haben wir uns das Informationsvideo zu GitHub Pages angeschaut. Um eine Website zu programmieren, die im Browser dargestellt werden kann, benötigt man Grundkenntnisse in HTML (Hypertext Markup Language). Dabei handelt es sich um eine Auszeichnungssprache, die dazu dient, Texte, Bilder und Hyperlinks zu strukturieren. Zwar kann man mithilfe von GitHub Pages aus verschiedenen Vorformaten und Themen auswählen, die optisch ansprechend sind, wir haben uns jedoch dazu entschieden, von ganz unten zu beginnen und keine Formatvorlagen zu verwenden ("Start from scratch").

Wir erstellten zunächst ein neues Repository auf unserem Account murielantonia unter dem Titel "GitHub Pages". In diesem Repository haben wir einen neuen Ordner angelegt, der aus einer read.me Datei und einer index.html Datei besteht. In den index.html Ordner können wir nun den Quellcode für unsere Website programmieren. Unsere erste Zeile HTML-Code zeigt den Schriftzug "Hello World!" auf einer leeren Seite unter folgendem Link: https://murielantonia.github.io/GitHub-Pages/ 

![Pages01](bilder/Pages01.PNG "Erster Schriftzug")

Mit Hilfe eines Online Tutorials haben wir begonnen, uns erste Befehle in HTML anzueignen. Beispielhaft fügten wir den ersten Paragraphen aus unserem Tic-Tac-Toe Galaxy Dokument ein. Wir nutzten auch das neu errungene Wissen, um passende Überschriften zu formulieren und formatieren. Die meisten HTML-Elemente, in unserem Fall Titel und Paragraphen, sind von einem Tag-Paar umrahmt, also von einem Start- und einem Endtag. Der Starttag besteht aus einem Kleiner-Zeichen und dem Namen des Elementes, bei der Überschrift "Hello World" sei es h1, und endet mit einem Größer-Zeichen. Der Endtag setzt sich zusammen aus Kleiner-Zeichen, Schrägstrich, Name des Elements (h1) und Größer-Zeichen. Das klingt komplizierter, als es eigentlich ist:

![Pages02](bilder/Pages02.PNG "Überschriften programmieren")

So sieht unsere Website nach aktuellem Stand aus:

![Pages03](bilder/Pages03.PNG "Erster Paragraph")

##Fünfzehnte Informatikstunde<a name="fünfzehn"><a/>                                                                09.02.2017

Heute haben wir erfolgreich GitHub Desktop heruntergeladen. Damit konnten wir vereinfacht den Bilderordner aus der Tic-Tac-Toe Galaxy in den GitHub-Pages Ordner übertragen.
Zunächst mussten wir unsere Projekte in die Desktopversion clonen.

![Pages05](bilder/Pages05.PNG "Github Desktop")

Danach konnten wir auf unserem Desktop die Bilderordner mit drag-and-drop verschieben.

![Pages04](bilder/Pages04.PNG "Verschieben der Bilder")

War dies vollbracht, mussten wir nur noch unser Werk synchronisieren, damit die Bilder im Dokument erscheinen konnten. 

Nun arbeiteten wir weiter an unserer Website. Dazu haben wir den Text aus dem Tic-Tac-Toe Galaxy Projekt in die index.html File kopiert und in Paragraphen unterteilt. Wie bereits erklärt, entsteht ein Paragraph zwischen dem Tag-Paar, also zwischen Start- und Endtag mit dem Titel "p". Die Überschriften haben wir in fett und die Zusammenfassung in kursiv geschrieben. Damit wir später wissen, an welche Stellen die Bilder eingefügt werden sollen, haben wir uns Notizen dazu gemacht (Bild).

![Pages07](bilder/Pages07.PNG "Paragraphen im Quellcode")

![Pages08](bilder/Pages08.PNG "Fette Überschrift in Quellcode")

![Pages10](bilder/Pages10.PNG "Kursiver Text in Quellcode")

![Pages09](bilder/Pages09.PNG "Übersicht auf Website")

Um uns die Arbeit zu erleichtern, haben wir den Text der Tic-Tac-Toe Galaxy in ein leeres Worddokument kopiert, damit wir gleichzeitig in zwei Fenstern arbeiten konnten.

![Pages06](bilder/Pages06.PNG "Arbeitsweise")

Unser Versuch, ein Inhaltsverzeichnis mit Hyperlinks zu erstellen, ist zunächst leider gescheitert.

![Pages12](bilder/Pages12.PNG "Das Scheitern")

Übersetzung: Bei den Links im Inhaltsverzeichnes handelt es sich um interne Links und damit um Verweise innerhalb der Webseite auf Unterseiten. Das a steht für "anchor" (Anker) aus dem Englischen. Verbunden mit dem Attribut href (Hyperreferenz) entsteht ein Verweis eine andere Textstelle, die mit einem Tag markiert ist. Dieser muss an Textstelle und Inhaltsverzeichnis übereinstimmen. Der Linktext, beispielsweise "Idee" ist unabhängig von dieser relativen Addressierung und wird standardmäßig unterstrichen und in blau angezeigt. Nachdem der Link angeklickt wurde, färbt der Text sich lila.

##Zusätzliche Informatikstunde<a name="zusatz"><a/>                                                                   13.02.2017

Das Inhaltsverzeichnis funktioniert doch! Man muss die Website nur aktualisieren und ihr einige Zeit geben. Es sind noch einige Fehler drin, die jetzt behoben werden!

![Pages13](bilder/Pages13.PNG "Inhaltsverzeichnis klappt!")

Im Folgenden machten wir uns daran, die Bilder auf unsere Website zu übertragen. Dazu benutzten wir einen bestimmten Quellcode in der index.html.

![Pages14](bilder/Pages14.PNG "Quellcode für Bilder in inedx.html")

Übersetzung: Dies ist die Grundstruktur des HTML-Befehls für das Integrieren von Bildern und Grafiken. Dabei steht img für das englische Wort "image" (Bild) und src für "source" (Quelle). In unserem Fall handelt es sich bei dieser Quelle um den Bilderordner in unserem Repository und den Namen der Datei. Der Alternativtext wird mit dem Attribut "alt" definiert, beispielsweise Bild13. Dies ist als Information für den Surfer von Nutzen. Mit den Attributen "width" (Breite) und "height" Höhe kann man Größe und Verhältnis der Seitenlängen formatieren. Dazu wird im Browser ein Platzhalter in entsprechender Größe vorgesehen. 

Wir haben schon angefangen die Bilder richtig zu formatieren. Hier sieht man ein Beispiel:

![Pages15](bilder/Pages15.PNG "Erste formatierte Bilder")

##Sechzehnte Informatikstunde<a name="sechzehn"></a>                                                                    14.02.2017

Da heute Valentinstag ist, haben wir passend zum Thema alle Überschriften pink gefärbt.

![Pages17](bilder/Pages17.PNG "Pinke Überschriften auf Website")

Wir stellten fest, dass es für die Überschriften nicht nötig ist, den Text fett zu formatieren. 

![Pages18](bilder/Pages18.PNG "Quellcode für pinke Überschriften")

Jetzt habe wir erfolgreich unsere Über-Überschrift "Hello World!" nicht nur gelb markiert, sondern auch pink gefärbt! Der Kontrast ist atemberaubend!

![Pages](bilder/Pages19.PNG "Markiertes Hello World")

![Pages](bilder/Pages20.PNG "Quellcode markiertes Hello World!")

##Siebzehnte Informatikstunde<a name="siebzehn"></a>                                                                  16.02.2017

Heute erstellten wir zunächst eine kleine "Werbung" für unseren GitHub Account.

![Pages](bilder/Pages21.PNG "Werbung")

![Pages](bilder/Pages23.PNG "Quellcode für unsere Werbung")

Übersetzung:Wir nutzten viele verschiedene Specials.
Zunächst wird der Paragraph ("p") mit einem Starttag geöffnet. Danach wird "mark" geöffnet. Alles was zwischen diesem Tag-Paar ist, wird markiert. Für diese Markierung wählten die Farbe Pink (background-colour:FF00CC;). In unserem Text unterlegten wir "Unsere GitHub Seite" italic (i) und "Weitere tolle Projekte" fett (b). Wir fügten außerdem einen äußeren Link zu unserem GitHub Account ein. Anschließend werden die Endtags für "mark" und "p" eingefügt.

Danach machten wir uns weiter daran, die Bilder so zu formatieren, dass sie auf unsere Website nicht verzerrt sind. Hierbei gilt zunächst ausprobieren, da wir bisher noch keine Möglichkeit gefunden haben, die Maße in den Eigenschaften der Bilddateien zu überprüfen. Wir ändern die Länge und / oder Höhe (von 420 x 420), klicken "commit changes", aktualisieren GitHub und aktualisieren unsere Website. Dann hoffen wir, dass die Größe passt, denn sonst muss der beschriebene Ablauf noch einmal durhgeführt werden. Dies wiederholen wir für jedes Bild, außer denen, die mit 420 x 420 -Format kaum verzerrt und leicht erkennbar sind.
Da dies, nach einer mühseligen Doppelstunde, noch nicht für alle Bilder geklappt hat, hat Stefan uns noch einen Tipp gegeben: Wir können die Maße auch auf dem Desktop für jedes Bild ablesen. Zu Hause werden wir uns also noch einmal mit der Formatierung befassen!


##Zusätzliche Informatikstunde<a name="zusätzlich"></a>                                                           17.02.2017

Nachdem wir alle Bilder aus unserem "bilder" Ordner von unserem GitHub-Pages Projekt auf das Dektop heruntergeladen haben, konnten wir die Eigenschaften jedes einzelnen Bildes öffnen. Ganz oben konnten wir nun die richtigen Maße ablesen. Diese wurden dann in die Angaben im index Quellcode übertragen.

![Pages](bilder/Pages24.PNG "Arbeitsübersicht")

Schließlich programmierten wir noch einen inneren Link hinter jedes Kapitel, um "zurück zum Anfang" zu springen.

![Pages](bilder/Pages25.PNG "Zurück zum Anfang")

![Pages](bilder/Pages26.PNG "Quellcode zurück zum Anfang")

Übersetzung: Wir nutzten einen Tag, welcher in der Überschrift "Hello World!" auch verlinkt ist. Unseren inneren Link nannten wir "Zurück zum Anfang". Klickt man diesen nun, kommt man zu der Überschrift "Hello World" zurück und kann so auch das Inhaltsverzeichnis sehen. Das erleichtert es um einiges, sich auf der Website zu bewegen!

##Weitere Informatikstunde<a name="weitere"></a>                                                                  18.02.2017

Da wir diese Website so weit erfolgreich erstellt haben, wurde nun eine Website unter dem Titel "GitHub-Pages 2.0" erstellt. Auf dieser wird dem Leser das lästige scrollen erspart!
Dazu machten wir für jedes Kapitel einen eigenen Quellcode und verlinkten diesen mit einem äußeren Link auf der Startseite. Nun nimmt unsere Website langsam mehr gestalt an. Wir nutzten für jede Unterseite eine andere Hintergrundfarbe. Hier der Link zu der Seite: https://murielantonia.github.io/GitHub-Pages-2.0/Startseite

Als nächstes Projekt wollen wir unsere Website perfektionieren, beispielsweise Seitenleisten programmieren und die Bilder auf der Seite arrangieren. Mit einer einheitlichen Seitenleiste könnte von allen Einzelseiten auf jede andere Einzelseite zugegriffen werden, ohne den Umweg über die Startseite zu machen. Auf einer weiteren Seitenleiste könnte man Werbung einblenden und so auch noch Geld verdienen!




