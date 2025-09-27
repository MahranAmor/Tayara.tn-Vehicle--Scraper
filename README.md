🚗 Tayara Vehicle Scraper
Description
Workflow automatisé n8n pour extraire et structurer les annonces de véhicules depuis Tayara.tn. Utilise l'intelligence artificielle pour nettoyer et organiser les données en format CSV prêt à l'analyse.
✨ Fonctionnalités
🔄 Scraping Automatisé

Multi-pages : Scrape automatiquement 1 à 30+ pages
Robuste : Continue même si certaines pages échouent
Délais intelligents : Évite la surcharge serveur avec pauses automatiques
Retry automatique : Retente les requêtes échouées

🤖 IA de Nettoyage

Extraction intelligente des champs clés :

Marque et modèle du véhicule
Année de fabrication
Kilométrage
Prix en dinars tunisiens
Type de carburant
Boîte de vitesse
État du véhicule
Localisation géographique


Normalisation des formats de données
Validation et correction automatique

📊 Export Structuré

Format CSV compatible Excel/Google Sheets
Colonnes organisées et nommées clairement
Headers automatiques
Données prêtes à l'analyse

🛠️ Technologies Utilisées

n8n - Automation workflow
Jina.ai - Web scraping API
Mistral AI - Processing et nettoyage des données
JavaScript - Logique de boucles et manipulation

📋 Configuration
Prérequis

Instance n8n active
Accès à Jina.ai API
Modèle Mistral configuré

Structure du Workflow
Function Node (Pages) → Loop Over Items → HTTP Request → Wait Node → AI Agent → Create Spreadsheet
Paramètres Configurables

Nombre de pages : Modifier dans le Function Node
Délai entre requêtes : Ajustable dans Wait Node
Champs d'extraction : Personnalisables dans l'Agent IA

🚀 Installation

Importer le workflow dans n8n
Configurer vos credentials API
Ajuster le nombre de pages souhaité
Lancer l'exécution

📈 Performances

~20 pages en 2-3 minutes
Taux de réussite : >95%
Données structurées : 100% des résultats valides

🎯 Cas d'Usage

Analyse de marché automobile tunisien
Veille concurrentielle prix véhicules
Études statistiques parc automobile
Base de données pour revendeurs
Recherche académique mobilité urbaine

⚠️ Respect des Conditions

Usage éthique et respectueux des serveurs
Délais appropriés entre requêtes
Conformité aux conditions d'utilisation Tayara.tn
Données publiques uniquement

🔧 Personnalisation
Le workflow peut être adapté pour :

D'autres catégories Tayara (immobilier, électronique...)
Sites similaires (Tunisie Annonces, etc.)
Exports différents (JSON, XML, Base de données)
Langues multiples
