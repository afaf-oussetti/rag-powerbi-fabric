# RAG PowerBI Fabric

La documentation Power BI et Microsoft Fabric est volumineuse et éclatée entre plusieurs sources officielles, ce qui rend la recherche d'une réponse précise longue et fastidieuse. Ce projet propose un assistant conversationnel qui s'appuie sur cette documentation pour répondre directement aux questions techniques des utilisateurs.

## Présentation

**RAG PowerBI Fabric** est un assistant basé sur une architecture RAG (Retrieval-Augmented Generation) interrogeant la documentation officielle de Power BI et de Microsoft Fabric. Il est déployé en ligne via [Streamlit](https://streamlit.io/), ce qui le rend accessible directement depuis un navigateur, sans installation.

## Fonctionnalités

- Recherche sémantique dans la documentation Power BI et Microsoft Fabric
- Génération de réponses contextualisées à partir des documents retrouvés
- Interface web simple via Streamlit

## Stack technique

- Python
- Framework RAG (à préciser selon l'implémentation)
- Base vectorielle pour l'indexation des documents
- Streamlit pour l'interface et le déploiement

## Installation

```bash
git clone https://github.com/afaf-oussetti/rag-powerbi-fabric.git
cd rag-powerbi-fabric
pip install -r requirements.txt
```

## Utilisation

```bash
streamlit run app.py
```

## Démo en ligne

*(Lien vers l'application déployée à ajouter ici)*

## Roadmap

- [ ] Recherche hybride (combinaison recherche vectorielle + recherche par mots-clés)
- [ ] Évaluation systématique de la qualité des réponses (jeu de test, métriques de pertinence)

## Licence

Ce projet est sous licence [MIT](LICENSE).
