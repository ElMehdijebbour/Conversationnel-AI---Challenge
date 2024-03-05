# Partenaire Conversationnel AI 


Ce projet est  développé dans le cadre du challenge de sélection pour un stage à la Banque de France, axé sur l’exploration des modèles de Langage à Grande Échelle (LLM) pour aider à la rédaction de notes. L'application Streamlit créée permet aux utilisateurs, y compris ceux sans compétences en informatique, de générer du texte basé sur des instructions spécifiques, facilitant ainsi la rédaction de documents et de notes.

## Contexte du Challenge

Le challenge consiste à développer une Interface Homme-Machine (IHM) simple, permettant la génération de texte à partir d'instructions renseignées par l'utilisateur. Cela s'inscrit dans un effort plus large d'exploration des capacités des LLM au sein de la Banque de France, notamment pour la rédaction de notes. 

## Installation

Le projet est structuré pour utiliser un environnement virtuel, garantissant une gestion isolée des dépendances. Il nécessite également la configuration d'une clé API de openAI ChatGpt pour simuler l'accès aux services de LLM.

### Prérequis

- Python 3.9 ou version ultérieure.
- pip et virtualenv.

### Étapes d'installation

1. **Clonage du dépôt** : Clonez le dépôt GitHub sur votre machine locale pour commencer.

    ```bash
    git clone https://github.com/ElMehdijebbour/Conversationnel-AI---Challenge
    cd votre_repo
    ```

2. **Configuration de l'environnement virtuel** : Créez et activez un environnement virtuel pour isoler les installations des dépendances.

    ```bash
    python -m venv env
    # Sur Windows
    env\Scripts\activate
    # Sur Unix ou MacOS
    source env/bin/activate
    ```

3. **Installation des dépendances** : Installez les dépendances nécessaires à partir du fichier `requirements.txt`.

    ```bash
    pip install -r requirements.txt
    ```

4. **Configuration des variables d'environnement** : Créez un fichier `.env` à la racine du projet et ajoutez-y votre clé API pour les modèles LLM. (Notez que ce fichier ne doit pas être poussé sur des dépôts publics pour des raisons de sécurité.)

    ```
    OPENAI_API_KEY="votre_clé_api"
    ```

5. **Lancement de l'application** : Exécutez l'application Streamlit.

    ```bash
    streamlit run app.py
    ```

## Déploiement

L'application est déployée avec Vercel pour une mise à disposition facile et accessible. Pour plus d'informations sur le déploiement avec Vercel, visitez [Vercel Documentation](https://vercel.com/docs).


## Crédits

Développé par [El Mehdi Jebbour](https://github.com/ElMehdijebbour) dans le cadre du challenge de sélection pour un stage à la Banque de France sur l’exploration des modèles de LLM.

## Lien vers le Challenge

Pour plus de détails sur le challenge, visitez [Banque de France Challenge](https://app.b2ideas.eu/Project/DetailsProject/138).
