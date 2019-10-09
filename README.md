## 1. Text-Editor der Wahl

- Emacs

## 2. Eine Python-Bibliothek

Bokeh

Bokeh ist eine Bibliothek für interaktive Datenvisualisierung. Im Gegensatz zu Matplotlib rendert Bokeh seine Grafiken mit HTML und Java Script. Daher eignet es sich für die Erstellung von webbasierten Dashboards und Anwendungen. Es ist ein ebenso mächtiges Werkzeug, um Daten zu erforschen, zu verstehen, zu analysieren oder benutzerdefinierte Diagramme für ein Projekt oder einen Bericht zu erstellen.

## 3. Eine Fehlermeldung und ihre Lösung

#### Fehlermeldung


----------------------------------------------------------------------------
KeyError                                  Traceback (most recent call last)
<ipython-input-25-c4d5bcbc477b> in <module>
----> 1 pmid_data["result"]["title"]

KeyError: 'title'

----------------------------------------------------------------------------

#### Lösung

Der Key 'title' befindet sich nicht im Dictionary 'result' sondern im untergeordneten Dictionary '27708327'.

Daher muss die Abfrage lauten:

``` 
In: pmid_data["result"]["27708327"]["title"]
Out: 'Democratic databases: science on GitHub.'
```

## 4. Was ist JupyterLab?

Jupyter Notebook ist eine webbasierte interaktive Berechnungsumgebung zur Erstellung von Jupyter Notebooks-Dokumenten und wird hauptsächlich für die Datenanalyse, Datenvisualisierung und weitere interaktive, explorative Berechnungen verwendet.

JupyterLab ist die Benutzeroberfläche der neuesten Generation mit Notebooks. Es ist modular aufgebaut, so dass man mehrere Notebooks oder Dateien (z.B. HTML, Text, Markdowns etc.) als Registerkarten im gleichen Fenster öffnen kann. Außerdem kann eine Code-Konsole mit dem Notebook Kernel verknüpft werden.  Es bietet viel mehr ein IDE-ähnliches Erlebnis.

Für einen Anfänger ist es sinnvoll  mit Jupyter Notebook zu beginnen, da es nur aus einem Dateibrowser und einer (Notebook-)Editoransicht besteht und daher leichter zu bedienen ist. Wenn man mehr Funktionen benötigt, ist JupyterLab die bessere Wahl. JupyterLab bietet viel mehr Funktionen und eine verbesserte Oberfläche, die durch Erweiterungen ausgebaut werden kann.

