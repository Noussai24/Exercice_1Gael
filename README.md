# Exercice_1Gael
# Automatisation de la Recherche d'Images sur DuckDuckGo

Ce projet démontre comment automatiser un navigateur web pour effectuer une recherche d'images sur DuckDuckGo en utilisant Selenium en Python. Le script recherche le terme "generative ai" dans la section des images et vérifie qu'il y a plus de 20 résultats.

## Table des Matières

- [Vue d'Ensemble](#vue-densemble)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du Projet](#structure-du-projet)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Vue d'Ensemble

Ce projet utilise Selenium WebDriver pour :
1. Ouvrir DuckDuckGo.
2. Effectuer une recherche pour le terme "generative ai".
3. Naviguer vers la section Images.
4. Vérifier que le nombre de résultats d'images est supérieur à 20.

## Prérequis

- Python 3.x
- Selenium
- WebDriver Manager

## Installation

1. Clonez le dépôt :
    ```bash
    git clone https://github.com/votrenomutilisateur/duckduckgo-image-search.git
    cd duckduckgo-image-search
    ```

2. Créez un environnement virtuel et activez-le :
    ```bash
    python -m venv venv
    source venv/bin/activate   # Sous Windows utilisez `venv\Scripts\activate`
    ```

3. Installez les packages requis :
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

1. Exécutez le script :
    ```bash
    python duckduckgo_search.py
    ```

2. Le script ouvrira une fenêtre de navigateur, effectuera la recherche et vérifiera le nombre de résultats d'images.

## Structure du Projet

- `duckduckgo_search.py` : Script principal pour effectuer la recherche automatisée.
- `requirements.txt` : Liste des dépendances.

## Contribuer

Les contributions sont les bienvenues ! Veuillez ouvrir une issue ou soumettre une pull request pour toute modification ou amélioration.

## Licence

Ce projet est licencié sous la licence MIT. Voir le fichier LICENSE pour plus de détails.

---

### Exemple de Sortie

```plaintext
Ouverture de DuckDuckGo...
Recherche de "generative ai"...
Navigation vers la section Images...
25 résultats d'images trouvés.
