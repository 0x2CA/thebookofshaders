## Wie kann ich die Beispielprogramme auf einem RaspberryPi ausf�hren?

Vor wenigen Jahren konnte man noch nicht davon ausgehen, dass jedermann �ber einen Computer mit einer GPU verf�gt. Heutzutage gilt das nicht mehr. Doch im Bereich von Schulen, Universit�ten und anderen Weiterbildungseichrichtungen ist dies immer noch eine hohe Anforderung. 

Durch das [Raspberry Projekt](http://www.raspberrypi.org/) hat mittlerweile eine neue Generation kleiner und billiger Computer (das St�ck ab ca. 40 Euro) ihren Weg in viele Klassenzimmer gefunden. Vor allem verf�gt der [RaspberryPi](http://www.raspberrypi.org/) �ber einen ansehnlichen Grafikchip mit GPU, der direkt aus der Kommandozeile angesprochen werden kann. 

Ich habe ein flexibles Werkzeug f�r die Programmierung von GLSL-Shadern entwickelt, den [**glslViewer**](https://github.com/patriciogonzalezvivo/glslViewer). Damit k�nnen alle Beispiele aus diesem Buch ausgef�hrt werden. Sobald man Ver�nderungen am aktuellen Shader-Programmcode abspeichert, kompiliert das Programm den Shader erneut und bringt ihn zur Ausf�hrung. Auf dem Bildschirm erscheint daraufhin die aktualisierte Anzeige des Shaders.

Indem Du eine lokale Kopie dieses Buches und seiner Beispielprogramme auf Deinem Rechner anlegst (mehr dazu im vorhergehenden Kapitel) und den [```glslViewer```] (https://github.com/patriciogonzalezvivo/glslViewer) installierst, kannst Du die Beispielprogramme mit dem ```glslviewer``` ausf�hren. Wenn Du beim Start dieses Programms den Kommandozeilenschalter ```-l``` angibst, erscheint die erzeugte Grafik in einer Ecke des Bildschirms, w�hrend Du gleichzeitig den Shader-Programmcode mit einem beliebigen Text-Editor (etwa ```nano```, ```pico```, ```vi```, ```vim``` oder ```emacs```) bearbeitest. Das funktioniert auch, wenn Du mit dem Terminal des RaspberryPi �ber ssh/sftp verbunden bist.

Um die angesprochenen Tools auf einem RaspberryPi zu installieren, rufe nach dem Start des Betriebssystems und dem Einloggen folgende Befehle �ber die Kommandozeile auf:

```bash
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git-core
cd ~ 
git clone http://github.com/patriciogonzalezvivo/glslViewer.git
cd glslViewer
make
make install
cd ~
git clone https://github.com/patriciogonzalezvivo/thebookofshaders.git
cd thebookofshaders
```
