🚗 Tayara Vehicle Scraper
Solution complète pour extraire et structurer les annonces de véhicules depuis Tayara.tn, en offrant deux méthodes complémentaires :
1️⃣ Workflow automatisé n8n
2️⃣ Script Python autonome

✨ Fonctionnalités générales

Scraping multi-pages : 1 à 30+ pages, avec reprise automatique en cas d’erreurs

Nettoyage intelligent des champs clés (marque, modèle, année, prix, carburant, boîte, localisation, etc.)

Export CSV prêt à l’analyse (Excel/Google Sheets)

Délais intelligents et retry automatique pour protéger le serveur

🛠️ Méthodes disponibles
1️⃣ Workflow n8n

Automatisation totale grâce à n8n

Boucles, pauses intelligentes, API Jina.ai pour le scraping

Traitement des données avec un agent IA (Mistral)

Idéal pour un usage sans code et exécutions planifiées

2️⃣ Script Python

Méthode alternative pour les développeurs préférant le code

Basée sur requests et BeautifulSoup

Personnalisable pour ajouter des filtres, changer de format d’export ou intégrer à d’autres projets

Convient à une exécution ponctuelle ou intégrée dans un pipeline data

📋 Prérequis

n8n : instance active + credentials Jina.ai + modèle Mistral configuré

Python : environnement Python 3, bibliothèques requests, beautifulsoup4, csv installées

🚀 Installation rapide

Option n8n : importer le workflow, configurer les clés API, définir le nombre de pages et lancer.

Option Python : exécuter le script sur votre machine ou serveur après installation des dépendances.

📈 Performances

~20 pages traitées en 2–3 minutes

Taux de réussite >95 %

Données structurées et valides à 100 %

🎯 Cas d’usage

Analyse du marché automobile tunisien

Veille concurrentielle (prix et disponibilité)

Études statistiques du parc automobile

Base de données pour revendeurs

Recherche académique en mobilité urbaine

⚠️ Respect des conditions d’utilisation

Scraping éthique et respectueux des serveurs

Délais appropriés entre requêtes

Données strictement publiques
