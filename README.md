## 1. Text-Editor der Wahl

- Emacs

## 2. Eine Python-Bibliothek

-

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

Daher muss der Abfrage lauten:

      In: pmid_data["result"]["27708327"]["title"]

      Out: 'Democratic databases: science on GitHub.'


## 4. Was ist JupyterLab?

-

