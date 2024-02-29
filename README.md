# Ausgewählte Kapitel der Industriellen Informatik
## Memory-Safety und die Programmiersprache Rust

Empirische Erhebungen im letzten Jahrzehnt haben gezeigt, dass in allen großen Codebases (egal ob kommerziell oder Open-Source) der Anteil von Memory-Safety Fehlern an kritischen Sicherheitslücken bei ungefähr 70% liegt.  
Menschen machen Fehler, und die digitale Welt ist keine Ausnahme. Deswegen gibt es Bestrebungen in der Informatik, die Sicherheit von Software zu erhöhen, indem die Grundbausteine sicherer gemacht werden (wie z.B. auch Maschinen in der echten Welt).

Ein Grundbaustein sind die Programmiersprachen selbst, eine davon ist  [Die Programmiersprache Rust](https://www.rust-lang.org/) mit der wir uns hier vertraut machen wollen.  

Dieses repo enthält ein Jupyter-Notebook ausführbar mit dem Jupyter Rust Kernel und eine interaktive Slideshow mit [RISE](https://rise.readthedocs.io/en/stable/).


## Installation und Setup

Installieren Sie folgende Komponenten:

1. Installieren Sie Python (getestet mit 3.11).  
2. Installieren Sie cargo/rustc z.B. via rustup. 
3. Danach installieren Sie noch den [EvCxR Rust Kernel](https://github.com/google/evcxr/tree/master/evcxr_jupyter)  

Klonen Sie das repo und wechseln Sie in den Ordner:

```Bash
git clone https://github.com/dorianprill/akii-rust.git
cd akii-rust
```

Erstellen Sie ein neues Virtual Environment für Python (3.6+) und aktivieren Sie es 
(Für Windows schauen Sie bitte in der offiziellen Python Dokumentation nach):

```Bash
python -m venv .venv
source .venv/bin/activate
```

Jetzt sollten sie sich in einer virtuellen Shell befinden, angezeigt durch den Namen des virtual environments in der Kommandozeile.
Installieren sie die ABhängigkeiten aus der Datei `requirements.txt` mit `pip`.

```Bash
pip install -r requirements.txt
```

und installieren sie anschließend den [excvr Rust Kernel nach dieser Anleitung.](https://github.com/evcxr/evcxr/blob/main/evcxr_jupyter/README.md) 


## Das Notebook starten

Die virtuelle muss aktiviert sein, um das Jupyter-Notebook zu starten.
Führen sie folgenden Befehl aus:

```Bash
jupyter lab
```

und öffnen sie das Notebook `AKII-Rust.ipynb` in Jupyter Lab.

