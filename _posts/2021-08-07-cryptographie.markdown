---
layout: post
title: "Cryptographie"
img: cryptography-1091256_1920.jpg
date: 2021-08-07
description: Fermat-Euler, Lagrange, RSA, Diffie-Hellman... 
tag: [rsa, el-gamal, dsa, crt, lagrange, fermat, euler, pki, tls]
---
Le cours de cryptographie suivi à l'HEIG portait sur le contenu suivant :

## Notion mathématique 

- Théorie des nombres 
- Groupes finis 
- Anneaux et corps finis 
- Théorèmes de Fermat-Euler, Lagrange et des restes chinois(CRT)
- Crible d'Eratosthène, l'algorithme d'Euclide pour calculer un PGCD ainsi que
  l'algorithme d'Euclide étendu pour calculer l'identité de Bézout;
- Courbes elliptiques 
  - [Le Logarithme Discret sur courbe elliptique avec SageMath](https://rya-sge.github.io/access-denied/2021/07/30/logarithme-discret-courbe-elliptique/)

## Cryptographie 

- Introduction et histoire de la cryptographie 
- Terminologie et types d'adversaires 
- Algorithmes de chiffrement symétriques 
- Authentification symétrique
- Chiffrement à clef publique  (RSA, Diffie-Hellman, El Gamal)
  - Diffie-Hellman : [Diffie-Hellman expliqué en python](https://rya-sge.github.io/access-denied/2021/10/28/diffie-hellman-python/)
  - RSA: [Chiffrement RSA avec SageMath](https://rya-sge.github.io/access-denied/2021/07/27/chiffrement-rsa-sagemath/)
- Signatures digitales  (signature RSA, DSA)
- Cryptographie pratique 
- Infrastructure à clefs publiques (PKI)
- Aperçu du protocole SSL/TLS, de son utilisation ainsi que de son fonctionnement interne;

Les laboratoires étaient réalisés en python3 avec parfois l'utilisation de la librairie mathématique SageMath.

- Laboratoire 1 : Cryptanalyse du Chiffre de César et de Vigenère

- Laboratoire 2 : CBC-MAC & Algorithme de chiffrement par blocs

- laboratoire 3 : El Gamal, CRT et mauvaise implémentation de RSA

- Laboratoire 4 : Implémenter une PKI et de l’utiliser pour signer des emails ainsi que
  pour configurer une connexion HTTPS.



Source de l'image en couverture  :

Image par <a href="https://pixabay.com/fr/users/tumbledore-1767790/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1091256">tumbledore</a> de <a href="https://pixabay.com/fr/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1091256">Pixabay</a>