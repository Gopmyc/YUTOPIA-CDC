# **Natures de Chakra - [X]**  

## **Sommaire**
1.  

---

## Informations Générales sur les Sweps

- **Utilisation des sweps :**  
  Tous les sweps décrits dans ce document se contrôlent principalement via un **clic gauche** (sauf mention contraire). Chaque action peut correspondre à un effet immédiat ou à une durée d'action en fonction de la nature de la technique.
  Certaines techniques peuvent nécessiter un maintien du clic pour charger une attaque.
  La portée et l'effet varient en fonction du rang de la technique.

- **Temps d'affichage des éléments visuels :**  
  Tous les effets visuels créés lors de l'utilisation des sweps doivent impérativement être contrôlés et **supprimés après un certain temps** afin de maintenir une expérience de jeu fluide.  
  La durée d'affichage et de vie de chaque élément visuel est à définir, mais elle ne doit pas excéder **10 secondes** pour éviter l'encombrement de la scène et l'impact sur la performance du serveur.

- **Consommation de chakra :**  
  Chaque technique consomme du **chakra** lors de son activation. La quantité de chakra utilisée dépend de la puissance et de la complexité de la technique.
  Si le joueur n’a plus assez de chakra, la technique ne peut pas être exécutée.
  Possibilité de régénération lente du chakra hors combat.

- **Cooldown des techniques :**  
  Un **cooldown** est appliqué après l'utilisation de chaque technique. Cela permet de réguler l'utilisation abusive des techniques puissantes et d'encourager une stratégie réfléchie.
  Les techniques de rangs élevés ont un cooldown plus long.

- **Catégorisation des Techniques :**
  **RANG C** → Techniques de base, faible consommation de chakra.
  **RANG B** → Techniques intermédiaires, coût modéré en chakra.
  **RANG A** → Techniques avancées, nécessitent plus de chakra et de temps d’incantation.
  **RANG S** → Techniques ultimes, très coûteuses mais extrêmement puissantes.

## Scripted Weapons (SWEPs) :

---
### SWEPS [NAME] :
  #### **Description :**

  #### **Informations Générales :**
  | **Champ**                  | **Détail**                                  |
  |----------------------------|---------------------------------------------|
  | **Nom du SWEP**             | `NAME` |
  | **Nature du Chakra**        | `Suiton, Katon, etc.` |
  | **Type de SWEP**            | `Offensif / Défensif / Utilitaire / Support` |
  | **Portée**                  | `VALUE [UNIT]` |
  | **Consommation de Chakra**  | `VALUE [UNIT]` |
  | **Cooldown**                | `VALUE [UNIT]` |
  | **Durée de l'effet**        | `VALUE [UNIT]` (si applicable) |

---

  #### **Animation et Effets Visuels :**
  | **Champ**                      | **Détail**                                         |
  |---------------------------------|----------------------------------------------------|
  | **Animation à jouer**           | `VALUE` |
  | **Durée de l'animation**        | `VALUE [UNIT]` |
  | **Particules**                  | `VALUE` |
  | **Effet sonore**                | `VALUE` |
  | **Effet visuel supplémentaire** | `VALUE` |
  | **Apparence de l'effet**        | `Couleur, taille, intensité, etc.` |

---

  #### **Effets et Interactions avec les Ennemis :**
  | **Champ**                       | **Détail**                                                  |
  |----------------------------------|-------------------------------------------------------------|
  | **Type d'effet physique**       | `Ex: Repousse, attirance, explosion, etc.` |
  | **Force appliquée**             | `VALUE [UNIT]` |
  | **Zone d'effet**                | `VALUE [UNIT]` |
  | **Dégâts**                       | `VALUE` |
  | **Effet sur les ennemis**       | `Ralentissement, stun, dégâts sur temps, etc.` |
  | **Modification de mouvement**   | `Réduction de vitesse, immobilisation, etc.` |

---

  #### **Gestion de Chakra et Temps de Recharge :**
  | **Champ**                       | **Détail**                                                   |
  |----------------------------------|--------------------------------------------------------------|
  | **Consommation de chakra**      | `VALUE` |
  | **Cooldown**                    | `VALUE [UNIT]` |
  | **Condition spéciale**          | `Ex: Nécessite d'être immobile, ou autre condition` |

---


## 3. Livrables attendus  
Le prestataire devra livrer :  
- **Le menu intégré au module existant** : Le code sera directement ajouté au projet source via l'accès fourni.  
- **Respect des conventions** : Le code doit respecter la structure et les normes du projet pour faciliter la maintenance.  

---

## 4. Délais de réalisation  
**Date limite de livraison** : [À définir avec le prestataire]  

---

## 5. Budget et Conditions  
**Modalités de paiement** : Paiement après validation finale par l'équipe technique de Yutopia.  

---

## 6. Critères de Validation  
Le menu sera validé en fonction des critères suivants :  
- Fonctionnalités entièrement opérationnelles (drag-and-drop, menu contextuel, boutons interactifs).  
- Respect des normes d'intégration dans le projet.  
- Effets visuels et animations conformes aux spécifications.  

---

## 7. Confidentialité  
Le prestataire s'engage à respecter la confidentialité totale concernant le projet, incluant :  
- Ne divulguer aucune information relative au projet.  
- Ne pas utiliser les travaux réalisés dans son portfolio ou ailleurs sans autorisation écrite.  

---

## 8. Propriété Intellectuelle  
Le prestataire cède tous les droits d'exploitation des créations réalisées au commanditaire. Ces droits incluent l'utilisation, la reproduction, la modification et la distribution des créations.  

---

## 9. Non-concurrence  
Cette clause n'est pas applicable à cette prestation.  

---

## 1à. Modifications post-livraison  
- **Incluses** : Une série de corrections mineures si nécessaire.  
- **Supplémentaires** : Toute modification majeure sera facturée séparément après accord.  

---

## 11. Applicabilité des Clauses  
| Clause                        | Applicable (Oui/Non)  | Commentaire           |  
|-------------------------------|-----------------------|-----------------------|  
| Confidentialité               | Oui                   | Le prestataire doit garantir la non-divulgation. |  
| Propriété Intellectuelle      | Oui                   | Droits cédés au commanditaire. |  
| Non-concurrence               | Non                   | Non applicable à cette prestation. |  
| Modifications post-livraison  | Oui                   | Modifications mineures incluses. |  

---

## 12. Contact  
Pour toute question, contactez l'équipe Yutopia via Discord.