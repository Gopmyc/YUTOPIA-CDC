# **Natures de Chakra - [INTON]**  

## **Sommaire**
1. [Informations Générales sur les Sweps](#informations-générales-sur-les-sweps)
2. [SWEPS - Immobilisation des ombres](#sweps-immobilisation-des-ombres)
3. [SWEPS - Shuriken d’ombres](#sweps-shuriken-dombres)
4. [SWEPS - Stalagmite d’ombres](#sweps-stalagmite-dombres)
5. [SWEPS - Bouclier d’ombres](#sweps-bouclier-dombres)
6. [SWEPS - Sphère d’ombres](#sweps-sphère-dombres)
7. [SWEPS - Immobilisation de masse](#sweps-immobilisation-de-masse)
8. [Livrables attendus](#6-livrables-attendus)  
9. [Délais de réalisation](#7-délais-de-réalisation)  
10. [Budget et Conditions](#8-budget-et-conditions)  
11. [Critères de Validation](#9-critères-de-validation)  
12. [Confidentialité](#10-confidentialité)  
13. [Propriété Intellectuelle](#11-propriété-intellectuelle)  
14. [Non-concurrence](#12-non-concurrence)  
15. [Modifications post-livraison](#13-modifications-post-livraison)  
16. [Applicabilité des Clauses](#14-applicabilité-des-clauses)  
17. [Contact](#15-contact) 

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

### SWEPS [Immobilisation des ombres] :
  #### **Description :**
	  L’utilisateur forme un disque au sol en étant à son centre. 
	  La zone stun toute personnes entrant dans son périmètre, le lanceur doit, lui, rester immobile pour   maintenant sa cible.

  #### **Informations Générales :**
  | **Champ**                  | **Détail**                                  |
  |----------------------------|---------------------------------------------|
  | **Nom du SWEP**             | `RANG-C [1]` |
  | **Nature du Chakra**        | `Inton` |
  | **Type de SWEP**            | `Défensif` |
  | **Portée**                  | `100` |
  | **Consommation de Chakra**  | `0` |
  | **Cooldown**                | `0` |
  | **Durée de l'effet**        | `0 [secondes]` |

---

  #### **Animation et Effets Visuels :**
  | **Champ**                      | **Détail**                                         |
  |---------------------------------|----------------------------------------------------|
  | **Animation à jouer**           | `sda_nara_jutsu2` |
  | **Durée de l'animation**        | `1 [secondes]` |
  | **Particules**                  | `[9]_magnetic_convergence_add` |
  | **Effet sonore**                | `VALUE` |
  | **Effet visuel supplémentaire** | `N/A` |
  | **Apparence de l'effet**        | `N/A` |

---

  #### **Effets et Interactions avec les Ennemis :**
  | **Champ**                       | **Détail**                                                  |
  |----------------------------------|-------------------------------------------------------------|
  | **Type d'effet physique**       | `STUN` |
  | **Force appliquée**             | `N/A` |
  | **Zone d'effet**                | `100` |
  | **Dégâts**                       | `0` |
  | **Effet sur les ennemis**       | `stun` |
  | **Modification de mouvement**   | `immobilisation` |

---

  #### **Gestion de Chakra et Temps de Recharge :**
  | **Champ**                       | **Détail**                                                   |
  |----------------------------------|--------------------------------------------------------------|
  | **Consommation de chakra**      | `0` |
  | **Cooldown**                    | `0` |
  | **Condition spéciale**          | `être immobile` |

---

### SWEPS [Shuriken d’ombres] :
  #### **Description :**
	  L’utilisateur projette de maniere simultané entre 2 et 4 projectiles devant lui.

  #### **Informations Générales :**
  | **Champ**                  | **Détail**                                  |
  |----------------------------|---------------------------------------------|
  | **Nom du SWEP**             | `RANG-C [2]` |
  | **Nature du Chakra**        | `Inton` |
  | **Type de SWEP**            | `Offensif` |
  | **Portée**                  | `200` |
  | **Consommation de Chakra**  | `0` |
  | **Cooldown**                | `0` |
  | **Durée de l'effet**        | `3 [secondes]` |

---

  #### **Animation et Effets Visuels :**
  | **Champ**                      | **Détail**                                         |
  |---------------------------------|----------------------------------------------------|
  | **Animation à jouer**           | `sda_atk12_kunai` |
  | **Durée de l'animation**        | `1.5 [secondes]` |
  | **Particules**                  | `[3]_wind_prison_add_2` |
  | **Effet sonore**                | `VALUE` |
  | **Effet visuel supplémentaire** | `N/A` |
  | **Apparence de l'effet**        | `Color [0, 0, 255, 255]` |

---

  #### **Effets et Interactions avec les Ennemis :**
  | **Champ**                       | **Détail**                                                  |
  |----------------------------------|-------------------------------------------------------------|
  | **Type d'effet physique**       | `N/A` |
  | **Force appliquée**             | `N/A` |
  | **Zone d'effet**                | `75` |
  | **Dégâts**                       | `` |
  | **Effet sur les ennemis**       | `Degats` |
  | **Modification de mouvement**   | `N/A` |

---

  #### **Gestion de Chakra et Temps de Recharge :**
  | **Champ**                       | **Détail**                                                   |
  |----------------------------------|--------------------------------------------------------------|
  | **Consommation de chakra**      | `300` |
  | **Cooldown**                    | `` |
  | **Condition spéciale**          | `être immobile` |

---

### SWEPS [Stalagmite d’ombres] :
  #### **Description :**
    L'utilisateur forme un stalagmite d’ombre sortant du sol, projetant les adversaires et les blessant. 

  #### **Informations Générales :**
  | **Champ**                  | **Détail**                                  |
  |----------------------------|---------------------------------------------|
  | **Nom du SWEP**             | `RANG-B [1]` |
  | **Nature du Chakra**        | `Inton` |
  | **Type de SWEP**            | `Offensif` |
  | **Portée**                  | `600` |
  | **Consommation de Chakra**  | `0` |
  | **Cooldown**                | `0` |
  | **Durée de l'effet**        | `3 [secondes]` |

---

  #### **Animation et Effets Visuels :**
  | **Champ**                      | **Détail**                                         |
  |---------------------------------|----------------------------------------------------|
  | **Animation à jouer**           | `sda_jutsu2_doton` |
  | **Durée de l'animation**        | `1.5 [secondes]` |
  | **Particules**                  | `[3]_wind_futon_add_2` |
  | **Effet sonore**                | `VALUE` |
  | **Effet visuel supplémentaire** | `N/A` |
  | **Apparence de l'effet**        | `N/A` |

---

  #### **Effets et Interactions avec les Ennemis :**
  | **Champ**                       | **Détail**                                                  |
  |----------------------------------|-------------------------------------------------------------|
  | **Type d'effet physique**       | `N/A` |
  | **Force appliquée**             | `N/A` |
  | **Zone d'effet**                | `120` |
  | **Dégâts**                       | `0` |
  | **Effet sur les ennemis**       | `Degats + projection` |
  | **Modification de mouvement**   | `N/A` |

---

  #### **Gestion de Chakra et Temps de Recharge :**
  | **Champ**                       | **Détail**                                                   |
  |----------------------------------|--------------------------------------------------------------|
  | **Consommation de chakra**      | `0` |
  | **Cooldown**                    | `0` |
  | **Condition spéciale**          | `être immobile` |

---

### SWEPS [Bouclier d’ombres] :
  #### **Description :**
    L’utilisateur forme un bouclier d’ombres devant lui. 
    Le bouclier bloque tous les impacts inférieurs à `x` dommage. 
    Le bouclier dispawn au bout de `x` temps.  

  #### **Informations Générales :**
  | **Champ**                  | **Détail**                                  |
  |----------------------------|---------------------------------------------|
  | **Nom du SWEP**             | `RANG-A [1]` |
  | **Nature du Chakra**        | `Inton` |
  | **Type de SWEP**            | `Deffensif` |
  | **Portée**                  | `200` |
  | **Consommation de Chakra**  | `0` |
  | **Cooldown**                | `0` |
  | **Durée de l'effet**        | `10 [secondes]` |

---

  #### **Animation et Effets Visuels :**
  | **Champ**                      | **Détail**                                         |
  |---------------------------------|----------------------------------------------------|
  | **Animation à jouer**           | `sda_nara_jutsu2` |
  | **Durée de l'animation**        | `1.5 [secondes]` |
  | **Particules**                  | `` |
  | **Effet sonore**                | `VALUE` |
  | **Effet visuel supplémentaire** | `N/A` |
  | **Apparence de l'effet**        | `MODELS : [models/shikigamidanceshield_big.mdl]` |

---

  #### **Effets et Interactions avec les Ennemis :**
  | **Champ**                       | **Détail**                                                  |
  |----------------------------------|-------------------------------------------------------------|
  | **Type d'effet physique**       | `N/A` |
  | **Force appliquée**             | `N/A` |
  | **Zone d'effet**                | `N/A` |
  | **Dégâts**                      | `N/A` |
  | **Effet sur les ennemis**       | `N/A` |
  | **Modification de mouvement**   | `N/A` |

---

  #### **Gestion de Chakra et Temps de Recharge :**
  | **Champ**                       | **Détail**                                                   |
  |----------------------------------|--------------------------------------------------------------|
  | **Consommation de chakra**      | `0` |
  | **Cooldown**                    | `0` |
  | **Condition spéciale**          | `être immobile` |

---

### SWEPS [Sphère D’ombres] :
  #### **Description :**
    L'utilisateur projette entre 2 et 4 sphères horizontalement. 
    L’impact provoque un stun.  

  #### **Informations Générales :**
  | **Champ**                  | **Détail**                                  |
  |----------------------------|---------------------------------------------|
  | **Nom du SWEP**             | `RANG-A [2]` |
  | **Nature du Chakra**        | `Inton` |
  | **Type de SWEP**            | `Offenssif` |
  | **Portée**                  | `600` |
  | **Consommation de Chakra**  | `0` |
  | **Cooldown**                | `0` |
  | **Durée de l'effet**        | `10 [secondes]` |

---

  #### **Animation et Effets Visuels :**
  | **Champ**                      | **Détail**                                         |
  |---------------------------------|----------------------------------------------------|
  | **Animation à jouer**           | `sda_nara_jutsu2` |
  | **Durée de l'animation**        | `1.5 [secondes]` |
  | **Particules**                  | `` |
  | **Effet sonore**                | `VALUE` |
  | **Effet visuel supplémentaire** | `N/A` |
  | **Apparence de l'effet**        | `MODELS : [models/hunter/misc/sphere075x075.mdl], COLOR : [0, 0, 0, 255]` |

---

  #### **Effets et Interactions avec les Ennemis :**
  | **Champ**                       | **Détail**                                                  |
  |----------------------------------|-------------------------------------------------------------|
  | **Type d'effet physique**       | `N/A` |
  | **Force appliquée**             | `N/A` |
  | **Zone d'effet**                | `N/A` |
  | **Dégâts**                      | `0` |
  | **Effet sur les ennemis**       | `degats` |
  | **Modification de mouvement**   | `STUN` |
  | **Effet impact**                | `Crée des entitées (MODELS : [models/mm_entrave/mm_entrave.mdl], COLOR : [0, 0, 0, 255]) sur les cibles touchées puis une fois l'animation joué les entitées sont remplacé par les entitées (MODELS : [models/mm_entravestatic/mm_entravestatic.mdl], COLOR : [0, 0, 0, 255]), les entitées dispawn au bout de 5 secondes)` |

---

  #### **Gestion de Chakra et Temps de Recharge :**
  | **Champ**                       | **Détail**                                                   |
  |----------------------------------|--------------------------------------------------------------|
  | **Consommation de chakra**      | `0` |
  | **Cooldown**                    | `0` |
  | **Condition spéciale**          | `être immobile` |

---

### SWEPS [Immobilisation de masse] :
  #### **Description :**
    L’utilisateur forme un disque au sol en étant à son centre. 
    La zone stun toute personnes entrant dans son périmètre, le lanceur doit, lui, rester immobile. 
    Les cibles entrant dans le cercle sont stun. 
 

  #### **Informations Générales :**
  | **Champ**                  | **Détail**                                  |
  |----------------------------|---------------------------------------------|
  | **Nom du SWEP**             | `RANG-S [1]` |
  | **Nature du Chakra**        | `Inton` |
  | **Type de SWEP**            | `Deffenssif` |
  | **Portée**                  | `1000` |
  | **Consommation de Chakra**  | `0` |
  | **Cooldown**                | `0` |
  | **Durée de l'effet**        | `10 [secondes]` |

---

  #### **Animation et Effets Visuels :**
  | **Champ**                      | **Détail**                                         |
  |---------------------------------|----------------------------------------------------|
  | **Animation à jouer**           | `sda_nara_jutsu2 + sda_emote32` |
  | **Durée de l'animation**        | `sda_nara_jutsu2 : 1.5 [secondes], sda_emote32 : 8.5 [secondes]` |
  | **Particules**                  | `[5]_earthquake_add` |
  | **Effet sonore**                | `VALUE` |
  | **Effet visuel supplémentaire** | `N/A` |
  | **Apparence de l'effet**        | `MODELS : [models/hunter/tubes/circle2x2.mdl], COLOR : [0, 0, 0, 255], SCALE : [VALUE : [1 > 20], DELTA_TIME : 3]` |

---

  #### **Effets et Interactions avec les Ennemis :**
  | **Champ**                       | **Détail**                                                  |
  |----------------------------------|-------------------------------------------------------------|
  | **Type d'effet physique**       | `N/A` |
  | **Force appliquée**             | `N/A` |
  | **Zone d'effet**                | `1000` |
  | **Dégâts**                      | `0` |
  | **Effet sur les ennemis**       | `degat` |
  | **Modification de mouvement**   | `STUN` |
  | **Effet impact**                | `Crée des entitées (MODELS : [models/mm_entrave/mm_entrave.mdl], COLOR : [0, 0, 0, 255]) sur les cibles touchées puis une fois l'animation joué les entitées sont remplacé par les entitées (MODELS : [models/mm_entravestatic/mm_entravestatic.mdl], COLOR : [0, 0, 0, 255]), les entitées dispawn au bout de 5 secondes)` |

---

  #### **Gestion de Chakra et Temps de Recharge :**
  | **Champ**                       | **Détail**                                                   |
  |----------------------------------|--------------------------------------------------------------|
  | **Consommation de chakra**      | `0` |
  | **Cooldown**                    | `0` |
  | **Condition spéciale**          | `être immobile` |

---

## 8. Livrables attendus  
Le prestataire devra livrer :
- **Les scripts et entitées intégré au projet** : Le code sera directement ajouté au projet source via l'accès fourni.  
- **Respect des conventions** : Le code doit respecter la structure et les normes du projet pour faciliter la maintenance.  

---

## 9. Délais de réalisation  
**Date limite de livraison** : [N/A] 

---

## 10. Budget et Conditions  
**Modalités de paiement** : Paiement après validation finale par l'équipe technique de Yutopia.  

---

## 11. Critères de Validation  
La demande sera validé en fonction des critères suivants :  
- Fonctionnalités entièrement opérationnelles.  
- Respect des normes d'intégration dans le projet.  
- Effets visuels et animations conformes aux spécifications.  

---

## 12. Confidentialité  
Le prestataire s'engage à respecter la confidentialité totale concernant le projet, incluant :  
- Ne divulguer aucune information relative au projet.  
- Ne pas utiliser les travaux réalisés dans son portfolio ou ailleurs sans autorisation écrite.  

---

## 13. Propriété Intellectuelle  
Le prestataire cède tous les droits d'exploitation des créations réalisées au commanditaire. Ces droits incluent l'utilisation, la reproduction, la modification et la distribution des créations.  

---

## 14. Non-concurrence  
Cette clause n'est pas applicable à cette prestation.  

---

## 15. Modifications post-livraison  
- **Incluses** : Une série de corrections mineures si nécessaire.  
- **Supplémentaires** : Toute modification majeure sera facturée séparément après accord.  

---

## 16. Applicabilité des Clauses  
| Clause                        | Applicable (Oui/Non)  | Commentaire           |  
|-------------------------------|-----------------------|-----------------------|  
| Confidentialité               | Oui                   | Le prestataire doit garantir la non-divulgation. |  
| Propriété Intellectuelle      | Oui                   | Droits cédés au commanditaire. |  
| Non-concurrence               | Non                   | Non applicable à cette prestation. |  
| Modifications post-livraison  | Oui                   | Modifications mineures incluses. |  

---

## 17. Contact  
Pour toute question, contactez l'équipe Yutopia via Discord.