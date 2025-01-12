# Pizza-mama

Voici un exemple simplifié et adapté de fichier README pour votre projet Pizza Mama :

🍕 Pizza Mama

Pizza Mama est un projet web développé avec Django. Ce site affiche une liste de pizzas avec leurs prix et un badge pour identifier les pizzas végétariennes. Le côté client est réalisé en HTML/CSS pour un design simple et épuré.

📋 Fonctionnalités
	•	Affichage d’une liste de pizzas avec leurs noms, descriptions et prix.
	•	Identification des pizzas végétariennes grâce à un badge distinctif.
	•	Backend simple et robuste construit avec Django.
	•	Interface utilisateur statique en HTML et CSS.

🛠️ Technologies utilisées
	•	Backend : Django 4.x
	•	Frontend : HTML, CSS (sans framework CSS)
	•	Base de données : SQLite (par défaut de Django)

⚙️ Installation

1. Clonez le dépôt

git clone https://github.com/Alioune4002/Pizza-mama.git
cd pizza-mama

2. Créez un environnement virtuel et activez-le

python -m venv env
# Sur Windows :
env\Scripts\activate
# Sur macOS/Linux :
source env/bin/activate

3. Installez les dépendances

pip install -r requirements.txt

4. Configurez la base de données

Exécutez les commandes suivantes pour appliquer les migrations :

python manage.py makemigrations
python manage.py migrate

5. Lancez le serveur local

python manage.py runserver

Le site sera accessible à l’adresse suivante : http://127.0.0.1:8000.

6. (Optionnel) Créez un super-utilisateur pour gérer les données

python manage.py createsuperuser


🌱 Exemple de Pizza
	•	Margherita : 8,00€ (Badge végétarien 🥦)
	•	Pepperoni : 10,00€
	•	Végétarienne Deluxe : 12,00€ (Badge végétarien 🥦)

Les pizzas végétariennes sont marquées avec un badge 🥦 pour les différencier facilement.

💡 Améliorations futures
	•	Ajouter une fonctionnalité pour permettre aux utilisateurs de commander des pizzas.
	•	Intégrer un design responsive avec Bootstrap ou Tailwind CSS.
	•	Ajouter une page admin personnalisée pour gérer les pizzas facilement.
