# AT&T Spam Detector 🕵️‍♀️ — Deep Learning Project

Ce projet a été réalisé dans le cadre d'un cursus de formation en Data Science. Il s'appuie sur une étude de cas inspirée par AT&T Inc. pour automatiser la détection de messages SMS indésirables (SPAM) afin de protéger les utilisateurs contre les fraudes et les nuisances numériques.

## 📋 Présentation du Projet

AT&T, l'un des plus grands fournisseurs de services mobiles au monde, fait face à une augmentation constante des spams SMS. Auparavant géré manuellement, ce flux nécessite aujourd'hui une solution intelligente capable de classifier les messages en temps réel.

Objectif : Développer un modèle de Deep Learning capable de prédire si un SMS est un "Ham" (message légitime) ou un "Spam" en se basant uniquement sur son contenu textuel.

## 🛠️ Stack Technique

Langage : Python

Framework DL : PyTorch

Data Processing : Pandas, NumPy, Scikit-learn

NLP : Tokenisation via Regex, Construction de vocabulaire personnalisé

Visualisation : Matplotlib, Seaborn


## 📊 Résultats et Performances

Le modèle a été évalué sur un jeu de données de test indépendant. Voici les résultats obtenus :

Accuracy: 94.2%

Precision (Spam): 93.8%

Recall (Spam): 61.1%

F1-Score: 74.0%

Analyse de la Matrice de Confusion :

Très peu de Faux Positifs (6) : La priorité a été donnée à la non-blocage des messages importants des clients.

Bonne détection globale du spam malgré le déséquilibre du dataset.

## 📂 Structure du Repo

ATT_Spam_Detector_.ipynb : Le notebook complet avec le code, les commentaires et les analyses.


spam.csv : Dossier contenant le dataset original (SMS Spam Collection).

