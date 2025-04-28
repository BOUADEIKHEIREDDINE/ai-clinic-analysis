
# AI Clinic - Energy Data Analysis Projects

Ce dépôt regroupe plusieurs projets d'analyse de données réalisés dans le cadre de l'AI Clinic. Chaque notebook explore une problématique différente en utilisant des données énergétiques, climatiques et démographiques.

## 📂 Structure du projet
En raison de la taille importante des fichiers de données, le dossier databasis/ n'est pas inclus dans ce dépôt GitHub. Les notebooks restent néanmoins accessibles et prêts à être exécutés localement avec les données appropriées.
ai_clinic_energy_analysis/
│
├── databasis/                        # Dossier pour stocker les bases de données (localement)
│   ├── eco2mix-regional-cons-def.csv
│   ├── temperature-quotidienne-regionale.csv
│   ├── pop_2016_2022.xlsx
│   ├── Nombre_dusines_par_region.xlsx
│   └── data.csv
│
├── notebooks/                        # Dossier contenant tous les notebooks .ipynb
│   ├── analyse_consommation_electrique.ipynb
│   ├── analyse_temperature_regionale.ipynb
│   ├── fusion_donnees_statistiques.ipynb
│   ├── comparaison_energie_population_temperature.ipynb
│   └── analyse_donnees_generale.ipynb
│
├── README.md                          # Présentation du projet
├── requirements.txt                   # Liste des dépendances Python

## 🧠 Contenu des notebooks

- **analyse_consommation_electrique.ipynb** : Analyse de la consommation d'électricité par région.
- **analyse_temperature_regionale.ipynb** : Analyse des températures régionales quotidiennes.
- **fusion_donnees_statistiques.ipynb** : Fusion et traitement de jeux de données statistiques.
- **comparaison_energie_population_temperature.ipynb** : Comparaison entre consommation électrique, population et climat.
- **analyse_donnees_generale.ipynb** : Analyse exploratoire générale de jeux de données.

---

## ⚠️ Remarque importante

- **Les fichiers de données ne sont pas inclus dans ce dépôt.**  
- La base de données est **trop volumineuse** pour être hébergée sur GitHub.
- **Seuls les notebooks sont disponibles.**
- Pour exécuter correctement les notebooks, vous devez disposer localement des fichiers listés dans `/databasis/`.
- Les chemins d'accès aux données sont **relatifs** et configurés pour fonctionner automatiquement.

---

## 🚀 Comment exécuter les notebooks

1. Cloner le dépôt :
    ```bash
    git clone https://github.com/TON_UTILISATEUR/ai_clinic_energy_analysis.git
    cd ai_clinic_energy_analysis
    ```

2. Installer les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

3. Lancer Jupyter Notebook :
    ```bash
    jupyter notebook
    ```

4. Ouvrir le dossier `notebooks/` et choisir le fichier `.ipynb` à exécuter.

---

## 🛠️ Technologies utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
