# NLP et Transformers - CY Tech

Travaux pratiques du cours *NLP et Transformers* (CY Tech, annee 2026-2027).

Tous les TP utilisent le corpus **Tiny Shakespeare**.

## Serie A - NLP classique

| Notebook | Sujet |
|----------|-------|
| `TP1_NLP_machine_learning.ipynb` | Pipeline TF-IDF, baseline, modeles ML, evaluation et analyse des erreurs |
| `TP2_NLP_deep_learning.ipynb` | Comparaison TF-IDF + regression logistique contre embeddings + LSTM |
| `TP3_NLP_prompting.ipynb` | Classification par prompting (zero-shot / few-shot) et parametres de decodage |

## Serie B - Mini-Transformer

| Notebook | Sujet |
|----------|-------|
| `TP1_transformer_bigramme.ipynb` | Du texte brut au modele bigramme |
| `TP2_transformer_attention.ipynb` | Construction de l'auto-attention pas a pas |
| `TP3_transformer_layernorm_mlp.ipynb` | LayerNorm et reseau feed-forward |
| `TP4_transformer_modele_complet.ipynb` | Assemblage et entrainement du modele complet |

## Execution

Les notebooks tournent sous Python 3.13 (ou dans Google Colab). Dependances
principales : `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `torch`, et
`transformers` (uniquement pour le TP 3 de la serie A).
