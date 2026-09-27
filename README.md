  requirements.txt sonar-project.properties
# AbAssurance & AssurePlus — Databricks Data Lakehouse

Ce projet implémente une architecture Lakehouse Medallion (Bronze, Silver, Gold) sur Databricks pour l'ingestion, le nettoyage, le rapprochement (matching) et la qualité des données d'assurance issues de deux sources : **ABAssurance** et **AssurePlus**.

---

## 🏗️ Architecture du Projet

Le projet suit la structure standardisée suivante :

```text
abassurance-databricks/
├── data/sample/          # Jeux de données d'exemple (ABAssurance & AssurePlus)
├── src/                  # Modules Python réutilisables (clean, match, quality)
├── notebooks/            # Pipelines d'exécution Databricks (01 à 08)
├── tests/                # Tests unitaires des modules src/
└── docs/                 # Documentation fonctionnelle et technique