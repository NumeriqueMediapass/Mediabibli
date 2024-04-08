
# MediaBibli

MediaBibli est un projet open-source de gestion de bibliothèque et de médiathèque, développé avec le framework Django. Il offre une solution complète pour gérer un réseau de médiathèques, y compris le transfert de livres entre les médiathèques, les réservations, et toutes les fonctionnalités nécessaires au bon fonctionnement d'une bibliothèque.

## Fonctionnalités

- Gestion d'un réseau de médiathèques ou d'une médiathèque unique
- Transfert de livres entre médiathèques
- Réservation de livres et autres ressources
- Gestion des adhérents et des abonnements
- Gestion des catalogues de livres, de revues, de DVD, etc.
- Recherche avancée dans le catalogue
- Historique des emprunts et des retours
- Statistiques et rapports sur l'utilisation de la médiathèque
- Gestion des pénalités de retard
- Interface d'administration conviviale

## Prérequis

- Python 3.10 ou supérieur
- Django 5.x ou supérieur
- Un environnement virtuel (recommandé)

## Installation en local

1. Clonez le référentiel MediaBibli depuis GitHub :
```bash
git clone https://github.com/votre-utilisateur/MediaBibli.git
```
2. Naviguez jusqu'au répertoire du projet :
```bash
cd MediaBibli
```
3. Créez un environnement virtuel (facultatif mais recommandé) :
```bash
python -m venv env
```
4. Activez l'environnement virtuel :
```bash
source env/bin/activate (Unix)
env\Scripts\activate (Windows)
```
5. Installez les dépendances à partir du fichier `requirements.txt` :
```bash
pip install -r requirements.txt
```
6. Créez un fichier `.env` pour stocker les variables d'environnement sensibles, telles que les clés d'API et les informations de base de données. Vous pouvez utiliser le fichier `.env.example` comme modèle.
7. Appliquez les migrations Django pour créer les tables de la base de données :
```bash
python manage.py migrate
```
8. Créez un superutilisateur pour accéder à l'interface d'administration :
```bash
python manage.py createsuperuser
```
9. Lancez le serveur de développement Django :
```bash
python manage.py runserver
```
10. Accédez à MediaBibli dans votre navigateur à l'adresse `http://127.0.0.1:8000/`.

## Contribution

Les contributions à MediaBibli sont les bienvenues ! Si vous souhaitez contribuer, veuillez consulter notre guide de contribution et notre code de conduite.

## Licence

MediaBibli est un logiciel open-source distribué sous la licence MIT. Consultez le fichier `LICENSE` pour plus de détails.