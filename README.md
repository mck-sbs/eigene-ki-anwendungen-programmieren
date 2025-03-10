# Materialien zum Buch "Eigene KI-Anwendungen programmieren".

Video-Anleitung zur Installation von ANACONDA auf Windows: [ANACONDA-WINDOWS](https://youtu.be/yHod97z3GaI?si=jAEDP2uN3c8uJwJf)


Video-Anleitung zur Installation von KNIME auf Windows: [KNIME-WINDOWS](https://youtu.be/NiJ-nJqyAwM?si=55z7rr9wgo7pkyTJ)


Video-Anleitung zur Installation von ANACONDA auf mac: [ANACONDA-MAC](https://youtu.be/XEP31aQ-UFw?si=TE2oAZM6uR1CWdB_)


Video-Anleitung zur Installation von KNIME auf mac: [KNIME-MAC](https://youtu.be/FI2Lu7SCBRQ?si=r0w9RTXH1OEimtHP)

Video-Anleitung, um Jupyter ggf. in einem neuen Environment zu intsallieren und zu starten: [JUPYTER](https://youtu.be/c7Dp09SQl8E)


# Hinweise, Korrekturen und Ergänzungen

Liebe Leserin, lieber Leser,

es erreichen mich wertvolle Hinweise von der Leserschaft – vielen Dank dafür. An dieser Stelle möchte ich darauf eingehen:

- Das Zeichen '\\' leitet in einem String eine Escape-Sequenz ein. Mit '\n' wird z.B. eine neue Zeile eingefügt, also `print("Hallo\nWelt!")`. Wenn das Zeichen als "normales" Zeichen interpretiert werden soll, können Sie einfach ein 'r' vor dem String (r für row) einfügen. Beispiel: Sie möchten mit `data = pd.read_csv(path, delimiter=',')` eine Datei laden. Das vorherige Initialisieren der Variable mit `path = "C:\Users\mk\Downloads\iris.csv"` führt zu einem Fehler, den Sie einfach mit `path = r"C:\Users\mk\Downloads\iris.csv"` korrigieren können.
  
- macOS mit M-Chips: Sie können fast alle Programme auch mit dieser HW/SW verwenden. Es kann lediglich zu Problemen kommen, wenn KNIME in Kombination mit KERAS-Bausteinen verwendet wird. In diesem Fall können Sie KNIME zur Vorbereitung und Verarbeitung der Daten nutzen, das künstliche neuronale Netz bauen Sie anschließend mit Python-Bausteinen in KNIME auf. Beispiele dazu sind im Buch und auch hier in den Programmen. Die Python-Beispiele (ohne KNIME) funktionieren aber auch hier problemlos. Sie müssen nur sicherstellen, dass die notwendige Software richtig installiert ist. Hinweise zur Installation und Problemlösung finden Sie in den verlinkten Videos.




------------------------------------------

"Eigene KI-Anwendungen programmieren", [Rheinwerk Verlag](https://www.rheinwerk-verlag.de/eigene-ki-anwendungen-programmieren)

![Cover](https://s3-eu-west-1.amazonaws.com/cover2.galileo-press.de/print/9783836297639_800.png)



