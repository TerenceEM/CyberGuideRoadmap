# Rapport de Projet - CyberGuide
## Plateforme d'Orientation en Cybersécurité pour Entreprises Débutantes

**Évaluation ECSI3-Evaluation-01**
**Date :** 2026-02-02
**Référence :** Cas pratique – Sensibilisation et Orientation dans le paysage cyber

---

## 1. Lien du Site Publié

🔗 **URL du site :** [À COMPLÉTER après publication sur GitHub Pages/Netlify/Vercel]

Exemple : `https://[votre-username].github.io/cyberguide/`

**Instructions de publication :** Consultez le fichier `GUIDE_PUBLICATION.md` fourni avec le projet.

---

## 2. Note de Démarche (10-20 lignes)

### Pourquoi cette plateforme existe

CyberGuide a été conçu comme une réponse au constat suivant : en 2026, l'information en cybersécurité est abondante mais difficile à exploiter pour une entreprise débutante. Les sources sont dispersées, hétérogènes et il est rarement évident de savoir par où commencer.

### Choix de structure

La plateforme est structurée selon une **logique de parcours progressif** :
1. **Identification du contexte** (secteurs d'activité) pour personnaliser les recommandations
2. **Sensibilisation multi-profils** (Employé/IT/Dirigeant) car chaque rôle a des besoins spécifiques
3. **Orientation réglementaire** via un questionnaire simple pour identifier les obligations légales
4. **Ressources concrètes** (acteurs, prestataires, outils) organisées par type de besoin
5. **Passage à l'action** avec quiz, checklists et scénarios pratiques

### Sélection et organisation de l'information

L'information a été **sourcée depuis des ressources publiques officielles** (ANSSI, CNIL, CERT-FR, Cybermalveillance.gouv.fr) et organisée selon une **hiérarchie de priorités** :
- Les fondamentaux d'abord (MFA, sauvegardes, EDR)
- Puis les mesures intermédiaires (SIEM, IAM, conformité)
- Enfin les solutions avancées (XDR, SOAR, Zero Trust)

La navigation est **simple et intuitive** avec un menu persistant permettant d'accéder à n'importe quelle section à tout moment. Chaque page propose des **appels à l'action clairs** vers les prochaines étapes logiques.

Le contenu évite le jargon technique non expliqué et utilise systématiquement des **exemples concrets** et des **cas d'usage réels** pour faciliter la compréhension.

---

## 3. Couverture des 4 Domaines Obligatoires

### ✅ Domaine 1 : Sensibilisation

**Page dédiée :** `sensibilisation.html`

**Contenu :**
- **3 profils distincts** : Employé, Équipe IT, Dirigeant
- **Vocabulaire et notions clés** : risque, menace, vulnérabilité, impact, surface d'attaque (tableau complet)
- **Menaces actuelles illustrées** :
  - Pour les employés : Phishing, compromission de comptes, perte de matériel, ingénierie sociale
  - Pour l'IT : Ransomware, exploitation de vulnérabilités, attaques supply chain
  - Pour les dirigeants : Impact financier, responsabilité légale, impact réputationnel
- **Exemples concrets** pour chaque menace avec scénarios réels
- **Bonnes pratiques actionnables** :
  - Employés : gestion mots de passe, MFA, hygiène email, sécurité appareils, télétravail
  - IT : patch management, IAM, sauvegardes, segmentation, monitoring, scan vulnérabilités
  - Dirigeants : gouvernance, gestion des risques, culture de sécurité, préparation crise

### ✅ Domaine 2 : Normes et Réglementations

**Page dédiée :** `reglementation.html`

**Contenu :**
- **Réglementations obligatoires détaillées** :
  - RGPD (universel)
  - NIS2 (opérateurs essentiels)
  - Secteur Santé (HDS, PGSSI-S)
  - Secteur Finance (DORA, PSD2, MiFID II)
  - OIV (Opérateurs d'Importance Vitale)
- **Pour chaque réglementation** :
  - Périmètre d'application
  - Implications concrètes
  - Sanctions encourues
  - Premières actions à initier
  - Sources officielles
- **Normes volontaires** : ISO 27001, ISO 27002, ISO 27701, SOC 2, PCI DSS, NIST CSF, CIS Controls
- **Outil d'orientation** : Questionnaire en 5 questions pour identifier les réglementations applicables

### ✅ Domaine 3 : Prestataires

**Page dédiée :** `prestataires.html`

**Minimum requis :** 5 types de prestataires
**Fourni :** 6 catégories complètes

**Catégories couvertes** :
1. **Réponse à Incident (DFIR)** : Wavestone, Orange Cyberdefense, Thales, Sygnia, Mandiant
2. **Audit & Conseil** : Deloitte, PwC, Capgemini, Advens, Devoteam
3. **Pentest** : Synacktiv, Intrinsec, Vaadata, Zenika Security, Yogosha
4. **MSSP/SOC** : Orange Cyberdefense, Atos, Thales, Advens, Sekoia.io
5. **Sensibilisation** : KnowBe4, Conscio, Cybermalveillance.gouv.fr, ANSSI, SecureData, Phished
6. **Conformité** : Caprioli & Associés, EY, KPMG, DPO Consulting, AFNOR

**Chaque catégorie inclut** :
- Quand faire appel
- Services proposés
- Noms des prestataires avec leurs spécialités
- Budget indicatif
- Logique "qui contacter selon la situation"

### ✅ Domaine 4 : Outils

**Page dédiée :** `outils.html`

**Minimum requis :** 5 catégories avec 3 éléments minimum chacune
**Fourni :** 8 catégories avec 6 outils en moyenne

**Catégories couvertes** :
1. **EDR/XDR** : CrowdStrike, SentinelOne, Microsoft Defender, Palo Alto Cortex, Trend Micro, Carbon Black
2. **IAM** : Okta, Microsoft Entra ID, Ping Identity, CyberArk, OneLogin, JumpCloud
3. **Sauvegarde** : Veeam, Acronis, Commvault, Rubrik, Cohesity, Nakivo
4. **SIEM** : Splunk, Microsoft Sentinel, IBM QRadar, Elastic Security, LogRhythm, Sekoia.io
5. **Scan Vulnérabilités** : Tenable, Qualys, Rapid7, Acunetix, OpenVAS, Burp Suite
6. **Email Security** : Proofpoint, Mimecast, Microsoft Defender for O365, Barracuda, Cisco, Cofense
7. **MDM** : Microsoft Intune, Jamf, VMware Workspace ONE, MobileIron, Cisco Meraki, Kandji
8. **Firewall** : Palo Alto, Fortinet, Check Point, Cisco, pfSense, Cloudflare WAF

**Chaque catégorie inclut** :
- Définition et utilité
- Fonctionnalités clés
- Noms des éditeurs avec descriptions
- Budget indicatif
- Conseils de sélection

---

## 4. Contenu Général et Contextualisation

### Identification des Contextes (4+ secteurs requis, 6 fournis)

**Page :** `secteurs.html`

**Secteurs couverts :**
1. **E-commerce** : Actifs critiques (données bancaires, clients), menaces (SQL injection, skimming, DDoS), conséquences (sanctions RGPD, perte clients), IT
2. **Santé** : DME, équipements médicaux, menaces (ransomware, vol données médicales), risques humains, IT+OT
3. **Industrie/Manufacturing** : SCADA, ICS, PLC, menaces (malware OT, espionnage), dommages matériels, IT+OT
4. **Finance/Banque** : Systèmes transactionnels, menaces (APT, fraude SWIFT), impact systémique, IT
5. **SaaS/Tech** : Infrastructure cloud, menaces (supply chain logicielle, fuite multi-tenants), IT cloud
6. **Collectivités** : Services publics, menaces (ransomware, cyberattaques géopolitiques), IT+OT

**Pour chaque secteur :**
- Actifs critiques typiques
- Menaces dominantes avec exemples
- Conséquences prévisibles (financières, réglementaires, réputationnelles, humaines)
- Distinction IT/OT

### Démarche et Raison d'Être

**Page d'accueil** (`index.html`) explique :
- **Pourquoi** : Information abondante mais difficilement exploitable
- **Mission** : Structurer les premiers pas en guidant vers bonnes démarches, sources, obligations, interlocuteurs, outils
- **Approche** : 5 étapes (identifier contexte, sensibiliser, connaître obligations, trouver contacts, passer à l'action)
- **Logique** : "Je réponds à quelques questions et j'obtiens une trajectoire claire"

---

## 5. Acteurs Étatiques (5+ requis, 9 fournis)

**Page :** `acteurs.html`

**Acteurs couverts :**
1. **ANSSI** : Autorité nationale, OIV, guides, qualification produits
2. **Cybermalveillance.gouv.fr** : Assistance victimes, 0 805 805 817, orientation vers prestataires
3. **CERT-FR** : Veille, alertes, réponse incidents critiques, bulletins de sécurité
4. **CNIL** : RGPD, protection données, notification violations
5. **OCLCTIC** : Police judiciaire, enquêtes cybercriminalité
6. **ENISA** : Agence européenne, rapports, certifications EU
7. **DGE** : Accompagnement PME/ETI
8. **Bpifrance** : Financement, diagnostics cyber gratuits
9. **AFNOR** : Certification ISO 27001

**Chaque acteur inclut :**
- Rôle et missions
- Pour qui
- Quand contacter
- Ressources disponibles
- Contacts

**Logique d'orientation** : Tableau "qui contacter selon la situation" (attaque en cours → Cybermalveillance + CERT-FR ; question RGPD → CNIL ; etc.)

---

## 6. Contenu Action (Quiz, Checklist, Scénario)

**Page :** `action.html`

### Quiz de Sensibilisation (10 questions)

Couvre :
- Définitions (phishing, MFA, ransomware, EDR, RGPD)
- Situations pratiques (email suspect, ingénierie sociale, urgence cyber)
- Bonnes pratiques (règle 3-2-1, verrouillage écran, mises à jour)

Avec réponses détaillées et explications pédagogiques

### Checklist de Sécurité (3 niveaux)

**Niveau 1 Fondamentaux (10 items)** : EDR, firewall, sauvegardes, MFA, chiffrement, WiFi, sensibilisation
**Niveau 2 Intermédiaire (12 items)** : Politique sécurité, analyse risques, IAM, segmentation, SIEM, scan vulnérabilités, MDM, PCA/PRA, RGPD, phishing simulé
**Niveau 3 Avancé (12 items)** : SIEM, SOC, threat intelligence, pentest annuel, red team, Zero Trust, DLP, CASB, SOAR, bug bounty, ISO 27001, table-top exercises
**Conformité réglementaire (6 items)** : RGPD, NIS2, PCI DSS, conformité sectorielle

Total : 40+ actions concrètes organisées par niveau de maturité

### Scénario d'Incident Ransomware (4 phases)

1. **Détection** : Lundi 8h30, fichiers .locked, message de rançon 50 000€
   - Actions recommandées : ne pas éteindre, isoler, cellule de crise, Cybermalveillance, changer mots de passe
   - Ce qu'il ne faut PAS faire

2. **Containment & Investigation** : T+2h, attaque LockBit via phishing
   - DFIR, vérification sauvegardes, identification source, notification CNIL

3. **Éradication & Récupération** : Suppression accès attaquant, restauration depuis sauvegardes
   - Plan si pas de sauvegardes (NoMoreRansom, décision paiement, reconstruction)

4. **Retour d'expérience** : REX, plan d'action correctif (EDR, email security, MFA, segmentation, formation)

**Réalisme** : Coûts (80 000€), délais (3 jours arrêt), taux de récupération (95%)

---

## 7. Qualité Pédagogique et d'Orientation

### Organisation de l'Information

- **Navigation cohérente** : Menu persistant sur toutes les pages
- **Progression logique** : Du contexte général aux actions concrètes
- **Cartes cliquables** : Chaque section propose des "prochaines étapes"
- **Tableaux de décision** : "Qui contacter selon la situation", "Priorisation selon maturité"
- **Codes couleur** : 🟢 Fondamentaux, 🟡 Intermédiaire, 🔴 Avancé

### Qualité Pédagogique

- **Vocabulaire expliqué** : Tableau complet des termes techniques
- **Exemples concrets** : Chaque concept illustré par un cas réel
- **Pas de jargon non expliqué** : Acronymes définis à la première occurrence
- **Multi-profils** : Contenu adapté selon le rôle (employé/IT/dirigeant)
- **Actionnable** : Toujours des "premières actions" concrètes

### Pertinence de l'Orientation

- **Logique contextuelle** : Recommandations selon secteur, taille, maturité
- **Priorisation claire** : Ce qui est URGENT vs Important vs Nice-to-have
- **Budget indicatif** : Toujours mentionné pour aider à la décision
- **Éviter les pièges** : Section "Red flags" et "Ce qu'il ne faut PAS faire"
- **Sources fiables** : Liens vers ressources officielles (ANSSI, CNIL, etc.)

---

## 8. Structure Technique du Site

### Fichiers du Projet

```
Projet-Web/
├── index.html              # Page d'accueil et présentation
├── secteurs.html          # 6 secteurs d'activité
├── sensibilisation.html   # 3 profils de sensibilisation
├── reglementation.html    # Réglementations et normes
├── acteurs.html          # 9 acteurs étatiques
├── prestataires.html     # 6 catégories de prestataires
├── outils.html           # 8 catégories d'outils
├── action.html           # Quiz, checklist, scénario
├── style.css             # Styles complets
├── GUIDE_PUBLICATION.md  # Instructions de publication
└── RAPPORT_PROJET.md     # Ce document
```

### Technologies Utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles responsive (Flexbox, Grid)
- **Pas de JavaScript** : Simplicité maximale, accessibilité totale
- **Design responsive** : Adaptation mobile via media queries

### Accessibilité et Utilisabilité

- Navigation intuitive avec menu persistant
- Ancres de navigation (#quiz, #checklist, #scenario)
- Pas de dépendance JavaScript (fonctionne même JavaScript désactivé)
- Temps de chargement minimal (HTML/CSS pur)
- Compatible tous navigateurs modernes

---

## 9. Points Forts du Projet

✅ **Exhaustivité** : Tous les domaines requis couverts et dépassés (6 secteurs vs 4, 6 catégories prestataires vs 5, 8 catégories outils vs 5)

✅ **Qualité du contenu** : Information sourcée, vérifiée, à jour (2026)

✅ **Pédagogie** : Vocabulaire expliqué, exemples concrets, progression logique

✅ **Orientation efficace** : Tableaux de décision, logique "qui contacter quand", priorisation claire

✅ **Actionnable** : Quiz, checklists par niveau de maturité, scénario réaliste

✅ **Design épuré** : Focus sur le contenu, pas de distraction esthétique

✅ **Maintenance facile** : HTML/CSS pur, facile à mettre à jour

---

## 10. Captures d'Écran

### À compléter après publication

[Insérer ici les captures d'écran de chaque page principale : Accueil, Secteurs, Sensibilisation, Réglementation, Acteurs, Prestataires, Outils, Action]

**Instructions pour les captures :**
1. Ouvrir le site publié dans un navigateur
2. Capturer chaque page en full-page screenshot
3. Inclure dans ce document PDF final

**Pages à capturer :**
- [ ] Page d'accueil (index.html)
- [ ] Secteurs d'activité (secteurs.html)
- [ ] Sensibilisation (sensibilisation.html)
- [ ] Réglementation (reglementation.html)
- [ ] Acteurs étatiques (acteurs.html)
- [ ] Prestataires (prestataires.html)
- [ ] Outils de sécurité (outils.html)
- [ ] Quiz et Checklist (action.html)

---

## 11. Sources et Références

Toutes les informations ont été sourcées depuis des ressources publiques et officielles :

- **ANSSI** : https://www.ssi.gouv.fr/ (guides, référentiels, panorama de la menace)
- **Cybermalveillance.gouv.fr** : https://www.cybermalveillance.gouv.fr/ (fiches pratiques, kit sensibilisation)
- **CERT-FR** : https://www.cert.ssi.gouv.fr/ (bulletins d'actualité, alertes)
- **CNIL** : https://www.cnil.fr/ (guides RGPD, outils gratuits)
- **Commission Européenne** : NIS2, DORA, ENISA
- **Éditeurs de solutions** : Sites officiels pour informations produits
- **Études de marché** : Gartner, Forrester (pour positionnement des solutions)

---

## 12. Conclusion

CyberGuide répond au besoin exprimé dans le sujet : **structurer les premiers pas en cybersécurité pour une entreprise débutante**.

La plateforme offre :
- ✅ **Une vision d'ensemble** du paysage cyber
- ✅ **Une orientation personnalisée** selon le contexte
- ✅ **Des ressources concrètes** (acteurs, prestataires, outils) avec noms et contacts
- ✅ **Un passage à l'action** avec quiz, checklists et scénarios

Le tout dans une interface **simple, navigable et pédagogique**, sans nécessiter de connaissances techniques préalables.

---

**Projet réalisé dans le cadre de l'évaluation ECSI3 - SecureSphere by EPITA**
**Date de rendu :** 2026-02-02