# Competición Kaggle: Sentimiento Financiero

## Descripción
Este repositorio contiene los códigos y modelos utilizados en la competición de Kaggle [Sentimiento Financiero](https://www.kaggle.com/competitions/sentimiento-financiero), realizada como parte de la asignatura **Procesamiento de Texto y Lenguaje Natural**.

El objetivo de la competición es clasificar el sentimiento de textos financieros en tres categorías. Se han implementado múltiples enfoques para abordar el problema y mejorar el rendimiento del modelo.

La métrica utilizada para la evaluación es **F1 Macro**.
La evaluación se realiza en dos fases:
- **Primera evaluación:** Utiliza el 50% del conjunto de test.
- **Evaluación final:** Se realiza con el 50% restante del test.

---

## Datasets
Los conjuntos de datos utilizados en la competición son:
- `FinancES_train_kaggle.csv`: Dataset de entrenamiento.
- `FinancES_test_kaggle.csv`: Dataset de prueba.

---

## Modelos Implementados
Se han explorado diversos modelos para la clasificación del sentimiento financiero:

### Modelos Basados en Representaciones Clásicas
- **TF-IDF + SVM**: `clasificacion_comentarios_tfidf_svm.ipynb`
- **Word2Vec + Random Forest**: `clasificacion_comentarios_word2vec_rf.ipynb`
- **FastText**: `FastText.ipynb`

### Modelos Basados en Redes Neuronales
- **RNN + LSTM**: `clasificacion_comentarios_RNN_LSTM.ipynb`

### Modelos Basados en Transformers
- **RoBERTa Fine-Tuning**: `Finetuning_RoBERTa.ipynb`
- **RoBERTa con contexto**:
    - `Roberta_context.ipynb`
    - `roberta_2_context.ipynb`
- **Variantes de RoBERTa:**
  - `roberta_opt_bay.ipynb` (Optimización Bayesiana)
  - `roberta_spanish.ipynb`
  - `roberta_multilingual.ipynb`
- **RoBERTuito**: `Robertuito.ipynb`
- **BETO**:
  - `beto.ipynb`
  - `beto_opt_bay.ipynb` (Optimización Bayesiana)

Además, se incluye el archivo `word2vec_model.bin`, que contiene un modelo de Word2Vec preentrenado utilizado en algunos experimentos.

---

## Autores
- Carmen Linares Vázquez.
- María Millán Gordillo.
- Pablo Téllez López.
