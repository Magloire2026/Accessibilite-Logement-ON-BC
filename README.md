# Accessibilité au logement — Ontario vs Colombie-Britannique (2021)

## Contexte
L’accessibilité au logement est un enjeu majeur des politiques publiques au Canada.  
Un indicateur clé est le **ratio logement / revenu**, qui mesure la part du revenu consacrée aux dépenses de logement. Selon la SCHL, un logement est considéré comme abordable lorsque ce ratio est inférieur à 30 %.

Ce projet propose une **analyse comparative** entre l’Ontario et la Colombie-Britannique, deux provinces où le coût du logement est particulièrement élevé.

## Problématique
Quels types de ménages consacrent la plus grande part de leur revenu au logement en Ontario et en Colombie-Britannique en 2021 ?

## Objectifs
- Analyser les déterminants du ratio logement / revenu  
- Évaluer l’impact du type de ménage et du revenu  
- Comparer l’accessibilité entre l’Ontario et la Colombie-Britannique  

## Données
- **Source** : Fichier de microdonnées à grande diffusion (FMGD), Recensement 2021 — Statistique Canada  
- **Échantillon** : plus de 500 000 ménages  
- **Variables principales** :
  - Ratio logement / revenu
  - Revenu médian du ménage
  - Type de ménage
  - Nombre de chambres
  - Province (Ontario / Colombie-Britannique)

## Hypothèses
- Les ménages unipersonnels présentent une charge logement plus élevée  
- Les ménages avec plus de chambres ont un ratio plus faible  
- La Colombie-Britannique est moins abordable que l’Ontario  

## Méthodologie
1. Nettoyage et validation des données  
2. Analyse exploratoire (statistiques descriptives et visualisations)  
3. Transformation logarithmique de la variable dépendante pour limiter l’influence des valeurs extrêmes  
4. Régression linéaire multiple (OLS)  
5. Interprétation des coefficients et validation des hypothèses  

## Résultats clés
- **73,8 %** des ménages consacrent moins de 30 % de leur revenu au logement  
- Les **ménages unipersonnels** sont les plus touchés par une charge élevée  
- Le **revenu plus élevé** est associé à une charge logement proportionnellement plus faible  
- À caractéristiques équivalentes, **l’Ontario est légèrement plus abordable que la Colombie-Britannique**  

## Impact et interprétation
Cette analyse met en évidence des **groupes de ménages plus vulnérables**, notamment les personnes vivant seules.  
Les résultats peuvent aider les décideurs publics à cibler plus efficacement les politiques d’aide au logement.

## Limites
- Analyse transversale (pas de causalité)
- Absence de variables liées aux marchés locaux (prix, taux de vacance)
- Modèle linéaire simplifiant des relations complexes

## Recommandations
- Cibler prioritairement les ménages unipersonnels dans les politiques d’aide  
- Adapter les stratégies selon les réalités provinciales  
- Compléter l’analyse avec des données locales et longitudinales  

## Auteur
Magloire Dakeyo  
Étudiant en sciences des données appliquées  
Portfolio : https://magloire2026.github.io/
