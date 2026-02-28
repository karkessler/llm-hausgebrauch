# LLM für den Hausgebrauch

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18293327.svg)](https://doi.org/10.5281/zenodo.18293327)

Technische Einführung in Large Language Models (LLMs) für Studierende und Praktiker:innen.

## Inhalte

- Transformer-Architektur und Self-Attention
- Tokenisierung, Embeddings, Backpropagation
- Vektor-Datenbanken und RAG
- Grenzen und Risiken von LLMs

## Materialien

📄 **Skript:** [https://tutor.kkessler.de/LLM/llm-hausgebrauch.html](https://tutor.kkessler.de/LLM/llm-hausgebrauch.html)

## Notebooks

Die Jupyter-Notebooks können direkt in Google Colab geöffnet werden:

- [Mathematische Grundlagen](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/kapitel_3_mathematische_grundlagen.ipynb)
- [Tokenisierung](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/tokenisierung_beispiel.ipynb)
- [Positional Encoding](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/positional_encoding_beispiel.ipynb)
- [Attention Rechenbeispiel](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/attention_rechenbeispiel.ipynb)
- [Multi-Head Attention (Toy)](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/multihead_attention_toy.ipynb)
- [Causal Masking](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/causal_masking_rechenbeispiel.ipynb)
- [Next Token Vorhersage 1](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/next_token.ipynb)
- [Next Token Vorhersage 2 (Toy)](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/next_token_prediction_toy.ipynb)
- [Gradient Descent (Wq diagonal)](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/gradient_descent_wq_diagonal.ipynb)
- [Decoder: Softmax + Cross-Entropy](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/decoder_softmax_crossentropy_wout.ipynb)
- [Qdrant Demo](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/qdrant_demo.ipynb)
- [RAG End-to-End (Toy)](https://colab.research.google.com/github/karkessler/llm-hausgebrauch/blob/main/notebooks/rag_end_to_end_toy.ipynb)

## Hinweise zur lokalen Ausführung der Notebooks

- Paketinstallation (im Projektverzeichnis): `pip install -r requirements-notebooks.txt`
- Empfohlen: eigenes Python-Environment (virtuelle Umgebung oder Conda) mit Jupyter-Kernel `python3`.
- Nach `%pip install ...` in einem Notebook ggf. den Kernel neu starten, damit neue Pakete sicher importiert werden.
- `qdrant_demo.ipynb` benoetigt `qdrant-client` und `sentence-transformers`.
- Falls beim Import von `sentence-transformers` ein Keras-3-Fehler auftritt, zusaetzlich ausfuehren: `%pip install tf-keras` und den Kernel neu starten.

## Lizenz

CC BY 4.0
