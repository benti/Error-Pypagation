# dataAnalyzer
python script to calculate physical quantities from data including units and uncertainty propagation

# ToDo

- Messdaten aus Dateien lesen (Einzelmessungen, Konstanten, Messreihen, abhängige Größen)
- Darum kümmern, dass N,I,O? nicht anders interpretiert werden
- SI-System implementieren, m,c,d,k,M als Vorfaktoren?, clearUnits optimieren
- Latex-Ausgabe verbessern
- Student-t-Faktor beim Mittelwert
- gewichteter Mittelwert
- Regressionen?
- Performance-Verbesserungen?
- GnuPlot-Erweiterung?

# Run it

To use it, you need python3 and sympy. In Ubuntu:

sudo apt-get install python3

sudo apt-get install python3-pip

sudo pip3 install sympy


Then, run:

python3 dataAnalyser.py
