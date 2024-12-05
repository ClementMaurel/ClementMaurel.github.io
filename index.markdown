# 👨‍🎓 Clément MAUREL  

## 🎯 Objectif  
**🔍 Recherche d'un contrat d'apprentissage en master**  
Étudiant et futur diplômé d'un **BUT Sciences des données**, j'occupe actuellement un poste de **📊 Data Analyst** en alternance chez **✈️ Airbus Commercial Aircraft**. Je suis à la recherche d'un contrat en apprentissage pour préparer un **🎓 Master** dans le domaine de l'ingénierie des données ou du **📂 Data Management**.  

---

## 📬 Coordonnées  
- 📞 **Téléphone :** 06 40 71 97 05  
- ✉️ **E-mail :** [clems2000@outlook.fr](mailto:clems2000@outlook.fr)  
- 📍 **Adresse :** 4 route de Castelnau, 31330 Ondes  
- 🌍 **Localisation :** Toulouse  
- 🎂 **Date de naissance :** 04/08/2003  
- 🚗 **Permis de conduire :** Permis B (avec véhicule personnel)  

---

## 🎓 Diplômes et Formations  
### **📚 BUT Sciences des données**  
**Depuis septembre 2022**  
IUT de Carcassonne, Carcassonne (11000)  
**Parcours VCOD (Visualisation et Conception d'Outils Informatiques)**  
- **📂 Data Management** : Gestion et organisation des données pour assurer leur accessibilité et leur intégrité.  
- **💻 Programmation** : Développement de solutions logicielles adaptées aux besoins utilisateurs.  
- **📈 Analyse statistique** : Interprétation de données complexes via des méthodes statistiques.  
- **🤖 Intelligence artificielle** : Initiation au Machine Learning.  

---

## 💼 Expériences professionnelles  

### **📊 Analyste de données (apprentissage)**  
**Depuis septembre 2023**  
**✈️ Airbus Commercial Aircraft**, Toulouse (Saint-Martin)  
- 🛠️ Développement de scripts automatisés avec **Google Apps Script**.  
- 🐍 Analyse et traitement des données avec **Python**.  
- 📊 Création et suivi de tableaux de bord de performance (**KPI**).  
- 📝 Présentation de rapports analytiques clairs et concis.  
- 🤝 Collaboration avec diverses équipes pour répondre aux besoins en données.  

### **💻 Développeur Visual Basic**  
**Juin 2021 - Juillet 2021**  
**⚡ Engie Solutions (Cofely)**, Toulouse (31) - Stage de première année  
- 📂 Automatisation de fichiers Excel avec **VBA (Visual Basic for Applications)**.  
- 📑 Création de rapports analytiques pour comprendre les performances et tendances.  

---

## 🛠️ Compétences  

### **💻 Programmation**  
- 🐍 Python  
- 📊 R  
- 🤖 Google Apps Script  
- 💾 VisualBasic  

### **📂 Bases de données**  
- 📋 MyAccess  
- 🗂️ PgSQL  
- 🌐 MongoDB  
- 🛠️ Neo4j  

### **📊 Visualisation**  
- 📉 PowerBI  
- 📊 Tableau  
- 📈 Splunk  

### **🗺️ Cartographie**  
- 🗺️ Arcgis  
- 🗺️ Arcmap  
- 🌍 PostGis  
- 🔄 FME  

---

## 🌍 Langues  
- **🇬🇧 Anglais :** Niveau B1  
- **🇪🇸 Espagnol :** Notions  

---

## ⭐ Atouts  
- 🤝 Adaptabilité  
- 👥 Esprit d'équipe  
- 🎨 Créativité  
- 🔍 Curiosité  

---

## 🏉 Centres d'intérêt  

### **🏉 Rugby**  
Joueur fidèle au **Grenade Sport** depuis l'âge de 5 ans (2008-2022), occupant le poste de troisième ligne. Expérience en rugby à 7, à 12, à 13 et à 15.  

### **🎨 Design**  
Passion pour le **design de l'information**, l'**architecture**, les **arts urbains** et la **peinture**. Intérêt pour la créativité et l'expression visuelle.  


---
 # Diagramme


```mermaid
classDiagram

Portfolio "1" --> "*" Page : contient
Portfolio "1" --> "*" Projet : contient
Portfolio "1" --> "1" CV : contient

class Portfolio {
    +String titre
    +String description
    +String theme
}

class Page {
    +String nom
    +String contenu
}

class Projet {
    +String nom
    +String description
    +String url
}

class CV {
    +String fichier
}


```

```mermaid
sequenceDiagram
    participant Utilisateur
    participant ServeurGitHub
    participant ServeurWebJekyll

    Utilisateur->>ServeurWebJekyll: Demande page
    ServeurWebJekyll->>ServeurGitHub: Récupère projets
    ServeurGitHub->>ServeurWebJekyll: Envoie projets
    ServeurWebJekyll->>Utilisateur: Affiche projets
```
---
