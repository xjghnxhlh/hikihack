## 📚 Documentation et illustrations

Afin de compléter cette analyse de la vulnérabilité **CVE-2017-7921**, plusieurs ressources sont mises à disposition. Elles ont pour objectif d'aider à comprendre les conséquences potentielles d'un équipement vulnérable, l'importance des mises à jour de sécurité et les bonnes pratiques de sécurisation.

Toutes les démonstrations présentées dans ce dépôt ont été réalisées **dans un environnement de test autorisé**, à des fins exclusivement éducatives, de recherche et de sensibilisation à la cybersécurité. Avant leur publication, l'ensemble des informations sensibles (identifiants, mots de passe, adresses IP, numéros de série, noms d'hôtes et autres données confidentielles) a été **anonymisé ou masqué** afin de préserver la confidentialité.

---

## 📄 Rapport de prévention

Un rapport technique détaillé accompagne ce dépôt. Il présente notamment :

* une description de la vulnérabilité **CVE-2017-7921** ;
* les produits et versions concernés ;
* les risques liés à l'exposition d'un équipement vulnérable ;
* les impacts potentiels sur la confidentialité, l'intégrité et la disponibilité des systèmes ;
* les recommandations de mitigation et les bonnes pratiques permettant de réduire les risques.

Le rapport est disponible ici :

**➡️ Rapport de prévention – CVE-2017-7921**

https://github.com/xjghnxhlh/hikihack/blob/main/Rapport_Prevention_CVE-2017-7921.pdf

---

## 📷 Illustration n°1 — Exemple de récupération d'informations

La capture d'écran suivante présente un **exemple de résultat observé lors d'un audit de sécurité réalisé dans un environnement de test autorisé**. Elle illustre le type d'informations qui peuvent être exposées lorsqu'un équipement affecté par **CVE-2017-7921** n'a pas été correctement mis à jour ou sécurisé.

Les identifiants et toutes les informations permettant d'identifier un système réel ont été volontairement **floutés** avant leur publication. Cette illustration est destinée uniquement à montrer l'impact potentiel de la vulnérabilité dans un contexte pédagogique.

<p align="center">
  <img src="https://github.com/xjghnxhlh/hikihack/blob/main/credentials.png?raw=true" alt="Informations récupérées - Données anonymisées" width="900">
</p>

---

## 📷 Illustration n°2 — Interface d'administration

La capture ci-dessous montre l'interface d'administration d'un équipement **dans un environnement de démonstration autorisé**. Son objectif est d'illustrer les conséquences qu'une vulnérabilité non corrigée peut avoir lorsqu'un équipement est exposé sans les mesures de sécurité appropriées.

L'ensemble des éléments permettant d'identifier l'équipement ou son propriétaire a été anonymisé. Cette illustration ne constitue pas une démonstration d'exploitation, mais une représentation visuelle de l'impact potentiel d'une mauvaise gestion des mises à jour de sécurité et des configurations.

<p align="center">
  <img src="https://github.com/xjghnxhlh/hikihack/blob/main/Capture%20d%E2%80%99%C3%A9cran%202026-08-03%20021626.png?raw=true" alt="Interface d'administration - Environnement de test" width="900">
</p>

---

## 🎯 Objectif de ces illustrations

Ces ressources visuelles ont pour objectif de sensibiliser les administrateurs, chercheurs en sécurité et étudiants aux conséquences qu'une vulnérabilité comme **CVE-2017-7921** peut avoir lorsqu'elle n'est pas corrigée.

Elles permettent d'illustrer concrètement :

* les informations susceptibles d'être exposées sur un équipement vulnérable ;
* les conséquences potentielles d'une configuration insuffisamment sécurisée ;
* l'importance d'appliquer les correctifs de sécurité publiés par les fabricants ;
* la nécessité de maintenir les firmwares à jour et de limiter l'exposition des interfaces d'administration sur Internet ;
* l'intérêt des audits réguliers afin d'identifier les équipements vulnérables avant qu'ils ne puissent être compromis.

> **Important :** Les captures d'écran et le rapport sont fournis exclusivement dans un objectif de documentation, de recherche et de sensibilisation à la cybersécurité. Ils ne constituent ni un guide pratique d'exploitation, ni une incitation à réaliser des actions non autorisées contre des systèmes appartenant à des tiers. Toute utilisation doit s'inscrire dans un cadre légal, éthique et avec l'autorisation explicite du propriétaire des équipements concernés.
