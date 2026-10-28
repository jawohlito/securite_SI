# FAQ de Référence : Normes ISO 27000, Cybersécurité, ANSSI & NIS 2

Ce document synthétise les réponses aux questions fondamentales relatives à la famille de normes ISO/IEC 27000, aux exigences de gouvernance et de gestion des risques (GRC), ainsi qu'aux articulations avec les cadres de l'ANSSI et la directive européenne NIS 2.

---

### 1. <u>Qu'est-ce que l'ISO ?</u>

L'**ISO** (*International Organization for Standardization* / Organisation internationale de normalisation) est une organisation non gouvernementale indépendante fondée en 1947, dont le siège est situé à Genève (Suisse).

* Elle regroupe les instituts nationaux de normalisation de plus de 160 pays (ex. l'AFNOR pour la France, l'ANSI pour les États-Unis, le BSI pour le Royaume-Uni).
* Sa mission est d'élaborer et de publier des **normes internationales volontaires**, consensuelles et adaptées au marché mondial dans une multitude de domaines (qualité avec l'ISO 9001, environnement avec l'ISO 14001, technologies de l'information, etc.).
* Dans le domaine du numérique, l'ISO collabore étroitement avec l'**IEC** (*Commission Électrotechnique Internationale*) au travers du comité technique conjoint **ISO/IEC JTC 1** (*Joint Technical Committee 1*), notamment responsable de la publication de la famille des normes ISO/IEC 27000.

---

### 2. <u>De quand date l'ISO 27001 ?</u>

La toute première version de la norme **ISO/IEC 27001** a été publiée en **octobre 2005**.

* **Historique des origines** : la norme trouve sa genèse dans le standard britannique **BS 7799** (publié par le BSI dans les années 1990), dont la deuxième partie (*BS 7799-2*) a servi de socle direct pour créer la première mouture internationale ISO/IEC 27001:2005.
* **Évolution** : une refonte majeure a eu lieu en **2013** (alignement sur la structure cadre commune des normes de systèmes de management, dite *Annex SL* / *Harmonized Structure*), puis une nouvelle révision en **2022**.

---

### 3. <u>Quelle est la dernière révision de la norme ?</u>

La dernière révision majeure de la norme est **ISO/IEC 27001:2022** (publiée le 25 octobre 2022).

* Cette version a intégré un amendement officiel mineur publié en 2024 : **ISO/IEC 27001:2022/Amd 1:2024** (*Actions relatives au changement climatique*), commun à l'ensemble des normes de systèmes de management ISO.
* **Principales nouveautés de l'édition 2022** :
  * Réorganisation complète de l'Annexe A : passage de 114 contrôles répartis en 14 clauses (version 2013) à **93 contrôles regroupés en 4 thèmes** (Organisationnel, Personnel, Physique, Technologique).
  * Introduction de **11 nouveaux contrôles de sécurité** incontournables (ex. *Threat Intelligence*, sécurité du Cloud, préparation à la continuité des TIC, gestion de la configuration, masquage des données, prévention des fuites de données, filtrage web, codage sécurisé).

---

### 4. <u>Où trouver les documents de la norme ISO 27001 ?</u>

Les normes de la famille ISO/IEC sont des documents protégés par le droit d'auteur commercial et ne sont pas distribuées gratuitement. On peut se les procurer légalement auprès des boutiques officielles de normalisation :

1. **Boutique officielle de l'ISO** :
   * [Page officielle ISO/IEC 27001:2022 (ISO.org)](https://www.iso.org/standard/27001)
2. **Boutique officielle de l'AFNOR** (organisme français de normalisation, version bilingue ou traduite en français) :
   * [Boutique AFNOR Éditions - Norme NF EN ISO/IEC 27001](https://boutique.afnor.org/)
3. **Plateforme de consultation en ligne ISO (OBP - *Online Browsing Platform*)** :
   * [ISO Online Browsing Platform](https://www.iso.org/obp/ui/) (permet de visualiser gratuitement la table des matières, l'avant-propos, le domaine d'application et les termes/définitions).

---

### 5. <u>Combien ça coûte d'être certifié ISO 27001 ?</u>

Le budget global d'un projet de certification ISO 27001 se décompose en deux grands volets :

#### A. Le coût de l'audit de certification officiel
Facturé par un organisme certificateur accrédité (ex. AFNOR Certification, BSI, Bureau Veritas, SGS, DNV). Il dépend du nombre de jours d'audit imposés par les règles internationales (norme ISO/IEC 27006), calculés selon l'effectif, la criticité, la complexité technique et le nombre de sites :
* **Petite entreprise / PME (10 à 50 collaborateurs, mono-site)** : environ **8 000 € à 15 000 €** pour le cycle initial de 3 ans (audit initial Étape 1 + Étape 2, suivi des deux audits annuels de surveillance).
* **Entreprise moyenne (100 à 500 collaborateurs)** : environ **18 000 € à 35 000 €**.
* **Grande entreprise ou périmètres multi-sites complexes** : au-delà de **50 000 €**.

#### B. Les coûts internes et d'accompagnement (mise en conformité)
Ce sont souvent les postes budgétaires les plus conséquents :
* **Accompagnement conseil / cabinet externe** (aide au cadrage, analyse de risques, rédaction de la PSSI, audit blanc) : généralement entre **15 000 € et plus de 60 000 €** selon le degré d'autonomie interne.
* **Outillage** : licences de plateformes GRC, outils d'inventaire, gestion des vulnérabilités, sauvegardes immuables, coffres-forts de mots de passe, etc.
* **Temps-homme interne** : mobilisation de la DSI, du RSSI, des équipes RH, juridiques et des responsables métiers (souvent estimé entre 0,5 et 1,5 ETP sur une durée de 9 à 18 mois).

---

### 6. <u>Qui est certifié : l'entreprise ou un humain ?</u>

* **C'est l'organisation (l'entreprise, une entité juridique ou un périmètre opérationnel défini) qui est certifiée ISO/IEC 27001.** Le certificat atteste que son Système de Management de la Sécurité de l'Information (SMSI) répond aux exigences de la norme.
* **Un être humain n'est jamais « certifié ISO 27001 ».** Un individu acquiert une **certification de compétences personnelles** (délivrée par des organismes de formation agréés tels que PECB, BSI, IRCA), attestant qu'il dispose de l'expertise pour mettre en place la norme (*Lead Implementer*) ou pour l'auditer (*Lead Auditor*).

---

### 7. <u>Qu'est-ce que la certification ISO 27001 Lead Implementer ?</u>

La certification **ISO/IEC 27001 Lead Implementer** est un titre de qualification professionnelle individuelle de haut niveau.

* **Rôle** : elle atteste que le professionnel certifié possède les compétences méthodologiques, managériales et techniques requises pour piloter, déployer, gérer et pérenniser un Système de Management de la Sécurité de l'Information (SMSI) conforme à la norme ISO/IEC 27001 au sein d'une organisation.
* **Programme type** :
  1. Cadrage du projet, contexte de l'organisation et leadership (clauses 4 et 5).
  2. Méthodologie d'appréciation et de traitement des risques SSI (clause 6).
  3. Déploiement des 93 mesures de sécurité de l'Annexe A / ISO 27002 (clause 8).
  4. Suivi des métriques, indicateurs de performance, audit interne et revue de direction (clauses 9 et 10).
  5. Obtention validée par le passage d'un examen officiel surveillé (ex. PECB Certified ISO/IEC 27001 Lead Implementer).

---

### 8. <u>C'est quoi la différence entre 27001 / 27002 / 27005 ?</u>

Ces trois normes sont complémentaires et forment le triptyque central de la suite ISO 27000 :

| Norme | Rôle principal | Nature | Audit & Certification |
| :--- | :--- | :--- | :--- |
| **ISO/IEC 27001** | **Exigences du système (SMSI)** : définit le cadre de gouvernance (politique, objectifs, leadership, amélioration continue) et liste les contrôles en Annexe A. | Norme d'**exigences** (*« L'organisation doit... »*). | **Seule norme certifiable** pour une entreprise. |
| **ISO/IEC 27002** | **Guide de bonnes pratiques opérationnelles** : fournit les explications détaillées, les modalités de mise en œuvre et les attributs des 93 mesures de sécurité de l'Annexe A de l'ISO 27001. | Norme de **recommandations** et de lignes directrices. | **Non certifiable** en elle-même (sert de guide d'application). |
| **ISO/IEC 27005** | **Gestion des risques de sécurité de l'information** : fournit une méthodologie détaillée pour identifier, analyser, évaluer et traiter les risques SSI en accord avec la clause 6.1 de l'ISO 27001. | Norme méthodologique de support. | **Non certifiable** (fournit la démarche d'analyse de risques). |

---

### 9. <u>Est-ce que l'on peut dire que l'ISO 27001 est > à NIS 2 ou bien l'inverse ?</u>

**Ni l'un ni l'autre : ces deux dispositifs ne se situent pas sur le même plan juridique et conceptuel.**

1. **Nature juridique différente** :
   * **ISO 27001** est une **norme internationale d'adhésion volontaire**. Elle relève du choix stratégique ou contractuel de l'entreprise.
   * **NIS 2 (Directive UE 2022/2555)** est une **obligation légale réglementaire européenne**. Elle s'impose impérativement aux entités désignées comme « Essentielles » ou « Importantes », sous peine de lourdes sanctions administratives et financières.

2. **Complémentarité opérationnelle** :
   * **ISO 27001 est le meilleur tremplin technique pour NIS 2** : une entreprise certifiée ISO 27001 couvre déjà une immense partie des exigences de base de NIS 2 (gouvernance, analyse de risques, contrôle d'accès, hygiène informatique, sécurité de la chaîne d'approvisionnement).
   * **Mais l'ISO 27001 ne suffit pas seule pour être conforme à NIS 2** : NIS 2 impose des exigences réglementaires très contraignantes non prévues par l'ISO 27001, telles que des **délais stricts de notification des incidents majeurs aux autorités nationales** (alerte précoce sous 24h, notification sous 72h auprès du CERT-FR/ANSSI) et la **responsabilité juridique personnelle directe des dirigeants d'entreprise**.

---

### 10. <u>Quel document de l'ANSSI aide à être ISO ?</u>

L'ANSSI met à disposition plusieurs guides de référence publique qui s'alignent parfaitement avec les exigences de l'ISO/IEC 27001 :

1. **La méthode EBIOS Risk Manager (EBIOS RM)** :
   * C'est l'outil méthodologique par excellence pour répondre aux exigences de la clause 6.1 (*Appréciation et traitement des risques*) de l'ISO 27001 et à la norme ISO 27005.
2. **Le Guide d'élaboration d'une PSSI (*Politique de Sécurité des Systèmes d'Information*)** :
   * Guide méthodologique complet pour formaliser sa gouvernance de sécurité et satisfaire les exigences des clauses 5.2 et 6.2 de l'ISO 27001.
3. **Le Guide d'hygiène informatique (les 42 mesures fondamentales)** :
   * Donne des prescriptions concrètes et éprouvées qui permettent d'implémenter les mesures techniques et opérationnelles de l'Annexe A de l'ISO 27001.
4. **Le Référentiel SecNumCloud** :
   * Élaboré pour la qualification des offres Cloud, il s'appuie explicitement sur la base de la norme ISO/IEC 27001 en y ajoutant des exigences renforcées en matière de robustesse et de souveraineté.

---

### 11. <u>Qu'est-ce que la triade CIA ?</u>

La **triade CIA** rassemble les trois objectifs et principes directeurs fondamentaux de la sécurité de l'information :

* **C – Confidentiality (Confidentialité)** : protection des données contre la divulgation ou l'accès non autorisé. L'information n'est accessible qu'à ceux qui en ont le droit et le besoin d'en connaître (ex. chiffrement, habilitations, authentification).
* **I – Integrity (Intégrité)** : préservation de l'exactitude, de l'exhaustivité et de la validité des données et des processus. Les informations ne doivent être modifiées, altérées ou supprimées ni par accident, ni par malveillance (ex. signatures numériques, sommes de contrôle, hachage).
* **A – Availability (Disponibilité)** : garantie que les systèmes, réseaux et données sont accessibles et exploitables en temps voulu par les utilisateurs autorisés (ex. redondance d'infrastructure, sauvegardes, résilience face aux dénis de service).

*(Note : Dans la littérature francophone, elle est couramment complétée pour former le sigle **DICP**, qui y ajoute la **Preuve** ou **Traçabilité**).*

---

### 12. <u>Définir la GRC ?</u>

La **GRC** (*Gouvernance, Risque et Conformité* / *Governance, Risk and Compliance*) est un modèle global et intégré de pilotage managérial visant à harmoniser et optimiser la gestion d'une organisation :

* **G – Gouvernance** : ensemble des règles, processus, responsabilités et structures de direction permettant d'aligner les activités informatiques et de sécurité sur les objectifs stratégiques globaux de l'entreprise.
* **R – Gestion des Risques** (*Risk Management*) : capacité de l'organisation à identifier, évaluer, hiérarchiser et traiter proactivement les risques (opérationnels, cyber, financiers, réputationnels) afin de maintenir l'exposition sous un seuil tolérable.
* **C – Conformité** (*Compliance*) : ensemble des démarches assurant le respect rigoureux des lois, règlements (RGPD, NIS 2, LPM), normes sectorielles (PCI-DSS, ISO 27001) et engagements contractuels.

---

### 13. <u>Qu'est-ce qu'une PSSI ?</u>

Une **PSSI** (*Politique de Sécurité des Systèmes d'Information*) est le document cadre institutionnel et stratégique d'une entreprise fixant :
* La vision, les priorités et les objectifs de sécurité validés formellement par la direction générale.
* Les responsabilités de chaque acteur (direction, RSSI, administrateurs, sous-traitants, utilisateurs finaux).
* L'ensemble des règles et directives opérationnelles à respecter (gestion des accès, usage des mots de passe, télétravail, sécurité des développements, chiffrement, gestion des supports amovibles).
* Elle sert de loi interne opposable et constitue la colonne vertébrale documentaire de tout SMSI conforme à l'ISO 27001.

---

### 14. <u>Quelle est la différence entre un PCI et un PCA ?</u>

* **PCA (Plan de Continuité d'Activité / *Business Continuity Plan - BCP*)** :
  * **Portée globale et métier** : il s'adresse à l'ensemble de l'entreprise.
  * Il définit l'ensemble des mesures organisationnelles, humaines, logistiques et financières permettant à l'organisation de maintenir la délivrance de ses produits et services critiques en mode dégradé en cas de sinistre majeur (crise sanitaire, incendie des locaux, panne électrique générale).
* **PCI (Plan de Continuité Informatique)** :
  * **Portée purement technique et SI** : c'est un sous-ensemble du PCA centré sur l'infrastructure numérique.
  * Il vise à assurer le fonctionnement ininterrompu ou à tolérance de panne des systèmes d'information vitaux (via des clusters haute disponibilité, des liaisons télécoms redondantes, des réplications de bases de données synchrones sur un second datacenter).

---

### 15. <u>Quelle est la différence entre un PRI et un PRA ?</u>

* **PRA (Plan de Reprise d'Activité / *Disaster Recovery Plan - DRP*)** :
  * **Démarche métier post-sinistre** : intervient après une interruption complète ou un sinistre ayant paralysé les activités.
  * Il régit la réinstallation progressive du personnel, la bascule sur des locaux de secours, la réactivation des flux métiers et le retour à une situation nominale de travail.
* **PRI (Plan de Reprise Informatique)** :
  * **Procédure technique détaillée d'exécution** : déclinaison opérationnelle du PRA gérée par les équipes IT.
  * Il décrit précisément la séquence technique de restauration des sauvegardes, de reconstruction des serveurs, de rétablissement du routage réseau et de contrôle de l'intégrité des bases de données après sinistre.
  * **Indicateurs clés associés** : le **RTO** (*Recovery Time Objective* - durée maximale acceptable d'interruption) et le **RPO** (*Recovery Point Objective* - perte maximale de données tolérée dans le temps).

---

### 16. <u>Récupérer les documents de l'ISO 27001</u>

La norme ISO/IEC 27001 est une publication payante couverte par un copyright strict. Les documents officiels sont disponibles aux adresses suivantes :

* **Achat de la norme officielle internationale (ISO)** :
  * [Boutique ISO - ISO/IEC 27001:2022](https://www.iso.org/standard/27001)
* **Achat de la version française homologuée (AFNOR)** :
  * [Boutique AFNOR Éditions - NF EN ISO/IEC 27001](https://boutique.afnor.org/)
* **Consultation gratuite en ligne des métadonnées et définitions** :
  * [Plateforme de consultation en ligne ISO (OBP)](https://www.iso.org/obp/ui/#iso:std:iso-iec:27001:ed-3:v1:en)

---

### 17. <u>Récupérer les documents de l'ISO 27002</u>

Tout comme l'ISO 27001, la norme ISO/IEC 27002 (le catalogue détaillé de recommandations pour les mesures de sécurité) est payante :

* **Achat de la norme officielle internationale (ISO)** :
  * [Boutique ISO - ISO/IEC 27002:2022](https://www.iso.org/standard/75652.html)
* **Achat de la version française homologuée (AFNOR)** :
  * [Boutique AFNOR Éditions - NF EN ISO/IEC 27002](https://boutique.afnor.org/)
* **Aperçu et table des matières officielle** :
  * [Aperçu ISO/IEC 27002 sur la plateforme OBP](https://www.iso.org/obp/ui/#iso:std:iso-iec:27002:ed-3:v1:en)

---

### 18. <u>Récupérer les documents de l'ANSSI en lien avec cette problématique</u>

Contrairement aux normes ISO, toutes les publications, guides et référentiels méthodologiques de l'ANSSI sont **librement accessibles et téléchargeables gratuitement en PDF** sur son portail officiel :

1. **Méthode EBIOS Risk Manager** :
   * [Guide officiel EBIOS RM (ANSSI)](https://cyber.gouv.fr/la-methode-ebios-risk-manager)
2. **Guide d'hygiène informatique (42 règles indispensables)** :
   * [Guide d'hygiène informatique (ANSSI)](https://cyber.gouv.fr/publications/guide-dhygiene-informatique)
3. **Guide d'élaboration d'une PSSI** :
   * [Élaborer une Politique de Sécurité des SI (ANSSI)](https://cyber.gouv.fr/publications/elaboration-dune-politique-de-securite-des-systemes-dinformation-pssi)
4. **Référentiel SecNumCloud** :
   * [Référentiel d'exigences SecNumCloud (ANSSI)](https://cyber.gouv.fr/publications/referentiel-d-exigences-secnumcloud)
5. **Dossier et recommandations sur la directive NIS 2** :
   * [Espace NIS 2 sur cyber.gouv.fr](https://cyber.gouv.fr/la-directive-nis-2)
