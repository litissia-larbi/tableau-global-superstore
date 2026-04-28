# 📊 Global Superstore : Entre croissance des ventes et érosion des profits

Projet de visualisation de données massives réalisé avec **Tableau Public** dans le cadre du M1 IBD à l'Université Paris 8 — 2025/2026.

---

## 🔗 Dashboard interactif

👉 **[Accéder au dashboard Tableau Public](https://public.tableau.com/shared/Z27WSXFS4)**

---

## 📁 Dataset

| Propriété      |  Détail                                                               |
|----------------|-----------------------------------------------------------------------|
| Source         | Global Superstore Dataset                                             |
| Période        | 2011 — 2014                                                           |
| Lignes         | 51 290 commandes                                                      |
| Couverture     | 147 pays, 13 régions mondiales                                        |
| Variables clés | Sales, Profit, Region, Segment, Category, Sub-Category, Discount      |

---

## ❓ Problématique

> *"Comment les différences régionales, les segments clients et les politiques de remise influencent-elles la rentabilité du Global Superstore ?"*

Malgré une croissance des ventes de **+90% entre 2011 et 2014**, le taux de marge global ne dépasse pas **11,6%**. Ce décalage entre volume et rentabilité structure l'ensemble de l'analyse.

---

## → Dashboards Disponibles

<table>
  <tr>
    <td align="center" width="50%">
      <b>📈 Page 1 — Vue d'ensemble</b><br>
      <i>Une croissance du chiffre d'affaires sous pression sur la rentabilité</i><br><br>
      <img src="screenshots/Screenshot 1.png" width="100%"/>
      <br><br>
      • 4 KPI Cards (CA : 12,6M$, Résultat net, Marge 11,6%, 25 035 commandes)<br>
      • Courbe Sales vs Profit 2011–2014<br>
      • Top 5 sous-catégories par ventes (Phones, Copiers, Chairs...)
    </td>
    <td align="center" width="50%">
      <b>🗺️ Page 2 — Analyse géographique</b><br>
      <i>Fortes disparités de rentabilité à l'échelle mondiale</i><br><br>
      <img src="screenshots/Screenshot 2.png" width="100%"/>
      <br><br>
      • Carte choroplèthe profit par pays<br>
      • Classement des 13 régions par profit<br>
      • Écart de 1 à 18 : Central (311K$) vs Canada (17K$)
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <b>👥 Page 3 — Segments & Catégories</b><br>
      <i>Performance des segments clients — contribution au profit</i><br><br>
      <img src="screenshots/Screenshot 3.png" width="100%"/>
      <br><br>
      • Consumer domine : 749 240$ de profit<br>
      • Tables : seule sous-catégorie déficitaire à -64 083$<br>
      • Copiers : meilleure sous-catégorie à 258 568$
    </td>
    <td align="center" width="50%">
      <b>💹 Page 4 — Analyse de la rentabilité</b><br>
      <i>Furniture, le frein à la croissance — marges sous pression</i><br><br>
      <img src="screenshots/Screenshot 4.png" width="100%"/>
      <br><br>
      • Furniture : 6,9% vs Technology : 14,0%<br>
      • Tables : taux de marge négatif à -8,5%<br>
      • Paper : meilleure marge à 24,2%
    </td>
  </tr>
</table>

---

## 📈 Résultats clés

- 💰 **Taux de marge global : 11,6%** — seulement 11,6 centimes conservés par dollar vendu
- 📦 **Tables : sous-catégorie la plus déficitaire** — perte nette de 64 083$ malgré 1,4M$ de CA
- 👥 **Consumer : segment le plus rentable** — 749 240$ soit 2,7x plus que Home Office
- 🪑 **Furniture : catégorie la moins rentable** — 6,9% de marge vs 14% pour Technology
- 🌍 **Central : région la plus rentable** — 311 404$ de profit

---

## ⚠️ Limites identifiées

- **Données de remise inexploitables** : anomalie d'encodage dans Tableau (valeurs décimales affichées à 0)
- **Absence de détail des coûts** : impossible de déterminer pourquoi Tables perd de l'argent
- **Période limitée** : données couvrant uniquement 2011–2014
- **Granularité géographique** : la carte identifie les pays déficitaires mais n'explique pas les causes

---

## 💡 Recommandations

1. **Revoir la stratégie de prix sur Tables** — augmenter les prix, réduire les coûts ou arrêter les modèles déficitaires
2. **Concentrer les efforts sur le segment Consumer** — 2,7x plus rentable que Home Office
3. **Renforcer les régions performantes** — Central et North représentent ensemble +500 000$ de profit

---

## 🛠️ Technologie

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)

---

## 👩‍💻 Auteure

**Litissia LARBI** — M1 IBD, Visualisation de données massives, Université Paris 8 — 2025/2026
