# Errata zu `lectures/llm-hausgebrauch.pdf`

Stand: 26.02.2026

## Version 1.0 (19.01.2026)

### Seite 22 (Attention-Rechenbeispiel)

- Im roten Kasten (`Ergebnis`) ist der letzte Wert des neuen Attention-Vektors als
  `(0.304, 0.529, 0.603, 0.339)` angegeben.
- Korrekt ist:
  `(0.304, 0.529, 0.603, 0.399)`
- Begründung:
  Das zugehoerige Notebook `notebooks/attention_rechenbeispiel.ipynb` ergibt konsistent
  den Wert `0.3986366`, gerundet `0.399`. Die auf der Folie gezeigten Attention-Gewichte
  und Scores sind damit ebenfalls konsistent.

### Seite 31 (Gradientenabstieg Iteration)

- In der Tabelle `Weiter Schritt 5: Das Netz lernt durch Fehlerkorrektur` ist in der
  letzten Zeile (Iteration 5) mindestens ein Wert inkonsistent.
- Auffaellig ist insbesondere `w22 = 0.15` (positiv).
- Korrekt (gemaess Rechnung/Notebook `notebooks/gradient_descent_wq_diagonal.ipynb`) ist:
  `w22 = -0.155` (gerundet) bzw. negativ.
- Entsprechend unterscheiden sich in der letzten Tabellenzeile auch die Werte fuer
  `Output z` und `Fehler` leicht:
  Notebook: `z_hat ≈ 0.536`, Fehler `≈ 0.036`
  Folie: `z_hat ≈ 0.540`, Fehler `≈ 0.040`

## Hinweis zur Verifikation

- Die Jupyter-Notebooks wurden gegen das PDF geprueft und sind inhaltlich konsistent.
- Die oben genannten Abweichungen liegen auf PDF-/Folienseite, nicht in den Notebooks.
