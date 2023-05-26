# Cryptage de dossier avec pyAesCrypt

Ce script Python utilise la bibliothèque pyAesCrypt pour crypter un dossier à l'aide de l'algorithme de chiffrement AES. Il demande à l'utilisateur de spécifier le chemin du dossier à protéger et un mot de passe, puis il effectue le cryptage du dossier en créant un fichier d'archive crypté.

## Installation

Pour exécuter ce script, vous devez installer les dépendances suivantes :

- pyAesCrypt : `pip install pyAesCrypt`

Le module `getpass` est également utilisé pour masquer la saisie du mot de passe à l'utilisateur lors de l'exécution du script. Ce module est généralement inclus avec l'installation standard de Python, il n'est donc pas nécessaire de l'installer séparément.

## Utilisation (j'ai utilisé jupyter notebook d'ananconda comme environnement de travail)

1. Exécutez le script Python 'Devoir1_LEUMENI_LIONEL.ipynb' en cliquant sur le bouton executer ou alors avec la combinaison de touches (Shift+Entrer)
2. Suivez les instructions pour fournir le chemin du dossier à protéger et un mot de passe.
3. Le dossier sera crypté et un fichier d'archive crypté sera créé.
4. Le nom de l'archive cryptée sera affiché à l'écran.

Assurez-vous de ne pas perdre le mot de passe utilisé pour crypter le dossier, car il sera nécessaire pour déchiffrer le dossier ultérieurement.

## Notes

- Ce script utilise l'algorithme de chiffrement AES pour assurer la sécurité du dossier crypté.
- Assurez-vous d'utiliser un mot de passe fort et de le garder en sécurité.
- Ce script ne prend pas en charge le chiffrement de fichiers individuels, seulement des dossiers entiers.

MERCI!
