## Описание проекта

Данный репозиторий содержит **практическую реализацию** ключевых механизмов внимания (Attention), используемых в современных архитектурах нейросетей (Transformer, GPT, BERT, Qwen).

В проекте реализованы **6 механизмов внимания**:

| № | Механизм | Файл |
|---|----------|------|
| 1 | Self-Attention | `self-att.ipynb` |
| 2 | Multi-Head Attention | `multi-head-att.ipynb` |
| 3 | Masked Self-Attention | `Masked Self-Attention.ipynb` |
| 4 | Cross-Attention | `Cross_Attention.ipynb` |
| 5 | Gated Attention | `gated attention.ipynb` |
| 6 | Gated DeltaNet | `gated_deltanet.ipynb` |

Каждый механизм сопровождается:
- Реализацией на Python (NumPy)
- Визуализацией результатов (тепловые карты, графики)
- Выводом числовых значений в консоль

**Полное теоретическое описание** содержится в файле [`ATTENTION.docx`](ATTENTION.docx).

### Требования

- Python 3.8+
- Jupyter Notebook / JupyterLab
