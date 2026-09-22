# Accès à l’eau potable

## Contexte

Ce projet analyse l’accès à l’eau potable dans le monde à partir de données couvrant plusieurs années.

L’objectif est de proposer un tableau de bord Power BI permettant de suivre les évolutions, de comparer les pays et les régions, afin de trouver où concentrer les efforts.

## Données

Les données ont été collectées par un Data Engineer à partir de sources publiées par :

- l’Organisation mondiale de la Santé (**OMS**) ;
- l’Organisation des Nations unies pour l’alimentation et l’agriculture (**FAO**).

Elles comprennent notamment des informations sur les populations concernées, les pays, les régions, les périodes étudiées et le type de zone : urbaine ou rurale.

Les données ont été préparées avant intégration dans Power BI : vérification des formats, harmonisation des libellés géographiques et traitement des valeurs manquantes.

## Démarche

Le projet a été réalisé avec **Power BI** :

- préparation et transformation des données avec **Power Query** ;
- création des indicateurs et calculs avec **DAX** ;
- conception d’un tableau de bord interactif.

Le tableau de bord comprend :

- des indicateurs clés ;
- une carte mondiale ;
- une analyse de l’évolution dans le temps ;
- une comparaison entre zones urbaines et rurales ;
- des filtres par période, pays et région.

## Résultats

L’analyse fait ressortir deux constats principaux :

- l’accès à l’eau potable progresse globalement sur la période étudiée ;
- la situation reste très différente selon les pays et les régions.

La visualisation par zone urbaine et rurale permet également de mieux comprendre les disparités territoriales et d’identifier les zones où la population concernée reste importante.

## Limites et pistes d’amélioration

Les données peuvent varier selon les méthodes de collecte, la couverture géographique et les dates de mise à jour des sources.

Pour aller plus loin, le tableau de bord pourrait être enrichi avec :

- des données plus récentes ;
- des indicateurs sur l’assainissement ou la qualité de l’eau ;
- des données démographiques et socio-économiques ;
- une analyse plus détaillée de l’évolution par pays.

## Outils utilisés

- Power BI
- Power Query
- DAX
