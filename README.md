<h1 align="center">📊 Looker Studio Test Dataset</h1>

<p align="center">
  <img src="star.gif" alt="demo" width="200"/>
</p>

<p align="center">
  Dataset Excel prêt à l'emploi pour tester Looker Studio (dashboard, filtres, iframe)
</p>

---

## 🚀 Objectif

Ce projet fournit un **jeu de données réaliste e-commerce** pour :

- Tester Looker Studio rapidement
- Construire des dashboards interactifs
- Expérimenter l’intégration en iframe

---

## 📁 Dataset

Fichier : `looker_studio_test_data.xlsx`

### 🧾 Contenu

| Champ | Description |
|------|------------|
| Date | Date de la vente |
| Country | Pays |
| City | Ville |
| Product_Category | Catégorie produit |
| Product | Produit |
| Sales_Channel | Online / Store |
| Units_Sold | Quantité |
| Unit_Price | Prix |
| Revenue | Chiffre d’affaires |
| Customer_Type | New / Returning |

---

## 📊 Exemple d’analyses possibles

- 📈 Chiffre d’affaires dans le temps
- 🌍 Performance par pays
- 🛒 Top produits
- 🧍‍♂️ Nouveaux vs clients récurrents
- 🏪 Online vs magasin

---

## 🛠️ Import dans Looker Studio

### 1. Accéder à Looker Studio
👉 https://lookerstudio.google.com/

---

### 2. Créer une source de données
- Cliquer sur **Créer**
- Puis **Source de données**

---

### 3. Importer le fichier
- Choisir **File Upload**
- Importer `looker_studio_test_data.xlsx`

---

### 4. Vérifier les types
Assure-toi que :
- `Date` → Date
- `Revenue` → Nombre
- `Units_Sold` → Nombre

---

### 5. Créer un rapport
- Cliquer sur **Créer un rapport**
- Ajouter la source

---

## 🎨 Dashboard recommandé

Ajoute ces composants :

- 📈 Time Series → Revenue par Date
- 📊 Bar Chart → Revenue par Product
- 🌍 Geo Map → Revenue par Country
- 🥧 Pie Chart → Sales_Channel
- 🎯 Filtres → Date / Country / Category

---

## 🌐 Intégration iframe

### Activer le partage public :
- Cliquer sur **Partager**
- Mettre : *Accessible à tous*

---

### Exemple iframe :

```html
<iframe 
  width="800" 
  height="600" 
  src="https://lookerstudio.google.com/embed/reporting/XXXX/page/XXXX" 
  frameborder="0" 
  style="border:0" 
  allowfullscreen>
</iframe>
